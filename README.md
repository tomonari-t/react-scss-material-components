#

## To use SCSS

1. Install `sass-loader`, `node-sass`

```bash
% npm install --save-dev sass-loader node-sass
```

2. Edit webpack.config.*.js

Find `test: /\.css$/` and rewrite `test: /\.scss$/`.

Add below after css-loader

```js
// config/webpack.config.dev.js
// config/webpack.config.prod.js

{
  loader: require.resolve('sass-loader'),
},

```

## To use material-components

1. Install `RMWC`

```bash
% npm i rmwc --save
```

2.