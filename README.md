# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)
-   [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./images/screenshot.png)

### Links

-   Solution URL: [Github](https://github.com/conrackx/qr-code-component)
-   Live Site URL: [Github Pages](https://conrackx.github.io/qr-code-component/)

## My process

This is just another go at a simple html and css build, this time i focused on using git branches as well as using web-dev-server (npm) instead of live-server (vscode extension)

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow

### What I learned

refreshed on many subjects and good practices, improved my coding workspace and extended en some much needed practices (ligatures-enabled font, zsh, web-dev-server, standarized indentation with prettier, used git branches...)

also reinforced the usage of variables and basic style resets:

```css
:root {
    /* colors */
    --white: hsl(0, 0%, 100%);
    --lightgray: hsl(212, 45%, 89%);
    --bluegray: hsl(220, 15%, 55%);
    --darkblue: hsl(218, 44%, 22%);

    /* fonts */
    --outfit: "Outfit", sans-serif;
}
/* Basic resets */
* {
    box-sizing: border-box;
}

html {
    font-size: 62.5%;
}
```

In order to lighten my code editor (in hopes of moving towards a lighter and more performant alterntive) i disabled vscode's live-server extension and installed web-dev-server using node/npm, this is the process:

```bash
npm install -g @web/dev-server
```

then to enable, navigate to the source files and:

```bash
web-dev-server --open --watch
```

or the short version:

```bash
wds -ow
```

### Continued development

id like to improve this accessibility wise and integrate pug/sass to my development at this point, also id like a cleaner repo by using external image hosting site, a well made .gitignore and a deeper license knowledge.

## Author

-   Frontend Mentor - [@conrackx](https://www.frontendmentor.io/profile/conrackx)
-   Twitter - [@conrackx](https://www.twitter.com/conrackx)

## Acknowledgments

not many to thank, but htmlreference.io and cssreference.io websites have been gold for me, thanks.
