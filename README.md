# rfc-js-export-as-namespace
A proposal for JS `export * as myName from 'my-file'` syntax for namespaced re-export.

```js
export * as myName from 'my-file'
```

equivalent to:

```js
import * as myName from 'my-file'

export myName
```
