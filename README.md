# piccoin-open-source-piccoin-open-source
piccoin-open-source
 <meta property="og:title" content="Git Large File Storage">
  <meta property="og:description" content="Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://git-lfs.github.com">
  <meta property="og:image" content="https://git-lfs.github.com/images/facebook-promo.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:site" content="@github">
  <meta name="twitter:creator" content="@github">
  <meta name="twitter:title" content="Git Large File Storage">
  <meta name="twitter:description" content="Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.">
  <meta name="twitter:image:src" content="https://git-lfs.github.com/images/tweet-promo.png">
  <link rel="stylesheet" href="/css/main.css">
  <link rel="canonical" href="https://git-lfs.github.com/">
  <link rel="icon" type="image/x-icon" href="/favicon.png" />
  <script src="/js/application.js" type="text/javascript"></script>
  <script src="//use.typekit.net/eoi7zul.js"></script>
  <script>try{Typekit.load();}catch(e){}</script>
</head>


  <body class="home">

    <header class="site-header">
  <div class="wrapper">

    <div class="column">

      <a class="site-title" href="/">
        <svg version="1.0" class="git-lfs-logo-svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 412 48.07" enable-background="new 0 0 412 48.07" xml:space="preserve" width="412" height="49">
  <path fill="#3E2F05" d="M82.29,24.43c-0.42,0.04-0.57,0.14-0.57,0.5v7.61c-2.69,1.27-6.23,1.7-9.17,1.7c-9.67,0-13-5.7-13-13.32
  c0-7.58,4.36-13.21,13.28-13.21c2.55,0,5.84,0.64,8,2.05v6.69l-3.93-0.28l-0.53-3.19c-0.11-0.5-0.25-0.64-0.57-0.71
  c-0.89-0.25-2.16-0.46-3.26-0.46c-4.57,0-7.3,3.47-7.3,9.03c0,5.84,2.48,9.31,7.54,9.31c0.96,0,2.12-0.11,2.94-0.25
  c0.39-0.07,0.57-0.18,0.57-0.64v-4.64h-3.93l0.5-3.19h10.87v2.83L82.29,24.43z M84.41,33.81v-2.8l1.81-0.25
  c0.5-0.07,0.57-0.18,0.57-0.71V19.65c0-0.39-0.11-0.64-0.46-0.74l-1.91-0.67l0.39-2.87h7.33v14.7c0,0.57,0.04,0.64,0.57,0.71
  l1.81,0.25v2.8H84.41z M88.98,12.53c-2.02,0-3.19-1.17-3.19-3.19s1.17-3.12,3.19-3.12c2.05,0,3.22,1.1,3.22,3.12
  S91.03,12.53,88.98,12.53z M109.16,32.82c-1.52,0.74-3.75,1.42-5.77,1.42c-4.21,0-5.81-1.7-5.81-5.7v-9.28c0-0.21,0-0.35-0.28-0.35
  h-2.48v-3.15c3.12-0.35,4.36-1.91,4.75-5.77h3.36v5.03c0,0.25,0,0.35,0.28,0.35h4.99v3.54h-5.28v8.46c0,2.09,0.5,2.9,2.41,2.9
  c0.99,0,2.02-0.25,2.87-0.57L109.16,32.82z M117.77,33.81v-2.8l2.23-0.25c0.5-0.07,0.57-0.18,0.57-0.71V11.92
  c0-0.53-0.07-0.67-0.57-0.71l-2.23-0.25v-2.8h11.79v2.8l-2.94,0.28c-0.53,0.04-0.57,0.18-0.57,0.67v18.1h6.3
  c0.39,0,0.5-0.04,0.57-0.39l0.57-3.54h3.9v7.72H117.77z M150.98,33.81l-0.35-1.91l-0.18-0.04c-1.35,1.31-3.12,2.37-5.95,2.37
  c-4.46,0-5.17-3.05-5.17-5.24c0-3.54,2.2-5.17,6.62-5.45l4.07-0.28v-1.95c0-1.66-0.18-2.8-2.37-2.8c-1.7,0-2.59,0.25-2.59,2.37
  l-4.99-0.42c0-4.78,4.36-5.45,7.61-5.45c5.38,0,7.54,1.45,7.54,6.41v8.61c0,0.57,0.04,0.64,0.57,0.71l1.7,0.28v2.8H150.98z
   M150.03,26.2l-2.41,0.18c-2.09,0.14-2.83,0.67-2.83,2.09c0,1.42,0.85,1.95,2.02,1.95c1.2,0,2.41-0.67,3.22-1.27V26.2z
   M158.45,33.81v-2.87l1.59-0.21c0.5-0.07,0.57-0.18,0.57-0.71V19.65c0-0.39-0.11-0.64-0.46-0.74l-1.91-0.67l0.39-2.87h6.23
  l0.43,2.83h0.21c1.17-1.81,2.73-3.19,4.99-3.19c0.81,0,2.44,0.14,3.08,0.32v6.45l-4.25-0.14l-0.35-1.88
  c-0.07-0.32-0.18-0.39-0.46-0.39c-0.92,0-2.02,0.78-2.55,1.24v9.39c0,0.57,0.04,0.67,0.57,0.71l3.51,0.28v2.83H158.45z
   M190.01,18.62c0.64,0.81,1.31,1.95,1.31,3.58c0,3.93-3.08,6.23-7.54,6.23c-1.13,0-2.16-0.14-2.8-0.32l-1.17,1.88l3.47,0.21
  c6.13,0.39,9.74,0.57,9.74,5.28c0,4.07-3.58,6.37-9.74,6.37c-6.41,0-8.85-1.63-8.85-4.43c0-1.59,0.71-2.44,1.95-3.61
  c-1.17-0.5-1.56-1.38-1.56-2.34c0-0.78,0.39-1.49,1.03-2.16c0.64-0.67,1.35-1.35,2.2-2.12c-1.74-0.85-3.05-2.69-3.05-5.31
  c0-4.07,2.69-6.87,8.11-6.87c1.52,0,2.44,0.14,3.26,0.35h6.91v3.01L190.01,18.62z M179.52,34.77c-0.46,0.57-0.92,1.17-0.92,1.88
  c0,1.42,1.81,1.84,4.29,1.84c2.05,0,4.85-0.14,4.85-2.05c0-1.13-1.35-1.2-3.05-1.31L179.52,34.77z M183.42,18.51
  c-1.95,0-3.4,0.96-3.4,3.26c0,1.74,0.96,2.94,3.29,2.94c1.98,0,3.33-1.17,3.33-3.01C186.64,19.61,185.44,18.51,183.42,18.51z
   M210.33,32.43c-2.2,1.06-4.6,1.81-7.26,1.81c-6.84,0-9.17-4.25-9.17-9.77c0-6.41,3.93-9.46,8.78-9.46c4.67,0,7.79,2.44,7.79,8.57
  c0,0.42-0.04,1.66-0.07,2.37h-10.84c0.18,2.51,1.27,4.18,4.18,4.18c1.38,0,2.87-0.32,5.28-1.2L210.33,32.43z M205.23,22.58
  c-0.04-2.97-1.2-3.75-2.66-3.75c-1.52,0-2.76,0.85-2.97,3.75H205.23z M219.33,33.81v-2.76l2.23-0.25c0.5-0.07,0.57-0.18,0.57-0.71
  V11.92c0-0.53-0.07-0.67-0.57-0.71l-2.23-0.25v-2.8h18.7v7.15l-3.9-0.18l-0.5-2.69c-0.07-0.35-0.21-0.46-0.6-0.46h-5.42v6.94h8.15
  v3.93h-8.15v7.15c0,0.57,0.04,0.64,0.57,0.71l5.21,0.28v2.8H219.33z M239.69,33.81v-2.8l1.81-0.25c0.5-0.07,0.57-0.18,0.57-0.71
  V19.65c0-0.39-0.11-0.64-0.46-0.74l-1.91-0.67l0.39-2.87h7.33v14.7c0,0.57,0.04,0.64,0.57,0.71l1.81,0.25v2.8H239.69z M244.26,12.53
  c-2.02,0-3.19-1.17-3.19-3.19s1.17-3.12,3.19-3.12c2.05,0,3.22,1.1,3.22,3.12S246.31,12.53,244.26,12.53z M250.56,33.81v-2.8
  l1.77-0.25c0.5-0.07,0.57-0.18,0.57-0.71v-18.7c0-0.39-0.11-0.64-0.46-0.74l-1.95-0.67l0.39-2.87h7.37v22.98
  c0,0.57,0.04,0.64,0.57,0.71l1.74,0.25v2.8H250.56z M278.04,32.43c-2.2,1.06-4.6,1.81-7.26,1.81c-6.84,0-9.17-4.25-9.17-9.77
  c0-6.41,3.93-9.46,8.78-9.46c4.67,0,7.79,2.44,7.79,8.57c0,0.42-0.04,1.66-0.07,2.37h-10.84c0.18,2.51,1.27,4.18,4.18,4.18
  c1.38,0,2.87-0.32,5.28-1.2L278.04,32.43z M272.94,22.58c-0.04-2.97-1.2-3.75-2.66-3.75c-1.52,0-2.76,0.85-2.97,3.75H272.94z
   M300.53,15.68l-0.42-2.87c-0.07-0.42-0.18-0.57-0.42-0.67c-0.57-0.18-1.42-0.39-2.59-0.39c-2.66,0-3.97,1.2-3.97,3.01
  c0,2.34,2.41,2.97,5.1,3.79c3.36,1.03,7.12,2.3,7.12,7.61c0,5.81-4.53,8.07-9.95,8.07c-3.19,0-6.76-0.81-8.11-1.45v-6.91h3.97
  l0.71,3.36c0.07,0.42,0.14,0.53,0.6,0.64c0.43,0.11,1.63,0.39,2.97,0.39c2.87,0,4.46-1.13,4.46-3.29c0-2.27-2.02-2.97-4.39-3.65
  c-3.51-0.99-7.83-1.95-7.83-7.65c0-5.45,4.11-7.97,9.49-7.97c3.05,0,5.67,0.74,7.26,1.42v6.91L300.53,15.68z M320.96,32.82
  c-1.52,0.74-3.75,1.42-5.77,1.42c-4.21,0-5.81-1.7-5.81-5.7v-9.28c0-0.21,0-0.35-0.28-0.35h-2.48v-3.15
  c3.12-0.35,4.36-1.91,4.75-5.77h3.36v5.03c0,0.25,0,0.35,0.28,0.35H320v3.54h-5.28v8.46c0,2.09,0.5,2.9,2.41,2.9
  c0.99,0,2.02-0.25,2.87-0.57L320.96,32.82z M321.24,24.71c0-5.88,3.08-9.7,9.56-9.7c6.55,0,9.1,3.9,9.1,9.31
  c0,6.02-3.05,9.92-9.56,9.92C323.86,34.24,321.24,30.27,321.24,24.71z M334.31,24.5c0-4.18-1.27-5.67-3.58-5.67
  c-2.34,0-3.9,1.45-3.9,5.7c0,4.29,1.38,5.98,3.75,5.98C332.89,30.52,334.31,28.92,334.31,24.5z M341.32,33.81v-2.87l1.59-0.21
  c0.5-0.07,0.57-0.18,0.57-0.71V19.65c0-0.39-0.11-0.64-0.46-0.74l-1.91-0.67l0.39-2.87h6.23l0.43,2.83h0.21
  c1.17-1.81,2.73-3.19,4.99-3.19c0.81,0,2.44,0.14,3.08,0.32v6.45l-4.25-0.14l-0.35-1.88c-0.07-0.32-0.18-0.39-0.46-0.39
  c-0.92,0-2.02,0.78-2.55,1.24v9.39c0,0.57,0.04,0.67,0.57,0.71l3.51,0.28v2.83H341.32z M368.73,33.81l-0.35-1.91l-0.18-0.04
  c-1.35,1.31-3.12,2.37-5.95,2.37c-4.46,0-5.17-3.05-5.17-5.24c0-3.54,2.2-5.17,6.62-5.45l4.07-0.28v-1.95c0-1.66-0.18-2.8-2.37-2.8
  c-1.7,0-2.59,0.25-2.59,2.37l-4.99-0.42c0-4.78,4.36-5.45,7.61-5.45c5.38,0,7.54,1.45,7.54,6.41v8.61c0,0.57,0.04,0.64,0.57,0.71
  l1.7,0.28v2.8H368.73z M367.77,26.2l-2.41,0.18c-2.09,0.14-2.83,0.67-2.83,2.09c0,1.42,0.85,1.95,2.02,1.95
  c1.2,0,2.41-0.67,3.22-1.27V26.2z M391.53,18.62c0.64,0.81,1.31,1.95,1.31,3.58c0,3.93-3.08,6.23-7.54,6.23
  c-1.13,0-2.16-0.14-2.8-0.32l-1.17,1.88l3.47,0.21c6.13,0.39,9.74,0.57,9.74,5.28c0,4.07-3.58,6.37-9.74,6.37
  c-6.41,0-8.85-1.63-8.85-4.43c0-1.59,0.71-2.44,1.95-3.61c-1.17-0.5-1.56-1.38-1.56-2.34c0-0.78,0.39-1.49,1.03-2.16
  c0.64-0.67,1.35-1.35,2.2-2.12c-1.74-0.85-3.05-2.69-3.05-5.31c0-4.07,2.69-6.87,8.11-6.87c1.52,0,2.44,0.14,3.26,0.35h6.91v3.01
  L391.53,18.62z M381.05,34.77c-0.46,0.57-0.92,1.17-0.92,1.88c0,1.42,1.81,1.84,4.29,1.84c2.05,0,4.85-0.14,4.85-2.05
  c0-1.13-1.35-1.2-3.05-1.31L381.05,34.77z M384.95,18.51c-1.95,0-3.4,0.96-3.4,3.26c0,1.74,0.96,2.94,3.29,2.94
  c1.98,0,3.33-1.17,3.33-3.01C388.17,19.61,386.96,18.51,384.95,18.51z M411.86,32.43c-2.2,1.06-4.6,1.81-7.26,1.81
  c-6.84,0-9.17-4.25-9.17-9.77c0-6.41,3.93-9.46,8.78-9.46c4.67,0,7.79,2.44,7.79,8.57c0,0.42-0.04,1.66-0.07,2.37h-10.84
  c0.18,2.51,1.27,4.18,4.18,4.18c1.38,0,2.87-0.32,5.28-1.2L411.86,32.43z M406.76,22.58c-0.04-2.97-1.2-3.75-2.66-3.75
  c-1.52,0-2.76,0.85-2.97,3.75H406.76z"/>
  <polygon fill="#AC3025" points="24.51,28.18 24.59,48.07 49.02,33.96 49.02,14.2 "/>
  <polygon fill="#F64935" points="39.56,8.73 15.13,22.84 15.13,30.77 9.46,27.5 9.46,19.57 33.9,5.46 24.44,0 0,14.11 0,33.88
  24.59,48.07 24.59,28.31 49.02,14.2 "/>
