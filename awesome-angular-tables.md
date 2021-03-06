## Awesome Angular Tables

### [Compiler ranges](awesome-cli-js.md#nvm-sets-of-tools)

|[@types/node](https://nodejs.org/en/download/releases)|[@angular/cli](https://github.com/angular/angular-cli/releases)|[@angular](https://github.com/angular/angular/releases)/compiler-cli|[typescript](https://github.com/Microsoft/TypeScript/releases)|Comments|
|---|---|---|---|---|
|node -v|ng -v||tsc -v|
||1.2.* |>=2.3.1 <3.0.0|>=2.0.2 <2.3.0|
|6.9+|1.4.* |>=4.0.0 <5.0.0|>=2.1.0 <2.4.0|cli 1.4.9 produces "core": "4.2.4", "typescript": "2.3.3"|
|6.9+|1.5.* |>=5.0.0 <5.1.0|>=2.4.2 <2.5.0|cli 1.5.0 produces "core": "5.0.0", "typescript": "2.4.2"|
|6.9+|1.6.* |>=5.1.0 <5.2.0|>=2.4.2 <2.6.0|cli 1.6.3 produces "core": "5.1.0", "typescript": "2.4.2"|
|6.9+|1.7.* |>=5.2.0 <6.0.0|>=2.4.2 <2.7.0|cli 1.7.3 produces "core": "5.2.0", "typescript": "2.5.3"|
|8.9+|6.0.* |>=6.0.0 <7.0.0|>=2.7.0 <2.8.0|cli 6.0.0 produces "core": "6.0.0", "typescript": "2.7.2"|
|x.x+| |>=7.0.0 <8.0.0|

#### Usage

Get dependencies from an Angular version that differs from you current CLI: 

```bash
# switch node version
nvm list
nvm use 6.9.0
# use non-global cli
npm install @angular/cli@1.7.3
ng new myNg520project
```

package.json

```yaml
  "dependencies": {
    "@angular/core": "^5.2.0",
    ...
  "devDependencies": {
    "@angular/cli": "~1.7.3",
    "@angular/compiler-cli": "^5.2.0",
    "@types/node": "~6.0.60",
    "typescript": "~2.5.3",
```

* [angular-cli dependency on typescript](https://github.com/angular/angular-cli/blob/master/packages/%40angular/cli/upgrade/version.ts) - scroll down to versionCombos
* [Version comparer (ng5 vs ng6)](https://github.com/cexbrayat/angular-cli-diff/compare/1.7.4...6.0.0) - scroll down to package.json
* [Upgrade to ng6](https://stackoverflow.com/questions/48970553/want-to-upgrade-project-from-angular-v5-to-angular-v6/49474334#49474334)

### APIs

* [Angular](https://angular.io/api/)

|Type|Name|
|---|---|
|[@](#-decorators)|Decorator|
|C|Class|
|D|Directive|
|E|Enum|
|F|Function|
|I|Interface|
|K|Const|
|P|Pipe|
|T|Type Alias|

### @ Decorators

|npm|Name|Properties|
|---|---|---|
|[@angular/core](https://angular.io/api/core/)|[@Component({})](https://angular.io/api/core/Component)|`changeDetection?: ChangeDetectionStrategy`<br/>`viewProviders?: Provider[]`<br/>`moduleId?: string`<br/>`templateUrl?: string`<br/>`template?: string`<br/>`styleUrls?: string[]`<br/>`styles?: string[]`<br/>`animations?: any[]`<br/>`encapsulation?: ViewEncapsulation`<br/>`interpolation?: [string, string]`<br/>`entryComponents?: `<code>Array&lt;Type&lt;any&gt;&brvbar;any[]&gt;</code><br/>`preserveWhitespaces?: boolean`<br/>`// inherited from core/Directive`<br/>`selector?: string`<br/>`inputs?: string[]`<br/>`outputs?: string[]`<br/>`host?: {[key: string]: string}`<br/>`providers?: Provider[]`<br/>`exportAs?: string`<br/>`queries?: {[key: string]: any}`|
|[@angular/core](https://angular.io/api/core/)|[@Directive({})](https://angular.io/api/core/Directive)|`selector?: string`<br/>`inputs?: string[]`<br/>`outputs?: string[]`<br/>`host?: {[key: string]: string}`<br/>`providers?: Provider[]`<br/>`exportAs?: string`<br/>`queries?: {[key: string]: any}`|
|[@angular/core](https://angular.io/api/core/)|[@Inject({})](https://angular.io/api/core/Inject)<br/>on parameters|`token: any`|
|[@angular/core](https://angular.io/api/core/)|[@Injectable()](https://angular.io/api/core/Injectable)||
|[@angular/core](https://angular.io/api/core/)|[@Input({})](https://angular.io/api/core/Input)|`bindingPropertyName?: string`|
|[@angular/core](https://angular.io/api/core/)|[@NgModule({})](https://angular.io/api/core/NgModule)|`providers?: Provider[]`<br/><code>declarations?: Array&lt;Type<any>&brvbar;any[]&gt;</code><br/><code>imports?:Array&lt;Type&lt;any&gt;&brvbar;ModuleWithProviders&brvbar;any[]&gt;</code><br/><code>exports?: Array&lt;Type&lt;any&gt;&brvbar;any[]&gt;</code><br/><code>entryComponents?: Array&lt;Type&lt;any&gt;&brvbar;any[]&gt;</code><br/><code>bootstrap?: Array&lt;Type&lt;any&gt;&brvbar;any[]&gt;</code><br/><code>schemas?: Array&lt;SchemaMetadata&brvbar;any[]&gt;</code><br/>`id?: string`|
|[@angular/core](https://angular.io/api/core/)|[@Optional()](https://angular.io/api/core/Optional)<br/>on parameters||
|[@angular/core](https://angular.io/api/core/)|[@Output({})](https://angular.io/api/core/Output)|`bindingPropertyName?: string`|
|[@angular/core](https://angular.io/api/core/)|[@Pipe({})](https://angular.io/api/core/Pipe)|`name: string`<br/>`pure?: boolean`|

## Links

* [Ionic Troubleshooting](https://ionicframework.com/docs/troubleshooting/)

The End
