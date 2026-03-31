---
title: Projects
nav:
  order: 3
  tooltip: Student Thesis Projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Thesis Projects

Here we advertise thesis projects for both graduate and undergraduate students. 
If you are interested in one or more of the projects, feel free to [get in touch]({% link contact/index.md %}).


{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
