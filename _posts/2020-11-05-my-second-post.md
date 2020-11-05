---
title: "2nd post"
date: 2020-11-05
my_num: 5
---
# Welcome to my second post!
1st line
2nd line
3rd line
4th line
5th line
Page title with Liquid:
{{ page.title }}
<br>

Hey, will it show spece without br tag?
{{ "that's only lower case" | capitalize }}

**block for**
{% for i in (1..page.my_num) %}
  <li>{{ i }}</li>
{% endfor %}
**endfor**
