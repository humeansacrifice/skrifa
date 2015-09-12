---
page_title: Alerts
layout: page
user: User Label
ed: Edition Label
resource: true
categories: [Formatting]
topics: [Visual Elements]
cat_url: all-formatting-articles.html
top_url: all-topic-visual-elements-articles.html
overview: This article covers how to use alerts and callouts with this theme.
tags:
keywords: alerts, callouts
---
{% include alerts_callouts.html %}

##Getting Started with Alerts

Alerts are captured as variables in the ```alerts_callouts.html``` in the ```_includes``` folder. You can use them like WordPress Shortcodes.

**To use alerts on a page:**

1. Add {% raw %}{% include alerts_callouts.html %}{% endraw %} to your page, under the frontmatter.
2. Add an alert by {% raw %}{{alert_name}}Alert Body Here!{{end}}</div>{% endraw %}

**Alert Names**
Alerts included with this theme are named as follows:

- warning
- danger
- success
- info

##Notes

- Hyphens don't appear to work in variable names. Use underscores or one-word names.
- I couldn't get the alert boxes to render when using closing the div tag in the variable capture. Until it's figured out, you'll need to add a ```</div>``` tag after the {% raw %}{{end}}{% endraw %}. Sorry.
- You can't use Markdown inside of alerts or callouts.
- If you want to post an alert to every page of your site, you can add the code to your page layout, right below the frontmatter. Every page using the layout will show the alert.


##Examples

{{warning}}This is a warning box.{{end}}</div>
{{danger}}This is a danger box. Scary{{end}}</div>
{{success}}This is a success box. Hooray{{end}}</div>
{{info}}This is an info box. FYI{{end}}</div>
<div>Have fun!</div>
