Hướng dẫn nhanh
====

Các thao tác cơ bản để chạy ứng dụng (dùng Phonegap và OnsenUI).

## Yêu cầu

 * Node.js - [Install Node.js](http://nodejs.org)
 * Cordova - Cài bằng lệnh `npm install cordova`
 * PhoneGap - Cài bằng lệnh `npm install -g phonegap`
 * OnsenUI - Cài bằng lệnh `npm install onsenui`

## Hướng dẫn

1. Cài đặt PhoneGap

    $ npm install -g phonegap

2. Cài đặt Cordova

    $ npm install -g cordova

3. Cài đặt Onsen UI

    $ npm install onsenui

Mở trình duyệt và test thử bằng localhost:3000

### Cấu trúc thư mục

    README.md     --> This file
    www/          --> Asset files for app
      index.html  --> App entry point
      js/
      lib/
        angular/  --> AngularJS dependency
        onsen/
          stylus/ --> Stylus files for onsen-css-components.css
          js/     --> JS files for Onsen UI
          css/    --> CSS files for Onsen UI
      scripts/    --> Cordova scripts directory
    platforms/    --> Cordova platform directory
    plugins/      --> Cordova plugin directory
    merges/       --> Cordova merge directory
    hooks/        --> Cordova hook directory
    scripts/      --> Cordova TS scripts directory and TS definitions

## Lệnh PhoneGap

 * `phonegap serve` - Chạy PhoneGap có autoreload.
 * `phonegap serve --no-autoreload` - Chạy PhoneGap không có autoreload.
