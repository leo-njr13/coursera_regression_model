



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>Coursera-Regression-Models/report.md at master · Xiaodan/Coursera-Regression-Models</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="Xiaodan/Coursera-Regression-Models" name="twitter:title" /><meta content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/1871047?v=3&amp;s=400" property="og:image" /><meta content="Xiaodan/Coursera-Regression-Models" property="og:title" /><meta content="https://github.com/Xiaodan/Coursera-Regression-Models" property="og:url" /><meta content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models" property="og:description" />

      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="6A338890:72C8:E02A5DC:54D0B606" name="octolytics-dimension-request_id" /><meta content="8363382" name="octolytics-actor-id" /><meta content="leo-njr13" name="octolytics-actor-login" /><meta content="8ec6d40538c542cf55b24252fc42c4ce971e963fa0fb8661c86933dc08bcaa00" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="kA5xoALxPJGsMSLJqcT1xR4jo1otaL1mTRCClevpGcy7WnWYSBGKLWeQRKZNqg+49zclqUAdeBc2GBNXNeqc8A==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-e3321d79480f0738576ff81cb2f3f717fdbb0bf35ea5938c30005a3349371133.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-6a66f68bf38641cc43f50402e8c57e8877e13f6772ebccbf99e988ca628e5ccd.css" media="all" rel="stylesheet" type="text/css" />
    
    


    <meta http-equiv="x-pjax-version" content="ec9e27f39f1653a03c9697c87f9e4842">

      
  <meta name="description" content="Coursera-Regression-Models - Repo for Coursera.com online course: Regression Models">
  <meta name="go-import" content="github.com/Xiaodan/Coursera-Regression-Models git https://github.com/Xiaodan/Coursera-Regression-Models.git">

  <meta content="1871047" name="octolytics-dimension-user_id" /><meta content="Xiaodan" name="octolytics-dimension-user_login" /><meta content="22655652" name="octolytics-dimension-repository_id" /><meta content="Xiaodan/Coursera-Regression-Models" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="22655652" name="octolytics-dimension-repository_network_root_id" /><meta content="Xiaodan/Coursera-Regression-Models" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/Xiaodan/Coursera-Regression-Models/commits/master.atom" rel="alternate" title="Recent Commits to Coursera-Regression-Models:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" ga-data-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/Xiaodan/Coursera-Regression-Models/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/Xiaodan/Coursera-Regression-Models/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/leo-njr13" data-ga-click="Header, go to profile, text:username">
      <img alt="leo-njr13" class="avatar" data-user="8363382" height="20" src="https://avatars1.githubusercontent.com/u/8363382?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">leo-njr13</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="Xiaodan/Coursera-Regression-Models">This repository</span>
    </li>
      <li>
        <a href="/Xiaodan/Coursera-Regression-Models/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="zAgotd4P6rB1qCebkOelTqgYBwfhIY0w/dOjF40/OKxZ54eugXyfHdB0nQ5uHlB2brBYfpENocUANVknc/3L7A==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hlaaGSC5XIGhA57deccBrcCHSH7sGeaDJTTM/nuIrIVIekmuZ7iaCY2rdRJbKVPhdbT9JKAozntBj6IG5VXI7Q==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="22655652" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/Xiaodan/Coursera-Regression-Models/watchers">
        0
      </a>
      <a href="/Xiaodan/Coursera-Regression-Models/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/Xiaodan/Coursera-Regression-Models/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="1eodKrBEnLn6PF6qtWnMJGhQVVkI4Zrw2zut7PwEOfCAUfvTx7FnkKkFB0rXgO712PRuLPzuDCy0fFul43gBiA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar Xiaodan/Coursera-Regression-Models">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/Xiaodan/Coursera-Regression-Models/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/Xiaodan/Coursera-Regression-Models/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="h5xOJ6xfNy6fwNj4nokX5xuVUNanUTvJTLdWKPzWnzGxY1X9qW/KIDji8dV+4PN2ycZ6Q+EnNDMnBLj76HrO1A==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star Xiaodan/Coursera-Regression-Models">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/Xiaodan/Coursera-Regression-Models/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/Xiaodan/Coursera-Regression-Models/fork" class="minibutton with-count js-toggler-target fork-button tooltipped-n" title="Fork your own copy of Xiaodan/Coursera-Regression-Models to your account" aria-label="Fork your own copy of Xiaodan/Coursera-Regression-Models to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/Xiaodan/Coursera-Regression-Models/network" class="social-count">5</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/Xiaodan" class="url fn" itemprop="url" rel="author"><span itemprop="title">Xiaodan</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/Xiaodan/Coursera-Regression-Models" class="js-current-repository" data-pjax="#js-repo-pjax-container">Coursera-Regression-Models</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/Xiaodan/Coursera-Regression-Models/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/Xiaodan/Coursera-Regression-Models" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /Xiaodan/Coursera-Regression-Models">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/Xiaodan/Coursera-Regression-Models/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /Xiaodan/Coursera-Regression-Models/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
      <a href="/Xiaodan/Coursera-Regression-Models/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /Xiaodan/Coursera-Regression-Models/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/Xiaodan/Coursera-Regression-Models/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /Xiaodan/Coursera-Regression-Models/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/Xiaodan/Coursera-Regression-Models/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /Xiaodan/Coursera-Regression-Models/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/Xiaodan/Coursera-Regression-Models/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /Xiaodan/Coursera-Regression-Models/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/Xiaodan/Coursera-Regression-Models.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:Xiaodan/Coursera-Regression-Models.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/Xiaodan/Coursera-Regression-Models" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/Xiaodan/Coursera-Regression-Models" class="minibutton sidebar-button" title="Save Xiaodan/Coursera-Regression-Models to your computer and use it in GitHub Desktop." aria-label="Save Xiaodan/Coursera-Regression-Models to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/Xiaodan/Coursera-Regression-Models/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of Xiaodan/Coursera-Regression-Models as a zip file"
                   title="Download the contents of Xiaodan/Coursera-Regression-Models as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/Xiaodan/Coursera-Regression-Models/blob/6d9eb475e0376d8d24672ebcbd53b36c8ad3c473/motor_trend_project/report.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:224aba0a6df08e0488d512b5694f1907 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/Xiaodan/Coursera-Regression-Models/blob/master/motor_trend_project/report.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/Xiaodan/Coursera-Regression-Models/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/Xiaodan/Coursera-Regression-Models" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">Coursera-Regression-Models</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/Xiaodan/Coursera-Regression-Models/tree/master/motor_trend_project" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">motor_trend_project</span></a></span><span class="separator">/</span><strong class="final-path">report.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="Sally Zhang" class="avatar" data-user="1871047" height="24" src="https://avatars1.githubusercontent.com/u/1871047?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/Xiaodan" rel="author">Xiaodan</a></span>
        <time datetime="2015-01-25T17:04:49Z" is="relative-time">Jan 25, 2015</time>
        <div class="commit-title">
            <a href="/Xiaodan/Coursera-Regression-Models/commit/72e0d2014a10890d2c97425bd8ccd6d8751878c3" class="message" data-pjax="true" title="Update report.md">Update report.md</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="Sally Zhang" data-user="1871047" height="24" src="https://avatars1.githubusercontent.com/u/1871047?v=3&amp;s=48" width="24" />
            <a href="/Xiaodan">Xiaodan</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>189 lines (150 sloc)</span>
          <span class="meta-divider"></span>
        <span>8.702 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/Xiaodan/Coursera-Regression-Models/raw/master/motor_trend_project/report.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/Xiaodan/Coursera-Regression-Models/blame/master/motor_trend_project/report.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/Xiaodan/Coursera-Regression-Models/commits/master/motor_trend_project/report.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

          <a class="octicon-button tooltipped tooltipped-nw"
             href="github-windows://openRepo/https://github.com/Xiaodan/Coursera-Regression-Models?branch=master&amp;filepath=motor_trend_project%2Freport.md" aria-label="Open this file in GitHub for Windows">
              <span class="octicon octicon-device-desktop"></span>
          </a>

              <a class="octicon-button tooltipped tooltipped-n js-update-url-with-hash"
                 aria-label="Clicking this button will fork this project so you can edit the file"
                 href="/Xiaodan/Coursera-Regression-Models/edit/master/motor_trend_project/report.md"
                 data-method="post" rel="nofollow"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger tooltipped tooltipped-s"
               href="/Xiaodan/Coursera-Regression-Models/delete/master/motor_trend_project/report.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
    
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><table data-table-type="yaml-metadata">
  <thead>
  <tr>
  <th>title</th>

  <th>author</th>

  <th>output</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>Regression Models Project - Motor Trend Data Analysis Report</div></td>

  <td><div>by Xiaodan (Sally) Zhang</div></td>

  <td><div><table>
  <thead>
  <tr>
  <th>pdf_document</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div><table>
  <thead>
  <tr>
  <th>fig_height</th>

  <th>fig_width</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><div>7</div></td>

  <td><div>7</div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table></div></td>
  </tr>
  </tbody>
