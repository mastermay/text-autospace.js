text-autospace.js
=================

自动在中英文间添加空白符，优化中文排版。

使用方法及演示参考[demo](http://mastermay.github.io/text-autospace.js/)

## fork 后修改了啥?

主要是修复 bug. 

- 原版本不能正确处理右定界符, 且错误地划分了 `,.?!` 等符号的类型. 
- 去掉了英文单双引号. 因为难以简单辨别它们是左定界符还是右定界符.
- 改 `$(document).on("ready"...)` 为 `$(document).ready(...)`. 