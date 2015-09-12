---
page_title: Using Analytics and Tracking Scripts
layout: page
user: User Label
ed: Edition Label
resource: true
last_updated: September 7, 2015
categories: [Technical Setup]
cat_url: all-technical-setup-articles.html
overview: This article covers how to use Google Analytics and other tracking scripts with this theme.
tags:
keywords: Pardot, tracking code, GA, tracking scripts
---
{% include alerts_callouts.html %}

##Google Analtyics

This theme's tracking codes are contained in ```_includes``` files. To use Google Analytics, replace the contents of ```_includes/google_analytics.html``` with your own GA code. The _default_ layout, which is used in all included page layouts, includes the Google Analytics code.

##Other Tracking Codes

If you use other tracking scripts (like marketing automation, Yahoo Analytics, Crazy Egg, and so on), create files for each code and then place them in the appropriate ```head.html```, ```footer.html```, or ```default.html``` layout files using an include statement. For example, this theme includes a Pardot tracking code in the ```default.html``` layout file.

{{info}} You should delete ```pardot_tracking.html``` and remove its include statement from the ```default``` layout. Unless, of course, you've got your own Pardot tracking code to use. It's included with this theme as an example.{{end}}
