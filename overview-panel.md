---
page_title: Overview Panel
layout: page
last_updated: 9/6/2015
user: User Label
ed: Edition Label
resource: true
categories: [Formatting]
cat_url: all-formatting-articles.html
overview: This article covers how to use Overview Panels with this theme
tags:
keywords:
toc: false
---
{% include alerts_callouts.html %}

##Overview Panel Basics

The Overview Panel gives readers a brief overview or summary of a page's conent.

- Its guts live in ```_includes/overview_panel.html```
- The Overview Panel appears at the top of each page using the page.html layout.
- It pulls text from the ```overview:``` variable in page frontmatter.
- If ```overview``` isn't defined on a page, the panel will not appear.
- You can also use ```page.overview``` in search results and article lists to provide more information to readers.
