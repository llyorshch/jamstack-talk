---
marp: true
title: A Jamstack Journey
description: Hosting Marp slide deck on the web
paginate: true
_paginate: false
theme: gaia
_class: lead
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.jpg')
---

<style>
section.lead h1 {
  text-align: center;
}
section.subLead h2 {
  text-align: center;
  font-size: 6em;
  
}

img[alt~="center"] {
  display: block;
  margin: 0 auto;
}
</style>

![bg left:50% 47%](assets/Jamstack_Icon_Original_Transparent.png)

# **A Jamstack Journey**

@llyorshch
jorge@ge.org.es

---
<!-- _class: lead -->
# "I need a web page"

![w:600](assets/cunyao.gif)

---
<!-- _class: lead -->
# "I already have hosting"

![ w:750](assets/wordpress.png)

---
# Done! <!--fit-->

--- 
<!-- _class: lead -->

Of course not

---

# What's the matter?

--- 

# What's the matter?
![w:1000 center](assets/I_ve_got_a_bad_feeling_about_this.gif)

--- 

### Why?

- To deliver HTML, you don't need a LAMP stack
  
![w:700 center](assets/lamp.svg)

---

# Enter Jamstack

![w:900 center](assets/jamstack_acronym.jpg)

---
# Jamstack Runtime Architecture

![w:600 center](assets/jamstack_architecture.png)

---
# Jamstack Workflow

![w:800 center](assets/jamstack_workflow.png)

---
# Ok but, why Jamstack?

My take on this:

* Better developer experience (Modern tools, Git, Markdown) 🤓
* No security issues → Peace of mind 💆🏻
* Damn fast 🚴🏻‍♀️💨
---
# Ok but, why Jamstack?

My take on this:

- Better developer experience (Modern tools, Git, Markdown) 🤓
- No security issues → Peace of mind 💆🏻
- Damn fast 🚴🏻‍♀️💨

But also...

* Scalability
* Portability
* Maintainability

---

# Cool. What next?

![w:700 center](assets/jamstack_landscape.png)

---

# (Some) Site Generators [(all)](https://jamstack.org/generators/)

|  | Tech | Leitmotif |
| --- | --- | --- |
| ![h:65](assets/jekyll_logo.svg) | Ruby | The grandfather adopted by GitHub |
| ![h:65](assets/next-js_logo.svg) | Js & React | Almighty Web Dev Framework |
| ![h:60](assets/Gatsby_Logo.svg) | Js & React | Also React but more CMS based |
| ![h:65](assets/Nuxt-js_logo.png) | Js & Vue | For the Vue.js fans |
| ![h:60](assets/hugo-logo.svg) | Go | Batteries included and ready to "go" |

---

# My Choice (YMMV)

![h:200 center](assets/hugo-logo.svg)

Because
* I am not a _hardcore_ Javascript developer
* I don't like Ruby (but Jekyll is nice)
* The learning curve was less overwhelming

---
# Pros and cons

| Pros | Cons |
| --- | --- |
| Good documentation | Debugging is not easy |
| The template language is simple but powerful| The abstractions are not straightforward |
| The themes are perfect for a quick start | In "Server" mode, the hugo daemon sometimes needs to be restarted |
| Working with Markdown is great | You have to know the basics of Go |
| VSCode integration |  |

--- 

# Build & Deploy options

Local environment: `hugo` command

![h:100](assets/Netlify_logo.svg)

![h:100](assets/Github_Actions_Logo.png) Github Actions

---

# Netlify

![h:500 center](assets/Netlify_Deploys.png)

---

# Netlify CMS

![h:500 center](assets/Netlify_CMS.png)

---

# Github Action

![h:500 center](assets/Github_Action.png)

---
<!-- _class: lead -->

# Demo time!
<!--
Demo Steps

- Show the structure of the site
  - content
  - Data
  - public
  - static
  - Template Layouts
  - Template plugins
  - Hugo config
  - Netlify config
  - Github actions config
- Local development
- Netlify build and deploy
- Github action build and deploy
- Netlify CMS
-->
---
<!-- _class: lead -->
<!-- _footer: https://github.com/llyorshch/jamstack-talk/ -->

# Thanks!