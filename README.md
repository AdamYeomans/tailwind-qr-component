# QR code component solution built using Tailwindcss.

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Designed with](#designed-with)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Improvements](#potential-improvements-to-design)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./Screenshot.png)

### Links

- Live Site URL: [https://adamyeomans.github.io/tailwind-qr-component/](https://adamyeomans.github.io/tailwind-qr-component/)

## My process

### Designed with

- Figma [File](https://www.figma.com/file/zDwNJtoCKMe3nTmcpX3yPp/qr-code?node-id=0%3A1)

### Built with

- Mobile-first workflow
- HTML5 markup
- Flex
- [Tailwindcss](https://tailwindcss.com/) - CSS Framework

### What I learned

In this project I gained familiarity with the Tailwindcss framework, incoperating their allowance for arbitrary vaules.

```html
<div class="w-[290px] h-[290px] bg-[url('./images/image-qr-code.png')] rounded-[10px] bg-cover"></div>
```

For example within the above code snippet, using arbitrary values with the bg tailwind class to avoid creating a custom class.

### Continued development

Within future solutions, I would like to start using tailwind fractional and interger units instead of arbitrary values. However, within this project I chose to use arbitrary values to first gain familiarity with Tailwindcss.

### Potential improvements to design

This design could be improved by removing arbitrary values and thus allowing for screen sizes below that value. This would require adding a breakpoint below sm for Tailwindcss as their smallest breakpoint is too large.

## Author

- Website - [Adam Yeomans](https://adamyeomans.me/)