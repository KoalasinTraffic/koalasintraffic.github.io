---
layout: spd
title: Enemies
---

# Enemies

There are many different enemies to defend against in Small People Defense. Enemies are spawned with a new wave every 30 seconds, or 6 seconds if rushed by the player. Their stats are dependent on the number of enemies spawned and based on how much money the player could have earned over the course of the level.

# Serfs

Serfs are spawned every 3 seconds. Rushing does not influence the spawn rate of serfs. Starting from wave 100, serfs are promoted to super serfs and have 10% more health.

[//]: # (Stats can be found within HUDLevel.cpp)

# Enemy List

<ul>
  {% assign items = site.enemy %}
  {% for item in items %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
<ul>
