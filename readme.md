# pkgroll multi platform

## How to reproduce
```shell
pnpm i
npm run build
```

## Expected behavior
there should be 2 files in dist:
- index.node.js
- index.browser.js

## Actual behavior
the files output:
- index.js
- index2.js
