>## 在vscode中的配置
```javascript
// eslint config start
    "eslint.options": {
        "configFile": "C:/Users/Administrator/.eslint/.eslintrc.js",
        "plugins": [
            "html"
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
```