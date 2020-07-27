# Panda Blog Hexo

Derived from Hexo implementation of the free [HTML5Up Phantom Template](http://html5up.net/phantom)

Panda is a photography/design portfolio oriented, responsive theme. [Demo here](http://www.codeblocq.com/assets/projects/hexo-theme-phantom/).

## Features Overview

- Disqus and Facebook comments
- Google Analytics
- Cover image for posts and pages
- Tags Support
- Responsive Images
- Image Gallery
- Social Accounts configuration
- Pagination

## Not Supported

- Post Categories will not be displayed
- Posts and Pages Dates will not be displayed

## External libraries used

- [FeatherLight.js](http://noelboss.github.io/featherlight/) (Gallery)
- [jQuery](https://jquery.com/)
- [Skel](https://github.com/n33/skel)

## Installation

### SCSS support

Phantom uses SCSS as a css preprocessor. SCSS is not supported by default in hexo, the `hexo-renderer-scss` is required.

Install it by using:

```
$ npm install --save hexo-renderer-scss
```
### Install the theme

Install the theme by using:

```
$ git clone https://gitlab.com/j-mcavoy/hexo-theme-panda.git themes/panda
```

Then update your blog's main `_config.yml` to set the theme to `panda`:

i.e:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: panda
```

## Theme Configuration

The theme's global configuration is done in `/themes/panda/_config.yml`.
