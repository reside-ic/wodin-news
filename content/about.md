---
title: "About"
---

Wodin is [odin](https://mrc-ide.github.io/odin) on the web, an application that compiles the odin domain specific language for differential equations into JavaScript and allows exploration of dynamical systems without installing any software at all. It has been built by us at [RESIDE](https://reside-ic.github.io) to support teaching activities within the [MRC Centre for Global Infectious Disease Analysis](https://www.imperial.ac.uk/mrc-global-infectious-disease-analysis/)

It is composed of many moving parts

* [`wodin`](https://github.com/mrc-ide/wodin), an [express](https://expressjs.com/)-based API and [TypeScript](typescriptlang.org)/[Vue.js](https://vuejs.org/) based web application
* [`odin.api`](https://github.com/mrc-ide/odin.api), a [porcelain](https://reside-ic.github.io/porcelain/)/[plumber](https://www.rplumber.io/) API which interfaces between `wodin` and `odin`
* [`odin`](https://mrc-ide.github.io/odin), a domain specific language (DSL) for expressing systems differential equations
* [`odin-js`](https://mrc-ide.github.io/odin-js/), JavaScript support code for running odin models in JavaScript
* [`dopri-js`](https://mrc-ide.github.io/dopri-js/), a differential equation solver written in TypeScript
