---
title: "Origin"
date: 2022-02-25T09:21:49-05:00
draft: false
math:
    enable: true
---

$a+b=c$

{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}

