>## 第一步：全局安装ESLInt,babel-eslint,eslint-plugin-html,eslint-plugin-react
```bash 
npm i babel-eslint eslint-plugin-html eslint-plugin-react -g
```
>## 第二步：在任意目录放置.eslintrc.js
>## 第三步：在vscode中的配置
```javascript
// eslint config start
    "eslint.options": {
        "configFile": "C:/Users/Administrator/.eslint/.eslintrc.js",
        "plugins": [
            "html",
            "react"
        ]
    },
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "html",
        "vue",
        {
            "language": "html",
            "autoFix": true
        },
        {
            "language": "vue",
            "autoFix": true
        }
    ],
    // 为了解决 [vue/no-parsing-error] Parsing error: x-invalid-end-tag. 报错
    "vetur.validation.template": false,
```