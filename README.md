# Service Worker Exploration
Made by [yussan](https://twitter.com/xyussanx). Please read [Getting Started](#getting-started) to start.

![service worker cover](https://philna.sh/images/service-worker.png)

## Overview

A service worker is a script that your browser runs in the background, separate from a web page, opening the door to features that don't need a web page or user interaction. Today, they already include features like push notifications and background sync. In the future, service workers will support other things like periodic sync or geofencing. The core feature discussed in this tutorial is the ability to intercept and handle network requests, including programmatically managing a cache of responses.

The reason this is such an exciting API is that it allows you to support offline experiences, giving developers complete control over the experience.

Before service worker, there was one other API that gave users an offline experience on the web called AppCache. There are a number of issues with the AppCache API that service workers were designed to avoid.

ref : https://developers.google.com/web/fundamentals/primers/service-workers/

## Index 
* [Cache static files]()
* [Offline first]()
* [WIP] Push notification
* [WIP] Geofencing

## Prerequisites
Service worker only support `localhost` and `HTTPS`, you need some webserver to run in local. Here are some that we recomend :
* [https-server (npm)](https://www.npmjs.com/package/http-server)
* [Web Server from Chrome (Google Chrome Extention)](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)

## Getting Started
We split the module into several directory, to get started please read `README.md` we provide in each directory.