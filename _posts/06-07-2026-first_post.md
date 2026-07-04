---
layout: post
title: "Day X: [Short, specific title — e.g. 'Replacing my blocking socket loop with epoll']"
date: 2026-07-05
tags: [redis, systems-programming, c, build-in-public]
---

## What I was trying to do

<!-- 1-2 sentences. State the concrete goal for this step, not the whole project.
Example: "Today's goal was to stop blocking on a single client's read() and instead
handle multiple clients without spawning a thread per connection." -->

## The problem / why it's hard

<!-- This is the most important section. Explain the underlying CS concept
a reader should walk away understanding, even if they never touch your code.
Example: "A single-threaded blocking read() call stalls the entire server —
if client A sends nothing, client B can't be served either. Here's why..." -->

## What I tried

<!-- Show the actual approach, with a short code snippet (5-15 lines max —
don't paste your whole file). Include what DIDN'T work first if relevant;
readers love the messy middle, not just the clean answer. -->

```c
// short, relevant snippet only
```

## What I learned

<!-- The "aha" — the insight that makes this post worth reading.
Compare to how real Redis does it if you can (this is your differentiation angle). -->

## What's next

<!-- 1 sentence teaser for the next post — keeps readers coming back. -->

---

**X thread version** (post this on X, link to full post):

1/ [Hook — a surprising fact or question. e.g. "Redis handles 10,000s of
connections with ONE thread. I just found out why blocking sockets can't do this."]

2/ [The problem in plain language, 1-2 short sentences]

3/ [Screenshot or code snippet — visuals get more engagement than text alone]

4/ [The insight/lesson]

5/ [Link to full blog post] + "Building Redis from scratch in C, posting every step 🧵"

