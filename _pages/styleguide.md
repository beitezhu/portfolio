---
layout: page
title: Technical
permalink: /styleguide/
image: beite_logo.webp
---


Tableau: COVID-19 Tracker By Country
Created a static dashboard tracking COVID-19 Cases by country by using a dataset from Kaggle and creating data visualization on Tableau to display results. 
<!DOCTYPE html>
<html>
<head>
    <title>Technical Skills</title>
    <style>
        body { font-family: Arial, sans-serif; }
        .skill-category { font-weight: bold; }
        ul { list-style-type: none; }
        li { margin-bottom: 5px; }
    </style>
</head>
<body>
    <h2>Technical Skills</h2>

    <div class="skills">
        <div class="skill">
            <span class="skill-category">SQL</span>
            <ul>
                <li>MySQL, Oracle SQL Developer, PostgreSQL</li>
                <li>OLAP cubes, Grouping sets, Rollup, Aggregations, Joins, Subqueries, Window Functions, Union, Crosstabs, Case, etc.</li>
                <li>Data Warehouse modeling for efficient queries</li>
                <li>Star schema for OLAP</li>
                <li>Snowflake schema for OLTP</li>
                <li>Foundations in ETL</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">Python</span>
            <ul>
                <li>Numpy, Pandas, SKLearn, Matplotlib</li>
                <li>Ensemble learning: bootstrap aggregation, gradient boosting, adaboost, etc.</li>
                <li>Loops, functions, classes, object oriented programming</li>
                <li>Database connections</li>
                <li>Read and write files</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">R</span>
            <ul>
                <li>Ggplot</li>
                <li>MLR, Logistic Regression, KNN, KMeans, Text mining, Classification and regression trees, Random forest</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">PowerBI</span>
            <ul>
                <li>DAX/M</li>
                <li>Time Intelligence</li>
                <li>Slicing/Filtering</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">Tableau</span>
            <ul>
                <li>Interactive Dashboards</li>
                <li>Slicing/Filtering</li>
                <li>Calculated Columns</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">AWS & Azure & GCP</span>
            <ul>
                <li>Conceptual understanding of cloud database offerings such as SQL Server on Azure VM, Azure Databricks, Azure SQL Managed Instance, Azure SQL Database, Azure CosmosDB, AWS Aurora, AWS Elasticache, AWS DynamoDB, AWS DocumentDB, AWS Redshift, AWS Neptune & GraphQL, GCP BigQuery, GCP BigTable, GCP DataStore, GCP Cloud SQL, GCP Cloud Spanner</li>
            </ul>
        </div>

        <div class="skill">
            <span class="skill-category">Excel</span>
            <ul>
                <li>Pivot Tables</li>
                <li>PowerQuery</li>
                <li>Solver</li>
                <li>Data Analysis Toolpack</li>
                <li>Montecarlo Simulations</li>
            </ul>
        </div>
    </div>
</body>
</html>


***

### Headings by default:

# This is the default title
## This is the default title
### This is the default title
#### This is the default title
##### This is the default title
###### This is the default title

{% highlight markdown %}
## Heading first level
### Heading second level
#### Heading third level
{% endhighlight %}

***

### Lists

#### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

#### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

{% highlight markdown %}
1. Order list item 1
2. Order list item 1

* Unordered list item 1
* Unordered list item 2
{% endhighlight %}

***

### Quotes

> Coming together is a beginning; keeping together is progress; working together is success. — Edward Everett Hale

***

### Syntax Highlighter

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}

***

### Videos

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>

***

### Images

![]({{site.baseurl}}/images/09.jpg)
*Backyard*

***
