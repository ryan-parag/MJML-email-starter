# MJML Email Starter

This projects helps compile multiple MJML templates at once using:

## What is MJML?
MJML is a markup language designed to reduce the pain of coding a responsive email. Its semantic syntax makes it easy and straightforward and its rich standard components library speeds up your development time and lightens your email codebase. MJML’s open-source engine generates high quality responsive HTML compliant with best practices.

MJML rolls up all of what Mailjet has learned about HTML email design over the past few years and abstracts the whole layer of complexity related to responsive email design.

Get your speed and productivity boosted with MJML’s semantic syntax. Say goodbye to endless HTML table nesting or email client specific CSS. Building a responsive email is super easy with tags such as <mj-section> and <mj-column>.

MJML has been designed with responsiveness in mind. The abstraction it offers guarantee you to always be up-to-date with the industry practices and responsive. Email clients update their specs and requirements regularly, but we geek about that stuff - we’ll stay on top of it so you can spend less time reading up on latest email client updates and more time designing beautiful email.

## Where can I learn how to make an email using MJML?
Start building responsive email with MJML. You’ll find in the documentation the full list of components available and their associated attributes.
[Official Documentation](https://mjml.io/documentation)
[MJML Resources](https://mjml.io/resources)

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