</table><h2>
<a id="user-content-executive-summary" class="anchor" href="#executive-summary" aria-hidden="true"><span class="octicon octicon-link"></span></a>Executive Summary</h2>

<p>In this report, we will analyze <code>mtcars</code> data set and explore the relationship between a set of variables and miles per gallon (MPG). The data was extracted from the 1974 <em>Motor Trend</em> US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973–74 models). We use regression models and exploratory data analyses to mainly explore how <strong>automatic</strong> (am = 0) and <strong>manual</strong> (am = 1) transmissions features affect the <strong>MPG</strong> feature. The t-test shows that the performance difference between cars with automatic and manual transmission. And it is about 7 MPG more for cars with manual transmission than those with automatic transmission. Then, we fit several linear regression models and select the one with highest Adjusted R-squared value. So, given that weight and 1/4 mile time are held constant, manual transmitted cars are 14.079 + (-4.141)*weight more MPG (miles per gallon) on average better than automatic transmitted cars. Thus, cars that are lighter in weight with a manual transmission and cars that are heavier in weight with an automatic transmission will have higher MPG values.</p>

<h2>
<a id="user-content-exploratory-data-analysis" class="anchor" href="#exploratory-data-analysis" aria-hidden="true"><span class="octicon octicon-link"></span></a>Exploratory Data Analysis</h2>

