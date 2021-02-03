---
title: How to create a skeleton-like loading effect using only a few lines of
  CSS (SCSS)
metaDescription: This is a sample meta description. If one is not present in
  your page/post's front matter, the default metadata.desciption will be used
  instead.
date: 2021-02-03T18:17:38.597Z
author: Håvard Brynjulfsen
summary: Users hate to wait. Use skeleton loading instead of a boring spinner.
tags:
  - tech
  - environment
  - politics
  - sport
---
## Just give me the code

What we'll be creating: [Demo (CodePen)](https://codepen.io/havardob/full/dyGGGzq)

Notice that I've added a height and a width to the `div` element. I'm only doing this so that we have someplace to view what the `skeleton` class does.

## Breaking it down

We start of with a basic background-color. This will be the background of our skeleton at which the shine effect will slide across. 

```
background-color: #e2e5e7;
```

Then we'll add the shine effect using `background-image: linear-gradient()`: