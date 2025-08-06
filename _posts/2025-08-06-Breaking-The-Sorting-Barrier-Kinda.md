---
title: Breaking the sorting barrier, kinda
description: A*, pathfinding
author: omj
date: 2025-08-06 12:00
tags: Algorithm, Pathfinding]
pin: false
math: true
mermaid: true
# image:
#   path: /commons/devices-mockup.png
#   lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
#   alt: Responsive rendering of Chirpy theme on multiple devices.
---


<!-- markdownlint-capture -->
<!-- markdownlint-disable -->
## Breaking the sorting barrier, kinda
<!-- markdownlint-restore -->

Exciting breakthrough in pathfinding algorithms! A new research paper (https://arxiv.org/pdf/2504.17033) has developed an algorithm that breaks the theoretical speed barrier for shortest path calculations potentially revolutionizing how we handle pathfinding in games.
This isn't actually an A* improvement, but rather a fundamentally new approach to single-source shortest paths that achieves O(m log²/³ n) complexity versus traditional methods at O(m + n log n). For sparse maps (think open worlds with scattered obstacles), early tests show 2-5x speed improvements that grow with map size. However, on dense maps (like tight dungeon layouts), the advantage diminishes and can even reverse.
The implications for large-scale game worlds could be massive imagine faster NPC pathfinding across entire continents!

https://claude.ai/public/artifacts/8f67134c-f403-48e9-a942-8235f873ecec
(Thanks Claude)