<p>First, we load the data set <code>mtcars</code> and change some variables from <code>numeric</code> class to <code>factor</code> class.   </p>

<div class="highlight highlight-r"><pre>library(<span class="pl-vo">ggplot2</span>)
data(<span class="pl-vo">mtcars</span>)
<span class="pl-vo">mtcars</span>[<span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-c1">3</span>, ] <span class="pl-c"># Sample Data</span></pre></div>

<pre><code>##                mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4     21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag 21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710    22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
</code></pre>

<div class="highlight highlight-r"><pre>dim(<span class="pl-vo">mtcars</span>)</pre></div>

<pre><code>## [1] 32 11
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">cyl</span> <span class="pl-k">&lt;-</span> as.factor(<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">cyl</span>)
<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">vs</span> <span class="pl-k">&lt;-</span> as.factor(<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">vs</span>)
<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">am</span> <span class="pl-k">&lt;-</span> <span class="pl-st">factor</span>(<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">am</span>)
<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">gear</span> <span class="pl-k">&lt;-</span> <span class="pl-st">factor</span>(<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">gear</span>)
<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">carb</span> <span class="pl-k">&lt;-</span> <span class="pl-st">factor</span>(<span class="pl-vo">mtcars</span><span class="pl-k">$</span><span class="pl-vo">carb</span>)
attach(<span class="pl-vo">mtcars</span>)</pre></div>

<pre><code>## The following objects are masked from mtcars (pos = 3):
## 
##     am, carb, cyl, disp, drat, gear, hp, mpg, qsec, vs, wt
## 
## The following objects are masked from mtcars (pos = 4):
## 
##     am, carb, cyl, disp, drat, gear, hp, mpg, qsec, vs, wt
## 
## The following object is masked from package:ggplot2:
## 
##     mpg
</code></pre>

