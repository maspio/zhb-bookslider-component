[![edit-in-Components.studio](https://components.studio/assets/ext/edit_in_cso.svg)](https://components.studio/edit/qJxg2wDSj01IsUFm3Kag)
# ZHB Bookslider Component

A web component for the [Zentral- und Hochschulbibliothek Luzern](https://www.zhbluzern.ch/home/) using the [liberry data portal](https://www.liberry.de/portal.html) to render library collections in a **book cover slider** fashion.

## Features

- minimalistic and responsive design
- animated cover slide transitions
- mouse and touch interaction
- liberry data portal
  - acts as an api gateway to public/private library catalogs
  - transforms bibliographic formats like MARCXML to modern json
  - offers standardized api and data format for clients to consume
  - extends library system functions and enriches library data
  - can load book cover images from several sources

## Inspiration

### ETH Zürich

An previous implementation by the [ETH Bibliothek](https://library.ethz.ch/) of the [ETH Zürich](https://ethz.ch/de.html).

- [Screenshot](https://mail.google.com/mail/u/0?ui=2&ik=a440350b69&attid=0.0.2&permmsgid=msg-f:1674304573226333017&th=173c532374f7b359&view=fimg&sz=s0-l75-ft&attbid=ANGjdJ_HPXebkc4LSTjTNO7byXUmJernFmqeuvvO7bfVUk89r6LArjIuQ6K2Mi5gLitcsGLGpW8jGeq-cGZ8he5OdGI9ncy2a6eroKMu7Yh5GLfyxxLYvgT9Uq5A-gc&disp=emb)
- [Source: https://www.library.ethz.ch/de/](https://www.library.ethz.ch/de/)

## Integration

Sample html script module integration.

### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ZHB Bookslider Component</title>
    <script
      src="https://components.studio/web_modules/qJxg2wDSj01IsUFm3Kag"
      type="module"
    ></script>
  </head>
  <body>
    <zhb-bookslider-component></zhb-bookslider-component>
  </body>
</html>
```

# Standard JS WebComponent

The ZHB Bookslider is bundled as a native WebComponent using only vanilla javascript. A brief introduction follows including some helpful links.

## What are web components?

Web components are a set of web platform APIs that allow you to create new custom, reusable, encapsulated HTML tags to use in web pages and web apps. Custom components and widgets build on the Web Component standards, will work across modern browsers, and can be used with any JavaScript library or framework that works with HTML.

Web components are based on existing web standards. Features to support web components are currently being added to the HTML and DOM specs, letting web developers easily extend HTML with new elements with encapsulated styling and custom behavior.

## Links

- [A Brief Introduction](https://www.webcomponents.org/introduction)
- [W3C Specifications](https://github.com/w3c/webcomponents/)
- [ShadowDOM](https://developers.google.com/web/fundamentals/web-components/shadowdom)
- [CustomElements](https://developers.google.com/web/fundamentals/web-components/customelements)

# License

ISC License

Copyright (c) 2020, [Picibird GmbH](https://picibird.com/)

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

> Created with [Components.studio](https://components.studio)
