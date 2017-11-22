---
layout: defaults/page
permalink: index.html
narrow: true
---

{% include components/intro.md %}

[View Andrew's Resume]({{ site.baseurl}}{% link _pages/about.md %})

### Portfolio

Andrew has worked in academic libraries for many years and has a large portfolio of experience, publications, and presentations.

[Browse Andrew's Professional Portfolio]({{ site.baseurl }}{% link list/portfolio.html %}).


### Projects

Andrew keeps himself busy on open-source projects. [The full list is here]({{ site.baseurl }}{% link list/projects.md %}).


### Posts

Andrew sometimes posts about his work. [View all posts by year here]({{ site.baseurl }}{% link list/posts.html %}).

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}
