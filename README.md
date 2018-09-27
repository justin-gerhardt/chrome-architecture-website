Chrome Architecture Website [![Build Status](https://travis-ci.com/justin-gerhardt/chrome-architecture-website.svg?branch=master)](https://travis-ci.com/justin-gerhardt/chrome-architecture-website)
============================


The website is generated using [hugo](https://gohugo.io/). 

[Installation instructions](https://gohugo.io/getting-started/installing/)

Development
-----------

When you are ready to start developing run `hugo serve`.

 You can than access a local copy of the website at http://localhost:1313 . If you make any changes the server will automatically rebuild the site and refresh your browser (as long as you haven't broken the html). 

 ### CSS ###

 To edit the css in the theme you must:
  * Install node.js
  * run `npm install` inside the theme directory
  * when editing run `grunt watch` to automatically rebuild the css file
  * edit the scss files with your changes

as long as both `grunt watch` and `huge serve` are running at the same time style changes will be automatically built and displayed.

 Deploy
 ----------
 
 Commits to this repo are automatically build by [travis](https://travis-ci.com/justin-gerhardt/chrome-architecture-website) and deployed to aws.

 This process should take ~2 minutes.