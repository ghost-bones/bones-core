# Bones for Ghost CMS
Bones for Ghost is a commercial boilerplate theme for web developers to create sites and themes for clients and commercial sale.

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
For local independant development we recommend using the [Ghost-CLI](https://docs.ghost.org/install/local/).

If you havn't already installed [Node.js](https://nodejs.org/en/) and Node Package Manager which is included in Node.js you will require it to be able to install the Ghost-CLI.

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
