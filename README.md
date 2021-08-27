# BBC Homepage Recreation - A Frontend Project

This repo contains the development files for my recreation of the **BBC Homepage** using just **HTML, CSS with Sass and a bit of javascript**.

> Visit the live project **[here]**.

<br>

> ### Important
>
> **I AM NOT in any way affiliated with the BBC or their development team.** This is a personal project to showcase my development skills, no more no less.

<br>

## Why did I choose to do this project?

I wanted to showcase my ability to code a **frontend without the use of frameworks**. I chose the BBC homepage because of its unique navigation
bar and interesting card layout for it's featured news articles. Because the BBC homepage has some identical and repeating features, (such as the card layouts) I included only one or two examples of each card section.

<br>

## Instructions

```
npm install

npm start

npm run build
```

- `npm install` will install dependencies and create `node_modules` folder.
- `npm start` will run the parcel development server on `localhost:1234`
- `npm run build` will run the parcel build command, creating the `dist` folder and minifying the html and css.

<br>

## `src/` folder

- `index.html` Main and only output file.
- `scss/`
  - `abstracts/` Contains **Sass Maps** for the root colors and typography.
  - `base/` Contains the root styles, mostly derived from abstracts into utility classes and CSS Custom Properties.
  - `components/` Styles scoped to individual components like the navbar, grid layout for the cards etc.
  - `_index.scss` Directory file. All scss files are forwarded from here.
  - `main.scss` Main output file from which the **Sass** is compiled into **minified CSS**.

<br>

## Finished product

- Fully responsive and fluid layout.
- Inline SVG's for all icons for quality on all screen sizes.
- Optimised images for browsers by using 'srcset' and 'sizes' attributes on `<img>` tags.

[here]: https://vigilant-babbage-cfa8b1.netlify.app/
