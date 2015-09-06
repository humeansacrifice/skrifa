---
page_title: Labels
layout: page
user: User Label
ed: Edition Label
resource: true
categories: [Formatting]
overview: This article covers how to use Labels with this theme
tags:
keywords:
toc: false
---
{% include alerts_callouts.html %}

##Label Basics
This theme uses standard Bootstrap Labels to add visual indicators for user type and edition level. For example, you can use labels to indicate that an article is intended for Admins only, or that the features are only available in Pro accounts.


- Labels are defined in ```_includes/labels.html```
- This theme only defines two labels: ```user``` (user label) and ```ed``` (edition label). Define their values on page frontmatter.
