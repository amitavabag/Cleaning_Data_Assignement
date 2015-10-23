


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>getting-and-cleaning-data-assignment/CodeBook.md at master · diegoo/getting-and-cleaning-data-assignment</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="diegoo/getting-and-cleaning-data-assignment" name="twitter:title" /><meta content="getting-and-cleaning-data-assignment - Getting and Cleaning Data Course Project" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/15387?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/15387?v=3&amp;s=400" property="og:image" /><meta content="diegoo/getting-and-cleaning-data-assignment" property="og:title" /><meta content="https://github.com/diegoo/getting-and-cleaning-data-assignment" property="og:url" /><meta content="getting-and-cleaning-data-assignment - Getting and Cleaning Data Course Project" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTUxMzUzODk6MjQxMTNkMjJmOTA5MmM2MTE4MWE5OTFjYzBlY2ExMGI6MDJhZDQ4MmExNzU5Y2JhYzBhOGNjNmJjYjU4Y2U4MzI1MzExMmViZjM3Mzg5OTk2MDk1NTAwYTNiYzA0NDdhMw==--c8f406cb52381eec7215465cbe53a93b70690a3c">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="AD11C18B:07C9:24699CA4:5629AAE1" name="octolytics-dimension-request_id" /><meta content="15135389" name="octolytics-actor-id" /><meta content="amitavabag" name="octolytics-actor-login" /><meta content="7dd901db3f5caab996fd8704551ce5454c572fac331feb8ccf34ddf26db87106" name="octolytics-actor-hash" />

<meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />


  <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension4" content="Current repo nav">




    <meta name="is-dotcom" content="true">
        <meta name="hostname" content="github.com">
    <meta name="user-login" content="amitavabag">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="af76fbd4df014740dd1a2ed255f1e76f739379a4" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-ce671588d7b6afbb8bc61feba5b37b4acc3341aec654ff7a2405b657922ff0c1.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-8d66f9bfcef65682f8b799f2330467be836c483d58670c9388d40c9e4c0492a3.css" media="all" rel="stylesheet" />
    
    
    


    <meta http-equiv="x-pjax-version" content="f7a60445478c6154531fdca94f3ffd1b">

      
  <meta name="description" content="getting-and-cleaning-data-assignment - Getting and Cleaning Data Course Project">
  <meta name="go-import" content="github.com/diegoo/getting-and-cleaning-data-assignment git https://github.com/diegoo/getting-and-cleaning-data-assignment.git">

  <meta content="15387" name="octolytics-dimension-user_id" /><meta content="diegoo" name="octolytics-dimension-user_login" /><meta content="20162809" name="octolytics-dimension-repository_id" /><meta content="diegoo/getting-and-cleaning-data-assignment" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="20162809" name="octolytics-dimension-repository_network_root_id" /><meta content="diegoo/getting-and-cleaning-data-assignment" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/diegoo/getting-and-cleaning-data-assignment/commits/master.atom" rel="alternate" title="Recent Commits to getting-and-cleaning-data-assignment:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/diegoo/getting-and-cleaning-data-assignment/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
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
        data-channel="notification-changed:amitavabag"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
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



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="diegoo/getting-and-cleaning-data-assignment">This repository</span>
  </div>
    <a class="dropdown-item" href="/diegoo/getting-and-cleaning-data-assignment/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/amitavabag"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@amitavabag" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/15135389?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">amitavabag</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/amitavabag" data-ga-click="Header, go to profile, text:your profile">
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

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GJ/RB/limRmMCG9MLDn+MnReoi1C0cEb5jbHlADaiEZ+LITlfCeMN5fCv6tJrubMj0+1aDVDhm8NcZpSK4p9bQ==" /></div>
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
    <div class="pagehead repohead instapaper_ignore readability-menu">

      <div class="container">

        <div class="clearfix">
          

