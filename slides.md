---
layout: 
highlighter: shiki
css: unocss
colorSchema: dark
transition: fade-out
---

<div absolute top-10>
<img src="https://v2.nuxt.com/img/home/hero/gem-1.svg" h-20 w-20 />
</div>

<div w-full top-10 right-1 animate-pulse grid place-items-center absolute>
<img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 />
</div>

<div absolute top-10 right-10>
<img src="https://v2.nuxt.com/img/home/hero/gem-1.svg" h-20 w-20 />
</div>

<div absolute bottom-20 right-10>
<img src="https://v2.nuxt.com/img/home/hero/gem-1.svg" h-20 w-20 />
</div>

<div absolute bottom-20 left-10>
<img src="https://v2.nuxt.com/img/home/hero/gem-1.svg" h-20 w-20 />
</div>

<h1 flex="~ col" py-2>
<div text-center>Harnessing the power of the Nuxt Content Module</div>
</h1>

<div text-xl text-center>
With Selemon Brahanu
</div>

<div abs-br mx-10 my-12 flex="~ col" text-sm text-right>
  <div>VueJS Kenya</div>
<div text-sm opacity-50>October 19th 2023</div>
</div>

---
layout: intro
growX: 10
growY: 90
style: 'padding-left: 8rem;'
---

# Selemon Brahanu


<div class="leading-10 opacity-80">
<twemoji:man-construction-worker-medium-skin-tone mr-1 /> Front-End Engineer <br>
<twemoji:studio-microphone mr-1 />Speaker at VueJs Kenya.<br>
<twemoji:hammer-and-wrench mr-1 />Creator of <span cursor-pointer transition-all duration-200 hover:text-green-500><a href="https://ui-windi.netlify.app/" target="_blank" >Windi UI</a></span> , <span cursor-pointer transition-all hover:text-green-500 duration-200><a href="https://github.com/selemondev/nuxt-ui-vue" target="_blank" >Nuxt UI Vue</a></span> and <span cursor-pointer duration-200 opacity-50><a href='' >MarkQuest</a></span> <br/>
<twemoji:globe-showing-europe-africa mr-1 />Open source contributor.<br>
</div>

<div my-10 w-min flex="~ gap-1" items-center justify-center>
  <mdi:github op50 ma text-xl mr-1/>
 <div><a href="https://github.com/selemondev" target="_blank" font-300>@selemondev</a></div>
  <mdi:twitter op50 ma text-xl ml-4 mr-1/>
  <div><a href="https://twitter.com/selemondev" target="_blank" font-300>@selemondev</a></div>
</div>

<img src="https://github.com/selemondev.png" rounded-full w-35 abs-tr mt-32 mr-40/>

<div flex="~ gap2">

</div>


---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Nuxt Content Module</div>

<div grid place-items-center v-click>
  <NuxtContentGem animate-pulse h-30 w-20 my-6/>
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Nuxt Content</a>
</div>

<div w-full grid grid-cols-2>

<div pt-3>
<span v-click>- What is the Nuxt Content Module ✨?</span>
<div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>The Nuxt Content Module is an official module created by the Nuxt team that provides a powerful data layer for your Nuxt 3 application.</span>
</p>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>It enables you to write your content in the `content` directory and fetch them using an API with a MongoDB like syntax with the help of the <span hover:text-green-500 transition-all duration-200 ease-in><a href="https://content.nuxt.com/composables/query-content" target="_blank">queryContent()</a></span> composable.</span>
</p>

<p flex items-start space-x-1>
<NuxtContentGemList v-click/>
<span>
 <span text-sm v-click>It supports various formats that you can write your content in such as: </span>
 <ul>
 <li v-click text-sm>Markdown</li>
  <li v-click text-sm>JSON</li>
  <li v-click text-sm>YAML</li>
  <li v-click text-sm>CSV</li>
    <li v-click text-sm>etc</li>
 </ul>
 </span>
</p>

</div>
</div>

<!-- <div grid place-items-center w-full h-full>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-40 w-20 animate-pulse />
</div> -->

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-20 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-30 left-85 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-85 w-20/>
   <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-35 top-15 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-45 top-30 rotate-45 />
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-55 top-45 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-81 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>


