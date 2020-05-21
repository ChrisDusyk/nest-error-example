# Nest error

This is a freshly created Nest application, just scaffolded with `nest new error-project`.

## Reproduce Error

1. Clone repo
1. Run `yarn` to install dependencies
1. Run `yarn run start:dev`

Result: This error appears

```terminal
[11:14:47 a.m.] Starting compilation in watch mode...

[11:14:52 a.m.] Found 0 errors. Watching for file changes.

internal/modules/cjs/loader.js:625
  throw e;
  ^

Error: No valid exports main found for 'C:\Personal Code\error-project\node_modules\uuid'
    at resolveExportsTarget (internal/modules/cjs/loader.js:622:9)
    at applyExports (internal/modules/cjs/loader.js:499:14)
    at resolveExports (internal/modules/cjs/loader.js:548:12)
    at Function.Module._findPath (internal/modules/cjs/loader.js:654:22)
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:953:27)
    at Function.Module._load (internal/modules/cjs/loader.js:859:27)
    at Module.require (internal/modules/cjs/loader.js:1028:19)
    at require (internal/modules/cjs/helpers.js:72:18)
    at Object.<anonymous> (C:\Personal Code\error-project\node_modules\@nestjs\common\decorators\core\injectable.decorator.js:3:16)
    at Module._compile (internal/modules/cjs/loader.js:1139:30) {
  code: 'MODULE_NOT_FOUND'
}
```
