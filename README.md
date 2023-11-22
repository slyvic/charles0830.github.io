<h1 align="center"> 
	<a href="https://charles0830.github.io/">charles0830.github.io</a> - v2.0
	<p align="center">
		<img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E44D26?style=flat&logo=html5&logoColor=white"/>
		<img alt="CSS3" src="https://img.shields.io/badge/-CSS3-2965f1?style=flat&logo=css3&logoColor=white"/>
		<img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F0DB4F?style=flat&logo=javascript&logoColor=white"/>
		<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white"/>
		<img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white"/>
		<img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white"/>
		<img alt="NodeJS" src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/>
		<img alt="Docker" src="https://img.shields.io/badge/Docker-0db7ed?style=flat&logo=docker&logoColor=white"/>
		<img alt="Open Source? Yes!" src="https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github"/> 
	</p>
</h1>

<br/>

## Built With :package:

- 💙 [HTML5](https://www.w3schools.com/html/)
- 💜 [CSS3](https://www.w3schools.com/css/)
- 💙 [JavaScript](https://www.w3schools.com/js/DEFAULT.asp)
- 💜 [TypeScript](https://www.typescriptlang.org/)
- 💙 [Angular](https://angular.io/)
- 💜 [NodeJS](https://nodejs.org/)
- 💙 [Bootstrap](https://getbootstrap.com/)
- 💜 [Google Font](https://fonts.google.com/) for the fonts
- 💙 [FontAwesome](https://fontawesome.com/) for the icons
- 💜 [GitHub Pages](https://pages.github.com/) for hosting
- 💙 [Apify](https://apify.com/) for generating screenshot of website
- 💜 [SmartMockups](https://smartmockups.com/) for adding mockups/desktop background to screenshot


## How to run locally? :dart:

Make sure you have [Node](https://nodejs.org/en/) and [git](https://git-scm.com/) installed.

  ```bash
  node --version
  git --version
  ```

- Clone the repository :
	- With HTTPS:
	  ```bash
	  git clone https://github.com/charles0830/charles0830.github.io.git
	  ```
	- With SSH:
	  ```bash
	  git@github.com:charles0830/charles0830.github.io.git
	  ```

- Navigate to working Directory and **main** branch

  ```bash
  cd charles0830.github.io
  git switch main
  ```

- Install the dependencies:

  ```bash
  npm install -f
  ```
	- Installs all the dependencies required by the project.


- Fire up a development server:

  ```bash
  ng serve
  ```
	- Runs the app in the `development` mode.
	- Open [http://localhost:4200/](http://localhost:4200/) to view it in the Default Browser.
	- The page will reload if you make edits.
	- You will also see any lint errors in the console.


- Deploy code to GitHub Pages (gh-pages):

  ```bash
  ng deploy --base-href="/"
  ```
	- Builds the application for production to the `build` folder & deploys application on `GitHub Pages`.
	- It correctly bundles Angular in production mode and optimizes the build for the best performance.
	- The build is minified and the filenames include the hashes.


- Create a new branch:

  ```bash
  git checkout -b "<NAME-OF-THE-BRANCH>"
  ```

- Add, Commit & Push the local changes to remote repository:

  ```bash
  git add .
  git commit -m "<COMMIT-MESSAGE>"
  git push origin <NAME-OF-THE-BRANCH>
  ```

**For Docker Users**

Make sure you have [Docker](https://www.docker.com/products/docker-desktop/) installed.

```bash
docker --version
```

- To pull the [GitHub Container Registry](https://github.com/charles0830/charles0830.github.io/pkgs/container/charles0830.github.io) Image:
  ```bash
  docker pull ghcr.io/charles0830/charles0830.github.io:latest
  ```

- To pull the [Dockerhub](https://hub.docker.com/r/charles0830/charles0830.github.io) Image:
  ```bash
  docker pull charles0830/charles0830.github.io:latest
  ```

- To automatically pull and run the [GitHub Container Registry](https://github.com/charles0830/charles0830.github.io/pkgs/container/charles0830.github.io) Image:
  ```bash
  docker run -d -p 4200:80 ghcr.io/charles0830/charles0830.github.io:latest
  ```

- To automatically pull and run the [Dockerhub](https://hub.docker.com/r/charles0830/charles0830.github.io) Image:
  ```bash
  docker run -d -p 4200:80 charles0830/charles0830.github.io:latest
  ```
  
  Open [http://localhost:4200/](http://localhost:4200/) to view it in the Default Browser.


## Sections :bookmark:

- Home
- About
	- About
	- Skill
	- Education
- Portfolio
- Training
- Achievement
- Contact


## Folder Structure :open_file_folder:

<pre>

|   372.XXXXXXXXXXXXXXXX.js
|   3rdpartylicenses.txt
|   404.XXXXXXXXXXXXXXXX.webp
|   404.html
|   478.XXXXXXXXXXXXXXXX.js
|   about-bg.XXXXXXXXXXXXXXXX.svg
|   apple-touch-icon.png
|   bgimg.XXXXXXXXXXXXXXXX.webp
|   browserconfig.xml
|   fa-brands-400.XXXXXXXXXXXXXXXX.woff2
|   fa-brands-400.XXXXXXXXXXXXXXXX.woff
|   fa-brands-400.XXXXXXXXXXXXXXXX.eot
|   fa-brands-400.XXXXXXXXXXXXXXXX.svg
|   fa-brands-400.XXXXXXXXXXXXXXXX.ttf
|   fa-regular-400.XXXXXXXXXXXXXXXX.ttf
|   fa-regular-400.XXXXXXXXXXXXXXXX.woff2
|   fa-regular-400.XXXXXXXXXXXXXXXX.eot
|   fa-regular-400.XXXXXXXXXXXXXXXX.woff
|   fa-regular-400.XXXXXXXXXXXXXXXX.svg
|   fa-solid-900.XXXXXXXXXXXXXXXX.woff2
|   fa-solid-900.XXXXXXXXXXXXXXXX.woff
|   fa-solid-900.XXXXXXXXXXXXXXXX.ttf
|   fa-solid-900.XXXXXXXXXXXXXXXX.svg
|   fa-solid-900.XXXXXXXXXXXXXXXX.eot
|   favicon-16x16.png
|   favicon-32x32.png
|   favicon.ico
|   index.html
|   LICENSE
|   main.XXXXXXXXXXXXXXXX.js
|   manifest.webmanifest
|   ngsw-worker.js
|   ngsw.json
|   polyfills.XXXXXXXXXXXXXXXX.js
|   quote-img.XXXXXXXXXXXXXXXX.webp
|   README.md
|   robots.txt
|   runtime.XXXXXXXXXXXXXXXX.js
|   safety-worker.js
|   scripts.XXXXXXXXXXXXXXXX.js
|   sitemap_index.xml
|   styles.XXXXXXXXXXXXXXXX.css
|   worker-basic.min.js
|   
+---assets
|   |   data.min.js
|   |   
|   +---css
|   |       animate.min.css
|   |       font-awesome.min.css
|   |       
|   +---fonts
|   |       BlackOpsOne.eot
|   |       BlackOpsOne.svg
|   |       BlackOpsOne.ttf
|   |       BlackOpsOne.woff
|   |       BlackOpsOne.woff2
|   |       fa-brands-400.eot
|   |       fa-brands-400.svg
|   |       fa-brands-400.ttf
|   |       fa-brands-400.woff
|   |       fa-brands-400.woff2
|   |       fa-regular-400.eot
|   |       fa-regular-400.svg
|   |       fa-regular-400.ttf
|   |       fa-regular-400.woff
|   |       fa-regular-400.woff2
|   |       fa-solid-900.eot
|   |       fa-solid-900.svg
|   |       fa-solid-900.ttf
|   |       fa-solid-900.woff
|   |       fa-solid-900.woff2
|   |       
|   +---images
|   |   |   404.webp
|   |   |   about-bg.svg
|   |   |   bgimg.webp
|   |   |   footer-cloud.svg
|   |   |   monkey.webp
|   |   |   moon-dark.svg
|   |   |   moon.svg
|   |   |   mstile-144x144.png
|   |   |   mstile-150x150.png
|   |   |   mstile-310x150.png
|   |   |   mstile-310x310.png
|   |   |   mstile-70x70.png
|   |   |   og-image.jpg
|   |   |   Profile-pic-144x144.png
|   |   |   Profile-pic-192x192.png
|   |   |   Profile-pic-384x384.png
|   |   |   Profile-pic-512x512.png
|   |   |   Profile-pic.webp
|   |   |   quote-img.webp
|   |   |   safari-pinned-tab.svg
|   |   |   
|   |   +---achievement
|   |   |       DataScience.webp
|   |   |       HackerRank.webp
|   |   |       Hacktoberfest.webp
|   |   |       
|   |   \---portfolio
|   |           A-Social-Media.webp
|   |           AI-Image-Caption-Bot.webp
|   |           AI-Music-Generation.webp
|   |           E-Commerce-Site.webp
|   |           School-Donation-Analysis.webp
|   |           URL-Shortner.webp
|   |           
|   +---js
|   |       live2d.min.js
|   |       particles.min.js
|   |       vanilla-tilt.min.js
|   |       wow.min.js
|   |       
|   \---<a href="/assets/model/">model</a>
|   
\---screenshots
        color-loader-404.png
        color-main.png
        font-awesome-icon.png
        font.png
        icon.png
        PageSpeedInsight Desktop.png
        PageSpeedInsight Mobile.png
        screenshot.gif
</pre>



## Search engine optimization(SEO) :spider:

Search engine optimization (SEO) is the process of improving the quality and quantity of website traffic to a website or a web page from search engines.
Add the below code snippet to `index.html` with your site info. This step is not mandatory.

```html
<meta itemprop="name" content="--- YOUR TITLE ---">
<meta itemprop="description" content="--- SITE DESCRIPTION ---">
<meta itemprop="url" content="--- YOUR SITE URL ---"/>
<meta itemprop="image" content="--- YOUR IMAGE ---">
<link rel="image_src" href="--- YOUR IMAGE ---">

<meta name="author" content="--- YOUR NAME ---">
<meta name="description" content="--- SITE DESCRIPTION ---">
<meta name="keywords" content="--- SITE KEYWORDS ---">

<meta property="og:image" content="--- YOUR IMAGE ---">
<meta property="og:image:width" content="--- YOUR IMAGE WIDTH ---">
<meta property="og:image:height" content="--- YOUR IMAGE HEIGHT ---">
<meta property="og:image:alt" content="--- YOUR TITLE ---">
<meta property="og:title" content="--- YOUR TITLE ---">
<meta property="og:description" content="--- SITE DESCRIPTION ---">
<meta property="og:url" content="--- YOUR SITE URL ---">
<meta property="og:type" content="website">

<meta name="twitter:title" content="--- YOUR TITLE ---">
<meta name="twitter:description" content="--- SITE DESCRIPTION ---">
<meta name="twitter:site" content="@--- YOUR USERNAME ---">
<meta name="twitter:creator" content="@--- YOUR USERNAME ---">
<meta name="twitter:image:src" content="--- YOUR IMAGE ---">
<meta name="twitter:image" content="--- YOUR IMAGE ---">
<meta name="twitter:card" content="summary_large_image">

<script type="application/ld+json">
    {
        "@type": "Person",
        "@context": "https://schema.org",
        "url": "--- YOUR SITE URL ---",
        "description": "--- SITE DESCRIPTION ---",
        "name": "--- YOUR NAME ---",
        "image": "--- YOUR IMAGE ---",
        "email":"--- YOUR EMAIL ---",
        "address": "--- YOUR LOCATION ---",
        "sameAs":[
            "https://github.com/--- YOUR USERNAME ---/",
            "https://www.linkedin.com/in/--- YOUR USERNAME ---/",
            "https://gist.github.com/--- YOUR USERNAME ---/",
            "https://www.hackerrank.com/--- YOUR USERNAME ---",
            "https://www.instagram.com/--- YOUR USERNAME ---/",
            "https://www.facebook.com/--- YOUR USERNAME ---/",
            "https://twitter.com/--- YOUR USERNAME ---/",
            "https://dev.to/--- YOUR USERNAME ---",
            "https://wa.me/--- YOUR MOBILE NUMBER ---"
        ]
    }
</script>
```


## PageSpeed Insights

PageSpeed Insights (PSI) reports on the performance of a page on both mobile and desktop devices, and provides suggestions on how that page may be improved.

- **Desktop**

  [![PageSpeed Insight Desktop](screenshots/PageSpeedInsight%20Desktop.png)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fcharles0830.github.io%2F&strategy=desktop&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa)

- **Mobile**

  [![PageSpeed Insight Mobile](screenshots/PageSpeedInsight%20Mobile.png)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fcharles0830.github.io%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa)


## Creator / Maintainer :man_technologist:

👤 Charles Berry ([charles0830](https://github.com/charles0830))

If you have any questions, comments, or concerns, feel free to contact me below.

<p align="left">
	<a href="https://www.linkedin.com/in/charles0830"> 
    	<img alt="Connect via LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" />
  	</a>
	<a href="mailto:chberry830@gmail.com"> 
		<img alt="Connect via Email" src="https://img.shields.io/badge/Gmail-c14438?style=flat&logo=Gmail&logoColor=white" />
	</a>
	<a href="https://www.twitter.com/charles0830"> 
    	<img alt="Connect via Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white" />
  	</a>
</p>

This project was created for educational purposes and for personal use. Feel free to take inspiration.

If you like my content or find this code useful, give it a ⭐.
