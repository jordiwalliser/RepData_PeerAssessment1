



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>coursera-repdata/PA1_template.md at master · sefakilic/coursera-repdata</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" href="/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon-180x180.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="sefakilic/coursera-repdata" name="twitter:title" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" property="og:image" /><meta content="sefakilic/coursera-repdata" property="og:title" /><meta content="https://github.com/sefakilic/coursera-repdata" property="og:url" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTMzMjQyODE6Y2Y2ZDU3Y2JiZGIzZjk3Y2U3MTNiOTBiZTEwODQ1MWE6YTI1MjllMjBiMGU5ZjExZGM3ZDA0YmJmYzY4NGRiODdkZmIxYTdlMmU2N2JjMmRmNzA5NzkwMDEzNmVlMTVlNQ==--9a3be684b0e9dcfb9c63d1c5174be39b66ff12f4">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="BDD9A661:0600:3DE7D9B:56A58C34" name="octolytics-dimension-request_id" /><meta content="13324281" name="octolytics-actor-id" /><meta content="jordiwalliser" name="octolytics-actor-login" /><meta content="4439bece4a8bed20c2176ef9a1cd92b0e67799e402e7e871e2a614993eef79c2" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />



  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="jordiwalliser">

        <meta name="expected-hostname" content="github.com">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="5088f37b618c98a2476b14398645b683baf55de1" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-898431d6e5abf6c9cbfc59b1b036b8baa63244fe299f7d7eaee452b64571eaee.css" integrity="sha256-iYQx1uWr9snL/FmxsDa4uqYyRP4pn31+ruRStkVx6u4=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-b2d8d1fd984ff1b181275aaa1276c82bb266b4f58f08f3075941d786d5b432ec.css" integrity="sha256-stjR/ZhP8bGBJ1qqEnbIK7JmtPWPCPMHWUHXhtW0Muw=" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="39f056823b54a1976a98d9b33d8b4949">

      
  <meta name="description" content="coursera-repdata - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/sefakilic/coursera-repdata git https://github.com/sefakilic/coursera-repdata.git">

  <meta content="1227083" name="octolytics-dimension-user_id" /><meta content="sefakilic" name="octolytics-dimension-user_login" /><meta content="19899531" name="octolytics-dimension-repository_id" /><meta content="sefakilic/coursera-repdata" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/sefakilic/coursera-repdata/commits/master.atom" rel="alternate" title="Recent Commits to coursera-repdata:master" type="application/atom+xml">


      <link rel="canonical" href="https://github.com/sefakilic/coursera-repdata/blob/master/project1/PA1_template.md" data-pjax-transient>
  </head>


  <body class="logged_in   env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span aria-hidden="true" class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/sefakilic/coursera-repdata/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:jordiwalliser"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span aria-hidden="true" class="octicon octicon-bell"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span aria-hidden="true" class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>




      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/jordiwalliser"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@jordiwalliser" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/13324281?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">jordiwalliser</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/jordiwalliser" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
          <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
            Explore
          </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>


          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="/IKkwQYKfhkr0vW9kOschaN71OU1z43duYcXyGqRA6WPbe2oGKgvQnHWq0A6fUvstqZpidWoIBuDG8v78LLRkA==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div id="js-repo-pjax-container" class="context-loader-container js-repo-nav-next" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="l7IyYciKqr8mkXqwWAhBPkbsMsEqbYZHC6NUHoVHwW0KQCDrrnJs/sy8cU4ZNOJy+gi6EVtzTwgiwgq0V/dpdA==" /></div>      <input id="repository_id" name="repository_id" type="hidden" value="19899531" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/sefakilic/coursera-repdata/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <span aria-hidden="true" class="octicon octicon-eye"></span>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/watchers">
            3
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span aria-hidden="true" class="octicon octicon-eye"></span>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
                  <div class="select-menu-item-text">
                    <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span aria-hidden="true" class="octicon octicon-eye"></span>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span aria-hidden="true" class="octicon octicon-mute"></span>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="dIT3jRitMslS0vltQnKh0SpKAWSz/81js78/ySUuVq27dGgWCgKBaTiG6RC8ullqrtIiWfeLjGVZlU3qyh5w6A==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar sefakilic/coursera-repdata"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span aria-hidden="true" class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/stargazers">
          2
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="VSa1GTpf27x1tLfLW4ugGWIeUmDEACh5NwDmYHp3AytHsuIFl6Goszq2trHAmVm0O5XxT2nna2vdifKxKml1Pg==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star sefakilic/coursera-repdata"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span aria-hidden="true" class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/stargazers">
          2
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/fork" class="btn-with-count" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="k6E/NnBvMe+EsBkbv/RRETGuszEtbAhzakvJQmd4weGqTQO2fStqfvEDPJkS06e+pXPQxHSP9v+jIUYzMuJhvw==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of sefakilic/coursera-repdata to your account"
                aria-label="Fork your own copy of sefakilic/coursera-repdata to your account">
              <span aria-hidden="true" class="octicon octicon-repo-forked"></span>
              Fork
            </button>
