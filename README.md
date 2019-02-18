# Bones for Ghost CMS
Bones for Ghost is a commercial boilerplate [handlebarsjs](https://handlebarsjs.com/) theme for web developers to create sites and themes for clients and commercial sale.

## Purpose of the Theme
When we started our journey to transition to use Ghost CMS as our primary content management system for client jobs we found it difficult to find Ghost themes that are outside of Magazine and Blogging sites.

This theme is focused on assisting developers to create themes for commercial purpose such as a business or organisation.

## What Bones for Ghost is NOT
It is not a full theme that can be installed on any Ghost CMS, it is designed to be a starting point for other theme development while being modular enough to allow you to update your themes core technology as technology develops and industry requirements change.

While posts are apart of the theme this is not a starting point for Magazine/Blogging style themes.

## The future
It is our hope that through the development of this theme core and an accompanying CLI that we can allow developers to quickly provision a theme core as well as any additional required custom pages and posts.

# Installation
## Quick Start
For a quick start to use Bones for Ghost start by cloning this repository.

In your terminal change to your ```/content/themes/``` and use
```bash
git clone https://github.com/ghost-bones/bones-core.git
```
to clone the theme.

You can also use your own theme name by using
```bash
git clone https://github.com/ghost-bones/bones-core.git your-theme
```
. Replace 'your-theme' with the name of your theme.

## Ghost CLI Local Development
### Requirements
For local independent development we recommend using the [Ghost-CLI](https://docs.ghost.org/install/local/).

If you have not already installed [Node.js](https://nodejs.org/en/) and Node Package Manager which is included in Node.js you will require it to be able to install the Ghost-CLI.

### Ghost CLI Install
If you have NPM (Node Package Manager) installed run
```bash
npm install ghost-cli@latest -g
```
to install Ghost CLI.

### Ghost Install
To [install Ghost](https://docs.ghost.org/install/local/) for local development use
```bash
ghost install local
```
in the terminal. This will install a local development version of Ghost on your machine and spin it up to enable you to start developing.
For full instructions on how to manage a Ghost installation refer to the [Ghost CLI Documentation](https://docs.ghost.org/install/local/#starting--stopping)

### Bones Install
Refer to the Quick Start instructions above.

# Issues & Feature Requests
While we are developing initially for ourselves we hope that many others find this helpful. We are very eager to fix bugs and also to look at any feature requests. Please use this repo's issues section to log any bugs or feature requests.

# Theme development
## Official Ghost Theme Development Documentation
Following is an orientation of the bones-core theme, for full documentation check out the [official theme development guide](https://docs.ghost.org/api/handlebars-themes/) from Ghost.

## Theme Structure
The theme follow the basic structure listed in the [official handlebars-themes documentation](https://docs.ghost.org/api/handlebars-themes/structure/) and includes the  optional /partials directory for storing reused code. The goal here is to cut down on development work so it is best not to repeat ourselves if we don't have to.

```bash
├── /assets
    ├── /css
        ├── screen.css
    ├── /fonts
    ├── /images
    ├── /js
├── /partials
├── default.hbs
├── index.hbs
├── post.hbs
└── package.json

```

## Props to a Friendly Ghost
This theme does borrow some of its code from *Casper* the default theme for [Ghost](http://github.com/tryghost/ghost/).

This has been done for a couple of reasons;
* If you are already developing using Casper as a working base you will be familiar with it, so it should help reduce development,
* To reduce the development time for this theme, and
* Because that is what it is there for.

## Theme Development Assumptions
In creating this theme a few assumptions have been about you as a developer and what type of theme you are developing.

* You are developing for either a specific commercial client, or
* You are developing themes for free/sale for use by other developers or end users, and
* Your development skills may range from HTML/CSS to full-stack developers.

Additionally your clients and customers want;

* A consistent brand experience for their users,
* To be able to manage all their content via Ghost, including updating branding and menus.
