---
title: "A"
date: 2018-05-14T14:43:03+05:30
draft: false
---
This is a.md

{{ range .Site.Data.state}}
	<h2>{{ .name }}</h2>
{{end}}