---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Installation</div>

<div grid place-items-center v-click>
  <NuxtContentGem animate-pulse h-30 w-20 my-6/>
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Installation</a>
</div>


<div w-full grid grid-cols-2>

<div pt-3>
<span v-click>- There are 4 ways of installing the Nuxt Content Module ✨</span>
<div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>Using the CLI</span>
</p>

<div v-click>
```bash
pnpm add @nuxt/content
```
</div>


<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>Using the nuxi CLI</span>
</p>

<div v-click>
```bash
npx nuxi-edge@latest module add @nuxt/content
```
</div>


<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>Using the Nuxt Devtools</span>
</p>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span text-sm>Using the Nuxtr VSCode extension</span>
</p>
</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-50 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-80 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-80 />


  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-60 left-20 />
</div>
</div>

</div>





---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Configuration</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Configuration</a>
</div>


<div w-full grid grid-cols-2>

<div>
<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>Add the module</span>
</p>
<div>

<div v-click>

```ts
// nuxt.config.ts file

export default defineNuxtConfig({
  modules: ["@nuxt/content"]
})
```

</div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>Configuration</span>
</p>

<div v-click>
<span text-sm>The Nuxt Content module can be configured anyway you like as long as you know what you want.</span>
</div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>What can be configured?</span>
</p>

<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>The Content APIs</span>
</p>
</div>

<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>Markdown configs e.g Anchor Links, plugins etc</span>
</p>
</div>


<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>Themes</span>
</p>
</div>

<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>Sources</span>
</p>
</div>
</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-80 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />


  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-50 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-60 left-20 />
</div>
</div>


</div>




---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Content</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Content</a>
</div>


<div w-full grid grid-cols-2>

<div>
<p flex items-start space-x-1 v-click>
 <span>- What is the content directory?</span>
</p>
<div>

<div v-click>
<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>This is where we write our content using a file which has a `.md` extension</span>
</p>

</div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>The content module has a feature that NuxtJs and NextJs share.</span>
</p>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>That feature is known as file-based routing but in our case we will call it content-based routing because we are using the content directory.</span>
</p>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>Where each file is a path generated by the content module according to the directory structure</span>
</p>

<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>`content/index.md` is the same as `pages/index.vue` in the sense that they both resolve to '/'</span>
</p>
</div>

<div v-click pl-4>
<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span text-sm>`content/blog/index.md` and `pages/blog/index.vue` both resolve to '/blog'</span>
</p>
</div>



</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-50 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute w-20 left-50 top-35 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>





---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Content</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Content</a>
</div>


<div w-full grid grid-cols-2>

<div>
<p flex items-start space-x-1 v-click>
 <span>- How do we write our content in a .md file?</span>
</p>
<div>

<div v-click>
<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>Let's start from the top</span>
</p>
</div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>1. Front-matter</span>
</p>

<p flex items-start space-x-1 ml-4 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span>The Front-matter uses the YAML syntax with key-value pairs to provide meta-data to pages.</span>
</p>


<div v-click>

```md
---
title: 'Nuxt Content Module Talk'
description: 'Selemondev is giving a talk about the Nuxt Content Module'
head:
  meta:
    - name: 'keywords'
      content: 'nuxt-content, vuejs-kenya, nuxt3'
    - name: 'author'
      content: 'Selemondev'
---
```
</div>

<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>Under the hood the 
 <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/composables/use-content-head" >useContentHead() </a> </span>composable is utilized to set the page's meta-data
 </span>
</p>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-30 left-20 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-20 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-40 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-60 w-20/>

 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-80 w-20/>

 
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>



---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Content</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Content</a>
</div>


<div w-full grid grid-cols-2>

<div>
<p flex items-start space-x-1 v-click>
 <span>That becomes this: </span>
</p>
<div>

<div v-click>

```html
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Selemondev is giving a talk about the Nuxt Content Module">
    <meta name="keywords" content="nuxt-content, vuejs-kenya, nuxt3">
    <meta name="author" content="Selemondev">
    
    <title>Nuxt Content Module Talk</title>
</head>

```
</div>


