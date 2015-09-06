---
page_title: Using Categories
layout: page
user: User Label
ed: Edition Label
resource: true
categories: [Categories]
overview: This article covers how Categories are set up in this theme.
tags: getting-started
keywords:
---
{% include alerts_callouts.html %}

##Category Basics

- Categories are defined in the ```category-list``` array in the ```_config.yml``` file.
- Categories that aren't in the ```category-list``` array will not render or be used in any Liquid logic.
- On pages that display lists of categories, they will be ordered as they appear in the ```category-list``` array. Add values to the array in the order in which you want them to appear.
- To categorize a page, add comma-separated values contained in square brackets to the ```categories:``` variable on the page's frontmatter. For example: ```categories: [Category Setup, Formatting]```.

##How Categories are Used in this Theme

### articles-by-category.html

This page generates a list of all [pages, listed by category]({{site.baseurl}}articles-by-category.html). Keep in mind that the categories are listed in the same order they appear in the ```category-list``` array in your ```_config.yml``` file. If you want the categories to appear alphabetically, you'll need to arrange the values in the array alphabetically.

###category-logic.html

This file contains the logic for listing all pages within a specified category -- it's used to generate the _all articles in [category]_ pages.

 It relies on the page ```category_id:``` variable defined in the page frontmatter. Adding {% raw %}{% include category_logic.html %} on a page will generate a hyperlinked list of all articles that match.
