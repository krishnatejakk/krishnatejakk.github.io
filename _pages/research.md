---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

The purpose of our research is to develop next-generation techniques for developing efficient, reliable, and fair machine learning systems. To this end, our research attempts to address the following issues:
1. Development of data-efficient machine learning techniques to minimize the cost of training on large datasets.
2. Development of robust machine learning techniques to reduce the detrimental and potentially dangerous impact that adversaries in the datasets, such as imbalanced classes and noise in labels, have on machine learning models. 
3. Development of parameter efficient machine learning models with a goal of deployment in low resource environments and faster inference times.
4. Development of fair machine learning techniques to reduce the chance of discriminatory effects and unfairness resulting from machine learning models.

## Data Efficient Machine Learning
{% for post in site.dataefficientprojects reversed %}
  {% include archive-single.html %}
{% endfor %}
