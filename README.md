> ## 第一步：全局安装 eslint,babel-eslint,eslint-plugin-html,eslint-plugin-react,eslint-plugin-vue

```bash
npm i eslint babel-eslint eslint-plugin-html eslint-plugin-react eslint-plugin-vue -g
```

> ## 第二步：在任意目录放置.eslintrc.js
>
> ## 第三步：在vscode下载ESLint,Prettier - Code formatter,stylus,language-stylus,Vetur
>
> ## 第四步：在 vscode 中的配置

```javascript
// eslint config start
"editor.snippetSuggestions": "top",
// 粘贴自动格式化
"editor.formatOnPaste": true,
// 控制编辑器检测代码中的链接
"editor.links": true,
// 保存时自动格式化
"editor.formatOnSave": true,
// eslint config start
"eslint.autoFixOnSave": true,
"eslint.options": {
    "configFile": "你的目录/.eslintrc.js"
},
"eslint.validate": [
    "javascript",
    "javascriptreact",
    "html",
    "vue",
    {
        "language": "vue",
        "autoFix": true
    }
],
// prettier 格式化配置
"prettier.eslintIntegration": true,
"prettier.tabWidth": 2,
"prettier.useTabs": true,
"prettier.singleQuote": true,
"prettier.semi": false,
// vetur格式化配置
"vetur.format.defaultFormatterOptions": {
    "wrap_attributes": "force-aligned"
},
// 关闭vetur默认的验证
"vetur.validation.template": false,
"vetur.format.defaultFormatter.html": "none",
"vetur.format.defaultFormatter.css": "prettier",
"vetur.format.defaultFormatter.postcss": "prettier",
"vetur.format.defaultFormatter.scss": "prettier",
"vetur.format.defaultFormatter.less": "prettier",
"vetur.format.defaultFormatter.stylus": "stylus-supremacy",
"vetur.format.defaultFormatter.js": "prettier",
"vetur.format.defaultFormatter.ts": "prettier",
"stylusSupremacy.insertColons": false, // 是否插入冒号
"stylusSupremacy.insertSemicolons": false, // 是否插入分好
"stylusSupremacy.insertBraces": false, // 是否插入大括号
"stylusSupremacy.insertNewLineAroundImports": false, // import之后是否换行
"stylusSupremacy.insertNewLineAroundBlocks": false, // 两个选择器中是否换行
```
