1. `npm install --save-dev @babel/core @babel/cli @babel/preset-env @babel/node`
2. `npm install --save @babel/polyfill`
3. 项目跟目录创建文件 babel.config.js
4. babel.config.js 文件内容如下代码
5. 通过` npx babel-node index.js` 执行代码
```js
const presets = [
["@babel/env", {
targets: {
edge: "17",
firefox: "60",
chrome: "67",
safari: "11.1"
}
}]
];
module.exports = { presets };
```