## Embedded Analog Intelligence
> For credits and tools used to build the site, see Credits

### Demo
* [https://matt-chv.github.io/embedded-analog-intelligence/](https://matt-chv.github.io/embedded-analog-intelligence/)

#### Features

* Sitemap and XML Feed
* Pagination in homepage
* Posts under category
* Realtime Search Posts _(title & description)_ by query.
* Related Posts
* Highlight pre
* Next & Previous Post
* Disqus comment
* Projects page & Detail Project page
* Share on social media
* Whare with Whatsapp including Whatsapp
* Google analytics
* HTML Minify _(Compress HTML)_ using [Jekyll Compress HTML](https://github.com/penibelst/jekyll-compress-html)

#### Screenshot

![Screenshot Post Page]()

### Install & Configuration

1. Fork this repository
2. Edit site settings inside file of `_config.yml`
3. Edit your projects at file of `projects.md`, `_data/projects.json` and inside path of `_project/` _(for detail project)_.
4. Edit about yourself inside file of `about.md`

### How to Use?

**a. Add new Category**

All categories saved inside path of `category/`, you can see the existed categories.

**b. Add new Posts**

* All posts bassed on markdown syntax _(please googling)_. allowed extensions is `*.markdown` or `*.md`.
* This files can found at the path of `_posts/`.
* and the name of files are following `<date:%Y-%m-%d>-<slug>.<extension>`, for example:

```
2013-09-23-welcome-to-jekyll.md

# or

2013-09-23-welcome-to-jekyll.markdown
```

### Boiler Plate code for new posts:
```
---
title: Germany's AI policy
date: 2018-11-16
categories: [business, actuator, foresight, io, ros, technology, theory, training, mechatronics]
lang: en
---

# Post title and content from here
```
