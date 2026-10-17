---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
year: "{{ now.Format "2006" }}"
location: "Indonesia"
client: "Editorial"
cover: "cover.webp"
summary: "Summary of the photographic series..."
photos:
  - src: "foto-01.webp"
    caption: "Caption for frame 01."
  - src: "foto-02.webp"
    caption: "Caption for frame 02."
---

Introduction and storytelling narrative goes here...