<p>Then, we do some basic exploratory data analyses. Please refer to the <strong>Appendix: Figures</strong> section for the plots. According to the box plot, we see that manual transmission yields higher values of MPG in general. And as for the pair graph, we can see some higher correlations between variables like "wt", "disp", "cyl" and "hp".  </p>

<h2>
<a id="user-content-inference" class="anchor" href="#inference" aria-hidden="true"><span class="octicon octicon-link"></span></a>Inference</h2>

<p>At this step, we make the null hypothesis as the MPG of the automatic and manual transmissions are from the same population (assuming the MPG has a normal distribution). We use the two sample T-test to show it.  </p>

<div class="highlight highlight-r"><pre><span class="pl-vo">result</span> <span class="pl-k">&lt;-</span> t.test(<span class="pl-vo">mpg</span> <span class="pl-k">~</span> <span class="pl-vo">am</span>)
<span class="pl-vo">result</span><span class="pl-k">$</span><span class="pl-vo">p.value</span></pre></div>

<pre><code>## [1] 0.001373638
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-vo">result</span><span class="pl-k">$</span><span class="pl-vo">estimate</span></pre></div>

<pre><code>## mean in group 0 mean in group 1 
##        17.14737        24.39231
</code></pre>

<p>Since the p-value is 0.00137, we reject our null hypothesis. So, the automatic and manual transmissions are from different populations. And the mean for MPG of manual transmitted cars is about 7 more than that of automatic transmitted cars.  </p>

<h2>
<a id="user-content-regression-analysis" class="anchor" href="#regression-analysis" aria-hidden="true"><span class="octicon octicon-link"></span></a>Regression Analysis</h2>

<p>First, we fit the full model as the following.  </p>

