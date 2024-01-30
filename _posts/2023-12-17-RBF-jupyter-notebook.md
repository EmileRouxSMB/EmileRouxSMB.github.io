---
layout: post
title: RBF tutorial 
date: 2023-12-17 08:57:00-0400
description: RBF regression 
tags: Numerical-Methods Machine-Learning
categories: posts
giscus_comments: true
related_posts: false
---

Bellow is an exemple of use of the python package [rbf-regression](https://gitlab.com/emileroux83/rbf-regression) in a jupyter notebook.

It show how to use the package to fit a 1D function.



{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/RBF-tuto1.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/RBF-tuto1.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}


