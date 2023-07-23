---
theme: default
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Welcome to Slidev
---

# Website from zero to production

Presentation slides by Mahima Ramgolam

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<style>
  .slidev-layout.cover h1 {
    font-size: 45px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 900;
    /* padding-bottom: 25px; */
  }
</style>

<!--
[1mins]
Hi everyone,
Welcome to my session.
I am Mahima Ramgolam. A frontend developer.
First of all, I thank you for atttending my prsentation today,
lets dive directly into the subject,
my topic for today is Website from zero to production
-->

---

# About this session

<div class="text-green-200">We will be creating a single-page website/portfolio using VueJS/TailwindCSS without any backend
</div>

- Mainly for students or developers
- deploy a simple website/portfolio online for <b class="text-green-300">free</b>.

<u>Slides as follows:</u>

- How do we deploy a project for free online?
- Create a new repository to Github for a project.
- Use ready-made interactive UI components to build faster
- Deploy the project repository to Vercel or Netlify.

<style>

  h1 {
    font-size: 40px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

<!--
[3mins]
We will be creating a single-page website/portfolio using VueJS/TailwindCSS and
deploy it online through Vercel/Netlify


- students - looking for a job - built portfolio
- developers -developing projects -deploy website online to showcase recruiters
-->

---

# How to deploy a website online for free?

<div class="flex justify-between">

  <div class="flex flex-col gap-4">
  Using Vercel

  <a href="https://vercel.com/" target="_blank" class="border-none" >
  <img
  src="/vercel.png"
  class="w[400px]"
  />
  </a>

  <div class="text-sm">
  Vercel's <u>frontend cloud</u> gives developers frameworks,<br/> workflows, and infrastructure to build a faster,<br/> more personalized web.
  </div>
  </div>

  <div class="flex flex-col gap-4">
  Using Netlify
  <a href="https://www.netlify.com/" target="_blank" class="border-none" >
  <img
  src="/netlify.png"
  class="w[400px] h-[225px]"
  />
  </a>

  <div>
  Use any <u>frontend framework</u> to build, <br/> preview, and deploy to our global network <br/> from Git.
  </div>  
  </div>

</div>

<style>

  h1 {
    font-size: 40px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

---

# Step : Create a new project repository to Github

<div class="text-center"> Two ways to create/add project to github:
</div>
<br/>
<div grid="~ cols-2 gap-4">
<div >

<h3 class="text-center pb-4">1. Your local machine </h3>

<div class="flex items-center">
<img
  src="/terminal.png"
  class="w-56"
/>
<p class="text-sm">create project</p>
</div>

<div>
<div  class="flex items-center pt-4">
<img
  src="/github-screenshot.png"
  class="w-64 -mt-4"
/>

<div class="text-sm pl-2">create a repository in <br/>github & add project to repo</div>
</div>
</div>
<div class="pl-24 text-sm"> (manually) </div>
</div>

<div class="flex flex-col items-center">

<h3 class="text-center pb-4">2. Stackblitz</h3>
<div class="text-center">
<img
  src="/stackblitz.png"
  class="w-[400px]"
/>

<div class="text-sm">(in few clicks)</div>

</div>
</div>
</div>

<style>

  h1 {
    font-size: 40px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

<!--
[5mins]
1. Using stackblitz
- provides a full development environment in the browser, it currently supports javascript/adjacent framework such vue/react/angular/nuxt/nextjs.
- developers can create new project in seconds, connect these projects to their github code repositories to work on
- it takes care of installing dependencies, compiling, bumdling and hot reloading
- stakblitz is powered by webContainers

StackBlitz instructions
- Register for a free account on GitHub.
- StackBlitz uses your GitHub account as a social login.
- Register for a free StackBlitz account by using your GitHub account.
- On StackBlitz's site, click START A NEW APP then select Vue to start a new Vue workspace.
-->

---

# Step : Add ready-made interactive UI components

<div>Some examples of Tailwind UI components websites:
</div>

<div class="flex gap-4 items-center pb-12">
<a href="https://tailwindui.com/" target="_blank" class="border-none" >
<img
  src="/tailwindUI.png"
  class="w-32 h-8"
/>
</a>

<a href="https://flowbite.com/" target="_blank" class="border-none" >
<img
  src="/flowbites.png"
  class="w-32"
/>
</a>

<a href="https://daisyui.com/" target="_blank" class="border-none" >
<img
src="/daisyui.png"
class="w-32"
/>
</a>
</div>

# Demo:

<div class="-mt-4" v-click>to add: </div>

<ul v-after>
<li>Header</li>
<li>Hero section</li>
<li>simple blog page</li>
</ul>

<!--
[10mins]
flowbites header
flowbites > docs - navbar

gallerry
tailwindUI > applicationui > gridList
-->

<style>

  h1 {
    font-size: 35px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

---

# Step : Deploy online

<div class="flex justify-between">

  <div class="flex flex-col gap-4">
  Using Vercel

  <a href="https://daisyui.com/" target="_blank" class="border-none" >
  <img
  src="/vercel.png"
  class="w[400px]"
  />
  </a>

  <div class="text-sm">
  Vercel's frontend cloud gives developers frameworks,<br/> workflows, and infrastructure to build a faster,<br/> more personalized web.
  </div>
  </div>

  <div class="flex flex-col gap-4">
  Using Netlify
  <a href="https://daisyui.com/" target="_blank" class="border-none" >
  <img
  src="/netlify.png"
  class="w[400px] h-[225px]"
  />
  </a>

  <div>
  Use any frontend framework to build, <br/> preview, and deploy to our global network <br/> from Git.
  </div>  
  </div>

</div>

<style>

  h1 {
    font-size: 40px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

<!--
[2mins]
-->

---

# Thank you

<style>

  h1 {
    font-size: 40px;
    color: #34D399;
    line-height: 4rem;
    font-weight: 700;
  }
</style>

<!--
[10mins]
-->
