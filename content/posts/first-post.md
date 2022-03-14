---
title: "My First Post"
date: 2022-02-25T14:39:39-05:00
draft: false
tags: ["random"]
categories: ["Miscellaneous"]
toc:
    enable: false
math:
    enable: true
description: "This is the first post of this website."
featuredImage: "/images/postimg/banner-firstpost.jpeg"
featuredImagePreview: "/images/postimg/banner-firstpost.jpeg"

---
<!--more-->
This is the first post of this website. The website was powered by [**Hugo**](https://gohugo.io/) using [**FeelIt theme**](https://feelit.khusika.com/) developed by [**Khusika**](https://khusika.com/). All of the contents are hosted in [:(fab fa-brands fa-github):**GitHub**](https://github.com/) and deployed by [**Netlify**](https://netlify.com/). The theme is fully customizable and I can do a lot of interesting stuff to it too.


Here is some math:
\\[\zeta\left( 2\right)=1+\frac{1}{2^2}+\frac{1}{3^2}+\cdots=\frac{\pi^2}{6}. \\]

I can write chemical reactions like this:
\\[ \ce{Li^6_3 + n -> He^4_2 + H^3_1} \\]

I can also draw cool diagrams like this:
{{< mermaid >}}
graph LR;
    A[All] -->|of| B(these)
    B --> C{objects}
    C -->|are| D[homeomorphic]
    C -->|to| E[each other]
{{< /mermaid >}}

or like this:
{{< mermaid >}}
gantt
    dateFormat  YYYY-MM-DD
    title The Jurassic Period
    section What I want to do
    Sleep            :done,    des1, 2014-01-06,2014-01-08
    Sleep               :active,  des2, 2014-01-09, 3d
    Sleep               :         des3, after des2, 5d
    Play games               :         des4, after des3, 5d
    section What I hate to do
    Wash dishes :crit, done, 2014-01-06,24h
    Wash dishes          :crit, done, after des1, 2d
    Wash dishes             :crit, active, 3d
    Clean bathroom      :crit, 5d
    Clean kitchen        :2d
    Wipe the floor           :1d
{{< /mermaid >}}

or a _git graph_:
{{< mermaid >}}
gitGraph:
options
{
    "nodeSpacing": 100,
    "nodeRadius": 10
}
end
    commit
    branch newbranch
    checkout newbranch
    commit
    commit
    checkout master
    commit
    commit
    merge newbranch
{{< /mermaid >}}

And guests can comment on my posts too (powered by [:(fas fa-solid fa-comments):**Vssue**](https://vssue.js.org/))


<script\>
function ShowJoke()
  {
    var Joke = [
    	'Joke1',
    	'Joke2',
    	'Joke3',
    	'Joke4',
    	'Joke5',
    	'Joke6'
    ];
    var Pick = Math.floor(Math.random() * (Joke.length));
    document.write(Joke[Pick]);
  }
  
  document.addEventListener("load", ShowJoke());
</script\>
