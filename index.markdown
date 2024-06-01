---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
author_profile: true
title: ""
---

# Hello!
## I'm currently spending time on:

- **Reading:** [3D Negotiation](https://www.google.com.sg/books/edition/3_d_Negotiation/uKpnhrrWEaUC?hl=en&gbpv=0) by David Lax and James K. Sebenius, [1984](https://www.goodreads.com/book/show/61439040-1984) by George Orwell
- **Learning:** [HarvardX CS109X Introduction to Data Science with Python](https://learning.edx.org/course/course-v1:HarvardX+CS109x+3T2023a/home), [Introduction to Linux](https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS101x+1T2023/home)
- **Project:** building this site!

## Skills

<div class="skills-container">
  {% assign skills = "Python, Requirements Gathering, Communication, Problem Solving, BeautifulSoup, numpy, pandas, scikit-learn" | split: ", " %}
  {% for skill in skills %}
    <span class="skill">{{ skill }}</span>
  {% endfor %}
</div>

<style>
  .skills-container {
    margin-top: 20px;
  }
  .skill {
    display: inline-block;
    background-color: #f0f0f0;
    color: #333;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 5px;
    text-decoration: none;
  }
  .skill:hover {
    background-color: #e0e0e0;
  }
</style>

