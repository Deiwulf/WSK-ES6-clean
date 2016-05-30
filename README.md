## Overview

This is a modification of [Google's Web Starter Kit](https://developers.google.com/web/tools/starter-kit/) which offers a highly productive and professional development environment/workflow. 

### Modifications Made
- ES6 enabled project-wide by default
- "Basic" with linked resources set as the default index
- Removed material design, swapped the main CSS with HTML5 boilerplate and refactored to .SCSS
- Added alternative command to build without image compression: `gulp hq`
- "Fixed" the babel-register warning by including the module
- Not a bit else.

## Quickstart

- Make sure to have [Node.js](https://nodejs.org/en/) installed.
- Download or clone this repo.
- Using CLI navigate to the root (where **package.json** is).
- Run `npm i --g gulp && npm i`
- Run `gulp serve' and do your thing
- Run `gulp` or `gulp hq` to wrap up for distribution
