---
layout: fullwidth
title: Micromouse
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Berkeley IEEE Micromouse
---

# Micromouse
{:.no_toc}

## Course Info

The UC Berkeley IEEE Student Branch’s Micromouse DeCal is a hands-on course aimed at undergraduates with an interest in robotics. In the class, teams of ~2 students are formed to build and program autonomous, maze-solving cars that follow the standards set in IEEE’s Micromouse competition.

The course assumes no experience and will be based around a series of labs and project milestones that cover a wide range of robotics concepts. The course will expose students to CircuitPython programming, autonomous navigation, sensors, PID, and basic electrical engineering, while preparing them for an in-class competition at the end of each semester. Teams are also provided with the opportunity to qualify for funding to attend competitions among other schools in California and neighboring states.

All necessary parts will be provided to students at no cost.

### Enrolling in HOPE

The Micromouse Discord is live: https://discord.gg/FRWvxrTChh

This semester the Decal will take place in Giannini Hall 141 on Mondays from 5-7PM, starting DATE GO HERE. Make sure to fill out the application! https://forms.gle/y2pQK1291sDVYtzM8

Note that the slides on this page are just for preview. They'll be updated before lecture and posted after.

### Prerequisites

???

## Course Schedule

TBD

CALENDAR GO HERE

{% for module in site.modules %} {{ module }} {% endfor %}

## Grading

???

### Office Hours

???

### Contact & Resources

use the Discord server

## Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

### Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
