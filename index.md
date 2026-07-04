---
layout: default
title: Home
---

# Hey, I'm Abhijit Shankhdhar 👋

I'm a Senior Backend Engineer with 5 years at Paytm, working on high-throughput distributed payment systems in Java, Spring Boot, Redis, and Kafka. Most recently I've been exploring AI-native backend development — including architecting a Model Context Protocol (MCP) server that lets AI clients handle merchant payment operations conversationally.

I care about systems that hold up under real load — reactive architectures, distributed rate limiting, event-driven coordination — and I like understanding things down to the metal, not just the framework layer.

- 💼 [LinkedIn](https://linkedin.com/in/abhijitshankhdhar)
- 💻 [GitHub](https://github.com/im-abhijit)
- 📧 abhijitshankhdhar@gmail.com

## What I'm building right now

I'm building **Redis from scratch in C** — raw sockets, my own epoll-based event loop, my own hash table, and persistence, with no libraries or shortcuts. It's a way to deliberately go deeper into the systems fundamentals behind tools I use every day at work, and I'm documenting every step — bugs, dead ends, and all — here and on X.

Follow the build day-by-day: [@your_x_handle](https://x.com/your_x_handle)

## Latest posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%b %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

## Build roadmap
