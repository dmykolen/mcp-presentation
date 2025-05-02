---
# theme: seriph
# theme: default
theme: ./theme
#theme: slidev-theme-neversink
colorSchema: dark
layout: default

defaults:
  class: [ bg-black ]

class: [ text-center, text-xs, bg-black ]

info: |
  ## About Model Context Protocol (MCP)

transition: slide-left
title: MCP
mdc: true
author: Dmytro Mykolenko
#addons:
#  - tldraw
#  - slidev-addon-python-runner
hideInToc: true

# color: black
---

<style>
@keyframes gradient-x {
  0%, 100% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
}

.animate-gradient-x {
  background-size: 300% 300%;
  animation: gradient-x 6s ease infinite;
}

@keyframes gradient-drift {
  0% {
    background-position: 0% 0%;
  }
  25% {
    background-position: 100% 50%;
  }
  50% {
    background-position: 50% 100%;
  }
  75% {
    background-position: 0% 50%;
  }
  100% {
    background-position: 0% 0%;
  }
}

.animate-gradient-drift {
  background-size: 200% 200%;
  animation: gradient-drift 10s ease infinite;
}

body {
  @apply bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500;
}
</style>


<div class="animate-gradient-drift bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 inset-0 bg-clip-text text-center text-8xl font-extrabold text-transparent shadow-lg shadow-white/50 b-0 rounded-md w-1/3 h-1/3 left-[35%] absolute top-1/3 p-6">MCP<p class="text-sm p-0 mx-2">(Model Context Protocol)</p>
</div>

<style>
  .slidev-page-1 {
    @apply bg-black;
  }
</style>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
hideInToc: true
color: dark
class: text-md
---

# Table of contents

<br>
<Toc maxDepth="1"></Toc>

---
transition: fade-out
src: ./pages/1.md
class: text-xs
---
<style>
  body {
    font-size: 0.75rem;
  }
</style>

---
transition: fade-out
mdc: true
src: ./pages/2.md
---


---
transition: fade-out
src: ./pages/3.md
---
---
transition: fade-out
src: ./pages/4.md
---
---
transition: fade-out
class: text-xs
src: ./pages/5.md
---
---
transition: fade-out
src: ./pages/6.md
---
---
src: ./pages/10.md
---
---
layout: default
---

<div class="grid grid-cols-2 gap-2 pt-2 -mt-42">
<div class="bg-black rounded-3xl border-4 border-purple-700 shadow-xl shadow-black p-2 relative overflow-hidden backdrop-blur-md scale-60" style="width: 425px; height: 812px;">
  <div class="absolute top-0 left-1/2 -translate-x-1/2 w-32 h-8 bg-gray-900 rounded-b-xl z-10"></div>
  <div class="absolute top-2 left-10 w-3/4 rounded-xl z-10 text-zinc-400 text-sm text-center font-bold">mcphub.io</div>
  <iframe src="https://mcphub.io/" class="w-full h-full rounded-2xl border-none" style="transform: scale(1); transform-origin: top left;" loading="lazy"></iframe>
</div>

<div class="bg-black rounded-3xl border-4 border-purple-700 shadow-xl shadow-black p-2 relative overflow-hidden backdrop-blur-md scale-60" style="width: 425px; height: 812px;">
  <div class="absolute top-0 left-1/2 -translate-x-1/2 w-32 h-10 bg-black rounded-b-xl z-10"></div>
  <div class="absolute top-2 left-10 w-3/4 rounded-xl z-10 text-zinc-400 text-sm text-center font-bold">mcp-get.com</div>
  <iframe src="https://mcp-get.com/" class="w-full h-full rounded-2xl border-none" style="transform: scale(1); transform-origin: top left;" loading="lazy"></iframe>
</div>
</div>
