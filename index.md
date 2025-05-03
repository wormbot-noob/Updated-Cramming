---
layout: default
title: "For Abeer – Study Hub"
---

<div class="system-section">
  <h2>Cardiovascular</h2>
  <div class="topics">
    {% for mod in site.data.modules.Cardiovascular %}
      <a href="{{ mod.url }}">{{ mod.name }}</a>
    {% endfor %}
  </div>
</div>

<!-- repeat for other systems, or hard-code links like before -->
