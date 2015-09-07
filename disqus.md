---
page_title: Using Disqus
layout: page
user: User Label
ed: Edition Label
resource: true
cat_url: all-comments-articles.html
last_updated: September 7, 2015
categories: [Comments]
overview: This article covers how to use Disqus for comments with this theme.
tags:
keywords: disqus
---
{% include alerts_callouts.html %}

##Disqus Basics

[Disqus](https://disqus.com/about/) is a service that allows you to add discussion functionality to your site. This theme includes Disqus code in the ```page.html``` layout.


I borrowed inspiration and the Disqus code from Tom Johnson's <a href="https://github.com/tomjohnson1492/documentation-theme-jekyll">Jekyll Documentation Theme.</a>


##Using Disqus with This Theme

- In the ```_config.yml``` file, define ```disqus_shortname``` with your site's Disqus shortname. If you remove 'skrifa' and leave the string blank, Disqus will not display.
- You can edit the Liquid logic for the Disqus code in the ```_includes/disqus.html``` file.
- all-CATEGORYNAME-articles.html pages use the ```cat_page.html``` layout, which is the same as ```page.html```, except it does not contain a include statement for ```disqus.html```.
- depending on your Disqus settings, the feature may not appear properly when testing your site locally.