<ul class="pagehead-actions">

  <li>
      <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="fZiV26RYto8R8uaA/KT4PYM8WEjx3im8bbBCPnZzqvhwA+GoW+nsA6v4aWwcsi3UfRqGmrX9HKKc7nxh8mYwEA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="20162809" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/diegoo/getting-and-cleaning-data-assignment/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/diegoo/getting-and-cleaning-data-assignment/watchers">
          1
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="rhkU/nF8AU2XUte5XBAqeAyAXDC4ci2qiUuQmaOKenwJa+ctZ1zHUgoUu30PTlo372JHRJqIL3nx5xs8FPbOdA==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar diegoo/getting-and-cleaning-data-assignment"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/diegoo/getting-and-cleaning-data-assignment/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="Uz9fRpigcMzaQZWMFcFXmQS67NooUaO+hO9Xh3wnNlQwOBShkWMr8zx9GSDXC4xf4YTF8atZfS5YAMlZG/g16g==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star diegoo/getting-and-cleaning-data-assignment"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/diegoo/getting-and-cleaning-data-assignment/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/fork" class="btn-with-count" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="6stjZsEUMhwSroIIfzxStpL8qkF6h0csZtTt5kvqyA8B0tsnyTj6m/dg4JyPv/SC+oco+/Xj/ekn/WeW8doxbg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of diegoo/getting-and-cleaning-data-assignment to your account"
                aria-label="Fork your own copy of diegoo/getting-and-cleaning-data-assignment to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
</form>
    <a href="/diegoo/getting-and-cleaning-data-assignment/network" class="social-count">
      1
    </a>
  </li>
</ul>

          <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="mega-octicon octicon-repo"></span>
  <span class="author"><a href="/diegoo" class="url fn" itemprop="url" rel="author"><span itemprop="title">diegoo</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/diegoo/getting-and-cleaning-data-assignment" data-pjax="#js-repo-pjax-container">getting-and-cleaning-data-assignment</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

</h1>

        </div>
      </div>
    </div>

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline ">
        <div class="repository-sidebar clearfix">
          
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/diegoo/getting-and-cleaning-data-assignment/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/diegoo/getting-and-cleaning-data-assignment" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /diegoo/getting-and-cleaning-data-assignment">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/diegoo/getting-and-cleaning-data-assignment/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /diegoo/getting-and-cleaning-data-assignment/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/diegoo/getting-and-cleaning-data-assignment/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /diegoo/getting-and-cleaning-data-assignment/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/diegoo/getting-and-cleaning-data-assignment/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /diegoo/getting-and-cleaning-data-assignment/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/diegoo/getting-and-cleaning-data-assignment/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /diegoo/getting-and-cleaning-data-assignment/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/diegoo/getting-and-cleaning-data-assignment/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /diegoo/getting-and-cleaning-data-assignment/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

            <div class="only-with-full-nav">
                
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3 class="text-small text-muted"><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/diegoo/getting-and-cleaning-data-assignment.git" readonly="readonly" aria-label="HTTPS clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3 class="text-small text-muted"><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:diegoo/getting-and-cleaning-data-assignment.git" readonly="readonly" aria-label="SSH clone URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3 class="text-small text-muted"><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini text-small text-muted input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/diegoo/getting-and-cleaning-data-assignment" readonly="readonly" aria-label="Subversion checkout URL">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options text-small text-muted">You can clone with
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NzGcGGk9ySuIrUNmDnx/ZsjOkoNJCyKuf6mkfFjeOLNN2fiQU4giLeo0j5yNkzmDchCZPTLyaD/vFP1kWxI+nA==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DK9ciB4x0LTFfydzNGVjEHCQO85RbU4PIC9noa5EtP1ihUOa4WiOQm7JVquheSPaZKH9l5GhoxMGL8/S/KYTCQ==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="I/KD1WUsTNNMSpGOqiGg4vDvNuIPubBfXKy5zr64dz/QRNXFrwZHE95oibCPvWBbWB+VZMzyH1wOz0sOACCtKw==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>
  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save diegoo/getting-and-cleaning-data-assignment to your computer and use it in GitHub Desktop." aria-label="Save diegoo/getting-and-cleaning-data-assignment to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-desktop-download"></span>
    Clone in Desktop
  </a>

              <a href="/diegoo/getting-and-cleaning-data-assignment/archive/master.zip"
                 class="btn btn-sm sidebar-button"
                 aria-label="Download the contents of diegoo/getting-and-cleaning-data-assignment as a zip file"
                 title="Download the contents of diegoo/getting-and-cleaning-data-assignment as a zip file"
                 rel="nofollow">
                <span class="octicon octicon-cloud-download"></span>
                Download ZIP
              </a>
            </div>
        </div>
        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/diegoo/getting-and-cleaning-data-assignment/blob/86fe7f91909d4ddc41891137f93d7a1ea20c2ea7/CodeBook.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:cab0bd7860fb6d3125bfe40ca53a8c51 -->

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
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
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
               href="/diegoo/getting-and-cleaning-data-assignment/blob/master/CodeBook.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
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
      <a href="/diegoo/getting-and-cleaning-data-assignment/find/master"
            class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-nw"
            data-pjax
            data-hotkey="t"
            aria-label="Quickly jump between files">
        <span class="octicon octicon-list-unordered"></span>
      </a>
      <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </div>

    <div class="breadcrumb js-zeroclipboard-target">
      <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/diegoo/getting-and-cleaning-data-assignment" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">getting-and-cleaning-data-assignment</span></a></span></span><span class="separator">/</span><strong class="final-path">CodeBook.md</strong>
    </div>
  </div>

