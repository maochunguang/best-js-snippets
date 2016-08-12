## best-js-snippets package
this is the best **atom snippets** of js that include **es6**, **express** ,**String**, **nodejs-fs**,**nodejs-utils** ,**dom**, and so on.

*Note: this is a fork of [turbo-javascript](extrabacon/atom-turbo-javascript) that uses arrow functions by default and adds  more snippets for express,node-fs,dom-child and so on.*

### special statement
*Note: the most common modules I use the shorCut to improve efficiency,but some uncommon modules are not necessary for us.So,I decided to use fullName to autocomplete uncommon modules .*

### nodejs-net,node-http,nodejs-dns,nodejs-crypto ,nodejs-stream and so on
```
net.
http.
dns.
crypto.
stream.
os.
queryString.
readline.
vm.
zlib.

// and so on
```


### lodash snippets

#### `_chunk⇥`,`_concat⇥` ,`_drop⇥`and so on
```
_.chunk(${1:array},${2:size});
_.concat(${1:array},${2:array2});
_.drop(${1:array},${2:size});

// and so on
```

### js-Math snippets

#### `Math.⇥`
```
Math.abs(${1:value})
Math.ceil(${1:value})
Math.floor(${1:value})
Math.max(${1:value})

// and so on
```
### js-Number snippets

#### `Number.⇥`
```
Number.isNaN()
Number.isFinite()
Number.parseInt(${1:num})

// and so on
```

### nodejs-assert snippets

#### `assert.⇥`
```
assert.equal(${1:actual}, ${2:expected});
assert.notEqual(${1:actual}, ${2:expected});
assert.ok(${1:actual});
assert.ifError(${1:actual});

// and so on
```

### nodejs-process snippets

#### `process.⇥`
```
process.abort()
process.arch
process.uptime()

// and so on
```
### nodejs-path snippets

#### `path.⇥`
```
path.basename('${1:pathname}')
path.dirname('${1:pathname}')
path.format(${1:pathname})
path.join('${1:pathname}','${2:name}')
path.parse(${1:pathname})
// and so on
```

### Express snippets

#### `aget⇥`,`apos⇥`,`aall⇥`,`adel⇥`, `aput⇥`
```js
app.get('${1:path}', (req, res, next) => {
});
......
app.put('${1:path}', (req, res, next) => {
});
```
#### `rqa⇥`,`rqb⇥`,`rqc⇥`,`rqg⇥`,`rqh⇥`,`rqi⇥`,
```js
var ${1:body} = req.accepts("${2:name}");
var ${1:body} = req.body;
var ${1:cookie} = req.cookie;
var ${1:key} = req.get("${2:name}");
var ${1:host} = req.hostname;
var ${1:ip} = req.ip;
```
#### `rqm⇥`,`rqp⇥`,`rqpa⇥`,`rqpr⇥`,`rqpt⇥`
```js
var ${1:method} = req.method;
var ${1:param} = req.params;
var ${1:path} = req.path;
var ${1:protocol} = req.protocol;
var ${1:path} = req.path;
```

### String snippets

#### `sle⇥`,`chat⇥`,`charCodeAt⇥`,`includes⇥`,an so on,**method fullName**  string method
```js
${1:value}.length;
${1:value}.charAt(${2:index});
${1:value}.charCodeAt(${2:index});
${1:value}.concat(${2:index});
${1:value}.includes(${2:index});
${1:value}.indexOf(${2:index});
${1:value}.lastIndexOf(${2:index});
${1:value}.startsWith(${2:index});
${1:value}.endsWith(${2:index});
${1:value}.localeCompare(${2:index});
${1:value}.match(${2:index});
${1:value}.replace(${1:str}, ${2:reg}, '${3:newStr}');
${1:value}.repeat(${2:index});
${1:value}.search(${2:index});
${1:value}.slice(${2:begin},${3:end});
${1:value}.split(${2:index});
${1:value}.substr(${2:start},${3:length});
${1:value}.substring(${2:begin},${3:end});
${1:value}.toUpperCase();
${1:value}.toLowerCase();
${1:value}.trim();
${1:value}.toString();
```
### nodejs-fs snippets

#### `fswrite⇥`,`fswrites⇥`,`fsread⇥`,`fsreads⇥`,`fsexists⇥`,`fsexistss⇥`
```js
fs.writeFile(${1:filename}, ${2:content});
fs.writeFileSync(${1:filename}, ${2:content});
fs.readFile(${1:filename}, ${2:charset});
fs.readFileSync(${1:filename}, ${2:charset});
fs.exists(${0:filename});
fs.existsSync(${0:filename});
```

### nodejs-utils snippets

#### `isa⇥`,`isbo⇥`,`isbu⇥`,`isd⇥`,`ise⇥`,`isf⇥`,`isn⇥`,`isnm⇥`,`iso⇥`,`isr⇥`,`iss⇥`,`issy⇥`,`isun⇥`, util typeof Object
```js
util.isArray(${1:name});
util.isBoolean(${1:name});
util.isBuffer(${1:name});
util.isDate(${1:name});
util.isError(${1:name});
util.isFunction(${1:name});
util.isNull(${1:name});
util.isNumber(${1:name});
util.isObject(${1:name});
util.isRegExp(${1:name});
util.isString(${1:name});
util.isSymbol(${1:name});
util.isUndefined(${1:name});
```

