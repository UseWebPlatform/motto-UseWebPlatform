# #UseWebPlatform

[![GitHub Stars](https://img.shields.io/github/stars/UseWebPlatform/motto-UseWebPlatform.svg?label=GitHub%20Stars)](https://github.com/UseWebPlatform/motto-UseWebPlatform)
[![GitHub Watchers](https://img.shields.io/github/watchers/UseWebPlatform/motto-UseWebPlatform.svg?label=GitHub%20Watchers)](https://github.com/UseWebPlatform/motto-UseWebPlatform)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://help.github.com/articles/about-pull-requests/)

Use universal the [Web Platform](https://www.w3.org/standards/) primitives with motto-in-hashtag-form #UseWebPlatform, extended motto [#UseThePlatform](https://www.polymer-project.org/about).

Use the primitives, a patterns and Polymer library for **reusable**, **performant**, **maintainable** code:

- [1. CSS Variables, HTML Templates, JavaScript, WebAssembly](#1-css-variables-html-templates-javascript-webassembly)
- [2. Web Components](#2-web-components)
- [3. HTTP/2 + Server Push + HTML Imports / ES6 Modules](#3-http2--server-push--html-imports--es6-modules)
- [4. Service Workers, Web Workers](#4-service-workers-web-workers)
- [5. Progressive Web Apps](#5-progressive-web-apps)
- [6. Web Accessibility](#6-web-accessibility)
- [7. Web APIs](#7-web-apis)
- [8. PRPL Pattern](#8-prpl-pattern)
- [9. RAIL Performance Model](#9-rail-performance-model)
- [10. Polymer Project](#10-polymer-project)

## 1. CSS Variables, HTML Templates, JavaScript, WebAssembly

### CSS Variables, CSS Mixins

- [CSS Variables: Why Should You Care?](https://developers.google.com/web/updates/2016/02/css-variables-why-should-you-care)
- [Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)
- [What is the difference between CSS variables and preprocessor variables?](https://css-tricks.com/difference-between-types-of-css-variables/)
- [Polymer custom CSS properties](https://www.polymer-project.org/2.0/docs/devguide/custom-css-properties)
- [Polymer custom CSS mixins](https://www.polymer-project.org/2.0/docs/devguide/custom-css-properties#use-custom-css-mixins)

**You Don't Need** SASS, LESS, Stylus, etc.

### HTML Templates

- [HTML \<template\> element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template)
- [Polymer data binding helper elements](https://www.polymer-project.org/2.0/docs/devguide/templates)
- [HTML templates, via JavaScript template literals](https://github.com/PolymerLabs/lit-html)

**You Don't Need** Mustache, Handlebars, Nunjucks, Pug, etc.

### JavaScript

[JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) (JS) is a lightweight interpreted or JIT-compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as node.js, Apache CouchDB, Adobe Acrobat, Google Apps Script, Google BigQuery UDF, etc.

#### Learn JavaScript properly

- [JavaScript Best Practices](https://www.w3schools.com/js/js_best_practices.asp)
- [JavaScript Common Mistakes](https://www.w3schools.com/js/js_mistakes.asp)
- [JavaScript Use Strict](https://www.w3schools.com/js/js_strict.asp)
- [JavaScript Performance](https://www.w3schools.com/js/js_performance.asp)
- [Learn How To Debug JavaScript with Chrome DevTools](https://codeburst.io/learn-how-to-debug-javascript-with-chrome-devtools-9514c58479db)
- [ES8 was Released and here are its Main New Features](https://hackernoon.com/es8-was-released-and-here-are-its-main-new-features-ee9c394adf66)

#### Static Types

- [You Might Not Need TypeScript (or Static Types)](https://medium.com/javascript-scene/you-might-not-need-typescript-or-static-types-aa7cb670a77b)
- [Polymer Custom Element Properties](https://www.polymer-project.org/2.0/docs/devguide/properties)

**You Don't Need** Dart, TypeScript, Elm, PureScript, CoffeeScript, ClojureScript, etc.

### WebAssembly

[WebAssembly](http://webassembly.org) or wasm is a new portable, size- and load-time-efficient format suitable for compilation to the web.

**You Don't Need** Google Native Client.

### Drop any frameworks

Drop any frameworks for their bad performance and maintainability, check out the [HNPWA](https://hnpwa.com) apps.

- [You Don't Need jQuery](https://github.com/oneuijs/You-Dont-Need-jQuery)
- [You might not need a CSS framework](https://hacks.mozilla.org/2016/04/you-might-not-need-a-css-framework/)
- [JavaScript back to basics: You might not need React or Angular 2](https://react-etc.net/entry/javascript-back-to-basics-you-might-not-need-react-or-angular-2)

**You Don't Need** Angular, jQuery, React, Vue, Bootstrap, Foundation, etc.

## 2. Web Components

[Web Components](https://www.webcomponents.org/introduction) are a set of web platform APIs that allow you to create new custom, reusable, encapsulated HTML tags to use in web pages and web apps.

[Web Components](https://developers.google.com/web/fundamentals/web-components/) let us extend the browser’s built-in component model - **the DOM** - rather than bring our own.

[The Gold Standard Checklist for Web Components](https://github.com/webcomponents/gold-standard/wiki)

Web components are based on four main specifications:

- **Custom Elements** lays the foundation for designing and using new types of DOM elements.
  - [Custom Elements Everywhere](https://custom-elements-everywhere.com)
- **Shadow DOM** defines how to use encapsulated style and markup in web components.
- **HTML Template** defines how to declare fragments of markup that go unused at page load, but can be instantiated later on at runtime.
- **HTML imports** defines the inclusion and reuse of HTML documents in other HTML documents.

**You Don't Need** Angular Components, React Components, Vue Components, etc.

## 3. HTTP/2 + Server Push + HTML Imports / ES6 Modules

In combination with [HTTP/2](https://developers.google.com/web/fundamentals/performance/http2/) and [Server Push](https://developers.google.com/web/fundamentals/performance/http2/#server_push), standard module formats like [HTML Imports](https://w3c.github.io/webcomponents/spec/imports/) and [ES6 Modules](http://exploringjs.com/es6/ch_modules.html) let us declare **fine-grained dependencies** and efficiently deliver them to the client in optimally cacheable form, without relying on complicated packaging tools and loaders.

**You Don't Need** Browserify, Rollup, Webpack, etc.

Polymer 3.0 library using [JavaScript modules via script tag](https://caniuse.com/#feat=es6-module), read more info at [MDN import](https://developer.mozilla.org/cs/docs/Web/JavaScript/Reference/Statements/import). :tada:

## 4. Service Workers, Web Workers

[Service Workers](https://developers.google.com/web/fundamentals/primers/service-workers/) let us build pure web apps that users can access even when their devices are **offline** or network conditions are poor, whereas previously we might have had to resort to manually installable native or “hybrid” apps.

Use [Workbox](https://developers.google.com/web/tools/workbox/) to simplify your development by making it easy to take advantage of powerful service worker features, eliminate boilerplate code, and automate service worker generation.

[Web Workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers) is a simple means for web content to run scripts in **background threads**. The worker thread can perform tasks without interfering with the user interface.

**You Don't Need** manually installable native or “hybrid” apps.

## 5. Progressive Web Apps

[Progressive Web Apps](https://developers.google.com/web/progressive-web-apps/) (PWA) are user experiences that have the reach of the web, and are:

- **Reliable** - Load instantly and never show the downasaur, even in uncertain network conditions.
- **Fast** - Respond quickly to user interactions with silky smooth animations and no janky scrolling.
- **Engaging** - Feel like a natural app on the device, with an immersive user experience.

This new level of quality allows Progressive Web Apps to earn a place on the user's **home screen**.

- [Introduction to Progressive Web App Architectures](https://developers.google.com/web/ilt/pwa/introduction-to-progressive-web-app-architectures-slides)
- [Progressive Web App Checklist](https://developers.google.com/web/progressive-web-apps/checklist)
- [Support native integration](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/#support_native_integration)
- [Progressive Web Apps (PWA) and Windows 10](https://forum.kirupa.com/t/progressive-web-apps-pwa-and-windows-10/637192)
- [How to Save PWA to iOS Homescreen](https://vimeo.com/236430523)
- [WHY You Should Build A Progressive Web App NOW](https://www.youtube.com/watch?v=0LOk_OgUWGM)
- [Twitter Lite PWA Significantly Increases Engagement and Reduces Data Usage](https://developers.google.com/web/showcase/2017/twitter)
- [A community-driven list of stats and news related to PWA](https://www.pwastats.com)
- [Integrating with Browsers and OS - Android Trusted Web Activity (Chrome Dev Summit 2017)](https://www.youtube.com/watch?v=_sLa0qhuqcA)
- [Kickstarting Your Journey to Progressive Web Apps (Chrome Dev Summit 2017)](https://www.youtube.com/watch?v=goafiwzhKMI)

| | Website | PWA (1) | Native App
--- | --- | --- | ---
Offline | NO :heavy_minus_sign: | YES :+1: | YES :+1:
App stores | NO :heavy_minus_sign: | NO :heavy_minus_sign: (2)(3) | YES :+1:
Responsive | YES :+1: | YES :+1: | YES :+1:
Searchable | YES :+1: | YES :+1: | NO :heavy_minus_sign:
Local Notifications | NO :heavy_minus_sign: | YES :+1: | YES :+1:
Push Messages | NO :heavy_minus_sign: | YES :+1: | YES :+1:
Install needed to run | NO :+1: | NO :+1: | YES :heavy_minus_sign:
Fast Updates | YES :+1: | YES :+1: | NO :heavy_minus_sign:
Cross-platform | YES :+1: | YES :+1: | NO :heavy_minus_sign:
Performance | NO :heavy_minus_sign: | YES :+1: (4) | YES :+1:
Lower dev time and cost | YES :+1: | YES :+1: | NO :heavy_minus_sign:
Lower user acquisition cost | YES :+1: | YES :+1: (5) | NO :heavy_minus_sign:
**Result** | +2 | +10 :heart: | 0

(1) PWA on [Chrome from v59 on Android](https://developers.google.com/web/updates/2017/02/improved-add-to-home-screen), [Chromebook](https://youtu.be/m-sCdS0sQO8?t=16m12s), [Samsung Internet v5.4 on Android](https://medium.com/samsung-internet-dev/announcing-samsung-internet-v5-4-stable-fd941e0dcd58), Windows 10 (coming soon)  
(2) Progressive Web Apps are coming soon to the Windows Store for Windows 10 Devices. :+1:  
(3) Updates don’t have to run through an app store. :+1:  
(4) Performance using RAIL Performance Model, WebAssembly, Web Workers.  
(5) [Progressive Web Apps vs Native: Which Is Better for Your Business?](https://www.technology.org/2017/07/28/progressive-web-apps-vs-native-which-is-better-for-your-business/)

**You Don't Need** Apache Cordova, PhoneGap, etc.

## 6. Web Accessibility

[Web Accessibility](https://www.w3.org/WAI/intro/accessibility.php) means that people with disabilities can use the Web.

[A11ycasts with Rob Dodson](https://www.youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g)

## 7. Web APIs

When writing code for the Web with JavaScript, there are a great many [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API) available.

[Chrome Samples](https://www.chromestatus.com/samples)

## 8. PRPL Pattern

[PRPL](https://developers.google.com/web/fundamentals/performance/prpl-pattern/) is a pattern for structuring and serving Progressive Web Apps (PWAs), with an emphasis on the performance of app delivery and launch. It stands for:

- **Push** critical resources for the initial URL route.
- **Render** initial route.
- **Pre-cache** remaining routes.
- **Lazy-load** and create remaining routes on demand.

CSR (Client Side Rendering) with PRPL Pattern has similar performance as SSR (Server Side Rendering).  
[JAMstack](https://jamstack.org) has similar architecture.

**You Don't Need** SSR using PHP, React, Vue, etc.

### PRPL-50

[Measure **Time to Interactive**](https://youtu.be/0A-2BhEZiM4?t=9m20s)

Budget for TTI on mobile 3G networks is only ~ **50 KB** per route :exclamation:

**Drop any frameworks**. Polymer 2.0 library has around 12 KB, so about 38 KB left for your budget. :tada:

### PRPL Servers

- [prpl-server-node](https://github.com/Polymer/prpl-server-node)
- [prpl-server-go](https://github.com/CaptainCodeman/prpl-server-go)

#### Features

- [Differential Serving](https://github.com/Polymer/prpl-server-node#differential-serving)
- [HTTP/2 Server Push](https://github.com/Polymer/prpl-server-node#http2-server-push)
- [Rendering for Bots (SEO, Open Graph)](https://github.com/Polymer/prpl-server-node#rendering-for-bots)

## 9. RAIL Performance Model

[RAIL](https://developers.google.com/web/fundamentals/performance/rail) is a user-centric performance model. Every web app has these four distinct aspects to its life cycle, and performance fits into them in different ways:

- **Response** - Input latency (from tap to paint) < 100ms.
- **Animation** - Each frame's work (from JS to paint) completes < 16ms.
- **Idle** - Main thread JS work chunked no larger than 50ms.
- **Load** - Page considered ready to use in 1000ms.

## 10. Polymer Project

Unlock the Power of Web Components with ES6. [Polymer](https://www.polymer-project.org) is a JavaScript library that helps you create custom **reusable** HTML elements, and use them to build **performant**, **maintainable** apps.

- [Projects using Polymer](https://github.com/abdonrd/PolymerProjects)
- [Polymer library](https://www.polymer-project.org/2.0/docs/devguide/feature-overview)
- [Polymer App Toolbox](https://www.polymer-project.org/2.0/toolbox/)
- [Polymer CLI](https://www.polymer-project.org/2.0/docs/tools/polymer-cli)
- [Polymer CLI Commands](https://www.polymer-project.org/2.0/docs/tools/polymer-cli-commands)
- [Polymer IDE plugins](https://github.com/StartPolymer/awesome-polymer#editor-plugins)
- [Polymer 2.x uses ES6 and compilation to ES5](https://www.polymer-project.org/2.0/docs/es6)
- [Polymer 3.0 preview uses npm and ES6 Modules](https://www.polymer-project.org/blog/2017-08-23-hands-on-30-preview.html)
- [Integration with other frameworks](https://github.com/StartPolymer/awesome-polymer#integration-with-other-frameworks)

We have a collection of [Awesome Polymer](https://github.com/StartPolymer/awesome-polymer) resources.

Try [Polymer Playground](https://github.com/StartPolymer/playground) :eyes:

---

> Do you like it? Please, star the motto :star: [:top:](#usewebplatform)

---

> Short link: [git.io/UseWebPlatform](https://git.io/UseWebPlatform)

---

### License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
