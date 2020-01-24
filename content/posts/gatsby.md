---
date: 2020-01-22T14:00:50.000+00:00
hero_image: "/content/images/stainless-steel-close-wrench-on-spanner-210881 (1).jpg"
title: 'Gatsby: The tool of the trade'
author: Talacha Web Team

---
Read time: **2 min 36 sec**

Stop managing content. Start telling your story. 

## Gatsby brings your content to the edge for lightning-fast, safe website delivery with no CMS overhead

Gatsby is a free and open-source framework based on React that helps developers build blazing-fast websites and apps.

![Gatsby Logo](https://app.forestry.io/sites/uvo8hwgcfd5hjw/body-media//content/images/Gatsby_Logo.png "Gatsby")

Gatsby.js is a PWA (Progressive Web App) generator. You get code and data splitting out-of-the-box. Gatsby loads only the critical HTML, CSS, data, and JavaScript so your site loads as fast as possible. Once loaded, Gatsby prefetches resources for other pages so clicking around the site feels incredibly fast.

Gatsby.js builds your site as “static” files which can be deployed easily on dozens of services.

## Components

Components are a key feature of React, and now they’re a commonly followed web design pattern. With the current level of complexity of user interfaces, it is almost impossible to write maintainable code in long pages of HTML or use templating engines and expect consistency.

So instead, we build reusable components and then use them to construct views. This way we have separate modules handling separate things, and it’s easier to manage and maintain. The component just contains all the information it requires, and Gatsby, since it uses React, follows the same pattern.

Atomic design is an approach that’s a good way of handling complex interfaces, and we could put it to use here with React components. Brad Frost has an amazing blog post describing what it is and how it works.

## Webpack bundling

Webpack creates optimized, minified bundles of HTML, JavaScript, and CSS. When it’s pre-configured with Babel and more plugins, it allows you to use the latest ES6+ JavaScript and GraphQL.

The icing on the cake: we’ve got hot reloading and code splitting built-in, giving a better development experience and better site performance. This is aimed at making the developer write minimal tooling configuration and focus more on the actual site development.

## Styling

Again, complex user interfaces mean complex styling patterns, and it’s only a matter of time before style-sheets get bloated. You get specificity issues, scroll through hundreds of lines of code trying to figure out things, and end up using !important to see the styling you added.

Gatsby has support for SCSS, CSS-in-JavaScript libraries, allowing you to manage styles better and with ease. Even the setup for this is fairly easy to handle with the installation of a plugin or package.

## Responsive Images

Resizing images for responsiveness on different devices, lazy-loading, using srcsets and picture… Already sounds tedious when it is to be done manually.

Although it is a requirement for performance and app-like optimized interfaces these days, we don’t see many tools that we can directly jump into and use.

Meanwhile, in Gatsby with just a plugin, particularly the gatsby-plugin-sharp, you can directly generate fluid images, add filters, change formats, blur up on load and a lot more. This saves a lot of work and time manually resizing images and writing explicit boilerplate code for responsive images. It also gives you way better performance along with smoother user experience.

## App-like experience

With the performance boost and features to add to the smoothness of the user experience, Gatsby aims at a full app-like experience borrowing from full PWAs. There are no reloads between pages when using gatsby-link instead of hyperlinks, and the app still appears smooth and performant thanks to lazy-loading images and code-splitting.

For sites following standards that you also want to be performant, we’ve got tons of things to do and guides to follow: minification and bundling, browser caching and async loading scripts or files, and so on. When working with a framework like React, you have more things to worry about even though it solves a couple of problems: code-splitting, SEO, routing if required, responsive images, and the list goes on.

Gatsby aims to solve all these problems, with less time spent on tooling, configuration, and the environment and more time to design and develop the site.