---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

This is my digital garden. Feel free to look around.

> 🧭 How to navigate: Click on a hub under Hub Worlds to get an index view of notes sorted by its category.

## Hub Worlds 🌎
- <a class="internal-link" href="/about">About 🐈</a>
- [[00 Books Hub|Books Hub 📚]]
- [[00 Interests Hub|Interests Hub 🤔]]
- [[00 Tutorials Hub|Tutorials Hub 🛠️]]

<div class="grid-element">
  <h2>Notes 👨‍💻</h2>

  {% assign notes = site.notes | where_exp: "item", "item.path contains 'notes'" %}
  <p>
    Here you can find all {{ notes.size }} notes in a nice graph view. The ones with emojis denote a hub note.
  </p>

  {% include notes_graph.html %}
</div>