</svg>
      </a>

      <nav class="site-nav">
        <a class="page-link" href="https://github.com/github/git-lfs/tree/master/docs?utm_source=gitlfs_site&amp;utm_medium=docs_link&amp;utm_campaign=gitlfs">Docs</a>
        <a class="page-link" href="https://github.com/github/git-lfs/releases/latest?utm_source=gitlfs_site&amp;utm_medium=downloads_link&amp;utm_campaign=gitlfs">Downloads</a>
        <a class="page-link" href="https://github.com/github/git-lfs?utm_source=gitlfs_site&amp;utm_medium=source_link&amp;utm_campaign=gitlfs">Source</a>
      </nav>

    </div>

  </div>
</header>


    <section class="home-hero">
  <div class="wrapper">

    <div class="column-half column">

      <h1 class="page-heading">An open source Git extension for versioning large files</h1>

      <p class="description">Git Large File Storage (LFS) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.</p>
      <div class="js-download">
        <a class="button primary-cta js-os-data" data-ga-params="download,button" data-os-attr="href"
           href="https://github.com/github/git-lfs/releases/latest"
           data-os-mac="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-darwin-amd64-1.2.0.tar.gz"
           data-os-windows="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-windows-1.2.0.exe">
          <span class="octicon octicon-cloud-download"></span>
          Download <span class="download-details">v1.2.0<span class="js-os-data" data-os-attr="text" data-os-mac=" (Mac)" data-os-Windows=" (Windows)"><span></span>
        </a>
      </div>
      <div class="js-linux visually-hidden">
        <a href="https://packagecloud.io/github/git-lfs/install" class="button primary-cta js-os-data" data-ga-params="download,packagecloud"><span class="octicon octicon-cloud-download"></span> Install <span class="download-details">v1.2.0 via PackageCloud (Linux)</span></a>
        <p class="secondary-download">or <a href="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-linux-amd64-1.2.0.tar.gz" data-ga-params="download,button">Download v1.2.0 (Linux)</a></p>
      </div>
      <div class="js-mac visually-hidden">
        <p class="secondary-download">
          <a href="http://brew.sh">Homebrew</a>: <code>brew install git-lfs</code><br>
          <a href="https://www.macports.org">MacPorts</a>: <code>port install git-lfs</code>
        </p>
      </div>

    </div>

    <div class="column-half column graphic">
      <h2>How it works:</h2>
      <img class="how-it-works-graphic" src="/images/graphic.gif" alt="a diagram showing how Git LFS works" width="500">
    </div>

  </div>
