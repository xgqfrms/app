# PWA

> Progressive Web Apps

https://pwa.xgqfrms.xyz

## Markdown to HTML/PDF

> VS code plugins

### Markdown previews

https://code.visualstudio.com/Docs/languages/markdown

## static web server

https://browsersync.io/

```sh
# step 1
$ npm install -g browser-sync

# step 2
$ cd build

# step 3
$ browser-sync start --server --files "./*.html"

# root path
$ browser-sync start --server --files "./**/*.*"
$ browser-sync start --server --files "./src/**/*.*"
```