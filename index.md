---
layout: default
title: Главная
---

viva! Добро пожаловать на этот сайт!

## 🧩 PE-разбор
{% assign pe_posts = site.categories.pe %}
{% for post in pe_posts %}
- <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

---

## 🛠 ASM Build
{% assign asm_posts = site.categories.asm-build %}
{% for post in asm_posts %}
- <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
