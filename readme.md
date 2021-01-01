# code-point-at

> ES2015 [`String#codePointAt()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/codePointAt) [ponyfill](https://ponyfill.com)


## Install

```
$ npm install --save code-point-at
```


## Usage

```js
var codePointAt = require('code-point-at');

codePointAt('🐴');
//=> 128052

codePointAt('abc', 2);
//=> 99
```

## API

### codePointAt(input, [position])


---

<div align="center">
	<b>
		<a href="https://tidelift.com/subscription/pkg/npm-code-point-at?utm_source=npm-code-point-at&utm_medium=referral&utm_campaign=readme">Get professional support for this package with a Tidelift subscription</a>
	</b>
	<br>
	<sub>
		Tidelift helps make open source sustainable for maintainers while giving companies<br>assurances about security, maintenance, and licensing for their dependencies.
	</sub>
</div>
