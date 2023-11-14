# SM-art-and-photography
Bringing art and photography together


git config --global.name "mugsim"
git config -- global user.email"simon.mugume@stud.unibas.ch"
git add -A

---
title: "Distill Navigation Bar Example"
output: distill::distill_article
navbar:
  left:
    - text: "Home"
      href: "/"
    - text: "Page 1"
      href: "/page1"
    - text: "Page 2"
      href: "/page2"
---

# Home Page
## Welcome to the Home Page
This is the home page content.

# Page 1
## Welcome to Page 1
This is the content of Page 1.

# Page 2
## Welcome to Page 2
This is the content of Page 2.

library (distill)
create_article("Home")

---
title: "My Distill Website"
output: distill::distill_article
---

# My Image

Here is a resized image of a cat:

<img src="images/cat.jpg" alt="Cat" width="300" height="200">


table of content
 distill::distill_article:
    toc: true
    toc_depth: 2
    toc_float: true


