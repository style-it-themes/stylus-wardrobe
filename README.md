<p align="center">
  <img alt="style-it-themes-logo" src="https://raw.githack.com/style-it-themes/style-it-themes-logos/master/style-it-themes-logo-full.svg" width="580">
</p>
<br>
<h1 align="center"><strong>Stylus Wardrobe</strong></h1>
<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?longCache=true&style=for-the-badge" alt="LICENCE">
  </a>
</p>
<p align="center">
  <a href="https://discord.gg/MhwZjV">
    <img src="https://img.shields.io/badge/style--it--themes-discord%20channel-blue.svg?style=for-the-badge" alt="Style-It Themes (sit) Discord Channel">
  </a>
  <a href="https://github.com/style-it-themes/stylus-wardrobe/releases">
    <img src="https://img.shields.io/github/tag/style-it-themes/stylus-wardrobe.svg?label=Current%20Version&style=for-the-badge" alt="Current version">
  </a>
  <a href="https://david-dm.org/Style-it-Themes/stylus-wardrobe?type=dev">
    <img src="https://img.shields.io/david/dev/style-it-themes/stylus-wardrobe.svg?label=devDependencies&style=for-the-badge" alt="devDependencies">
  </a>
</p>

# TOC
  * [About](#about)
  * [Features](#features)
  * [Installing](#installing)
    * [Requirements](#requirements)
    * [Install This Style](#install-this-style)
    * [Additional Userstyles](#additional-userstyles)
  * [I Found a Bug](#i-found-a-bug)
  * [Engaging with the Project](#engaging-with-the-project)
    * [Contribution Guidelines](#contribution-guidelines)
    * [Development Scripts](#development-scripts)
  * [Screens](#screens)
  * [Thanks](#thanks)

## About

The *Stylus Wardrobe* style is designed to be used in conjunction with [Stylus](https://github.com/openstyles/stylus)

It's made for my personal use only, and shared because... Why not.

## Features

The *Stylus Wardrobe* style has optional and built in redesigns that fix,
modernize or allow consistence styling through all accessible areas.
if you wish to view complete list click below.

<details>
  <summary>Click to Expand</summary>
 
 ### Preset styles

 * Custom colors
 * Cobalt
 * Material
 * Material Darker
 * Solarized Dark
 * Twilight
 * Ubuntu

> Note: When using custom colors, remember that restrictions in what shades to use in contrast are limited,
use wisely, as bugs reports regarding edge cases are not a priority. 

 ### Color Adjustments

 * Optionally darken/lighten to some extent the background, foreground colors. 

 ### Navigation

 * Optionally invert navigation colors

 ### Redesigned Inputs/Buttons/Select elements

 * Redesigned input styling for checkboxes, radio, dropdown and other interactable elements.
 
 You can optionally choose the checkbox size, however not all sizes will look or align well.

 ## The Kitchen Sink

 
</details> 

## Installing

### Requirements

* Stylus - install the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

### Install This Style

[![CLICK TO INSTALL WITH - STYLUS](https://img.shields.io/badge/Install_directly_with-Stylus-21d1d0.svg?longCache=true&style=for-the-badge)](https://github.com/style-it-themes/stylus-wardrobe/raw/main/stylus-wardrobe.user.styl)  
*Click to install directly from this repository*.

### Additional Userstyles
  Style-It Themes recommends the Global Overlay Scrollbars

* [Overlay Scrollbars](https://github.com/StylishThemes/Overlay-Scrollbars)

## I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).

If your issue is new, please [open an issue](https://github.com/style-it-themes/stylus-wardrobe/issues/new/choose) and report your problem.

You will need to be familiar with browser development tools.

[Firefox development tools](https://developer.mozilla.org/en-US/docs/Tools)
[Chrome development tools](https://developers.google.com/web/tools/chrome-devtools)

## Engaging with the Project

There are many ways to engage with the project, all contributions types are most welcome and encouraged, e.g. typo(s), documentation, prettification of any included portions, or even to provide feedback or ask a question, or help out with support/questions from other users, to name just a few ways you can engage with this project.

Open a pull request or [ticket](https://github.com/style-it-themes/stylus-wardrobe/issues/new/choose) to start the ball rolling.

For Git related contributions you will need:

1. [Fork](https://github.com/style-it-themes/stylus-wardrobe/fork) the project.
2. Install devdependencies `npm i --only-dev`
3. Edit the desired files according to current requirement below, commit changes, run fix script `npm run fix` and push changes.
4. Open a pull request

## Contribution Guidelines

Please expand the section below:

<details>
  <summary>Click to Expand</summary>

* Limit to the [K&R (KNF variation style)](https://en.wikipedia.org/wiki/Indentation_style#Variant:_BSD_KNF), and **2 SPACE INDENTATION** (no tabs, and no less than 2 spaces).

* K&R - KNF Variation Example:
  ```css
  element[attr='value'] {
  ··property: value;
  }
  ```

* **Not Allman**
  ```css
  element[property='value']
  {
  ··property: value;
  }
  ```

* Strict space between the `selector` and the `{`:
  ```css
  /* good */
  element[attr='value'] { }

  /* bad */
  element[attr='value']{ }
  ```

* 2 Space indentation
  ```css
  /* good */
  ··property: value;

  /* bad */
  ··property: value;
  --property: value;
  ·property: value;
  ```

:asterisk: Try to wrap lines at around 80 characters.

</details>

### Development Scripts

* `npm run authors`: Regenerate the AUTHORS file based on Git history
* `npm run ecfix`: Run editorconfig via ECLint with `--fix` on the styl file.

### For internal use Only

Releases are for internal use only, so remember to not include version bumps with your contributions 

* `npm run major`: Creates a semantic major release.
* `npm run minor`: Creates a semantic minor release.
* `npm run patch`: Creates a semantic patch release.

* `npm run update`: Update development dependencies.

> Note: Dependencies updates can be submitted as part of any contribution that is a separate commit
>       from main contribution, or as a standalone contribution.

## Screens

# COMING SOON

More screenshots available in [screens directory](/screens) for your perusal.

## Thanks

@vednoc kudos and thanks, for showing me another way to save retinas from the burn.

[Openstyles](https://github.com/openstyles/stylus) for developing Stylus. The best userstyle extension on all the web.

[:arrow_up: UP :arrow_up:](#file-readme-md)
