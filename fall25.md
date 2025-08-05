---
layout: page
title: 2025 Fall
---

{% assign team = site.data.team_fall25 | sort : "name" %}

### Instructors

<div class="clearfix">
{% for people in team %} 
    {% if people.type == "PI" %} 
        {% include avatar_entry.html %} 
    {% endif %} 
{% endfor %}
</div>

### Teaching Assistants
<div class="clearfix">
{% for people in team %} 
    {% if people.type == "TA" %} 
        {% include avatar_entry.html %} 
    {% endif %} 
{% endfor %}
</div>

### Course Schedule

<iframe style="width:100%; height:800px; overflow:hidden" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTsEiqs0nBac2Hi7Bt2MMorqUSo9agLotfj4kUIvG-RV_71DjMmvupZAxw2v5zMhg4Zdw59yo1rTPc-/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

### Labs and Final Project
Through this quarter, students will build a self-driving stack from scratch via labs and final projects.

- Lab 0: Carla setup
- Lab 1: Perception
- Lab 2: SLAM
- Final Project: Integrating Planning and Control

Labs will be distributed using Github Classroom.