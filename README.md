# popper.js
A DX implementation of Popper.js, a kickass library used to manage poppers in web applications

## Wut? Poppers?

A popper is an element on the screen which "pops out" from the natural flow of your application.  
Common examples of poppers are tooltips, popovers and drop-downs.

## So, yet another tooltip library?

Well, basically, **no**.  
Popper.js is a **positioning engine**, its purpose is to calculate the position of an element
to make it possible to position it near a given reference element.  

The engine is completely modular and most of its features are implemented as **modifiers**
(similar to middlewares or plugins).  
The whole code base is written in ES2015 and its features are automatically tested on real browsers thank to [SauceLabs](https://saucelabs.com/) and [TravisCI](travis-ci.org).

Popper.js has zero dependencies. No jQuery, no LoDash, nothing.  
It's used by big companies like [Twitter in Bootstrap v4](https://getbootstrap.com/), [Microsoft in WebClipper](https://github.com/OneNoteDev/WebClipper) and [Atlassian in AtlasKit](https://aui-cdn.atlassian.com/atlaskit/registry/).

### Popper.js

This is the engine, the library that computes and, optionally, applies the styles to
the poppers.

Some of the key points are:

- Position elements keeping them in their original DOM context (doesn't mess with your DOM!);
- Allows to export the computed informations to integrate with React and other view libraries;
- Supports Shadow DOM elements;
- Completely customizable thanks to the modifiers based structure;

Visit the [project page](https://fezvrasta.github.io/popper.js) to see a lot of examples of what you can do with Popper.js!

Find [the documentation here](https://github.com/FezVrasta/popper.js/blob/master/docs/_includes/popper-documentation.md).
