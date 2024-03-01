# Cayman-Dark Theme

*Cayman-Dark is an adaptation of the Cayman Jekyll theme for GitHub Pages.*

You can preview the theme at [chris1111.github.io/cayman-dark](http://chris1111.github.io/cayman-dark).

The dark mode functionality comes from Dark Reader which can be found here: [https://github.com/darkreader/darkreader](https://github.com/darkreader/darkreader)

## Usage

To use the Cayman-Dark theme with Github Pages, add the following to your site's `_config.yml`:

```yml
remote_theme: chris1111/cayman-dark
```

By default pages will be in dark mode however you can make specific pages use light mode. All you need to do is include the following code at the top of your markdown files.

```yaml
---
light_mode: true
---
```

## Original Theme
You can learn more about the underlying theme at [https://github.com/pages-themes/cayman](https://github.com/pages-themes/cayman)

Cayman-Dark is a fork of Cayman thus inherits its functionality. An example is shown below but there is more information at the Cayman repository (see above)

### Configuration variables

Cayman will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

## Changes
A list of changes I have made from the original theme due to my own personal preference
 - Removed "generated by Github pages footer"
 - Removed "skip to content button"
 - To see all changes, see https://github.com/pages-themes/cayman/compare/master...lewismiddleton:master
