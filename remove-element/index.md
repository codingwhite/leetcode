---
layout: solution
title: Remove Element
date: 2014-07-31 15:57:51 +0800
---
{% assign leetcode_name = {{page.path | remove: '/index.md'}}  %}
{% assign leetcode_readme = {{leetcode_name | append: '/README.md' | prepend: '_root/' }}  %}
{% include {{leetcode_readme}} %}
