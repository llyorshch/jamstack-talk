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
# No way! <!--fit-->
--- 
<!-- _class: lead -->

Nope. Be kind. 🤌🏻

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

![w:800 center](assets/gatsbycontentful2.png)

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

# Cool. What's next?

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
  - Hugo config
  - content
  - Data
  - public
  - static
  - Template Layouts
  - Template plugins
  - Netlify config
  - Github actions config
- Local development
- Netlify build and deploy
- Netlify CMS
- Github action build and deploy
-->
---
<!-- _class: lead -->
<!-- _footer:  -->

[![](assets/dulzumat-logo-pie-de-pagina.png)](http://www.dulzumat.com)

[![w:60](assets/Facebook_icon_2013.svg)](https://es-es.facebook.com/Dulzumat-107103074234058)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![w:60](assets/Instagram_AppIcon_Aug2017.png)](https://www.instagram.com/dulzumat/)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![w:80](assets/Octocat.png)](https://github.com/llyorshch/jamstack-talk/)