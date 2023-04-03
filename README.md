# motion-lab-documentation

[https://au-imclab-git.github.io/](https://au-imclab-git.github.io/)

## How to use this repository

This repository contains the documentation for the motion lab. It uses github pages with Jekyll to generate the website. The website is hosted at [https://au-imclab-git.github.io/](https://au-imclab-git.github.io/).

For an overview of how this works with github, see [https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll).

### How to edit the documentation

The documentation is written in markdown. The markdown files are located in the `docs` folder. The `index.markdown` file is the main page of the website. If you would like to add a new page, just create a new markdown file in the `docs` folder and add a link to it in the `index.markdown` file. Any updates you make to the `docs` folder will automatically get built and deployed to the website.

When you add a new page, for example, `new-documentation-section.markdown`, you will need to add the following to the top of the file:

```
---
layout: page
title: New Documentation Section
permalink: /new-documentation-section
---
```

## Notes

- This repository and the resulting documentation website are public. The intended purpose for this documentation is to provide help with setting up motion capture, using QTM, calibration, using presets, etc. It is not intended to be a place to store private information about the lab.