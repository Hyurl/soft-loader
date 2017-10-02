# SoftLoader

**Loads content locally and replaces the state of the browser.**

This module uses HTML5's History API, when you request contents through Ajax 
or WebSocket, you can use it to replace the content of the binding element, 
and change the URL and title of the browser without reload the page.

## Install

```sh
npm install soft-loader --save
```

## Example

```javascript
SoftLoader.bind(".content");

SoftLoader.replaceWith("<div>Test content.</div>", "Document Title", "/url");
```