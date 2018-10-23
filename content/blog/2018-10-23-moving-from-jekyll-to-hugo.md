+++
title =  "Moving from Jekyll to Hugo"
description = ""
date = 2018-10-23
draft = true
+++


Moving the OKF website from Jekyll to Hugo.

Why move?

Super slow build times, weird i18n

Why Hugo?

Running it locally with only 1 executable

Super fast build time

Nice i18n

Why not Gutenberg?

No mature enough yet :/

# Features

## Nested ranges

https://discourse.gohugo.io/t/solved-can-i-nest-ranges-looking-at-data/10594

## ATOM feed
https://gist.github.com/lpar/7ded35d8f52fef7490a5be92e6cd6937

``` toml
[mediaTypes]
[mediaTypes."application/atom"]
suffixes = ["xml"]

[outputFormats.Atom]
mediaType = "application/atom"
baseName = "atom"
isPlainText = false

[outputs]
section = [ "HTML", "Atom" ]
```

`layouts/_default/section.atom.xml`


Alternate formats in head block

``` html
# layouts/_default/section.html
{{ define "head" }}
  {{ range .AlternativeOutputFormats -}}
    <link rel="{{ .Rel }}" type="{{ .MediaType.Type }}" href="{{ .Permalink | safeURL }}">
  {{ end -}}
{{ end }}
```


## LUNR JS Search

double quotes
``"content":  {{ $page.RawContent | jsonify }}``


## Build and deploy



# Further reading

https://regisphilibert.com/blog/2018/02/hugo-the-scope-the-context-and-the-dot/
