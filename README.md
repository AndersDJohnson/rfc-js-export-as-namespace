# Note: Now supported in [ES2020/TypeScript 3.8](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-8.html#export-star-as-namespace-syntax)

# rfc-js-export-as-namespace
A proposal for JS `export * as myName from 'my-file'` syntax for namespaced re-export.

```js
export * as myName from 'my-file'
```

equivalent to:

```js
import * as myName from 'my-file'

export { myName }
```