<include-fragment class="commit-tease" src="/diegoo/getting-and-cleaning-data-assignment/contributors/master/CodeBook.md">
  <div>
    Fetching contributors&hellip;
  </div>

  <div class="commit-tease-contributors">
    <img alt="" class="loader-loading left" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" />
    <span class="loader-error">Cannot retrieve contributors at this time</span>
  </div>
</include-fragment>
<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/diegoo/getting-and-cleaning-data-assignment/raw/master/CodeBook.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/diegoo/getting-and-cleaning-data-assignment/blame/master/CodeBook.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/diegoo/getting-and-cleaning-data-assignment/commits/master/CodeBook.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

      <a class="octicon-btn tooltipped tooltipped-nw"
         href="https://windows.github.com"
         aria-label="Open this file in GitHub Desktop"
         data-ga-click="Repository, open with desktop, type:windows">
          <span class="octicon octicon-device-desktop"></span>
      </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/edit/master/CodeBook.md" class="inline-form js-update-url-with-hash" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="3spqt3+T96tVSTU+0ioldH4ZE/6hlING23Q276b4YW0ieMoTyed8SV0wYs2YMyvrHxObezixxyLK0v4AKT38lw==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/diegoo/getting-and-cleaning-data-assignment/delete/master/CodeBook.md" class="inline-form" data-form-nonce="af76fbd4df014740dd1a2ed255f1e76f739379a4" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="0QkpV1ZosMBD5fAvMwjMa2C0C2+goOguxoeBmsMGiweNBNe71ZmAMIVpdZsnExJKhELZPtQ6SDOnhApH8s6e7w==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <span class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      100 lines (85 sloc)
      <span class="file-info-divider"></span>
    2.59 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-code-book" class="anchor" href="#code-book" aria-hidden="true"><span class="octicon octicon-link"></span></a>Code Book</h1>

<h2><a id="user-content-variables" class="anchor" href="#variables" aria-hidden="true"><span class="octicon octicon-link"></span></a>variables</h2>

<h3><a id="user-content-subject" class="anchor" href="#subject" aria-hidden="true"><span class="octicon octicon-link"></span></a>subject</h3>

<p>experiment participant (id)</p>

<h3><a id="user-content-activity" class="anchor" href="#activity" aria-hidden="true"><span class="octicon octicon-link"></span></a>activity</h3>

<table><thead>
<tr>
<th align="right">id</th>
<th align="center">name</th>
</tr>
</thead><tbody>
<tr>
<td align="right">1</td>
<td align="center">WALKING</td>
</tr>
<tr>
<td align="right">2</td>
<td align="center">WALKING_UPSTAIRS</td>
</tr>
<tr>
<td align="right">3</td>
<td align="center">WALKING_DOWNSTAIRS</td>
</tr>
<tr>
<td align="right">4</td>
<td align="center">SITTING</td>
</tr>
<tr>
<td align="right">5</td>
<td align="center">STANDING</td>
</tr>
<tr>
<td align="right">6</td>
<td align="center">LAYING</td>
</tr>
</tbody></table>

<h3><a id="user-content-features" class="anchor" href="#features" aria-hidden="true"><span class="octicon octicon-link"></span></a>features</h3>

