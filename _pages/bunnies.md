---
layout: archive
title: "Bunnies"
permalink: /bunnies/
author_profile: true
---

Just a few minutes from the Economics Department at SU there's a [small farm](https://storaskuggans4hgard.se/) where they have some of the chubbiest bunnies known to man. If you get the chance, definitely go visit! Below are some of my favorite pictures.

{% assign bunny_images = site.static_files | where: "path", "/images/bunnies" %}
<div class="bunny-gallery" style="display: flex; flex-wrap: wrap; gap: 10px;">
  {% for image in bunny_images %}
    <div style="flex: 1 1 calc(50% - 10px); box-sizing: border-box;">
      <img src="{{ image.path }}" alt="Bunny image" style="width: 100%; display: block;">
    </div>
  {% endfor %}
</div>
