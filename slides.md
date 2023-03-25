---
theme: seriph
layout: cover
highlighter: shiki
colorSchema: light
transition: slide-left
title: "Collaborative Development with Git and GitHub: Best Practices, Case Studies & Lesson learned"
css: unocss
---

# Collaborative Development with Git and GitHub: Best Practices, Case Studies & Lesson learned

<div class="uppercase tracking-widest" m="t-10">
Satya Wikananda
</div>

<div class="abs-br mx-14 my-12 flex">
  <div class="ml-3 flex flex-col text-left gap-1">
    <div>GDSC Instiki</div>
    <div class="text-sm opacity-50">25 Maret 2023</div>
  </div>
</div>

---
layout: 'intro'
---

<h1 text="!5xl">Satya Wikananda</h1>

<div class="leading-8 opacity-80">
Mahasiswa & Frontend Engineer di AM Collective
</div>

<div my-10 w-min flex="~ gap-1" items-center justify-center>
  <div i-ri-user-3-line op50 ma text-xl/>
  <div><a href="https://satyawikananda.vercel.app" target="_blank" class="border-none! font-300">satyawikananda.vercel.app</a></div>
  <div i-ri-github-line op50 ma text-xl ml4/>
  <div><a href="https://github.com/satyawikananda" target="_blank" class="border-none! font-300">satyawikananda</a></div>
  <div i-ri-twitter-line op50 ma text-xl ml4/>
  <div><a href="https://twitter.com/satya_wikananda" target="_blank" class="border-none! font-300">satya_wikananda</a></div>
</div>

<img src="https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2.0,f_auto,g_center,h_250,q_auto:good,w_250/v1/gcs/platform-data-dsc/events/satya_gHRf6L7.jpeg" class="rounded-full w-40 abs-tr mt-30 mr-20"/>

---
layout: 'section'
---

# Jadi Git itu apa sih?

---
growX: 0
growY: 90
---

# Git

Pembahasan mengenai Git

Git adalah sebuah sistem pengontrol versi (version control system) yang dirancang untuk memudahkan pengembangan perangkat lunak dan kerja tim dalam mengelola kode sumber. 