</form>
    <a href="/sefakilic/coursera-repdata/network" class="social-count">
      21,672
    </a>
  </li>
</ul>

    <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span aria-hidden="true" class="octicon octicon-repo-forked"></span>
  <span class="author"><a href="/sefakilic" class="url fn" itemprop="url" rel="author"><span itemprop="title">sefakilic</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/sefakilic/coursera-repdata" data-pjax="#js-repo-pjax-container">coursera-repdata</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

    <span class="fork-flag">
      <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
    </span>
</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <a href="/sefakilic/coursera-repdata" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /sefakilic/coursera-repdata">
    <span aria-hidden="true" class="octicon octicon-code"></span>
    Code
</a>

  <a href="/sefakilic/coursera-repdata/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /sefakilic/coursera-repdata/pulls">
    <span aria-hidden="true" class="octicon octicon-git-pull-request"></span>
    Pull requests
    <span class="counter">0</span>
</a>
    <a href="/sefakilic/coursera-repdata/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /sefakilic/coursera-repdata/wiki">
      <span aria-hidden="true" class="octicon octicon-book"></span>
      Wiki
</a>
  <a href="/sefakilic/coursera-repdata/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /sefakilic/coursera-repdata/pulse">
    <span aria-hidden="true" class="octicon octicon-pulse"></span>
    Pulse
</a>
  <a href="/sefakilic/coursera-repdata/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /sefakilic/coursera-repdata/graphs">
    <span aria-hidden="true" class="octicon octicon-graph"></span>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/sefakilic/coursera-repdata/blob/887120ed7a37211dd2d2bdc05dbe0e81e0e1ae7d/project1/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:8a4aa3e01c1a68b226587289c2ddf6f0 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/sefakilic/coursera-repdata/blob/master/project1/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span aria-hidden="true" class="octicon octicon-check select-menu-item-icon"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/sefakilic/coursera-repdata/find/master"
          class="js-show-file-finder btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/sefakilic/coursera-repdata" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">coursera-repdata</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/sefakilic/coursera-repdata/tree/master/project1" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">project1</span></a></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/sefakilic/coursera-repdata/commit/a294c1c2856357eb6f345902dd359b0814b386b0" data-pjax>
          a294c1c
        </a>
        <time datetime="2014-05-18T15:05:57Z" is="relative-time">May 18, 2014</time>
      </span>
      <div>
        <img alt="@sefakilic" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1227083?v=3&amp;s=40" width="20" />
        <a href="/sefakilic" class="user-mention" rel="author">sefakilic</a>
          <a href="/sefakilic/coursera-repdata/commit/a294c1c2856357eb6f345902dd359b0814b386b0" class="message" data-pjax="true" title="peer assessment 1">peer assessment 1</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>1</strong>
         contributor
      </a>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@sefakilic" height="24" src="https://avatars2.githubusercontent.com/u/1227083?v=3&amp;s=48" width="24" />
            <a href="/sefakilic">sefakilic</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/sefakilic/coursera-repdata/raw/master/project1/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/sefakilic/coursera-repdata/blame/master/project1/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/sefakilic/coursera-repdata/commits/master/project1/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="btn-octicon tooltipped tooltipped-nw"
           href="github-windows://openRepo/https://github.com/sefakilic/coursera-repdata?branch=master&amp;filepath=project1%2FPA1_template.md"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <span aria-hidden="true" class="octicon octicon-device-desktop"></span>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/edit/master/project1/PA1_template.md" class="inline-form js-update-url-with-hash" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JUO2CDINQwDO1Tmt0/wC80+S5NxO/aQ1bMhg9PSzgp1CfSMoTe64yJ3j2iT7CWoOpY/SnAf1LUr8p/ECb5rgYA==" /></div>
          <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
            aria-label="Edit the file in your fork of this project" data-hotkey="e" data-disable-with>
            <span aria-hidden="true" class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/delete/master/project1/PA1_template.md" class="inline-form" data-form-nonce="5088f37b618c98a2476b14398645b683baf55de1" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="WCT8oe4BquwAJUeIqLe9LrdeWtPklvQJ1M/P4H3gmJf3jAEqBQBtiAKY51RrEJK0JZyKZ60tA0orm8zMe10VZA==" /></div>
          <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete the file in your fork of this project" data-disable-with>
            <span aria-hidden="true" class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      160 lines (113 sloc)
      <span class="file-info-divider"></span>
    3.81 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research: Peer Assessment 1</h1>

