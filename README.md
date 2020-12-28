# eleventy demo

## Start a local server

```js
npm start
```

## build the site

```js
npm run build
```

-------------------------------------------

https://www.sitepoint.com/getting-started-with-eleventy/

---------------------------------------------

Global variables in the njk template are defined in the "front matter". The `{{ content }}` variable is the stuff generated from the mardown.

> The two `{% include %}` definitions reference files included within the template. Create an HTML header file at `src/_includes/partials/htmlhead.njk`

> Eleventy lets you define defaults for all files in a directory by creating a <directory-name>.json file

-------------------------------

> Eleventy provides a standard navigation plugin,

> front-matter sections must be defined in every page you want in the menu. 

> The home page front matter in src/index.md can be updated accordingly:
```
‐‐‐
title: 11ty starter site
description: This is a demonstration website generated using the 11ty static site generator.
layout: page.njk
eleventyNavigation:
  key: home
  order: 100
‐‐‐
```

A navigation menu can now be added to the page template at `src/_includes/page.njk`:

> The navlist shortcode must be registered using an .addShortcode() function in .eleventy.js








