![](https://i.imgur.com/wfrTcgk.png)

# Gatsby Starter Portfolio: Bella

A portfolio starter for [Gatsby](https://www.gatsbyjs.org/). The target audience are designers and photographers.

[Demo Website](https://portfolio-bella.netlify.com/)

- Big Typography & Images
- White Theme
- [Prismic.io](https://prismic.io/) as CMS
- One-Page layout with sub-pages for projects

## Why?

If you want to quickly bootstrap a design/photography portfolio or use it as a foundation for your personal site the *gatsby-starter-portfolio* are a perfect fit for you! The project's goal is to offer minimalistic and fast websites. 

I hope you like my starters and create something awesome! To see some of my work you can visit my [website](https://www.lekoarts.de) or support me on [Patreon](https://www.patreon.com/lekoarts) to get some neat rewards (4K images, project files, tutorial insights).

Also check out the other *gatsby-starter-portfolio*:
- [gatsby-starter-portfolio-emma](https://github.com/LeKoArts/gatsby-starter-portfolio-emma)
- [gatsby-starter-portfolio-emilia](https://github.com/LeKoArts/gatsby-starter-portfolio-emilia)

## Features

- Configurable
    - Use the website.js to easily change the most important information
    - Google Fonts
- [Prismic.io](https://prismic.io/) as CMS
- [Emotion](https://emotion.sh/) + Emotion-Grid for CSS
- SEO
    - Sitemap
    - Schema.org JSONLD
    - OpenGraph Tags
    - Twitter Tags
- Offline Support
- WebApp Manifest Support
- Typography.js
- Responsive images
    - The right image size for every screen size
    - Traced SVG Loading (Lazy-Loading)
    - WebP Support

## Getting Started

Check your development environment! You'll need [Node.js](https://nodejs.org/en/), the [Gatsby CLI](https://www.gatsbyjs.org/docs/) and [node-gyp](https://github.com/nodejs/node-gyp#installation) installed. The official Gatsby website also lists two articles regarding this topic:
- [Gatsby on Windows](https://www.gatsbyjs.org/docs/gatsby-on-windows/)
- [Check your development environment](https://www.gatsbyjs.org/tutorial/part-one/#check-your-development-environment)

To copy and install this starter run this command (with "project-name" being the name of your folder you wish to install it in):

```
gatsby new project-name https://github.com/LeKoArts/gatsby-starter-portfolio-bella
npm run dev
```

### TODO: Prismic

### Adding new features/plugins

You can add other features by having a look at the offical [plugins page](https://www.gatsbyjs.org/docs/plugins/)

### Building your site

```
npm run build
```
Copy the content of the ``public`` folder to your webhost or use a website like Netlify which automates that for you.

## Configuration

You can configure your setup in ``config/website``:

```JS
TODO
```

**Attention:** You also need to edit ``static/robots.txt`` to include your domain!