### Declarations

#### `v⇥`  `ve⇥` ,var statement
```js
var ${1:name};
var ${1:name} = ${2:value};
```

#### `l⇥` ,`le⇥` let statement
```js
let ${1:name};
let ${1:name} = ${2:value};
```

#### `co⇥` ,`coe⇥`,`cos⇥`  const statement
```js
const ${1:name};
const ${1:name} = ${2:value};
const ${1:name} = Symbol('${1:name}');
```

### Flow Control

#### `if⇥`,`el⇥` , `ife⇥` ,`ei⇥` if else statement
```js
//if⇥
if (${1:condition}) {
  ${0}
}
//el⇥
else {
  ${0}
}
//ife⇥
if (${1:condition}) {
  ${2}
} else {
  ${3}
}
//ei⇥
else if (${1:condition}) {
  ${0}
}
```

#### `fl⇥` for loop
```js
for (let ${1:i} = 0; ${1:i} < ${2:iterable}${3:.length}; ${1:i}++) {
  ${4}
}
```

#### `fi⇥` for in loop
```js
for (let ${1:key} in ${2:source}) {
  if (${2:source}.hasOwnProperty(${1:key})) {
    ${0}
  }
}
```

#### `fo⇥` for of loop (ES6)
```js
for (let ${1:key} of ${2:source}) {
  ${0}
}
```

#### `wl⇥` while loop
```js
while (${1:condition}) {
  ${0}
}
```

#### `tc⇥` try/catch
```js
try {
  ${1}
} catch (${2:err}) {
  ${3}
}
```

#### `tf⇥` try/finally
```js
try {
 ${1}
} finally {
 ${2}
}
```

#### `tcf⇥` try/catch/finally
```js
try {
  ${1}
} catch (${2:err}) {
  ${3}
} finally {
  ${4}
}
```

### Functions

#### `f⇥` anonymous function
```js
function (${1:arguments}) {${0}}
```

#### `fn⇥` named function
```js
function ${1:name}(${2:arguments}) {
  ${0}
}
```

#### `iife⇥` immediately-invoked function expression (IIFE)
```js
((${1:arguments}) => {
  ${0}
})(${2});
```

#### `fa⇥` ,`fb⇥`,`fc⇥`, function apply,bind,call
```js
${1:fn}.apply(${2:this}, ${3:arguments})
${1:fn}.bind(${2:this}, ${3:arguments})
${1:fn}.call(${2:this}, ${3:arguments})
```

#### `af⇥`,`afb⇥`  arrow function (ES6)
```js
//`af⇥`
${1:(arguments)} => ${2:statement}
//`afb⇥`
${1:(arguments)} => {
\t${0}
}
```

#### `gf⇥`,`gfn⇥` generator function (ES6)
```js
function* (${1:arguments}) {
  ${0}
}
function* ${1:name}(${1:arguments}) {
  ${0}
}
```

### Iterables

#### `fe⇥` forEach loop (chainable)
```js
${1:iterable}.forEach((${2:item}) => {
  ${0}
});
```

#### `map⇥` map function (chainable)
```js
${1:iterable}.map((${2:item}) => {
  ${0}
});
```

#### `reduce⇥` reduce function (chainable)
```js
${1:iterable}.reduce((${2:previous}, ${3:current}) => {
  ${0}
}${4:, initial});
```

#### `filter⇥` filter function (chainable)
```js
${1:iterable}.filter((${2:item}) => {
  ${0}
});
```

#### `find⇥` ES6 find function (chainable)
```js
${1:iterable}.find((${2:item}) => {
  ${0}
});
```

### Objects and classes

#### `c⇥` class (ES6)
```js
class ${1:name} {
  constructor(${2:arguments}) {
    ${0}
  }
}
```

#### `cex⇥` child class (ES6)
```js
class ${1:name} extends ${2:base} {
  constructor(${2:arguments}) {
    super(${2:arguments})
    ${0}
  }
}
```

#### `cf⇥` class function (ES6)

```js
{$1:name}({$2:arguments}) {
  ${0}
}
```

#### `kv⇥` key/value pair
Javascript:
```js
${1:key}: ${2:'value'}
```

#### `m⇥` method (ES6 syntax)
```js
${1:method}(${2:arguments}) {
  ${0}
}
```

#### `get⇥`,`set⇥`  getter ,setter (ES6 syntax)
```js
get ${1:property}() {
  ${0}
}
set ${1:property}(${2:value}) {
  ${0}
}
```

#### `gs⇥` getter and setter (ES6 syntax)
```js
get ${1:property}() {
  ${0}
}
set ${1:property}(${2:value}) {

}
```

