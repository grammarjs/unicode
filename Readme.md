
# grammarjs-unicode

![experimental](http://img.shields.io/badge/status-experimental-orange.svg?style=flat)

Unicode plugin.

## Example

```js
var Grammar = require('grammarjs-grammar');
var unicode = require('grammarjs-unicode');
var grammar = new Grammar('my-grammar');
grammar.use(unicode());
```