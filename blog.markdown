---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

Welcome to my blog. I share insights, lessons learned, and practical notes from my journey as a cybersecurity student.  
My posts cover technical topics, project updates, and reflections on industry trends.

## Topics I Write About

- Ethical hacking and penetration testing
- Network security and monitoring
- Digital forensics and incident analysis
- Capture The Flag (CTF) writeups
- Cybersecurity learning resources and career development

## Latest Blog Posts

{% if site.posts.size > 0 %}
{% for post in site.posts limit: 10 %}
### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt | strip_html | truncate: 180 }}

[Read more]({{ post.url | relative_url }})

---
{% endfor %}
{% else %}
No posts published yet. Check back soon for upcoming articles and project writeups.
{% endif %}

## LinkedIn Highlights

I also share shorter cybersecurity insights and updates on LinkedIn.

- [LinkedIn Profile](https://www.linkedin.com/in/sara-amelia-bilic-586ba3353/)
- [Post: Add your LinkedIn post title here](ADD_LINK_TO_POST)
- [Post: Add your LinkedIn post title here](ADD_LINK_TO_POST)
- [Post: Add your LinkedIn post title here](ADD_LINK_TO_POST)

> Tip: Replace the placeholder links above with your actual LinkedIn post URLs.
