```sh
$ npm install && npm run lint

TypeError: Cannot read property 'name' of undefined
    at CallExpression.methodNames.find.item (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint-plugin-jest/rules/no-alias-methods.js:46:42)
    at Array.find (<anonymous>)
    at CallExpression (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint-plugin-jest/rules/no-alias-methods.js:45:40)
    at listeners.(anonymous function).forEach.listener (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/util/safe-emitter.js:45:58)
    at Array.forEach (<anonymous>)
    at Object.emit (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/util/safe-emitter.js:45:38)
    at NodeEventGenerator.applySelector (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/util/node-event-generator.js:251:26)
    at NodeEventGenerator.applySelectors (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/util/node-event-generator.js:280:22)
    at NodeEventGenerator.enterNode (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/util/node-event-generator.js:294:14)
    at CodePathAnalyzer.enterNode (/home/dandv/eslint-plugin-jest-bug/node_modules/eslint/lib/code-path-analysis/code-path-analyzer.js:632:23)
```
