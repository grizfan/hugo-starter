# Hugo & Bootstrap GitHub template repository site
## overview
This is a somewhat-opinionated starter site built using the [Hugo static site generator](https://gohugo.io/). I created this to use in conjunction with [Netlify](https://www.netlify.com/) for deployment and hosting.
I also set up this site to use the [SASS version of Bootstrap 4](https://getbootstrap.com/docs/4.3/getting-started/theming/#sass) and [Native JavaScript for Bootstrap](http://thednp.github.io/bootstrap.native/) in place of jQuery. 
## site features
So, what do you get with all of this? Hopefully, a sold starting point for building your own custom Hugo site. You can customize the SASS implementation of Bootstrap to drive you own unique design. All the basic Hugo pages are there, with partials already setup for the header, footer and document head section. You get Twitter cards and Facebook Open Graph tags for every page, Google Tag Manager and Google Analytics, an XML site map, robots.txt file, and the tags for common favicons. 
## requirements
While I built this on my Mac, you should be able to manage just fine in Windows using [Git Bash](https://gitforwindows.org/). 
* [NodeJS and NPM](https://nodejs.org)
* [Hugo version 58.x or newer](https://gohugo.io/)
* [A GitHub account](https://github.com/pricing) (or BitBucket or GitLab)
* [A Netlify free or paid account](https://www.netlify.com/pricing/)
## site organization
most of your work will be in the following directories:
* /assets/sass/ - customize Bootstrap
* /layouts - customize page design
* config.toml file - customize site description and features
```
├── README.md
├── archetypes
│   └── default.md
├── assets
│   ├── js
│   └── sass
│       ├── custom_variables.scss
│       ├── main.scss
│       └── styles.scss
├── config.toml
├── content
│   ├── _index.md
│   ├── about.md
│   └── posts
│       └── first-post.md
├── data
├── layouts
│   ├── 404.html
│   ├── _default
│   │   ├── baseof.html
│   │   ├── list.html
│   │   └── single.html
│   ├── about.html
│   ├── home.html
│   ├── index.html
│   ├── partials
│   │   ├── favicon.html
│   │   ├── footer.html
│   │   ├── gtm.html
│   │   ├── head.html
│   │   ├── header.html
│   │   ├── schema-blogPost.html
│   │   ├── schema-webPage.html
│   │   └── schema-webSite.html
│   ├── resources
│   │   └── _gen
│   │       ├── assets
│   │       └── images
│   └── robots.txt
├── netlify.toml
├── package-lock.json
├── package.json
```
## getting started
1. Git clone or download this repo into a new directory
2. For local development, you will first need to run `npm install` to install Bootstrap and a few other items specified in the package.json file. 
3. Once that completes, run `hugo server` to start up the local hugo environment and launch the preview server.
4. In your GitHub account, create a new repository, but do /not/ add a readme or license file.
5. Follow [these instructions](https://help.github.com/en/articles/changing-a-remotes-url) to change the remote URL for you local development directory to your newly created GitHub repository. 
6. In your Netlify account, [create a new site from Git](https://www.netlify.com/docs/) by following the instructions in your account control panel.
That covers the basics. 


