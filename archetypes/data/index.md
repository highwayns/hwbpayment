---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
layout: activiti
---

**Insert Lead paragraph here.**

## data list

{{ range first 10 ( where .Site.RegularPages "Type" "cool" ) }}
* {{ .Title }}
{{ end }}