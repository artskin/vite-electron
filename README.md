# electron-vite-vue

[![awesome-vite](https://awesome.re/mentioned-badge.svg)](https://github.com/vitejs/awesome-vite)
[![Netlify Status](https://api.netlify.com/api/v1/badges/ae3863e3-1aec-4eb1-8f9f-1890af56929d/deploy-status)](https://app.netlify.com/sites/electron-vite/deploys)
![GitHub license](https://img.shields.io/github/license/caoxiemeihao/electron-vite-vue?style=flat)
![GitHub stars](https://img.shields.io/github/stars/caoxiemeihao/electron-vite-vue?color=fa6470&style=flat)
![GitHub forks](https://img.shields.io/github/forks/caoxiemeihao/electron-vite-vue?style=flat)


**English | [įŽäŊä¸­æ](README.zh-CN.md)**

đĨŗ Real simple `Electron` + `Vue` + `Vite` boilerplate.

## Quick Start

[![quick-start](https://asciinema.org/a/483731.svg)](https://asciinema.org/a/483731)

## Overview

This is a `Vite`-integrated `Electron` template built with simplification in mind.

The repo contains only the most basic files, dependencies and functionalities to ensure flexibility for various scenarios. 

You need a basic understanding of `Electron` and `Vite` to get started. But that's not mandatory - you can learn almost all the details by reading through the source code. Trust me, this repo is not that complex. đ

## Directory

A `dist` folder will be generated everytime when `dev` or `build` command is executed. File structure of `dist` is identical to the `packages` directory to avoid any potential path calculation errors.

```tree
â
âââ dist                      Will be generated following the structure of "packages" directory
â   âââ main
â   âââ preload
â   âââ renderer
â
âââ scripts
â   âââ build.mjs             Build script -> npm run build
â   âââ watch.mjs             Develop script -> npm run dev
â
âââ packages
â   âââ main                  Main-process source code
â       âââ vite.config.ts
â   âââ preload               Preload-script source code
â       âââ vite.config.ts
â   âââ renderer              Renderer-process source code
â       âââ vite.config.ts
â
```

## List the modules you may use as far as possible

Used in Main-process đ [electron-vite-boilerplate](https://github.com/caoxiemeihao/electron-vite-boilerplate)

Used in Renderer-process đ [electron-vite-boilerplate/tree/nodeIntegration](https://github.com/caoxiemeihao/electron-vite-boilerplate/tree/nodeIntegration)

**ES Modules**

- [execa](https://www.npmjs.com/package/execa)
- [node-fetch](https://www.npmjs.com/package/node-fetch)
- [file-type](https://www.npmjs.com/package/file-type)

**Native Addons**

- [sqlite3](https://www.npmjs.com/package/sqlite3)
- [serialport](https://www.npmjs.com/package/serialport)

## Main window
<img width="400px" src="https://raw.githubusercontent.com/caoxiemeihao/blog/main/electron-vue-vite/screenshot/electron-15.png" />

## <!-- Wechat | | -->č¯ˇæåæ¯ä¸åčļ đĨŗ

<div style="display:flex;">
  <!-- <img height="333px" src="https://raw.githubusercontent.com/caoxiemeihao/blog/main/assets/wechat/group/qrcode.jpg" />
  &nbsp;&nbsp;&nbsp;&nbsp; -->
  <img height="333px" src="https://raw.githubusercontent.com/caoxiemeihao/blog/main/assets/wechat/%24qrcode/%24.png" />
</div>

