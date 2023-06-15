---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
weight: {{ now.Format "20060102" }}
menu:
  sidebar:
    name: "todo"
    identifier: {{ .Date }}
    weight: {{ now.Format "20060102" }}
    parent: {{ now.Format "2006-01" }}
---
