# MJML Email Starter

This projects helps compile multiple MJML templates at once using:

```
gulp
gulp-mjml
mjml
mjml-cli
```

## Folder Structure
```
public
  |
  |__ test.html
src
  |
  |__ test.mjml
gulpfile.js
package.json
README.md
```

## Get Started
Use the following commands to compile all of the MJML files in the `src` folder:

```
gulp compile
gulp watch
gulp (both gulp compile and gulp watch in parallel)
```

#### TODO
- add image optimizer
- verbose error warnings
