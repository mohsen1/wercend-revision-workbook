---
layout: default
title: Reverse outline worksheet for writers
description: Try Wercend’s revision exercises and print a one-page reverse outline worksheet for your writing group.
image:
  path: https://azimi.me/wercend-revision-workbook/assets/worksheet-preview.png
  width: 1200
  height: 630
  alt: Wercend worksheet asking who the reader is and what they need to understand or do.
---
{% capture guide %}{% include_relative README.md %}{% endcapture %}
{{ guide | replace: 'utm_source=github', 'utm_source=azimi.me' | replace: '](worksheet.md)', '](worksheet.html)' | replace: '](second-exercise.md)', '](second-exercise.html)' }}
