# vue-cli
Minimal script to repro failed npm vue-cli install

```
npm i -g @vue/cli
```

env:
```
pablo@top:~> node --version
v12.20.1
pablo@top:~> npm --version
7.5.3
pablo@top:~> npm show @vue/cli

@vue/cli@4.5.11 | MIT | deps: 35 | versions: 143
Command line interface for rapid Vue.js development
https://cli.vuejs.org/

keywords: vue, cli

bin: vue

dist
.tarball: https://registry.npmjs.org/@vue/cli/-/cli-4.5.11.tgz
.shasum: ab46e00559d4b8cae6a7b74f4140f250225893e8
.integrity: sha512-w6B1+Fb0AHwAd8eE1q4/KrJph/kXo/cqQ0Lf5MnXCYt7SXdDPBGTdyFAumMaSPQESXgmdWgEo8EhnVEBNpXDIw==
.unpackedSize: 158.9 kB

dependencies:
@types/ejs: ^2.7.0                 commander: ^2.20.0                 import-global: ^0.1.0
@types/inquirer: ^6.5.0            debug: ^4.1.0                      ini: ^1.3.5
@vue/cli-shared-utils: ^4.5.11     deepmerge: ^4.2.2                  inquirer: ^7.1.0
@vue/cli-ui-addon-webpack: ^4.5.11 download-git-repo: ^3.0.2          isbinaryfile: ^4.0.6
@vue/cli-ui-addon-widgets: ^4.5.11 ejs: ^2.7.1                        javascript-stringify: ^1.6.0
@vue/cli-ui: ^4.5.11               envinfo: ^7.5.1                    js-yaml: ^3.13.1
boxen: ^4.1.0                      fs-extra: ^7.0.1                   leven: ^3.1.0
cmd-shim: ^3.0.3                   globby: ^9.2.0                     lodash.clonedeep: ^4.5.0
(...and 11 more.)

maintainers:
- akryum <guillaume.b.chau@gmail.com>
- yyx990803 <yyx990803@gmail.com>
- soda <haoqunjiang+npm@gmail.com>

dist-tags:
latest: 4.5.11       next: 5.0.0-alpha.7

published a month ago by soda <haoqunjiang+npm@gmail.com>
pablo@top:~/vue-cli> npm i -g @vue/cli
npm ERR! code FETCH_ERROR
npm ERR! errno FETCH_ERROR
npm ERR! invalid json response body at https://registry.npmjs.org/@babel%2fplugin-proposal-json-strings reason: Unexpected end of JSON input

npm ERR! A complete log of this run can be found in:
npm ERR!     /Users/pablo/.npm/_logs/2021-03-16T03_18_52_003Z-debug.log
pablo@top:~> yarn global add @vue/cli
... [downloading] ...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...
success Installed "@vue/cli@4.5.11" with binaries:
      - vue
✨  Done in 56.81s.
pablo@top:~/vue-cli>