<div class="highlight highlight-r"><pre><span class="pl-vo">fullModel</span> <span class="pl-k">&lt;-</span> lm(<span class="pl-vo">mpg</span> <span class="pl-k">~</span> ., <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-vo">mtcars</span>)
summary(<span class="pl-vo">fullModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model has the Residual standard error as 2.833 on 15 degrees of freedom. And the Adjusted R-squared value is 0.779, which means that the model can explain about 78% of the variance of the MPG variable. However, none of the coefficients are significant at 0.05 significant level.  </p>

<p>Then, we use backward selection to select some statistically significant variables.  </p>

<div class="highlight highlight-r"><pre><span class="pl-vo">stepModel</span> <span class="pl-k">&lt;-</span> step(<span class="pl-vo">fullModel</span>, <span class="pl-v">k</span><span class="pl-k">=</span>log(nrow(<span class="pl-vo">mtcars</span>)))
summary(<span class="pl-vo">stepModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model is "mpg ~ wt + qsec + am". It has the Residual standard error as 2.459 on 28 degrees of freedom. And the Adjusted R-squared value is 0.8336, which means that the model can explain about 83% of the variance of the MPG variable. All of the coefficients are significant at 0.05 significant level.    </p>

<p>Please refer to the <strong>Appendix: Figures</strong> section for the plots again. According to the scatter plot, it indicates that there appear to be an interaction term between "wt" variable and "am" variable, since automatic cars tend to weigh heavier than manual cars. Thus, we have the following model including the interaction term:  </p>

<div class="highlight highlight-r"><pre><span class="pl-vo">amIntWtModel</span><span class="pl-k">&lt;-</span>lm(<span class="pl-vo">mpg</span> <span class="pl-k">~</span> <span class="pl-vo">wt</span> <span class="pl-k">+</span> <span class="pl-vo">qsec</span> <span class="pl-k">+</span> <span class="pl-vo">am</span> <span class="pl-k">+</span> <span class="pl-vo">wt</span><span class="pl-k">:</span><span class="pl-vo">am</span>, <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-vo">mtcars</span>)
summary(<span class="pl-vo">amIntWtModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>This model has the Residual standard error as 2.084 on 27 degrees of freedom. And the Adjusted R-squared value is 0.8804, which means that the model can explain about 88% of the variance of the MPG variable. All of the coefficients are significant at 0.05 significant level. This is a pretty good one.  </p>

<p>Next, we fit the simple model with MPG as the outcome variable and Transmission as the predictor variable.  </p>

<div class="highlight highlight-r"><pre><span class="pl-vo">amModel</span><span class="pl-k">&lt;-</span>lm(<span class="pl-vo">mpg</span> <span class="pl-k">~</span> <span class="pl-vo">am</span>, <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-vo">mtcars</span>)
summary(<span class="pl-vo">amModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>It shows that on average, a car has 17.147 mpg with automatic transmission, and if it is manual transmission, 7.245 mpg is increased. This model has the Residual standard error as 4.902 on 30 degrees of freedom. And the Adjusted R-squared value is 0.3385, which means that the model can explain about 34% of the variance of the MPG variable. The low Adjusted R-squared value also indicates that we need to add other variables to the model.  </p>

<p>Finally, we select the final model.  </p>

<div class="highlight highlight-r"><pre>anova(<span class="pl-vo">amModel</span>, <span class="pl-vo">stepModel</span>, <span class="pl-vo">fullModel</span>, <span class="pl-vo">amIntWtModel</span>) 
confint(<span class="pl-vo">amIntWtModel</span>) <span class="pl-c"># results hidden</span></pre></div>

<p>We end up selecting the model with the highest Adjusted R-squared value, "mpg ~ wt + qsec + am + wt:am".  </p>

<div class="highlight highlight-r"><pre>summary(<span class="pl-vo">amIntWtModel</span>)<span class="pl-k">$</span><span class="pl-vo">coef</span></pre></div>

<pre><code>##              Estimate Std. Error   t value     Pr(&gt;|t|)
## (Intercept)  9.723053  5.8990407  1.648243 0.1108925394
## wt          -2.936531  0.6660253 -4.409038 0.0001488947
## qsec         1.016974  0.2520152  4.035366 0.0004030165
## am1         14.079428  3.4352512  4.098515 0.0003408693
## wt:am1      -4.141376  1.1968119 -3.460340 0.0018085763
</code></pre>

<p>Thus, the result shows that when "wt" (weight lb/1000) and "qsec" (1/4 mile time) remain constant, cars with manual transmission add 14.079 + (-4.141)*wt more MPG (miles per gallon) on average than cars with automatic transmission. That is, a manual transmitted car that weighs 2000 lbs have 5.797 more MPG than an automatic transmitted car that has both the same weight and 1/4 mile time.  </p>

<h2>
<a id="user-content-residual-analysis-and-diagnostics" class="anchor" href="#residual-analysis-and-diagnostics" aria-hidden="true"><span class="octicon octicon-link"></span></a>Residual Analysis and Diagnostics</h2>

<p>Please refer to the <strong>Appendix: Figures</strong> section for the plots. According to the residual plots, we can verify the following underlying assumptions:<br>
1. The Residuals vs. Fitted plot shows no consistent pattern, supporting the accuracy of the independence assumption.<br>
2. The Normal Q-Q plot indicates that the residuals are normally distributed because the points lie closely to the line.<br>
3. The Scale-Location plot confirms the constant variance assumption, as the points are randomly distributed.<br>
4. The Residuals vs. Leverage argues that no outliers are present, as all values fall well within the 0.5 bands.  </p>

<p>As for the Dfbetas, the measure of how much an observation has effected the estimate of a regression coefficient, we get the following result:  </p>

<div class="highlight highlight-r"><pre>sum((abs(dfbetas(<span class="pl-vo">amIntWtModel</span>)))<span class="pl-k">&gt;</span><span class="pl-c1">1</span>)</pre></div>

<pre><code>## [1] 0
</code></pre>

<p>Therefore, the above analyses meet all basic assumptions of linear regression and well answer the questions.  </p>

<h2>
<a id="user-content-appendix-figures" class="anchor" href="#appendix-figures" aria-hidden="true"><span class="octicon octicon-link"></span></a>Appendix: Figures</h2>

<ol class="task-list">
<li>Boxplot of MPG vs. Transmission<br>
</li>
</ol>

<div class="highlight highlight-r"><pre>boxplot(<span class="pl-vo">mpg</span> <span class="pl-k">~</span> <span class="pl-vo">am</span>, <span class="pl-v">xlab</span><span class="pl-k">=</span><span class="pl-s1"><span class="pl-pds">"</span>Transmission (0 = Automatic, 1 = Manual)<span class="pl-pds">"</span></span>, <span class="pl-v">ylab</span><span class="pl-k">=</span><span class="pl-s1"><span class="pl-pds">"</span>MPG<span class="pl-pds">"</span></span>,
        <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s1"><span class="pl-pds">"</span>Boxplot of MPG vs. Transmission<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-10-1.png" target="_blank"><img src="/Xiaodan/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-10-1.png" alt="plot of chunk unnamed-chunk-10" style="max-width:100%;"></a><br>
2. Pair Graph of Motor Trend Car Road Tests  </p>

<div class="highlight highlight-r"><pre>pairs(<span class="pl-vo">mtcars</span>, <span class="pl-v">panel</span><span class="pl-k">=</span><span class="pl-vo">panel.smooth</span>, <span class="pl-v">main</span><span class="pl-k">=</span><span class="pl-s1"><span class="pl-pds">"</span>Pair Graph of Motor Trend Car Road Tests<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-11-1.png" target="_blank"><img src="/Xiaodan/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-11-1.png" alt="plot of chunk unnamed-chunk-11" style="max-width:100%;"></a><br>
3. Scatter Plot of MPG vs. Weight by Transmission  </p>

<div class="highlight highlight-r"><pre>ggplot(<span class="pl-vo">mtcars</span>, aes(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-vo">wt</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-vo">mpg</span>, <span class="pl-v">group</span><span class="pl-k">=</span><span class="pl-vo">am</span>, <span class="pl-v">color</span><span class="pl-k">=</span><span class="pl-vo">am</span>, <span class="pl-v">height</span><span class="pl-k">=</span><span class="pl-c1">3</span>, <span class="pl-v">width</span><span class="pl-k">=</span><span class="pl-c1">3</span>)) <span class="pl-k">+</span> geom_point() <span class="pl-k">+</span>  
scale_colour_discrete(<span class="pl-v">labels</span><span class="pl-k">=</span>c(<span class="pl-s1"><span class="pl-pds">"</span>Automatic<span class="pl-pds">"</span></span>, <span class="pl-s1"><span class="pl-pds">"</span>Manual<span class="pl-pds">"</span></span>)) <span class="pl-k">+</span> 
xlab(<span class="pl-s1"><span class="pl-pds">"</span>weight<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> ggtitle(<span class="pl-s1"><span class="pl-pds">"</span>Scatter Plot of MPG vs. Weight by Transmission<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Xiaodan/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-12-1.png" target="_blank"><img src="/Xiaodan/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-12-1.png" alt="plot of chunk unnamed-chunk-12" style="max-width:100%;"></a><br>
4. Residual Plots</p>

<div class="highlight highlight-r"><pre>par(<span class="pl-v">mfrow</span> <span class="pl-k">=</span> c(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>))
plot(<span class="pl-vo">amIntWtModel</span>)</pre></div>

<p><a href="/Xiaodan/Coursera-Regression-Models/blob/master/motor_trend_project/figure/unnamed-chunk-13-1.png" target="_blank"><img src="/Xiaodan/Coursera-Regression-Models/raw/master/motor_trend_project/figure/unnamed-chunk-13-1.png" alt="plot of chunk unnamed-chunk-13" style="max-width:100%;"></a> </p>
</article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="https://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05034s from github-fe138-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-af95b05cb14b7a29b0457c26b4a1d24151f4a47842c8e74bd556622f347b9d3d.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-48e1b4f1ba19a995fb5b6503c23c059ae885b47f760a1ee39ea676b991de5046.js" type="text/javascript"></script>
      
      
  </body>
</html>

