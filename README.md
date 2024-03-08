# Basic template with Eleventy, Liquid & Simple.css framework

## Folder structure
- pages in /src
- layouts in /_layouts
- includes in /_includes
- Json files in /_data
- CSS files in /assets/css
- images in /assets/images

## Page layout
- _layouts/base.liquid
- _layouts/default.liquid -> layout: base -> includes: header + footer
- _includes/header.liquid -> with primary navigation
- _includes/footer.liquid

## Responsive navbar
- add tags: primary in frontmatter

## Package.json scripts
- "start": "npx @11ty/eleventy --serve",
- "build": "eleventy",
- "debug": "DEBUG=* eleventy"

## Dependencies
- "@11ty/eleventy": "^2.0.1"
