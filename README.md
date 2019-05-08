Webpack Config File in TypeScript Demo
======================================

Use typescript to write webpack config file.

基本上跟js版没什么区别，只要webpack加上`--config-register ts-node/register`即可。

注意：也可以不用加`--config-register ts-node/register`，但是必须安装`ts-node`，否则处理不了。似乎webpack会自己找ts-node。

```
npm install
npm run webpack
npm run webpack-dev-server
```
