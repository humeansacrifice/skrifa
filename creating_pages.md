---
page_title: Creating Pages (Articles)
layout: page
last_updated: 9/6/2015
user: User Label
ed: Edition Label
resource: true
categories: [Writing]
cat_url: all-writing-articles.html
overview: This article covers how to create new pages and articles with this theme.
tags:
keywords: wrting new pages, new articles
toc:
---
{% include alerts_callouts.html %}

##Basics of Creating New Pages

The easiest way to create a new article page is to duplicate an existing one, or copy the frontmatter from the body of  ```article_template.html```.

Just duplicate a page, give it a name, fill out the frontmatter, and write your content.

{{info}}It's best to just save all articles in your root directory. I don't have a good handle on how to put things in folders without breaking all my relative links.{{end}}</div>

##Frontmatter Variable Definitions

Here are all the current variables defined for pages in this theme and what they do:


- **page_title:** The title of the page.
- **layout:** the page layout. Unless you create your own layouts, leave this alone.
- **last_updated:** Totes optional. There's a Liquid snippet in the ```footer.html``` file that displays this variable if present.
- **user:** User label. You can use this to apply a visual label to the page. See [Labels](labels.html) for more.
- **ed:** Edition Label. You can use this to apply a visual label to the page. See [Labels](labels.html) for more.
- **resource**: Set this as ```true``` if you want the page to appear on the ```articles-by-category``` page.
- **categories:** Comma-separated list of categories the page belongs in. See [Using Categories](category-setup.html) for more information.
- **overview:** Use this to give readers a high-level overview of  the article contents. This also appears on some category pages.
- **tags:** A sort of loose, second-level organizational tool. No functionality exists for this feature yet.
- **keywords:** Search keywords! Search is set up to search through these.
- **toc:** If this is left blank, a table of contents will be generated for the page. To suppress the table of contents, define this as ```false```. See [Table of Contents](table-of-contents.html) for more.

**Note:** There are a few other variables used on certain kinds of pages (like All "X" Articles pages ). Those are discussed elsewhere.
