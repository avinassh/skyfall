# skyfall

This is a clean bootstrap theme, a fork of [Nikhil's Theme](https://github.com/gunchu/nikhil-theme) and stylesheet is inspired from Armin Ronacher's [lucmur](https://github.com/mitsuhiko/lucumr).

You can see this live on [avi.im/blag](http://avi.im/blag).

## Installation
Same as standard installation of any pelican themes

## Settings

This theme supports [Isso Commenting Server](http://posativ.org/isso) (along with Disqus). To enable, your pelican config file should have following two settings:

    # Specify where your Isso server is running
    ISSO_SITE = '//localhost:8080/'
    # Specify where is embed.js file, usually, it's your
    # http://isso-server/js/embed.min.js
    ISSO_EMBED_JS = '//localhost:8080/isso/api/js/embed.min.js'

## Screenshot ##
![screenshot](screenshot.png)

## Notes:

Theme's layout is based on Nikhil's Theme. I have added couple of CSS classes to templates for further modifications(in `index.html`, added classes `article-title` and `article-date`). `article.html` was modifid to include `isso.html` for Isso server. Much of the stylesheet is inspired from lucumr.