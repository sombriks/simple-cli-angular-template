# [simple-cli-angular-template][repo]

[repo]:  https://github.com/sombriks/simple-cli-angular-template

_does not work either_

Bare minimal angular template. I wish it was [parcel][other-11] or
[vite][other-2], but it is what it is.

[other-1]: https://github.com/sombriks/parcel-angular-template
[other-2]: https://github.com/sombriks/vite-angular-template

## Initial setup

```bash
touch tsconfig.json index.html
mkdir src
touch src/main.ts src/app.component.ts src/styles.sass
npm i -D @angular/compiler-cli @angular-devkit/build-angular
npm i -D @angular/core @angular/common  zone.js sass
bon i -D @angular/platform-browser @angular/platform-browser-dynamic
npm pkg set scripts.dev="ng-builder serve"
npm pkg set scripts.build="ng-builder build"
```