<p flex items-start space-x-1 v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-5 w-5 rotate-45 />
 <span>If you want to use images in your markdown, you can place the images in the `public` directory and use it as such:</span>
</p>

<div v-click>

```md
![VueJs-Kenya](/vuejs-kenya.png)
```
</div>

<div v-click>

or you can check out the <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://github.com/davestewart/nuxt-content-assets" target="_blank">Nuxt Content Assets</a></span>  module built by <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://github.com/davestewart" target="_blank">Dave Stewart</a></span> for relative media path references.
</div>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-30 left-20 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-20 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-40 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-60 w-20/>

 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-80 w-20/>


   <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-80 />

 
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>














---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Fetch</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Fetch</a>
</div>


<div w-full grid grid-cols-2>

<div>
<p flex items-start space-x-1 v-click>
 <span>- How do we fetch our contents?</span>
</p>
<div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>By using the <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://nuxt.com/docs/api/composables/use-async-data" target="_blank">useAsyncData()</a></span> composable provided by Nuxt together with the <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/composables/query-content" target="_blank">queryContent()</a></span> composable provided by the Nuxt Content module</span>
</p>

<div v-click>

```ts
const { data } = useAsyncData(() => queryContent('/'))
```

</div>


<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>The <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/composables/query-content" target="_blank">queryContent()</a> </span> composable provides us with methods for querying and fetching our contents. </span>
</p>

<p flex items-start space-x-1 ml-3>
<NuxtContentGemList v-click/>
<span>
 <span v-click>These methods include: </span>
 <ul>
 <li v-click text-sm>find() - Returns all the content</li>
  <li v-click text-sm>only() - Returns only the selected subset of fields</li>
  <li v-click text-sm>findOne()</li>
  <li v-click text-sm>without() - Returns the result with a subset of fields removed</li>
 </ul>
 </span>
</p> 

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-20 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-30 left-85 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-85 w-20/>
   <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-35 top-15 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-45 top-30 rotate-45 />
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-55 top-45 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-81 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>










---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Fetch</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Fetch</a>
</div>


<div w-full grid grid-cols-2>

<div>
<div>

<p flex items-start space-x-1 ml-3>
<span>
 <ul>
 <li v-click text-sm>limit() - Returns all only the number of result(s) specified</li>
  <li v-click text-sm>count() - Returns the numbers of articles of a given path</li>
  <li v-click text-sm>skip() - Skip the specified number of results</li>
    <li v-click text-sm>where() - Filter the results by query</li>
  <li v-click>etc</li>
 </ul>
 </span>
</p>

<div v-click>

```ts
const { data } = useAsyncData(() => 
queryContent('/')
.only(['author', "_path", "title", "description", "date"])
.sort({
  date: -1
})
.limit(1)
.find()
)
```
</div>


<div v-click>

```ts
const { data } = useAsyncData(() => 
queryContent('/blog')
.only(['author', "_path", "title", "description", "date"])
.count()
)
```
</div>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-50 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute w-20 left-50 top-35 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>










---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Fetch</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Fetch</a>
</div>


<div w-full grid grid-cols-2>

<div>

<p flex items-start space-x-1 v-click>
 <span>- How do we fetch our contents?</span>
</p>

<div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>By using the <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-query" target="_blank">ContentQuery</a></span> renderless component by the Nuxt Content module.</span>
</p>

<div v-click>

```vue
<template>
  <div>
    <ContentQuery query="/blog" :only="['_path', 'title', 'description', 'date']" v-slot="{ data }">
      <pre>{{  data  }}</pre>
    </ContentQuery>
  </div>
</template>
```
</div>


<p flex items-start space-x-1 v-click>
<NuxtContentGemList/>
 <span>The <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-query" target="_blank">ContentQuery</a></span> renderless component shortens the access to the queryContent() composable.</span>
</p>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-20 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute w-20 left-20 top-35 />


  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-45 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-65 w-20/>

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-85 w-20/>



 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute w-20 left-45 top-35 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>









---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Rendering</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Rendering</a>
</div>


<div w-full grid grid-cols-2>

<div>

<p flex items-start space-x-1 v-click>
 <span>- How do we render our content?</span>
</p>

