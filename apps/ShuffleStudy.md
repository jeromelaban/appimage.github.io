---
layout: app

permalink: /ShuffleStudy/
description: A modern note-taking app for college students

icons:
  - ShuffleStudy/icons/128x128/shufflestudy.png

screenshots:
  - ShuffleStudy/screenshot.png

authors:
  - name: MrDrProfX
    url: https://github.com/MrDrProfX

links:
  - type: GitHub
    url: MrDrProfX/ShuffleStudyBuilds
  - type: Download
    url: https://github.com/MrDrProfX/ShuffleStudyBuilds/releases

desktop:
  Desktop Entry:
    Name: ShuffleStudy
    Comment: A modern note-taking app for college students
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: shufflestudy
    X-AppImage-Version: 1.4.3
    X-AppImage-BuildId: 97587930-4842-11a9-0af8-17c2a8c48791
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  homepage: https://shufflestudy.io
  author:
    name: Endwise
    email: contact@endwise.io
  environmentSource: environments/environment.ts
  environments:
    dev: environments/environment.ts
    prod: environments/environment.prod.ts
  main: main.js
  private: true
  dependencies:
    "@angular/animations": "^5.0.5"
    "@angular/cdk": "^5.0.0-rc.2"
    "@angular/common": 5.0.3
    "@angular/compiler": 5.0.3
    "@angular/core": 5.0.3
    "@angular/forms": 5.0.3
    "@angular/http": 5.0.3
    "@angular/material": "^5.0.0-rc.2"
    "@angular/platform-browser": 5.0.3
    "@angular/platform-browser-dynamic": 5.0.3
    "@angular/router": 5.0.3
    "@nicky-lenaers/ngx-scroll-to": "^0.6.0"
    angular-font-awesome: "^3.1.2"
    angular-froala-wysiwyg: "^2.7.3"
    angular-tree-component: "^6.0.0"
    angularfire2: "^5.0.0-rc.4"
    choice: "^2.0.2"
    core-js: 2.4.1
    dependency-sorter: "^0.1.0"
    electron-editor-context-menu: "^1.1.1"
    electron-google-analytics: "^0.1.0"
    electron-is: "^2.4.1"
    electron-is-dev: "^0.3.0"
    electron-log: "^2.2.14"
    electron-updater: "^2.21.10"
    enhanced-resolve: 3.3.0
    escape-string-regexp: "^1.0.5"
    firebase: "^4.13.1"
    firebaseui: "^2.5.1"
    firebaseui-angular: "^2.5.2"
    font-awesome: "^4.7.0"
    hammerjs: "^2.0.8"
    js-beautify: "^1.7.5"
    jspdf: "^1.3.5"
    mustache: "^2.3.0"
    ng-contenteditable: "^1.0.5"
    ng-drag-drop: "^4.0.0"
    ng2-split-pane: "^1.4.0"
    ng2-tree: "^2.0.0-rc.4"
    ngx-contextmenu: "^3.0.2"
    random-seed: "^0.3.0"
    rimraf: "^2.6.2"
    rxjs: 5.5.2
    sanitize-html: "^1.18.2"
    seedrandom: "^2.4.3"
    shuffle-array: "^1.0.1"
    string-hash: "^1.1.3"
    zone.js: 0.8.17
  license: SEE LICENSE IN LICENSE.md
---