<p>Column numbers are extracted from the original data file, <code>UCI HAR Dataset/features.txt</code></p>

<table><thead>
<tr>
<th align="right">feature column number</th>
<th align="center">feature column name</th>
</tr>
</thead><tbody>
<tr>
<td align="right">1</td>
<td align="center">tBodyAcc-mean()-X</td>
</tr>
<tr>
<td align="right">2</td>
<td align="center">tBodyAcc-mean()-Y</td>
</tr>
<tr>
<td align="right">3</td>
<td align="center">tBodyAcc-mean()-Z</td>
</tr>
<tr>
<td align="right">4</td>
<td align="center">tBodyAcc-std()-X</td>
</tr>
<tr>
<td align="right">5</td>
<td align="center">tBodyAcc-std()-Y</td>
</tr>
<tr>
<td align="right">6</td>
<td align="center">tBodyAcc-std()-Z</td>
</tr>
<tr>
<td align="right">41</td>
<td align="center">tGravityAcc-mean()-X</td>
</tr>
<tr>
<td align="right">42</td>
<td align="center">tGravityAcc-mean()-Y</td>
</tr>
<tr>
<td align="right">43</td>
<td align="center">tGravityAcc-mean()-Z</td>
</tr>
<tr>
<td align="right">44</td>
<td align="center">tGravityAcc-std()-X</td>
</tr>
<tr>
<td align="right">45</td>
<td align="center">tGravityAcc-std()-Y</td>
</tr>
<tr>
<td align="right">46</td>
<td align="center">tGravityAcc-std()-Z</td>
</tr>
<tr>
<td align="right">81</td>
<td align="center">tBodyAccJerk-mean()-X</td>
</tr>
<tr>
<td align="right">82</td>
<td align="center">tBodyAccJerk-mean()-Y</td>
</tr>
<tr>
<td align="right">83</td>
<td align="center">tBodyAccJerk-mean()-Z</td>
</tr>
<tr>
<td align="right">84</td>
<td align="center">tBodyAccJerk-std()-X</td>
</tr>
<tr>
<td align="right">85</td>
<td align="center">tBodyAccJerk-std()-Y</td>
</tr>
<tr>
<td align="right">86</td>
<td align="center">tBodyAccJerk-std()-Z</td>
</tr>
<tr>
<td align="right">121</td>
<td align="center">tBodyGyro-mean()-X</td>
</tr>
<tr>
<td align="right">122</td>
<td align="center">tBodyGyro-mean()-Y</td>
</tr>
<tr>
<td align="right">123</td>
<td align="center">tBodyGyro-mean()-Z</td>
</tr>
<tr>
<td align="right">124</td>
<td align="center">tBodyGyro-std()-X</td>
</tr>
<tr>
<td align="right">125</td>
<td align="center">tBodyGyro-std()-Y</td>
</tr>
<tr>
<td align="right">126</td>
<td align="center">tBodyGyro-std()-Z</td>
</tr>
<tr>
<td align="right">161</td>
<td align="center">tBodyGyroJerk-mean()-X</td>
</tr>
<tr>
<td align="right">162</td>
<td align="center">tBodyGyroJerk-mean()-Y</td>
</tr>
<tr>
<td align="right">163</td>
<td align="center">tBodyGyroJerk-mean()-Z</td>
</tr>
<tr>
<td align="right">164</td>
<td align="center">tBodyGyroJerk-std()-X</td>
</tr>
<tr>
<td align="right">165</td>
<td align="center">tBodyGyroJerk-std()-Y</td>
</tr>
<tr>
<td align="right">166</td>
<td align="center">tBodyGyroJerk-std()-Z</td>
</tr>
<tr>
<td align="right">201</td>
<td align="center">tBodyAccMag-mean()</td>
</tr>
<tr>
<td align="right">202</td>
<td align="center">tBodyAccMag-std()</td>
</tr>
<tr>
<td align="right">214</td>
<td align="center">tGravityAccMag-mean()</td>
</tr>
<tr>
<td align="right">215</td>
<td align="center">tGravityAccMag-std()</td>
</tr>
<tr>
<td align="right">227</td>
<td align="center">tBodyAccJerkMag-mean()</td>
</tr>
<tr>
<td align="right">228</td>
<td align="center">tBodyAccJerkMag-std()</td>
</tr>
<tr>
<td align="right">240</td>
<td align="center">tBodyGyroMag-mean()</td>
</tr>
<tr>
<td align="right">241</td>
<td align="center">tBodyGyroMag-std()</td>
</tr>
<tr>
<td align="right">253</td>
<td align="center">tBodyGyroJerkMag-mean()</td>
</tr>
<tr>
<td align="right">254</td>
<td align="center">tBodyGyroJerkMag-std()</td>
</tr>
<tr>
<td align="right">266</td>
<td align="center">fBodyAcc-mean()-X</td>
</tr>
<tr>
<td align="right">267</td>
<td align="center">fBodyAcc-mean()-Y</td>
</tr>
<tr>
<td align="right">268</td>
<td align="center">fBodyAcc-mean()-Z</td>
</tr>
<tr>
<td align="right">269</td>
<td align="center">fBodyAcc-std()-X</td>
</tr>
<tr>
<td align="right">270</td>
<td align="center">fBodyAcc-std()-Y</td>
</tr>
<tr>
<td align="right">271</td>
<td align="center">fBodyAcc-std()-Z</td>
</tr>
<tr>
<td align="right">345</td>
<td align="center">fBodyAccJerk-mean()-X</td>
</tr>
<tr>
<td align="right">346</td>
<td align="center">fBodyAccJerk-mean()-Y</td>
</tr>
<tr>
<td align="right">347</td>
<td align="center">fBodyAccJerk-mean()-Z</td>
</tr>
<tr>
<td align="right">348</td>
<td align="center">fBodyAccJerk-std()-X</td>
</tr>
<tr>
<td align="right">349</td>
<td align="center">fBodyAccJerk-std()-Y</td>
</tr>
<tr>
<td align="right">350</td>
<td align="center">fBodyAccJerk-std()-Z</td>
</tr>
<tr>
<td align="right">424</td>
<td align="center">fBodyGyro-mean()-X</td>
</tr>
<tr>
<td align="right">425</td>
<td align="center">fBodyGyro-mean()-Y</td>
</tr>
<tr>
<td align="right">426</td>
<td align="center">fBodyGyro-mean()-Z</td>
</tr>
<tr>
<td align="right">427</td>
<td align="center">fBodyGyro-std()-X</td>
</tr>
<tr>
<td align="right">428</td>
<td align="center">fBodyGyro-std()-Y</td>
</tr>
<tr>
<td align="right">429</td>
<td align="center">fBodyGyro-std()-Z</td>
</tr>
<tr>
<td align="right">503</td>
<td align="center">fBodyAccMag-mean()</td>
</tr>
<tr>
<td align="right">504</td>
<td align="center">fBodyAccMag-std()</td>
</tr>
<tr>
<td align="right">516</td>
<td align="center">fBodyBodyAccJerkMag-mean()</td>
</tr>
<tr>
<td align="right">517</td>
<td align="center">fBodyBodyAccJerkMag-std()</td>
</tr>
<tr>
<td align="right">529</td>
<td align="center">fBodyBodyGyroMag-mean()</td>
</tr>
<tr>
<td align="right">530</td>
<td align="center">fBodyBodyGyroMag-std()</td>
</tr>
<tr>
<td align="right">542</td>
<td align="center">fBodyBodyGyroJerkMag-mean()</td>
</tr>
<tr>
<td align="right">543</td>
<td align="center">fBodyBodyGyroJerkMag-std()</td>
</tr>
</tbody></table>

<h3><a id="user-content-note" class="anchor" href="#note" aria-hidden="true"><span class="octicon octicon-link"></span></a>Note:</h3>

<p>I chose to exclude <code>meanFreq()</code> quantities, since they are not the same type of measurement as <code>mean()</code> (if I understand correctly the original README.md) </p>
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
      </div>
      <div class="modal-backdrop"></div>
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
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.07653s from github-fe121-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-161cec7f4cb9a187f66c2ecb8f59c9098e2ad64458af917ec72f9d61d6b8089b.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-e86725a26cd06610bcb4eb0595c577ff55ce0278be0e917357c284057de00c04.js"></script>
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