<h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-source-r"><pre>unzip(<span class="pl-v">zipfile</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)</pre></div>

<h2><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-1.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-1.png" alt="plot of chunk unnamed-chunk-1" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>mean(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 9354
</code></pre>

<div class="highlight highlight-source-r"><pre>median(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 10395
</code></pre>

<h2><a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">steps</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), <span class="pl-v">by</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>), 
    <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">mean</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
ggplot(<span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">averages</span>, aes(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-smi">interval</span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> 
    ylab(<span class="pl-s"><span class="pl-pds">"</span>average number of steps taken<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-2.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-2.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<p>On average across all the days in the dataset, the 5-minute interval contains
the maximum number of steps?</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">averages</span>[which.max(<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), ]</pre></div>

<pre><code>##     interval steps
## 104      835 206.2
</code></pre>

<h2><a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<p>There are many days/intervals where there are missing values (coded as <code>NA</code>). The presence of missing days may introduce bias into some calculations or summaries of the data.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">missing</span> <span class="pl-k">&lt;-</span> is.na(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
<span class="pl-c"># How many missing</span>
table(<span class="pl-smi">missing</span>)</pre></div>

<pre><code>## missing
## FALSE  TRUE 
## 15264  2304
</code></pre>

<p>All of the missing values are filled in with mean value for that 5-minute
interval.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-c"># Replace each missing value with the mean value of its 5-minute interval</span>
<span class="pl-en">fill.value</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">steps</span>, <span class="pl-smi">interval</span>) {
    <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">NA</span>
    <span class="pl-k">if</span> (<span class="pl-k">!</span>is.na(<span class="pl-smi">steps</span>)) 
        <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> c(<span class="pl-smi">steps</span>) <span class="pl-k">else</span> <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> (<span class="pl-smi">averages</span>[<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>, <span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>])
    <span class="pl-k">return</span>(<span class="pl-smi">filled</span>)
}
<span class="pl-smi">filled.data</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span>
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span> <span class="pl-k">&lt;-</span> mapply(<span class="pl-smi">fill.value</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)</pre></div>

<p>Now, using the filled data set, let's make a histogram of the total number of steps taken each day and calculate the mean and median total number of steps.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-5.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-5.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>mean(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-source-r"><pre>median(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Mean and median values are higher after imputing missing data. The reason is
that in the original data, there are some days with <code>steps</code> values <code>NA</code> for 
any <code>interval</code>. The total number of steps taken in such days are set to 0s by
default. However, after replacing missing <code>steps</code> values with the mean <code>steps</code>
of associated <code>interval</code> value, these 0 values are removed from the histogram
of total number of steps taken each day.</p>

<h2><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<p>First, let's find the day of the week for each measurement in the dataset. In
this part, we use the dataset with the filled-in values.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-en">weekday.or.weekend</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">date</span>) {
    <span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> weekdays(<span class="pl-smi">date</span>)
    <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Monday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Tuesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Wednesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Thursday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Friday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> stop(<span class="pl-s"><span class="pl-pds">"</span>invalid date<span class="pl-pds">"</span></span>)
}
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span> <span class="pl-k">&lt;-</span> as.Date(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">weekday.or.weekend</span>)</pre></div>

<p>Now, let's make a panel plot containing plots of average number of steps taken
on weekdays and weekends.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span> <span class="pl-k">+</span> <span class="pl-smi">day</span>, <span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">filled.data</span>, <span class="pl-smi">mean</span>)
ggplot(<span class="pl-smi">averages</span>, aes(<span class="pl-smi">interval</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> facet_grid(<span class="pl-smi">day</span> <span class="pl-k">~</span> .) <span class="pl-k">+</span> 
    xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> ylab(<span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-7.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-7.png" alt="plot of chunk unnamed-chunk-7" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>

    </div>
  </div>

    </div>

        <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span aria-hidden="true" class="mega-octicon octicon-mark-github" title="GitHub "></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2016 <span title="0.05878s from github-fe142-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span aria-hidden="true" class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span aria-hidden="true" class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      
      <script crossorigin="anonymous" integrity="sha256-nuVc6vh/w03IYzQkn+9svs6I6BVHjg++gWQtV+0P/4k=" src="https://assets-cdn.github.com/assets/frameworks-9ee55ceaf87fc34dc86334249fef6cbece88e815478e0fbe81642d57ed0fff89.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-G+Ga1mKcjStSuxsBHGt+z3Q9tWkFTBwPNsjZhYzj9kA=" src="https://assets-cdn.github.com/assets/github-1be19ad6629c8d2b52bb1b011c6b7ecf743db569054c1c0f36c8d9858ce3f640.js"></script>
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span aria-hidden="true" class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
    <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <span aria-hidden="true" class="octicon octicon-x"></span>
    </button>
  </div>
</div>

  </body>
</html>

