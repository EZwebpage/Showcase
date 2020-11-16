---
title: Home
---

# <i class="fas fa-flask"></i>Home

## Feature

A _feature_ component, with an image, a heading, markdown text, and an optional image link.
Useful for your home page, where you want to highlight key points about your lab.

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Nec sagittis aliquam malesuada bibendum arcu.
{% endcapture %}
{%
  include feature.html
  image="images/laboratory.jpg"
  link="resources"
  heading="Extra, extra, read all about it!"
  text=text
%}

{% capture text %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Nec sagittis aliquam malesuada bibendum arcu.
{% endcapture %}
{%
  include feature.html
  image="images/laboratory.jpg"
  link="resources"
  heading="Extra, extra, read all about it!"
  text=text
%}
