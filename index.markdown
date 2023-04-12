---
layout: default
---


{% include career-profile.html %}

{% unless site.data.data.sidebar.education %}
  {% include education.html %}
{% endunless %}

{% include experiences.html %}

{% include projects.html %}

{% include oss-contributions.html %}

{% include publications.html %}

{% include skills.html %}


<!-- ---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
--- -->