<svg xmlns="http://www.w3.org/2000/svg" width="292" height="92pt" viewBox="0 0 219 92"><defs><clipPath id="a"><path d="M159 .79h25V69h-25Zm0 0"/></clipPath><clipPath id="b"><path d="M183 9h35.371v60H183Zm0 0"/></clipPath><clipPath id="c"><path d="M0 .79h92V92H0Zm0 0"/></clipPath></defs><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M130.871 31.836c-4.785 0-8.351 2.352-8.351 8.008 0 4.261 2.347 7.222 8.093 7.222 4.871 0 8.18-2.867 8.18-7.398 0-5.133-2.961-7.832-7.922-7.832Zm-9.57 39.95c-1.133 1.39-2.262 2.87-2.262 4.612 0 3.48 4.434 4.524 10.527 4.524 5.051 0 11.926-.352 11.926-5.043 0-2.793-3.308-2.965-7.488-3.227Zm25.761-39.688c1.563 2.004 3.22 4.789 3.22 8.793 0 9.656-7.571 15.316-18.536 15.316-2.789 0-5.312-.348-6.879-.785l-2.87 4.613 8.526.52c15.059.96 23.934 1.398 23.934 12.968 0 10.008-8.789 15.665-23.934 15.665-15.75 0-21.757-4.004-21.757-10.88 0-3.917 1.742-6 4.789-8.878-2.875-1.211-3.828-3.387-3.828-5.739 0-1.914.953-3.656 2.523-5.312 1.566-1.652 3.305-3.305 5.395-5.219-4.262-2.09-7.485-6.617-7.485-13.058 0-10.008 6.613-16.88 19.93-16.88 3.742 0 6.004.344 8.008.872h16.972v7.394l-8.007.61"/><g clip-path="url(#a)"><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M170.379 16.281c-4.961 0-7.832-2.87-7.832-7.836 0-4.957 2.871-7.656 7.832-7.656 5.05 0 7.922 2.7 7.922 7.656 0 4.965-2.871 7.836-7.922 7.836Zm-11.227 52.305V61.71l4.438-.606c1.219-.175 1.394-.437 1.394-1.746V33.773c0-.953-.261-1.566-1.132-1.824l-4.7-1.656.957-7.047h18.016V59.36c0 1.399.086 1.57 1.395 1.746l4.437.606v6.875h-24.805"/></g><g clip-path="url(#b)"><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M218.371 65.21c-3.742 1.825-9.223 3.481-14.187 3.481-10.356 0-14.27-4.175-14.27-14.015V31.879c0-.524 0-.871-.7-.871h-6.093v-7.746c7.664-.871 10.707-4.703 11.664-14.188h8.27v12.36c0 .609 0 .87.695.87h12.27v8.704h-12.965v20.797c0 5.136 1.218 7.136 5.918 7.136 2.437 0 4.96-.609 7.047-1.39l2.351 7.66"/></g><g clip-path="url(#c)"><path style="stroke:none;fill-rule:nonzero;fill:#f03c2e;fill-opacity:1" d="M89.422 42.371 49.629 2.582a5.868 5.868 0 0 0-8.3 0l-8.263 8.262 10.48 10.484a6.965 6.965 0 0 1 7.173 1.668 6.98 6.98 0 0 1 1.656 7.215l10.102 10.105a6.963 6.963 0 0 1 7.214 1.657 6.976 6.976 0 0 1 0 9.875 6.98 6.98 0 0 1-9.879 0 6.987 6.987 0 0 1-1.519-7.594l-9.422-9.422v24.793a6.979 6.979 0 0 1 1.848 1.32 6.988 6.988 0 0 1 0 9.88c-2.73 2.726-7.153 2.726-9.875 0a6.98 6.98 0 0 1 0-9.88 6.893 6.893 0 0 1 2.285-1.523V34.398a6.893 6.893 0 0 1-2.285-1.523 6.988 6.988 0 0 1-1.508-7.637L29.004 14.902 1.719 42.187a5.868 5.868 0 0 0 0 8.301l39.793 39.793a5.868 5.868 0 0 0 8.3 0l39.61-39.605a5.873 5.873 0 0 0 0-8.305"/></g></svg>

---
layout: 'center'
---

# Jenis Version Control System

<div class="flex flex-row justify-center">
<v-clicks>
  <svg xmlns="http://www.w3.org/2000/svg" class="mr-2" width="98" height="96"><path fill-rule="evenodd" clip-rule="evenodd" d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z" fill="#24292f"/></svg>
  <!-- <img src="/assets/gitlab-logo.jpg"> -->
  <svg xmlns="http://www.w3.org/2000/svg" class="mr-2" width="256" viewBox="0 0 443.43 63.27"><defs><linearGradient id="A" x1="64.01" y1="30.27" x2="32.99" y2="54.48" gradientUnits="userSpaceOnUse"><stop offset=".18" stop-color="#0052cc"/><stop offset="1" stop-color="#2684ff"/></linearGradient></defs><path d="M116.87 4.58c11.8 0 17.5 5.8 17.5 15.14 0 7-3.17 11.26-9.68 12.85 8.54 1.4 12.76 6.07 12.76 14.25 0 9.24-6.25 15.58-19.18 15.58H94.43V4.58zm-14.52 7.57V29.4h13.46c7.48 0 10.56-3.43 10.56-9s-3.34-8.27-10.56-8.27zm0 24.3v18h16.2c7.57 0 11-2.73 11-8.54 0-6.16-3.26-9.5-11.17-9.5zM150.4 1.5a4.94 4.94 0 0 1 5.28 5.28 5.28 5.28 0 0 1-10.56 0 4.94 4.94 0 0 1 5.28-5.28zm-3.87 16.9h7.57v44h-7.57zM183 55a24 24 0 0 0 4.75-.62v7.3a18.19 18.19 0 0 1-5.1.7c-9.42 0-14-5.54-14-13.73V25.43h-7.13v-7h7.13V9.06H176v9.33h11.7v7H176v23.1c0 3.87 2.3 6.5 7 6.5zm35.95 8.27c-6.42 0-11.35-2.9-14-8.62v7.74h-7.57V0H205v26.3c2.82-5.8 8.1-8.8 14.87-8.8 11.7 0 17.6 9.94 17.6 22.88-.04 12.4-6.2 22.88-18.52 22.88zm-1.15-38.72c-6.8 0-12.8 4.3-12.8 14.08v3.52c0 9.77 5.54 14.08 12 14.08 8.54 0 12.94-5.63 12.94-15.84-.08-10.56-4.3-15.84-12.14-15.84zm27.55-6.16h7.57V45c0 7.92 3.17 11.44 10.38 11.44 7 0 11.88-4.66 11.88-13.55V18.4h7.57v44h-7.57v-7.22a15.43 15.43 0 0 1-13.9 8.1c-10.12 0-15.93-7-15.93-19.1zm79.9 42.86c-2.64 1.4-6.7 2-10.74 2-15.66 0-23-9.5-23-23 0-13.3 7.3-22.8 23-22.8A23.26 23.26 0 0 1 325 19.62v7a22.17 22.17 0 0 0-10-2.07c-11.44 0-16.1 7.2-16.1 15.75s4.75 15.75 16.28 15.75a27.78 27.78 0 0 0 10-1.58zm8.63 1.14V0h7.57v39l18.92-20.6h9.86L349.54 40l21.56 22.4h-10.3l-19.36-20.6v20.6zm62.3.88c-16.46 0-23.67-9.5-23.67-23 0-13.3 7.4-22.8 20.77-22.8 13.55 0 19 9.42 19 22.8v3.43h-32.12c1.06 7.48 5.9 12.32 16.28 12.32a39 39 0 0 0 13.38-2.37v7c-3.6 1.92-9.15 2.62-13.64 2.62zm-16.1-26h24.55c-.44-8.18-4.14-12.85-11.7-12.85-8.02-.04-12.06 5.15-12.85 12.8zM438.68 55a24 24 0 0 0 4.75-.62v7.3a18.19 18.19 0 0 1-5.1.7c-9.42 0-14-5.54-14-13.73V25.43h-7.13v-7h7.13V9.06h7.4v9.33h11.7v7h-11.7v23.1c.01 3.87 2.28 6.5 6.96 6.5z" fill="#253858"/><path d="M2 6.26a2 2 0 0 0-2 2.32l8.5 51.54a2.72 2.72 0 0 0 2.66 2.27H51.9a2 2 0 0 0 2-1.68L62.4 8.6a2 2 0 0 0-2-2.32zM37.75 43.5h-13l-3.52-18.4H40.9z" fill="#2684ff"/><path d="M59.67 25.12H40.9l-3.15 18.4h-13L9.4 61.73a2.71 2.71 0 0 0 1.75.66H51.9a2 2 0 0 0 2-1.68z" fill="url(#A)"/></svg>
  <svg xmlns="http://www.w3.org/2000/svg" class="mt-2" width="64" height="64" fill-rule="evenodd"><path d="M32 61.477L43.784 25.2H20.216z" fill="#e24329"/><path d="M32 61.477L20.216 25.2H3.7z" fill="#fc6d26"/><path d="M3.7 25.2L.12 36.23a2.44 2.44 0 0 0 .886 2.728L32 61.477z" fill="#fca326"/><path d="M3.7 25.2h16.515L13.118 3.366c-.365-1.124-1.955-1.124-2.32 0z" fill="#e24329"/><path d="M32 61.477L43.784 25.2H60.3z" fill="#fc6d26"/><path d="M60.3 25.2l3.58 11.02a2.44 2.44 0 0 1-.886 2.728L32 61.477z" fill="#fca326"/><path d="M60.3 25.2H43.784l7.098-21.844c.365-1.124 1.955-1.124 2.32 0z" fill="#e24329"/></svg>
</v-clicks>
</div>

---
growX: 0
growY: 90
---

# GitHub
Kenalan sama GitHub dan manfaatnya dalam berkolaborasi di dunia software engineering

GitHub merupakan sebuah platform pengembangan perangkat lunak yang sering digunakan oleh para developer untuk melakukan kolaborasi dalam mengembangkan sebuah kode yang bersifat open source khususnya perangkat lunak.

Manfaat dari melakukan kolaborasi di GitHub dan pelajaran yang bisa dipetik:

<v-clicks>

- Menambah relasi baru dengan beberapa developer
- Menambah ilmu dan wawasan baru
- Meningkatkan kualitas sebuah kode sumber
- Mempercepat development dari sebuah pengembangan proyek open source
- Menambah pengalaman dan portfolio

</v-clicks>
<svg mt5 xmlns="http://www.w3.org/2000/svg" class="mr-2" width="98" height="96"><path fill-rule="evenodd" clip-rule="evenodd" d="M48.854 0C21.839 0 0 22 0 49.217c0 21.756 13.993 40.172 33.405 46.69 2.427.49 3.316-1.059 3.316-2.362 0-1.141-.08-5.052-.08-9.127-13.59 2.934-16.42-5.867-16.42-5.867-2.184-5.704-5.42-7.17-5.42-7.17-4.448-3.015.324-3.015.324-3.015 4.934.326 7.523 5.052 7.523 5.052 4.367 7.496 11.404 5.378 14.235 4.074.404-3.178 1.699-5.378 3.074-6.6-10.839-1.141-22.243-5.378-22.243-24.283 0-5.378 1.94-9.778 5.014-13.2-.485-1.222-2.184-6.275.486-13.038 0 0 4.125-1.304 13.426 5.052a46.97 46.97 0 0 1 12.214-1.63c4.125 0 8.33.571 12.213 1.63 9.302-6.356 13.427-5.052 13.427-5.052 2.67 6.763.97 11.816.485 13.038 3.155 3.422 5.015 7.822 5.015 13.2 0 18.905-11.404 23.06-22.324 24.283 1.78 1.548 3.316 4.481 3.316 9.126 0 6.6-.08 11.897-.08 13.526 0 1.304.89 2.853 3.316 2.364 19.412-6.52 33.405-24.935 33.405-46.691C97.707 22 75.788 0 48.854 0z" fill="#24292f"/></svg>

---
layout: 'section'
---

# Bagaimana untuk praktiknya?

<img src="https://media.tenor.com/X73EqPfwAfIAAAAC/minion-any-questions-question.gif" mt5 w-50 mx-auto rounded />

---
growX: 0
growY: 90
---

<div flex flex-row>
  <svg xmlns="http://www.w3.org/2000/svg" width="100" height="80" viewBox="0 0 219 92"><defs><clipPath id="a"><path d="M159 .79h25V69h-25Zm0 0"/></clipPath><clipPath id="b"><path d="M183 9h35.371v60H183Zm0 0"/></clipPath><clipPath id="c"><path d="M0 .79h92V92H0Zm0 0"/></clipPath></defs><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M130.871 31.836c-4.785 0-8.351 2.352-8.351 8.008 0 4.261 2.347 7.222 8.093 7.222 4.871 0 8.18-2.867 8.18-7.398 0-5.133-2.961-7.832-7.922-7.832Zm-9.57 39.95c-1.133 1.39-2.262 2.87-2.262 4.612 0 3.48 4.434 4.524 10.527 4.524 5.051 0 11.926-.352 11.926-5.043 0-2.793-3.308-2.965-7.488-3.227Zm25.761-39.688c1.563 2.004 3.22 4.789 3.22 8.793 0 9.656-7.571 15.316-18.536 15.316-2.789 0-5.312-.348-6.879-.785l-2.87 4.613 8.526.52c15.059.96 23.934 1.398 23.934 12.968 0 10.008-8.789 15.665-23.934 15.665-15.75 0-21.757-4.004-21.757-10.88 0-3.917 1.742-6 4.789-8.878-2.875-1.211-3.828-3.387-3.828-5.739 0-1.914.953-3.656 2.523-5.312 1.566-1.652 3.305-3.305 5.395-5.219-4.262-2.09-7.485-6.617-7.485-13.058 0-10.008 6.613-16.88 19.93-16.88 3.742 0 6.004.344 8.008.872h16.972v7.394l-8.007.61"/><g clip-path="url(#a)"><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M170.379 16.281c-4.961 0-7.832-2.87-7.832-7.836 0-4.957 2.871-7.656 7.832-7.656 5.05 0 7.922 2.7 7.922 7.656 0 4.965-2.871 7.836-7.922 7.836Zm-11.227 52.305V61.71l4.438-.606c1.219-.175 1.394-.437 1.394-1.746V33.773c0-.953-.261-1.566-1.132-1.824l-4.7-1.656.957-7.047h18.016V59.36c0 1.399.086 1.57 1.395 1.746l4.437.606v6.875h-24.805"/></g><g clip-path="url(#b)"><path style="stroke:none;fill-rule:nonzero;fill:#362701;fill-opacity:1" d="M218.371 65.21c-3.742 1.825-9.223 3.481-14.187 3.481-10.356 0-14.27-4.175-14.27-14.015V31.879c0-.524 0-.871-.7-.871h-6.093v-7.746c7.664-.871 10.707-4.703 11.664-14.188h8.27v12.36c0 .609 0 .87.695.87h12.27v8.704h-12.965v20.797c0 5.136 1.218 7.136 5.918 7.136 2.437 0 4.96-.609 7.047-1.39l2.351 7.66"/></g><g clip-path="url(#c)"><path style="stroke:none;fill-rule:nonzero;fill:#f03c2e;fill-opacity:1" d="M89.422 42.371 49.629 2.582a5.868 5.868 0 0 0-8.3 0l-8.263 8.262 10.48 10.484a6.965 6.965 0 0 1 7.173 1.668 6.98 6.98 0 0 1 1.656 7.215l10.102 10.105a6.963 6.963 0 0 1 7.214 1.657 6.976 6.976 0 0 1 0 9.875 6.98 6.98 0 0 1-9.879 0 6.987 6.987 0 0 1-1.519-7.594l-9.422-9.422v24.793a6.979 6.979 0 0 1 1.848 1.32 6.988 6.988 0 0 1 0 9.88c-2.73 2.726-7.153 2.726-9.875 0a6.98 6.98 0 0 1 0-9.88 6.893 6.893 0 0 1 2.285-1.523V34.398a6.893 6.893 0 0 1-2.285-1.523 6.988 6.988 0 0 1-1.508-7.637L29.004 14.902 1.719 42.187a5.868 5.868 0 0 0 0 8.301l39.793 39.793a5.868 5.868 0 0 0 8.3 0l39.61-39.605a5.873 5.873 0 0 0 0-8.305"/></g></svg>
</div>
Download Git <a href="https://git-scm.com/downloads" target="_blank">Disini</a>


<v-clicks>

1. Clone repository

```bash
git clone https://github.com/satyawikananda/awesome-music-playlist
```

2. Tambahkan remote ke code source
```bash
git remote add origin https://github.com/satyawikananda/awesome-music-playlist
```

3. Inisialisasikan sebelum commit

```bash
git add .
```

4. Commit kode dengan pesan

```bash
git commit -m "chore: update"
```

5. Push perubahan ke repository

```bash
git push origin main
```
</v-clicks>

---
growX: 0
growY: 90
---

<div flex flex-row justify-center space-x-4>
  <div flex flex-col text-center>
    <p font-bold>GitHub Issue</p>
    <img src="https://i.ibb.co/mJR6jRc/issue.png" alt="github-issue-example" class="rounded mb-2">
    Gambar dari: <a href="https://github.com/kawalcovid19/wargabantuwarga.com/issues" target="_blank">https://github.com/kawalcovid19/wargabantuwarga.com/issues</a>
  </div>
</div>

---
growX: 0
growY: 90
---

<div flex flex-row justify-center space-x-4>
  <div flex flex-col text-center>
    <p font-bold>GitHub Pull Request</p>
    <img src="https://i.ibb.co/Y7p3R8K/pr.png" alt="github-pr-example" class="rounded mb-2">
    Gambar dari: <a href="https://github.com/satyawikananda/awesome-music-playlist/pulls" target="_blank">https://github.com/satyawikananda/awesome-music-playlist/pulls</a>
  </div>
</div>

---
growX: 0
growY: 90
---

# Hal-hal yang perlu diperhatikan
Hal-hal yang perlu diperhatikan saat ingin berkolaborasi

<v-clicks>

- Membuat issue terlebih dahulu

- Perhatikan apakah terdapat label di issue tersebut

- Disarankan menggunakan <a font-bold href="https://www.conventionalcommits.org/en/v1.0.0/" target="_blank">conventional message commit</a>

- **Hormati** sesama pengembang yaa :D
<img src="https://media.tenor.com/cXcatp89g1EAAAAM/anime-boy.gif" mt5 w-50 rounded />

</v-clicks>

---
growX: 0
growY: 90
---

<div grid grid-cols-1 gap-4>
  <img src="https://i.ibb.co/fMdXZRg/pr1.png" rounded />
  <img src="https://pbs.twimg.com/media/EjQQt-tWAAARu_s?format=jpg&name=4096x4096" rounded />
  <!-- <img src="https://i.ibb.co/fMdXZRg/pr1.png" rounded />
  <img src="https://i.ibb.co/fMdXZRg/pr1.png" rounded /> -->
  <!-- <div flex flex-col>
  </div> -->
</div>

---
growX: 0
growY: 90
---

# Referensi
Berikut merupakan referensi yang bisa kamu pelajari lebih dalam mengenai Git maupun GitHub :D

- [Web Programming Unpas - Git & GitHub](https://www.youtube.com/playlist?list=PLFIM0718LjIVknj6sgsSceMqlq242-jNf)
- [Programming Zaman Now - Tutorial Git dasar](https://www.youtube.com/watch?v=fQbTeNX1mvM)
- [Sekolah Koding - Apa itu GitHub](https://www.youtube.com/playlist?list=PLCZlgfAG0GXCtwnagWsUzZum1CFZYqrB5)

---
layout: 'center'
---

# Thank you :D

<div flex flex-row items-center>
  <img src="https://media.tenor.com/5Xgt3Phtx64AAAAC/thank-you-sticker-thanks-sticker.gif" />
</div>