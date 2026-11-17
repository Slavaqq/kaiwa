---
layout: default
title: "日本語の会話"
---
<h1 lang="ja">{{ page.title }}</h1>

Testovací obsah

{% assign conversations = site.pages | where: 'layout', 'conversation' | sort: 'conversation_date' | reverse %}
{% for conversation in conversations %}
- [{{ conversation.title }}]({{ conversation.url | relative_url }})
{% endfor %}