</section>


<section class="home-secondary">
  <div class="wrapper">

    <div class="column">
      <a class="dot-com-announcement js-os-data" data-os-attr="href" data-ga-params="download,banner"
         href="https://github.com/github/git-lfs/releases/latest"
         data-os-mac="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-darwin-amd64-1.2.0.tar.gz"
         data-os-windows="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-windows-1.2.0.exe"
         data-os-linux="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-linux-amd64-1.2.0.tar.gz">
         GitHub.com support now available. <br/><span>Install the client to get started</span>.</a>
      </a>

    </div>


    <div class="column column-half home-getting-started">

      <h2 class="section-heading">Getting Started</h2>

      <ol class="install-steps">
        <li>
          <p>
            <a class="js-os-data" data-os-attr="href" data-ga-params="download,link"
               href="https://github.com/github/git-lfs/releases/latest"
               data-os-mac="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-darwin-amd64-1.2.0.tar.gz"
               data-os-windows="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-windows-1.2.0.exe"
               data-os-linux="https://github.com/github/git-lfs/releases/download/v1.2.0/git-lfs-linux-amd64-1.2.0.tar.gz">
               Download
            </a>
            and install the Git command line extension. You only have to set up Git LFS once.
          </p>
          <pre>git lfs install</pre>
        </li>
        <li>
          <p>Select the file types you'd like Git LFS to manage (or directly edit your .gitattributes). You can configure additional file extensions at anytime.</p>
