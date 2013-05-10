---
layout: page
title: Curriculum vitae
tagline:
---
{% include JB/setup %}

## Education
Diplom-Informatiker (FH) - Computer Science in Media (comparable to a M.S.C)

## Work Experience
`2010 - present, Senior Software Engineer, ninemsn`

### Engineering Team
Lead Developer for Automation, Infrastructure as Code and Release Management related challenges.
At ninemsn I'm part of the Engineering Team which mentors fellow developers and thrives for technical excellence.

### [news.ninemsn.com.au](http://news.ninemsn.com.au)
In October 2012 we launched Australia's biggest news site written in ASP.NET MVC3 hosted on Amazon.
In this project I championed the Release Management of the CMS and news site, working closely with the Operations and the Lead Architect to achieve Continues Delivery.
During the news and in a true DevOps fashion we automated everything from the infrastructure setup to push button deployments of the application, while still managing to being highly available.
As part of this project we implemented a Package Manager for windows, written in .NET to rollout IIS Websites and Windows Services using AWS S3 as a distribution method and Powershell to install the payloads.

### Mobile Advertising
I was part of a small team developing .NET for a mobile marketing and advertising web platform.



Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

In `_config.yml` remember to specify your own data:

    title : My Blog =)

    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


