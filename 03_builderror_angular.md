--------------------------------

cd my-angular-app

npm install -g @angular/cli

ng serve

--------------------------------

% node -v
v20.13.1

--------------------------------

Browserslist: caniuse-lite is outdated. Please run the following command: `npx browserslist --update-db`
10% building 3/3 modules 0 active(node:11007) [DEP0111] DeprecationWarning: Access to process.binding('http_parser') is deprecated.
(Use `node --trace-deprecation ...` to show where the warning was created)
ℹ ｢wds｣: Project is running at http://localhost:4200/webpack-dev-server/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: 404s will fallback to //index.html
10% building 3/4 modules 1 active ...webpack-dev-server/client/index.js?http://0.0.0.0:0/sockjs-node&sockPath=/sockjs-nodenode:internal/crypto/hash:79
  this[kHandle] = new _Hash(algorithm, xofLen, algorithmId, getHashCache());
                  ^

Error: error:0308010C:digital envelope routines::unsupported
    at new Hash (node:internal/crypto/hash:79:19)
    at Object.createHash (node:crypto:139:10)
    at module.exports (/Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/util/createHash.js:135:53)
    at NormalModule._initBuildHash (/Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/NormalModule.js:412:16)
    at /Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/NormalModule.js:444:10
    at /Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/NormalModule.js:320:13
    at /Users/shun_ishii/.Trash/my-angular-app/node_modules/loader-runner/lib/LoaderRunner.js:367:11
    at /Users/shun_ishii/.Trash/my-angular-app/node_modules/loader-runner/lib/LoaderRunner.js:203:19
    at VirtualFileSystemDecorator.readFile (/Users/shun_ishii/.Trash/my-angular-app/node_modules/@ngtools/webpack/src/virtual_file_system_decorator.js:46:13)
    at processResource (/Users/shun_ishii/.Trash/my-angular-app/node_modules/loader-runner/lib/LoaderRunner.js:202:11)
    at iteratePitchingLoaders (/Users/shun_ishii/.Trash/my-angular-app/node_modules/loader-runner/lib/LoaderRunner.js:158:10)
    at runLoaders (/Users/shun_ishii/.Trash/my-angular-app/node_modules/loader-runner/lib/LoaderRunner.js:365:2)
    at NormalModule.doBuild (/Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/NormalModule.js:292:3)
    at NormalModule.build (/Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/NormalModule.js:438:15)
    at Compilation.buildModule (/Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/Compilation.js:702:10)
    at /Users/shun_ishii/.Trash/my-angular-app/node_modules/webpack/lib/Compilation.js:944:14 {
  opensslErrorStack: [
    'error:03000086:digital envelope routines::initialization error',
    'error:0308010C:digital envelope routines::unsupported'
  ],
  library: 'digital envelope routines',
  reason: 'unsupported',
  code: 'ERR_OSSL_EVP_UNSUPPORTED'
}

Node.js v20.13.1

--------------------------------

cd my-angular-app

ng serve

--------------------------------

npm install --save-dev webpack@latest

--------------------------------

An unhandled exception occurred: Cannot find module 'webpack/lib/ParserHelpers'
Require stack:
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/worker-plugin/dist/worker-plugin.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/build-angular/src/angular-cli-files/models/webpack-configs/worker.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/build-angular/src/angular-cli-files/models/webpack-configs/index.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/build-angular/src/browser/index.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/build-angular/src/dev-server/index.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/architect/node/node-modules-architect-host.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/architect/node/index.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular/cli/models/architect-command.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular/cli/commands/serve-impl.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/schematics/tools/export-ref.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular-devkit/schematics/tools/index.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular/cli/utilities/json-schema.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular/cli/models/command-runner.js
- /Users/shun_ishii/.Trash/my-angular-app/node_modules/@angular/cli/lib/cli/index.js
- /Users/shun_ishii/.npm-global/lib/node_modules/@angular/cli/lib/init.js
- /Users/shun_ishii/.npm-global/lib/node_modules/@angular/cli/bin/ng
See "/private/var/folders/fg/slg8ny595pd04183zspq2f380000gn/T/ng-zLp7kD/angular-errors.log" for further details.

--------------------------------

Webpackのバージョンの互換性問題
Angular CLIとWebpackのバージョンが互換性がない場合に発生する可能性があります。

Node.jsのバージョンの互換性問題
使用中のNode.jsのバージョンがWebpackやAngular CLIと互換性がない可能性があります。

キャッシュの問題
npm installのキャッシュに問題があり、正しくモジュールがインストールされていない可能性があります。

--------------------------------
