## cjs-notebook

This is notebook for using esm module in node freely.

### Usage

Place the esm modules in `src` directory and set `rollup.config.js` referencing [rollup input option](https://rollupjs.org/guide/en/#input). And run `yarn prepare`. Then make a javascript source file in `notebook` directory and use the modules in `src/cjs`, which are converted to commonjs.