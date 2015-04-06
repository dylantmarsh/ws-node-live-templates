# ws-node-live-templates
Live Templates for Node.js/Express development in WebStorm

require
---
Abbreviation: require

Description: Require a node.js module

```js
var $module$ = require('$module$');
$END$
```

get
---
Abbreviation: get

Description: Express get router

```js
app.get('/$route$', function(req, res) {
    $END$
});
```

post
---
Abbreviation: post

Description: Express post router

```js
app.post('/$route$', function(req, res) {
    $END$
});
```

put
---
Abbreviation: put

Description: Express put router

```js
app.put('/$route$', function(req, res) {
    $END$
});
```

module (version 1)
---
Abbreviation: module

Description: Generate a module

```js
var $module_name$ = {
    $END$
};

module.exports = $module_name$;
```

module (version 2)
---
Abbreviation: module

Description: Generate a module

```js
module.exports = {
    $END$
};
```