#### `proto⇥` prototype method (chainable)
```js
${1:Class}.prototype.${2:methodName} = function (${3:arguments}) {
  ${0}
};
```

### Returning values

#### `r⇥`,`rth⇥`,`rn⇥`,`rt⇥` ,`rf⇥` ,`r0⇥`, `r-1⇥` return
```js
return ${0};    //`r⇥`
return this;    //`rth⇥`
return null;    //`rn⇥`
return true;    //`rt⇥`
return false;   //`rf⇥`
return 0;       //`r0⇥`
return -1;      //`r-1⇥`

```

### Types

#### `S⇥` String
#### `N⇥` Number
#### `O⇥` Object
#### `A⇥` Array
#### `D⇥` Date
#### `Rx⇥` RegExp

#### `tof⇥` typeof comparison
```js
typeof ${1:source} === '${2:undefined}'
```

#### `iof⇥` instanceof comparison
```js
${1:source} instanceof ${2:Object}
```

### Promises

#### `rp⇥` return Promise (ES6)
```js
return new Promise((resolve, reject) => {
  ${0}
});
```

#### `p⇥` new Promise (ES6)
```js
new Promise((resolve, reject) => {
  ${0}
})
```

#### `then⇥` Promise.then (chainable)
```js
${1:promise}.then((${2:value}) => {
  ${0}
});
```

#### `catch⇥` Promise.catch (chainable)
```js
${1:promise}.catch((${2:err}) => {
  ${0}
});
```

### ES6 modules

#### `ex⇥` module export
```js
export ${1:member};
```

#### `im⇥` module import
```js
import ${1:*} from '${2:module}';
```

#### `ima⇥` module import as
```js
import ${1:*} as ${2:name} from '${3:module}';
```

#### `imn⇥` named module import
```js
import \{ ${1:name} \} from '${2:module}';
```

### BDD testing (Mocha, Jasmine, etc.)

#### `desc⇥` describe
```js
describe('${1:description}', () => {
  ${0}
});
```

#### `its⇥` synchronous "it"
```js
it('${1:description}', () => {
  ${0}
});
```

#### `ita⇥` asynchronous "it"
```js
it('${1:description}', (done) => {
  ${0}
});
```

#### `bef⇥` before
```js
before(() => {
  ${0}
});
```

#### `befe⇥` beforeEach
```js
beforeEach(() => {
  ${0}
});
```

#### `aft⇥` after
```js
after(() => {
  ${0}
});
```

#### `afte⇥` afterEach
```js
afterEach(() => {
  ${0}
});
```

### Console

#### `cl⇥`,`cll⇥`, `ce⇥`,`ct⇥`,`cte⇥`,`cw⇥`  console.log
```js
console.log('${1:title}', ${2:$1}$0);
console.log(${0});
console.error(${0});
console.time(${0});
console.timeEnd(${0});
console.warn(${0});
```


### Timers

#### `st⇥`,`si⇥` ,`sim⇥` setTimeout,setInterval
```js
//`st⇥`
setTimeout(() => {
  ${0}
}, ${1:delay});
//`si⇥`
setTimeout(() => {
  ${0}
}, ${1:delay});
//`sim⇥`
setImmediate(() => {
  ${0}
});
```

### DOM specifics

#### `ae⇥` addEventListener
```js
${1:document}.addEventListener('${2:event}', function (e) {
  ${0}
});
```
#### `ga⇥`,`ra⇥` , `ac⇥`,`rc⇥`  get,setAttribute,append,removeChild
```js
${1:document}.getAttribute('${2:id}')
${1:document}.removeAttribute('${2:attr}');
${1:document}.appendChild(${2:elem});
${1:document}.removeChild(${2:elem});
```

#### `gi⇥` getElementById
```js
${1:document}.getElementById('${2:id}')
```

#### `gc⇥` getElementsByClassName
```js
Array.from(${1:document}.getElementsByClassName('${2:class}'))
```
`Array.from` polyfill required for ES5

#### `gt⇥` getElementsByTagName
```js
Array.from(${1:document}.getElementsByTagName('${2:tag}'))
```
`Array.from` polyfill required for ES5

#### `qs⇥` querySelector
```js
${1:document}.querySelector('${2:selector}')
```

#### `qsa⇥` querySelectorAll
```js
Array.from(${1:document}.querySelectorAll('${2:selector}'))
```
`Array.from` polyfill required for ES5


### Node.js specifics

#### `cb⇥` Node.js style callback
```js
(err${1:, value}) => {${0}}
```

#### `re⇥` require a module
```js
require('${1:module}');
```

#### `em⇥` export member
```js
exports.${1:name} = ${2:value};
```

#### `me⇥` module.exports
```js
module.exports = ${1:name};
```

#### `on⇥` attach an event handler (chainable)
```js
${1:emitter}.on('${2:event}', (${3:arguments}) => {
  ${0}
});
```

### Miscellaneous

#### `us⇥` use strict
```js
'use strict';
```

# License

The MIT License (MIT)
Copyright (c) 2016 maochunguang
