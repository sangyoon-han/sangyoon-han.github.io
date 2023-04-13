---
layout: default
---


{% include career-profile.html %}

{% unless site.data.data.sidebar.education %}
  {% include education.html %}
{% endunless %}


{% include publications.html %}

{% include projects.html %}

{% include experiences.html %}

<!-- {% include skills.html %} -->

{% include oss-contributions.html %}

<!-- ---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
--- -->
