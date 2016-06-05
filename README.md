## Overview

This is a modification of [Google's Web Starter Kit](https://developers.google.com/web/tools/starter-kit/) which is aimed at clean and out of the box development environment/workflow using bleeding edge tech.

### Mods
- ES6 with [babel](https://babeljs.io/) enabled project-wide by default
- **basic.html** linked with resources and set as the default index
- Removed material design, swapped the main CSS with that of [HTML5 boilerplate](https://html5boilerplate.com/) and refactored to .SCSS
- Added alternative command to build without image compression: `gulp hq`
- "Fixed" the babel-register warning by including the module
- Not a bit more

## Quickstart

- Make sure to have [Node.js](https://nodejs.org/en/) installed.
- Download or clone this repo.
- Using CLI navigate to the root (where **package.json** is).
- Run `npm i --g gulp && npm i`
- Run `gulp serve` and do your thing
- Run `gulp` or `gulp hq` to wrap up for distribution
