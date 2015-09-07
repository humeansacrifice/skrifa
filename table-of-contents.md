---
page_title: Table of Contents
layout: page
user: User Label
ed: Edition Label
resource: true
categories: [Formatting]
cat_url: all-formatting-articles.html
overview: This article covers how to use the Table of Contents
tags:
keywords:
toc: false
---
{% include alerts_callouts.html %}

##TOC Basics
I borrowed the Table of Contents code from Tom Johnson's <a href="https://github.com/tomjohnson1492/documentation-theme-jekyll">Jekyll Documentation Theme.</a>

- Its guts are contained in ```_includes/toc.html```.
- Every page using the page.html layout includes a TOC.
- To suppress the TOC on an individual page, include ```toc: false``` in the frontmatter.
- The TOC pulls in any _Markdown_ Level 2, 3, or 4 headings. HTML headings are pulled in inconsistently.
