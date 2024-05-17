
# install
--------------------------------
```
% node -v
v18.20.2
% npm -v
6.11.3
```
--------------------------------
```
npm install -g @angular/cli
```
--------------------------------
```
% ng --version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 8.3.0
Node: 18.20.2
OS: darwin x64
Angular: 
... 

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.803.0
@angular-devkit/core         8.3.0
@angular-devkit/schematics   8.3.0
@schematics/angular          8.3.0
@schematics/update           0.803.0
rxjs                         6.4.0
```    
--------------------------------
--------------------------------
```
ng new my-angular-app
cd my-angular-app
ng serve
```
--------------------------------

? Would you like to add Angular routing? No
? Which stylesheet format would you like to use? CSS

--------------------------------

added 1359 packages from 1065 contributors and audited 1362 packages in 39.12s
found 73 vulnerabilities (2 low, 31 moderate, 33 high, 7 critical)
  run `npm audit fix` to fix them, or `npm audit` for details
    Directory is already under version control. Skipping initialization of git.

--------------------------------

Node.js v18.20.2

--------------------------------
```
export NODE_OPTIONS=--openssl-legacy-provider
```
--------------------------------
```
% ng serve
Browserslist: caniuse-lite is outdated. Please run the following command: `npx browserslist --update-db`
10% building 3/3 modules 0 active(node:19190) [DEP0111] DeprecationWarning: Access to process.binding('http_parser') is deprecated.
(Use `node --trace-deprecation ...` to show where the warning was created)
ℹ ｢wds｣: Project is running at http://localhost:4200/webpack-dev-server/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: 404s will fallback to //index.html

chunk {main} main.js, main.js.map (main) 49.3 kB [initial] [rendered]
chunk {polyfills} polyfills.js, polyfills.js.map (polyfills) 269 kB [initial] [rendered]
chunk {runtime} runtime.js, runtime.js.map (runtime) 6.15 kB [entry] [rendered]
chunk {styles} styles.js, styles.js.map (styles) 9.74 kB [initial] [rendered]
chunk {vendor} vendor.js, vendor.js.map (vendor) 3.9 MB [initial] [rendered]
Date: 2024-05-17T05:43:26.806Z - Hash: 76629812cf3ac2089650 - Time: 7280ms
** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **
ℹ ｢wdm｣: Compiled successfully.
```
--------------------------------
--------------------------------

** Angular Live Development Server is listening on localhost:4200, 
open your browser on http://localhost:4200/ **

--------------------------------
