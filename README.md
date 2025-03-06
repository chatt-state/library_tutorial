# College Success Tutorial

This repository contains the College Success Tutorial website for Chattanooga State Community College, hosted at [success.chattanoogastate.edu](https://success.chattanoogastate.edu).

## Overview

The College Success Tutorial is an interactive web-based tutorial designed to help students learn and develop skills for success in college. The tutorial is built as a static website and hosted on GitHub Pages.

## Site Structure

- `index.html` - The main entry point for the tutorial
- `goodbye.html` - Farewell page shown after completion
- `assets/` - Contains all images and resources used in the tutorial
- `lib/` - Contains JavaScript libraries and CSS for functionality and styling
- `CNAME` - Configures the custom domain for GitHub Pages

## Development

This site is built as a static HTML website using pre-compiled libraries that handle the interactive tutorial experience. The site doesn't require a build process or server-side code to function.

## Hosting

The site is hosted on GitHub Pages with a custom domain configuration:
- GitHub Pages URL: [chatt-state.github.io](https://chatt-state.github.io)
- Custom domain: [success.chattanoogastate.edu](https://success.chattanoogastate.edu)

The custom domain is configured through both:
1. The CNAME file in this repository
2. DNS settings at Cloudflare (CNAME record pointing to chatt-state.github.io)

## Updating the Site

In most cases, the site should not require updates. However, if updates are needed, see the internal documentation for detailed instructions on the update process. 