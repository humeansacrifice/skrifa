---
page_title: _includes Files Reference
layout: page
user:
ed:
resource: true
last_updated: September 12, 2015
categories: [Technical Setup]
cat_url: all-technical-setup-articles.html
overview: This article covers what each file in the _includes directory does.
toc: false
tags:
keywords:
---
{% include alerts_callouts.html %}

Files from ```_includes``` are used throughout this theme. They are called in pages using {% raw %}{% include INCLUDE_FILE_NAME.html %}{% endraw %}
This list explains each file's purpose:

<table class="table table-striped table-hover ">
<tr class="success">
<th>File Name</th>
<th>Function</th>
  </tr>
  <tr>
    <td>alerts_callouts.html</td>
    <td>Includes the code for <a href="alerts-and-callouts.html">alerts</a> used in this theme. This must be included on a page to use the alerts.</td>
  </tr>
  <tr>
    <td>breadcrumb.html</td>
    <td>Contains <a href="breadcrumbs.html">breadcrumb navigation</a> for the page layout. Used on articles.</td>
  </tr>
  <tr>
    <td>breadcrumb_cat_page.html</td>
    <td>Contains <a href="breadcrumbs.html">breadcrumb navigation</a> for the cat_page layout used on "all-CATEGORYNAME-article" pages.</td>
  </tr>
  <tr>
    <td>breadcrumb_top_page.html</td>
    <td>Contains <a href="breadcrumbs.html">breadcrumb navigation</a> for the top_page layout used on "all-topic-TOPICNAME-article" pages.</td>
  </tr>
  <tr>
    <td>category_list_generator.html</td>
    <td>Generates a list of all categories and their articles.</td>
  </tr>
  <tr>
    <td>category_logic.html</td>
    <td>Generates a list of all articles in a given category. Used on the all-CATEGORYNAME-articles pages.</td>
  </tr>
  <tr>
    <td>category_page_list.html</td>
    <td>Generates a list of all all-CATEGORYNAME-articles pages in your site. Used on the homepage.</td>
  </tr>
  <tr>
    <td>disqus.html</td>
    <td>Contains code for <a href="disqus.html">Disqus comments</a>. If your config.yml file contains a Disqus shortname, this feature will be displayed on article pages.</td>
  </tr>
  <tr>
    <td>footer.html</td>
    <td>Contains the site's footer.</td>
  </tr>
  <tr>
    <td>google_analytics.html</td>
    <td>Contains Google Analytics tracking code. Replace this with your own.</td>
  </tr>
  <tr>
    <td>head.html</td>
    <td>Contains site head content such as stylesheet and script references, Google Analytics code, and site title.</td>
  </tr>
  <tr>
    <td>header.html</td>
    <td>Contains site's header, including the nav bar.</td>
  </tr>
  <tr>
    <td>labels.html</td>
    <td>Contains <a href="labels.html">label definitions</a>. Included on the page layout.</td>
  </tr>
  <tr>
    <td>overview_panel.html</td>
    <td>Generates the <a href="overview-panel.html">Overview Panel</a>. Included on the page layout.</td>
  </tr>
  <tr>
    <td>pardot_tracking.html</td>
    <td>Includes Pardot tracking code. This file is included as an example. Either delete it, or replace with your own tracking script.</td>
  </tr>
  <tr>
    <td>print_button.html</td>
    <td>Generates the Print This Page button that appears on article pages.</td>
  </tr>
  <tr>
    <td>search_script.html</td>
    <td>Search box that appears on article, category, and topic pages.</td>
  </tr>
  <tr>
    <td>search_script_wide.html</td>
    <td>Search box that appears on the homepage.</td>
  </tr>
  <tr>
    <td>series-sample-next.html</td>
    <td>Generates the Next button on the <a href="series.html">Sample Series.</a></td>
  </tr>
  <tr>
    <td>series-sample.html</td>
    <td>Generates the dropdown on the <a href="series.html">Sample Series.</a></td>
  </tr>
  <tr>
    <td>toc.html</td>
    <td>Generates the <a href="table-of-contents.html">Table of Contents</a>.</td>
  </tr>
  <tr>
    <td>topic_list_generator.html</td>
    <td>Generates a list of all topics and their articles.</td>
  </tr>
  <tr>
    <td>topic_logic.html</td>
    <td>Generates a list of all articles in a given topic. Used on the all-topic-TOPICNAME-articles pages.</td>
  </tr>
  <tr>
    <td>topic_page_list.html</td>
    <td>Generates a list of all all-topic-TOPICNAME-articles on the site. Used on homepage.</td>
  </tr>
</table>
