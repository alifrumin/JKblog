---
layout: post
title:  "Making a MEAN Stack App"
date:   2016-01-03 23:51:52 -0500
categories: jekyll update
---
The MEAN Stack
==============
M = MongoDB
E = ExpressJS
A = AngularJS
N = NodeJS

Pre-reqs
========
In order for you to follow along you will need to have Node.js and MongoDB installed on your computer

User-Stories
============
What are we building? below I will outline the MVP (Minimum Viable Product) we are shooting for.
-Users can posts
-Users can delete posts
-

Getting Started
===============
1. Create a directory for the app using the command line: `mkdir NAMEOFAPP`
2. then CD into that directory `cd NAMEOFAPP`
then create an index html file so we can see some stuff happening `touch index.html`
3. and an app.js to write some angularJS in `touch app.js`
4. Open this directory in your text editor
5. in the index.html add the following:

{% highlight html %}
<html>
  <head>
    <title>My Angular App!</title>
    <script src="http://ajax.googleapis.com/ajax/libs/angularjs/1.3.10/angular.min.js"></script>
    <script src="app.js"></script>
  </head>
  <body ng-app="flapperNews" ng-controller="MainCtrl">
    <div>
      {{test}}
    </div>
  </body>
</html>

{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
