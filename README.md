> ## 第一步：全局安装 eslint,babel-eslint,eslint-plugin-html,eslint-plugin-react,eslint-plugin-vue

```bash
npm i eslint babel-eslint eslint-plugin-html eslint-plugin-react eslint-plugin-vue -g
```

> ## 第二步：在任意目录放置.eslintrc.js
>
> ## 第三步：在 vscode 下载 ESLint,Prettier - Code formatter,stylus,language-stylus,Vetur
>
> ## 第四步：在 vscode 中的配置

```json
// 编辑器默认格式化由prettier-vscode
{
	// 粘贴自动格式化
	"editor.formatOnPaste": true,
	// 保存时自动格式化
	"editor.formatOnSave": true,
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[jsonc]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	// eslint 配置 
	"eslint.autoFixOnSave": true,
	"eslint.options": {
		"configFile": "C:/Users/Mark/.eslint/.eslintrc.js"
	},
	"eslint.validate": ["javascript", "javascriptreact", "html", "vue"],
	"vetur.format.defaultFormatter.js": "prettier-eslint",
	"vetur.format.defaultFormatterOptions": {
		"prettier": {
			// prettier 格式化配置
			"eslintIntegration": true,
			"semi": false,
			"tabWidth": 2,
			"useTabs": true,
			"singleQuote": false
		},
		"prettyhtml": {
			"printWidth": 100, // No line exceeds 100 characters
			"singleQuote": false // Prefer double quotes over single quotes
		}
	},
	// prettier配置
	"prettier.eslintIntegration": true,
	"prettier.semi": false,
	"prettier.tabWidth": 2,
	"prettier.useTabs": true,
	"prettier.singleQuote": false,
	"stylusSupremacy.insertColons": false, // 是否插入冒号
	"stylusSupremacy.insertSemicolons": false, // 是否插入分好
	"stylusSupremacy.insertBraces": false, // 是否插入大括号
	"stylusSupremacy.insertNewLineAroundImports": false, // import之后是否换行
	"stylusSupremacy.insertNewLineAroundBlocks": false
}
```
