---
layout: default
---

## About Me

<img class="profile-picture" src="profile.jpg" alt="Profile photo">

Hi! 👋 欢迎来到我的博客。

这里记录我在技术和生活上的思考与探索。

<!-- 联系方式，按需取消注释
[Email](mailto:you@example.com) / [GitHub](https://github.com/yourname)
-->

<br>

## Recent Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) — *{{ post.date | date: "%Y-%m-%d" }}*
  {{ post.description }}
{% endfor %}

[View all posts →](/blog)
