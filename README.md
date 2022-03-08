This is a Fork of [adityatelange/hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod)

It has mostly been for my own experimentation, so many things are in a WIP state. I welcome feedback. You can demo it [here](https://umamimike.github.io/hugo-PaperMod/).

As I was working on this, I diverged enough with some work that I felt uncomfortable trying to PR upstream until I had codified the changes. 

## New features

Your best bet is to go to[ Shortcode Examples | PaperMod-Fork](https://umamimike.github.io/hugo-PaperMod/posts/shortcode-examples/#fn:1)

### New Shortcodes

- to embed [asciinema](https://asciinema.org/)
- to include mermaid charts
- for embedding an svg
- for a blog image (WIP)
  - [ ] base url for images should be in config.yml as a Param, currently is hard coded for expediency.

## Undocumented Features

- minor color alterations
- media print produces a cleaner document 
- foldable TOC
- sub sections
- - changed search, currently BROKEN on gh-pages,
  - [ ] fix search
  - [ ] document
- `include` shortcode (for embedding other local markdown in to the current document)
  - [ ] make less brittle with file not found (use a with)
- concat
  - creates an overview of the current section with ALL content in a single document.
  - [ ] update styling with regard to flexbox problems
  - [ ] document

## Original Readme

<h1 align=center>Hugo PaperMod | <a href="https://adityatelange.github.io/hugo-PaperMod/" rel="nofollow">Demo</a></h1>

<h4 align=center>☄️ Fast | ☁️ Fluent | 🌙 Smooth | 📱 Responsive</h4>
<br>

> Hugo PaperMod is a theme based on [hugo-paper](https://github.com/nanxiaobei/hugo-paper).
> The goal of this project is to add more features and customization to the og theme.

The [demo](https://adityatelange.github.io/hugo-PaperMod/) includes a lot of documentation about Installation, Features with a few more stuff. Make sure you visit it, to get an awesome hands-on experience and get to know about the features ...

**ExampleSite** can be found here: [exampleSite](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite). Demo is built up with [exampleSite](https://github.com/adityatelange/hugo-PaperMod/tree/exampleSite) as source.

[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=0.83.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.83.0)
[![Build GH-Pages](https://github.com/adityatelange/hugo-PaperMod/workflows/Build%20GH-Pages/badge.svg)](https://github.com/adityatelange/hugo-PaperMod/deployments/activity_log?environment=github-pages)
[![GitHub](https://img.shields.io/github/license/adityatelange/hugo-PaperMod)](https://github.com/adityatelange/hugo-PaperMod/blob/master/LICENSE)
[![hugo-papermod](https://img.shields.io/badge/Hugo--Themes-@PaperMod-blue)](https://themes.gohugo.io/themes/hugo-papermod/)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=adityatelange_hugo-PaperMod&metric=alert_status)](https://sonarcloud.io/dashboard?id=adityatelange_hugo-PaperMod)
![code-size](https://img.shields.io/github/languages/code-size/adityatelange/hugo-PaperMod)

---

<p align="center">
  <kbd><img src="https://user-images.githubusercontent.com/21258296/114303440-bfc0ae80-9aeb-11eb-8cfa-48a4bb385a6d.png" alt="Mockup image" title="Mockup"/></kbd>
</p>

---

## Features/Mods 💥

- Uses Hugo's asset generator with pipelining, fingerprinting, bundling and minification by default.
- 3 Modes:
  - [Regular Mode.](https://github.com/adityatelange/hugo-PaperMod/wiki/Features#regular-mode-default-mode)
  - [Home-Info Mode.](https://github.com/adityatelange/hugo-PaperMod/wiki/Features#home-info-mode)
  - [Profile Mode.](https://github.com/adityatelange/hugo-PaperMod/wiki/Features#profile-mode)
- Table of Content Generation (newer implementation).
- Archive of posts.
- Social Icons (home-info and profile-mode)
- Social-Media Share buttons on posts.
- Menu location indicator.
- Multilingual support. (with language selector)
- Taxonomies
- Cover image for each post (with Responsive image support).
- Light/Dark theme (automatic theme switch a/c to browser theme and theme-switch button).
- SEO Friendly.
- Multiple Author support.
- Search Page with Fuse.js
- Other Posts suggestion below a post
- Breadcrumb Navigation
- Code Block Copy buttons
- No webpack, nodejs and other dependencies are required to edit the theme.

Read Wiki For More Details => **[PaperMod - Features](https://github.com/adityatelange/hugo-PaperMod/wiki/Features)**

---

## Install/Update 📥

Read Wiki For More Details => **[PaperMod - Installation](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation)**

---

## Social-Icons/Share-Icons 🖼️

Read Wiki For More Details => **[PaperMod-Icons](https://github.com/adityatelange/hugo-PaperMod/wiki/Icons)**

---

## FAQs / How To's Guide 🙋

Read Wiki For More Details => **[PaperMod-FAQs](https://github.com/adityatelange/hugo-PaperMod/wiki/FAQs)**

---

## Release Changelog

Release ChangeLog has info about stuff added: **[Releases](https://github.com/adityatelange/hugo-PaperMod/releases)**

---

## [Pagespeed Insights (100% ?)](https://pagespeed.web.dev/report?url=https://adityatelange.github.io/hugo-PaperMod/)

---

## Special Thanks 🌟

- [**Highlight.js**](https://github.com/highlightjs/highlight.js)
- [**Fuse.js**](https://github.com/krisk/fuse)
- [**Feather Icons**](https://github.com/feathericons/feather)
- [**Simple Icons**](https://github.com/simple-icons/simple-icons)
- **All Contributors and Supporters**
