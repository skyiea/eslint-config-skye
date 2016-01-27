# eslint-config-skye

ESLint [shareable config](http://eslint.org/docs/developer-guide/shareable-configs.html) by [Skye](https://github.com/skyiea)


## Install

```
$ npm install eslint-config-skye -D
```

You'll also need Babel's ESLint [parser](https://github.com/babel/babel-eslint) and [plugin](https://github.com/babel/eslint-plugin-babel) installed:

```
$ npm install babel-eslint eslint-plugin-babel -D
```


## Usage

Add some ESLint config to your `package.json`:

```json
{
	"eslintConfig": {
		"extends": "skye"
	}
}
```

Or to `.eslintrc`:

```json
{
	"extends": "skye"
}
```