<div align="center">
  <img
    alt="Nulite logo"
    height="80"
    src="https://em-content.zobj.net/source/apple/354/pill_1f48a.png"
  />

# Nulite

</div>

Nulite is a simple, elegant, minimalistic stater project for [Eleventy](https://www.11ty.dev/) to help you create a simple blog with focus on performance and simplicity.

This project is strongly influenced by [Steph Ango's blog](https://stephango.com/) (one of the creators of Obsidian).

If you like the project feel free to leave a star ⭐ You can also send me issues that you can find or proposals for improvement in PRs.

![Preview of the Nulite blog starter. A simple website whith sample articles](https://imgur.com/lmqf76D.png)

If you know Spanish, take a look at this article to [set up your blog for free with this template](https://codingpotions.com/crear-blog-gratis-markdown/)

## Features

- 🧐 Simple. Elegant, minimalist design, clear and easy to read.
- 📈 Good performance. Inline styles and the minimum amount of JS to make the page load as fast as possible.
- 🌙 Support for light/dark mode. Respects user tastes and allows toggle between both saving preferences.
- 📡 RSS. Bring back old days.
- 🎨 Easily customizable. Thanks to the CSS variables system you can change colors and fonts in one place.
- 🖍️ Syntax coloring. If you write blocks of code in the articles you will have coloring, and without adding extra JS.
- 📝 Article recommendation. Each article has a tag-based recommendation system to give the user more content to read.

## Getting started

1. Fork this repo, or click in the button "Use this template": `https://github.com/codingpotions/nulite`
2. `cd` into the project directory and run `npm install`

## Running and serving a dev build

```sh
npm run start
```

Browse to [http://localhost:8080](http://localhost:8080).

## Running and serving a prod build

```sh
npm run build
```

Output files are generated into the `_site` folder.

## Project structure

```
src/
  _includes/
    All UI partials. Inside the css folder, in the global.liquid you can change the CSS variables
  _data/
    Here you can change the site info, like the title and description
  posts/
    Each individual post in markdown files
  public/
    This folder contians statics files, copied directly into the output, like the favicon, for ecample
Configuration and build files
```