<pre>git lfs track "*.psd"</pre>
        </li>
        <li>
          <p>There is no step three. Just commit and push to GitHub as you normally would.</p>
<pre>git add file.psd
git commit -m "Add design file"
git push origin master</pre>
        </li>
      </ol>

      <h2 class="section-heading">Git LFS is an open source project</h2>

      <p>To file an issue or contribute to the project, head over <a href="https://github.com/github/git-lfs?utm_source=gitlfs_site&amp;utm_medium=repo_link&amp;utm_campaign=gitlfs">to the repository</a>
        or read our <a href="https://github.com/github/git-lfs/blob/master/CONTRIBUTING.md?utm_source=gitlfs_site&amp;utm_medium=contributing_link&amp;utm_campaign=gitlfs">guide to contributing</a>.</p>
      <p>If you're interested in integrating Git LFS into another tool or product, you might want to read the
        <a href="https://github.com/github/git-lfs/blob/master/docs/api/README.md?utm_source=gitlfs_site&amp;utm_medium=api_spec_link&amp;utm_campaign=gitlfs">API specification</a>
        or check out our <a href="https://github.com/github/lfs-test-server?utm_source=gitlfs_site&amp;utm_medium=reference_servedr&amp;utm_campaign=gitlfs">reference server implementation</a>.</p>

    </div><!-- /.home-getting-started -->

    <div class="column column-half home-features">

      <h2 class="section-heading">Features</h2>

      <ul class="features-list">

        <li class="feature">
          <div class="hero-octicon">
            <span class="mega-octicon octicon-file-binary"></span>
          </div>
          <div class="content">
            <h3>Large file versioning</h3>
            <p>Version large files—even those as large as a couple GB in size—with Git.</p>
          </div>
        </li>

        <li class="feature">
          <div class="hero-octicon">
            <span class="mega-octicon octicon-repo"></span>
          </div>
          <div class="content">
            <h3>More repository space</h3>
            <p>Host more in your Git repositories. External file storage makes it easy to keep your repository at a manageable size.</p>
          </div>
        </li>