<div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>By using the <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-doc" target="_blank">ContentDoc</a></span> component provided by the Nuxt Content module.</span>
</p>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>The <span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-doc" target="_blank">ContentDoc</a></span> component fetches and display the markdown component based on the current path.</span>
</p>

<div v-click>

```vue
<template>
  <div class="m-auto">
    <ContentDoc class="dark:text-white " />
  </div>
</template>
```
</div>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-20 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-30 left-85 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-85 w-20/>
   <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-35 top-15 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-45 top-30 rotate-45 />
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 absolute w-30 left-55 top-45 rotate-45 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-81 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-30 left-20 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>









---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Components</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Components</a>
</div>


<div w-full grid grid-cols-2>

<div>

<p flex items-start space-x-1 v-click>
 <span>- What are the components provided by the Nuxt Content module?</span>
</p>

<div>



<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span><span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-list" target="_blank">ContentList</a></span></span>
</p>





<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>This component fetches a list of documents and allows you to render them by using slots: </span>
</p>

<div v-click>

```vue
<template>
  <div>
    <ContentList path="/blog" :only="['_path']"  v-slot="{ list }">
      <pre>{{  list  }}</pre>
    </ContentList>
  </div>
</template>
```
</div>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-70 left-50 w-20/>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute w-20 left-50 top-35 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>


---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Components</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Components</a>
</div>


<div w-full grid grid-cols-2>

<div>
<div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span><span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-navigation" target="_blank">ContentNavigation</a></span></span>
</p>





<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>This component is a renderless component that shortens the access to the navigation. </span>
</p>

<div v-click>

```vue
<template>
  <div>
    <ContentNavigation path="/blog"  v-slot="{ navigation }">
      <pre>{{  navigation  }}</pre>
    </ContentNavigation>
  </div>
</template>
```
</div>


<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span><span hover:text-green-500 transition-all duration-200 ease-in> <a href="https://content.nuxt.com/components/content-slot" target="_blank">ContentSlot</a></span></span>
</p>


<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>This component makes it easier to use Markdown syntax in your Vue components. </span>
</p>


</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-55 w-20/>
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-35 left-75 w-20/>
 <!-- <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 absolute top-60 left-65 w-20/> -->
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-81 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-35 left-30 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-30 w-20 absolute top-0 left-20 />
</div>
</div>

</div>








---
layout: 'center'
class: 'text-center'
growX: 50
growY: 10
---

<div v-click transition-all duration-500 :class="$slidev.nav.clicks === 0 ? 'op0' : $slidev.nav.clicks > 1 ? 'op50 text-2xl' : 'translate-y-10 text-4xl'">Q/A</div>

<div grid place-items-center v-click>
 <img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-30 w-30 my-6 rotate-45 />
</div>

---

<div flex items-center space-x-2>
<img src="https://v2.nuxt.com/img/home/hero/gem-5.svg" h-10 w-10 />
<a href="https://content.nuxt.com" target="_blank" text-2xl v-click>Q/A</a>
</div>


<div w-full grid grid-cols-2>

<div>
<div>

<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>Questions?</span>
</p>


<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>Challenge</span>
</p>



<p flex items-start space-x-1 ml-3 v-click>
<NuxtContentGemList/>
 <span>Homework </span>
</p>

</div>
</div>

<div relative grid place-items-center w-full h-full>
<div>
 <!-- <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute top-50 left-40 w-10/> -->

  <!-- <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute top-60 left-20 w-10/> -->
 <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-65 rotate-30 top-30 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-17 absolute w-10 left-75 rotate-30 top-17 />


  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-50 rotate-30 top-45 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-35 rotate-30 top-60 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-25  top-75 />

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-40 rotate-85 top-80 />


  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-60 rotate-85 top-80 />

   <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute w-10 left-80 rotate-85 top-80 />




   <!-- <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 absolute top-85 left-20 w-10/> -->

  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 absolute top-0 left-80 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 absolute top-0 left-60 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 absolute top-0 left-40 />
  <img src="https://v2.nuxt.com/img/home/hero/gem-4.svg" h-20 w-10 absolute top-0 left-20 />
</div> 
</div>

</div>





---
layout: intro
class: text-center pb-5
growX: 50
growY: 120
---

# Thank You!





