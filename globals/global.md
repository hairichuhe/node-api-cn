<!-- YAML
added: v0.1.27
-->

<!-- type=global -->

* {Object} 全局的命名空间对象。

在浏览器中，顶层作用域就是全局作用域。
这意味着在浏览器中，如果在全局作用域内使用 `var something` 会定义一个全局变量。
在 Node.js 中则不同。
顶层作用域不是全局作用域；在 Node.js 模块中使用 `var something` 会是模块内部的。

