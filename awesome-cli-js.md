## Awesome CLI - JS on Windows

### SaaS

|CLI|Cmd|Category|
|---|---|---|
|Firebase|[firebase](https://firebase.google.com/docs/cli/)|DB|

### Platform, CI/CD

|CLI|Cmd|Category|SDK|
|---|---|---|---|
|Heroku|[heroku](https://devcenter.heroku.com/articles/heroku-cli#getting-started)|Cloud|
|AWS|[aws](http://docs.aws.amazon.com/cli/latest/reference/)|Cloud|
|Google Cloud|[gcloud version](https://cloud.google.com/shell/docs/quickstart)|Cloud|[Tools](https://cloud.google.com/products/tools/), [SDK](https://cloud.google.com/sdk/docs/quickstart-windows)|
|Azure|[az](https://docs.microsoft.com/en-us/cli/azure/get-started-with-azure-cli?view=azure-cli-latest)|Cloud|
|Cordova|[cordova -v](https://cordova.apache.org/docs/en/latest/reference/cordova-cli/#cordova-build-command)|Mobile|
|GIT|[git](https://git-scm.com/docs)|VCS|
|SSH|[ssh](https://www.ssh.com/ssh/command)|Remote Control|

### JavaScript

|CLI|Cmd|Config|Environment|Category|
|---|---|---|---|---|
|Protractor|[protractor --version](http://www.protractortest.org/#/)|[config.ts](http://www.protractortest.org/#/api-overview#config-file)||Test Runner|
|Ava|[ava](https://github.com/avajs/ava#cli)|[package.json](https://github.com/avajs/ava#configuration)||Test Runner|
|Karma|[karma](https://karma-runner.github.io/1.0/intro/installation.html)|[karma.conf.*](https://karma-runner.github.io/1.0/config/configuration-file.html)||Test Runner|
|Webpack|[webpack](https://webpack.js.org/api/cli/)|[webpack.config.js](https://webpack.js.org/configuration/#options)||Builder|
|Browserify|[browserify](https://github.com/browserify/browserify#usage)|||Builder|
|Jasmine|[jasmine](https://jasmine.github.io/setup/nodejs.html)|||Test Spec|
|Mocha|[test](http://mochajs.org/#getting-started)|[package.json](http://mochajs.org/#getting-started)||Test Spec|
|Electron|[electron-cli](https://www.npmjs.com/package/electron-cli)|||Desktop Components|
|NativeScript|[tns](https://github.com/NativeScript/nativescript-cli#quick-start)|||Mobile Components|
|Ionic|[ionic -v](https://ionicframework.com/docs/cli/commands.html)|[ionic.config.json](https://ionicframework.com/docs/cli/configuring.html#config-files)|[setx](https://ionicframework.com/docs/cli/configuring.html#environment-variables)|Components|
|Cordova|[cordova -v](https://cordova.apache.org/docs/en/latest/reference/cordova-cli/index.html)|[config.xml](https://cordova.apache.org/docs/en/latest/config_ref/index.html)||Mobile plugins|
|Vue|[vue --version](https://github.com/vuejs/vue-cli/blob/dev/docs/cli.md#usage)|[vue.config.js](https://github.com/vuejs/vue-cli/blob/dev/docs/cli-service.md#using-the-binary) [~/.vuerc](https://github.com/vuejs/vue-cli/blob/dev/docs/cli.md#presets)|[setx](https://github.com/vuejs/vue-cli/blob/dev/docs/env.md#environment-variables-and-modes)|Client side Framework|
|Angular|[ng -v](https://github.com/angular/angular-cli/wiki#additional-commands)|[.angular-cli.json](https://github.com/angular/angular-cli/wiki/angular-cli)||Client side Framework|
|TypeScript|[tsc -v](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)|[tsconfig.json](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)||Language|
|yarn|[yarn](https://yarnpkg.com/en/docs/cli/)|yarn.lock||Package Mgr|
|npm|[npm -v](https://docs.npmjs.com/cli/npm)|[package.json](https://docs.npmjs.com/files/package.json)||Package Mgr|
|Lerna|[lerna](https://lernajs.io/)|||Package Mgr|
|node.js|[node -v](https://nodejs.org/api/cli.html)|||Runtime|
|nvm-windows|[nvm version](https://github.com/coreybutler/nvm-windows#usage)|||Runtime selector|

#### JavaScript - not much in use anymore

|CLI|Cmd|Config|Environment|Category|
|---|---|---|---|---|
|Yeoman|[yo](http://yeoman.io/learning/)|||Code Generator|
|Gulp|[Gulp](https://github.com/gulpjs/gulp/blob/master/docs/CLI.md)|[gulpfile.js](https://github.com/gulpjs/gulp/blob/master/docs/recipes/run-grunt-tasks-from-gulp.md)||Builder|
|Grunt|[grunt](https://gruntjs.com/using-the-cli)|[Gruntfile.js](https://gruntjs.com/sample-gruntfile)||Builder|
|Bower|[Bower](https://bower.io/#getting-started)|||Package Mgr|

#### [NVM](https://rasor.github.io/using-nvm-for-windows-and-yarn.html) sets of tools - avoiding [version conficts](https://github.com/rasor/awesome-tables/blob/master/awesome-angular-tables.md#compiler-ranges)

With NVM you can change back in time (e.g. nvm use 6.9.0), when you need to work on old projects.  
This list below mirrors some versions I have globally installed (e.g. npm install -g ionic) on my PC. You can use it for inspiration.  

|[@types/node (npm)](https://nodejs.org/en/download/releases) [x.x.0]|[@angular/cli](https://github.com/angular/angular-cli/releases)  ([@angular](https://github.com/angular/angular/releases)) [x.0.0]|[typescript](https://github.com/Microsoft/TypeScript/releases)|[ionic cli](https://www.npmjs.com/package/ionic) ([ionic](https://www.npmjs.com/package/ionic-angular))|[cordova](https://www.npmjs.com/package/cordova)|[vue-cli](https://github.com/vuejs/vue-cli/tags) ([vue](https://github.com/vuejs/vue/tags)) [x.x.0]|Comments|
|---|---|---|---|---|---|---|
|**node -v (npm -v)**|**ng -v**|**tsc -v**|**ionic -v**|**cordova -v**|**[vue --version](https://github.com/vuejs/vue-cli/tree/master)**||
|6.9.0 Boron (3.10.8) [2016.10]|1.4.9 (4.2.4) [2017.03]|2.3.3||||
|7.6.0 (4.1.2) [2017.02]|1.6.3 (5.1.0) [2017.11]|2.4.2|3.2.0 (3.9.2)|8.0.0|2.9.0 [2017.10]|v.7.6.0 on windows works with sass transpiler|
|8.11.1 Carbon (5.6.0) [2017.11]|1.7.3 (5.2.0)|2.5.3|3.2.0 (3.9.2)||2.9.3 (2.5.16) [2018.02]||
|10.1.0 (5.6.0) [2018.05]|6.0.0 (6.0.0) [2018.05]|2.7.2|(4.0.0)||3.0.0||
|10.5.0 (6.1.0) [2018.0X]|6.2.2 (6.1.0) [2018.09]|2.9.2|4.1.2 (4.0.0.beta7)||||

### .NET

|CLI|Cmd|Config|Environment|Category|
|---|---|---|---|---|
|MSTest|[mstest](https://msdn.microsoft.com/en-us/library/ms182489.aspx)|||Test Runner|
|MSBuild|[msbuild](https://docs.microsoft.com/en-us/visualstudio/msbuild/msbuild-command-line-reference)|[.Targets](https://docs.microsoft.com/en-us/visualstudio/msbuild/msbuild-dot-targets-files)||Builder|
|.NET Core|[dotnet](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x)|||Server side Framework|
|NuGet|[*-Package](https://docs.microsoft.com/en-us/nuget/tools/powershell-reference)|[NuGet.Config](https://docs.microsoft.com/en-us/nuget/schema/nuget-config-file) [project.json](https://docs.microsoft.com/en-us/nuget/schema/project-json) [packages.config](https://docs.microsoft.com/en-us/nuget/schema/packages-config)||Package Mgr|

#### Editors

|CLI|Cmd|Config|Environment|Category|
|---|---|---|---|---|
|[Visual Studio Code](https://code.visualstudio.com/)|code|||Editor|
|[Sublime Text](https://www.sublimetext.com/)|subl|||Editor|
|EditorConfig||[.editorconfig](http://editorconfig.org/#example-file)||Plugin|

### Other CLI Lists

* [agarrharr/awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps)
* [alebcay/awesome-shell](https://github.com/alebcay/awesome-shell)

### Articles

* 2017-09-17 [The Past, Present, and Future of the Angular CLI](https://blog.angular.io/the-past-present-and-future-of-the-angular-cli-13cf55e455f8)

The End
