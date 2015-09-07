---
page_title: Series
layout: page
user: User Label
ed: Edition Label
resource: true
categories: [Series]
cat_url: all-series-articles.html
overview: This article covers how Series are set up in this theme.
tags:
keywords: series, Neil Young
---
{% include alerts_callouts.html %}

##Using Series

Series allow you to link articles that should be done in a defined order.
There are two components to series:

- The series dropdown
- The series next button

Each article in the series needs the series dropdown, the series next button, and ```series:``` and ```weight:``` frontmatter variables.

This functionality comes from Tom Johnson's <a href="https://github.com/tomjohnson1492/documentation-theme-jekyll">Jekyll Documentation Theme.</a>

##Creating New Series

Creating a new series involves several steps. You have to create a new dropdown and next button for each article, then define the correct variables in each article's frontmatter.


###Creating the Series Dropdown

1. Create a new ```_includes``` file named _series__[YOUR-SERIES-NAME].html_.
2. Copy the code from ```_includes/series-sample.html``` and paste it into your new file.
3. Change the button label to the name of your series (this will be displayed on the site).
4. Change the name in {% raw %} {% if p.series == "Sample series" %}{% endraw %} to the name of your series.
5. Save the file.

###Creating the Series Next Button

1. Create a new ```_includes``` file named _series-[YOUR-SERIES-NAME-next].html_.
2. Copy the code from ```_includes/series-sample-next.html``` and paste it into your new file.
3. Change the name in {% raw %} {% if p.series == "Sample series" %}{% endraw %} to the name of your series.
5. Save the file.

###Including Articles in Series

Before you begin:
The sample series in this theme defines _weight_ (the order in which the articles appear) with integers. The first article will be given a weight of "1", the second "2", and so on. You can define the weight however you like (for example, 1.0, 2.0, 2.1), just make sure to edit the ```plus``` value in your Series Next Button code so it increments properly.

1. Open an article you want to include in the series.
2. Add ```series[YOUR SERIES NAME]``` to the frontmatter.
3. Add ```weight: [NUMBER]``` to the frontmatter.
4. In the body of your article, add {% raw %}{% include series-[YOUR-SERIES-NAME].html  %}{% endraw %} where you want the dropdown to appear.
5. In the body of your article, add {% raw %}{% include series-[YOUR-SERIES-NAME-next].html  %}{% endraw %} where you want the Next button to appear.
6. Repeat these steps for every article in the series.

##Example

This theme includes a Sample Series that allows you to see a series in action.
Check out [Part 1](series-sample1.html).

Associated project files:

- ```series-sample1.html```: first article in series
- ```series-sample2.html```: second article in series
- ```_includes/series-sample.html```: code for the Sample Series dropdown
- ```_includes/series-sample-next.html```: code for the Sample Series Next button
