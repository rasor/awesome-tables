## Awesome Angular Tables

### Compilers

|[@angular](https://github.com/angular/angular/releases)/compiler-cli|[typescript](https://github.com/Microsoft/TypeScript/releases)|Comments|
|---|---|---|
|>=2.3.1 <3.0.0|>=2.0.2 <2.3.0|
|>=4.0.0 <5.0.0|>=2.1.0 <2.4.0| currently latest in that range: 4.4.6 and 2.3.4|
|>=5.0.0 <6.0.0|>=2.4.2 <2.5.0|

#### Usage

package.json

```yaml
  "devDependencies": {
    "@angular/compiler-cli": "4.4.6",
    "typescript": "2.3.4",
```

*  [Source - see versionCombos](https://github.com/angular/angular-cli/blob/master/packages/%40angular/cli/upgrade/version.ts) 

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
