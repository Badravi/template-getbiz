<div align="center">
 Documentation
</div>

### <section align="left"> Note </section>

1. <p>To avoid spelling mistakes in the entire code, install code spell checker extension in VS Code before you start coding</p>

- <https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker>

2. <p> Angular Check List </p>

- <https://docs.google.com/spreadsheets/d/1E3ttau6FblNbEgh_tFZFQo1a9NukRrn9OJXDDuaHtlw/edit?usp=sharing>

3. <p>
   Do Not use, old libraries / packages with no latest updates (within last 6 months), which is not open source and does not have more than a million downloads. Use only NPM and YARN.
   </p>

4. <p> Cache Control in Angular

<ul>
  <li>Busting the Cache of index.html file, while serving Angular build file in the production. Add Meta tag with cache-control information in the index.html</li>
  <li>
    meta http-equiv='Cache-Control' content='no-cache, no-store, must-revalidate 
   </li>
  <li>In the server side, setup the Response headers for the index.html file to cache-control="no-cache"

<https://angular.io/guide/service-worker-config#navigationrequeststrategy></li>

  <li>
  In the ngsw-config.json file, add the following lines

```json
  "navigationRequestStrategy": "freshness"
```

  </li>

  <li>
  This will make sure that index.html is never cached in the user’s browser. So now whenever we make a release, users will get the latest version only.
  </li>
</ul>

</p>

5. <p>Use Roboto Font</p>

- `<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500&amp;display=swap" rel="stylesheet" />`

6. ### Angular Documentation

- <https://angular.io>

7. ### TypeScript Documentation

- <https://www.typescriptlang.org>

8. ### Angular Material Documentation

- <https://material.angular.io>

9. ### RxJS Documentation

- <https://rxjs.dev>

10. ### Npm

- <https://www.npmjs.com>

11. ### Yarn

- <https://yarnpkg.com>

12. ### Tailwind CSS Documentation

- <https://tailwindcss.com>

13. ### Other JavaScript Libraries Documentation

- Luxon JS (Parse, validate, manipulate, and display dates and times in JavaScript)

- <https://moment.github.io/luxon/#/?id=luxon>

- Country City State JSON (JSON formatted data containing the world's countries, states/provinces, and cities)

- <https://github.com/khkwan0/countryCityStateJson>

- International Telephone Input

- <https://github.com/tanansatpal/ngx-mat-intl-tel-input>

- LibPhoneNumber

- <https://catamphetamine.gitlab.io/libphonenumber-js>

- Datetime-picker and TimePicker

- <https://h2qutc.github.io/angular-material-components/datetimepicker>

---

<div align="center">
CLI Commands
</div>

### NPM

```bash
1) Install dependencies - npm install
2) Install package - npm install [package]
3) Install dev package - npm install --save-dev [package]
4) Uninstall package - npm uninstall [package]
5) Uninstall dev package - npm uninstall --save-dev [package]
6) Update - npm update
7) Update Package - npm update [package]
8)Global install package - npm install --global [package]
9)Global uninstall package - npm uninstall --global [package]

npm init
npm run
npm test
npm login (and logout)
npm link
npm publish
npm cache clean
```

---

### YARN

```bash
1) Install dependencies - yarn
2) Install package - yarn add [package]
3) Install dev package - yarn add --dev [package]
4) Uninstall package - yarn remove [package]
5) Uninstall dev package - yarn remove [package]
6) Update - yarn upgrade
7) Update Package - yarn upgrade [package]
8)Global install package - yarn upgrade [package]
9)Global uninstall package - yarn global remove [package]

yarn init
yarn run
yarn test
yarn login (and logout)
yarn link
yarn publish
yarn cache clean
```

---

<div align="center">
 List of JavaScript Packages and Installation Commands (which can be executed in the Windows Terminal, Command Prompt and PowerShell)
</div>

```bash

1) Angular Material - ng add @angular/material

2) Angular Service Worker - ng add @angular/pwa

3) Tailwind CSS - yarn add tailwindcss postcss autoprefixer

4) Angular material Date Picker using moments.js - yarn add @angular/material-moment-adapter

5) Angular Material Extensions - yarn add @ng-matero/extensions
- @ng-matero/extensions-moment-adapter

6) Luxon JS - yarn add luxon

7) Sheet JS - yarn add xlsx

8) Country City State JSON - yarn add countrycitystatejson

9) LibPhoneNumber - yarn add libphonenumber-js

10) International Telephone Input - yarn add ngx-mat-intl-tel-input

11) NGX Datetime-picker and TimePicker - yarn add @angular-material-components/datetime-picker

12) NGX Datetime-picker using moments.js - yarn add @angular-material-components/moment-adapter

```

---
