---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hallo verden!
publishDate: 11 Apr 2022
name: Morten Jacobsen
value: 128
description: Bare en post til!
---

<Cool name={frontmatter.name} href="https://twitter.com/mortjac" client:load />

Bra!
