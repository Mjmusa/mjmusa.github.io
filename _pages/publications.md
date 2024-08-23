---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

### Jump to: [Journal Articles](#journal-articles)&nbsp;&nbsp;&nbsp;[Conference Articles](#conference-articles)&nbsp;&nbsp;&nbsp;[Patents](#patents)<br><br>


{% include base_path %}

# Journal Articles
{% for post in site.publications reversed %}
  {% if post.type == "journal" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Conference Articles
{% for post in site.publications reversed %}
  {% if post.type == "conference" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Patents
{% for post in site.publications reversed %}
  {% if post.type == "patent" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
