---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

# Hello! I'm Jon Moshier and this is my page. 

## I'm a software engineer living in Denver, CO. I work at [Transmed Systems](http://xbtransmed.com) writing code and building deployment infrastructure. Here's a copy of my [resume](https://github.com/jonmoshier/resume/blob/master/jonmoshier-resume.pdf) if you're inerested.

## Contact
Email: [jonmoshier@gmail.com](mailto:jonmoshier@gmail.com)  
Github: [github.com/jonmoshier](https://github.com/jonmoshier)  
LinkedIn: [linkedin.com/in/jmoshier](https://linkedin.com/in/jmoshier)

## Blog Posts

{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a>
{% endfor %}
