# BBC Homepage Recreation - A Frontend Project

This repo contains the development files for my recreation of the **BBC Homepage** using just **HTML, CSS with SASS and a bit of javascript**.

Visit the live project **HERE** hosted on **PROVIDER**
<br>
<br>
### Why did I choose to do this project?

I wanted to showcase my ability to code a **frontend without the use of frameworks**. I chose the BBC homepage because of its unique navigation 
bar and interesting card layout for it's featured news articles. Because the BBC homepage has many repeating features (such as the card 
layouts) I included only one or two examples of each card section.
<br>
<br>

### Features - `src` folder

- `index.html` Main and only output file. 
- `assets` Contains svg files and images as a reference to the inline ones used in `index.html`.
- `scss`
  - `abstracts` Contains **SCSS Maps** for the root colors and typography. 
  - `base` Contains the root styles, mostly derived from abstracts into utility classes and CSS Custom Properties.
  - `components` Styles scoped to individual components like the navbar, grid layout for the cards etc.
  - `_index.scss` Directory file. All scss files are forwarded from here.
  - `main.scss` Main output file from which the **SASS** is compiled into **minified CSS**.

### Features - finished product 

- Fully responsive and fluid layout. 
- Inline SVG's for all icons for quality on all screen sizes.
- Optimised images for browsers by using 'srcset' and 'sizes' attributes on `<img>` tags.
- To avoid any [copyright issues with the BBC] I used a different font face than [BBC Reith].
 
### NPM Scripts - `package.json`

- `start` will run the Parcel development server.
- `build` will run the Parcel build command, creating the `dist` folder and minifying the html and css.

[copyright issues with the BBC]: https://www.bbc.co.uk/branding/reith-font
[BBC Reith]: https://www.bbc.co.uk/gel/articles/introducing-bbc-reith








