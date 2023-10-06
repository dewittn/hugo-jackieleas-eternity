---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}

images: "/images/portraits/{{ .Name | replace "-" " " | title }}.jpg"
images: 
    - /images/portraits/
tags:
    - portrait  # all posts
    - selfies
images: "{{ replace .Name "-" " " | title }}"
---

