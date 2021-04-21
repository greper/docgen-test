
Run this script
```shell
npm run docgen
```

Will get this error
```shell
npm run docgen

> docgen-test@0.0.0 docgen
> vue-docgen -c docgen.config.js

(node:20776) UnhandledPromiseRejectionWarning: Error: Error parsing D:\Codes\fast-crud\docgen-test\src\components\jsx-test.jsx for @requires tags: Unterminated regular expression (9:27)
    at D:\Codes\fast-crud\docgen-test\node_modules\vue-docgen-cli\lib\getSources.js:135:27
    at step (D:\Codes\fast-crud\docgen-test\node_modules\vue-docgen-cli\lib\getSources.js:63:23)
    at Object.throw (D:\Codes\fast-crud\docgen-test\node_modules\vue-docgen-cli\lib\getSources.js:44:53)
    at rejected (D:\Codes\fast-crud\docgen-test\node_modules\vue-docgen-cli\lib\getSources.js:36:65)
(Use `node --trace-warnings ...` to show where the warning was created)
(node:20776) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). T
o terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 3)
(node:20776) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.

```
