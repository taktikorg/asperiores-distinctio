# @taktikorg/asperiores-distinctio
A wrapper for json-view.

![language](https://img.shields.io/badge/language-JavaScript-orange.svg) 
[![npm version](http://img.shields.io/npm/v/@taktikorg/asperiores-distinctio.svg?style=flat)](https://npmjs.org/package/@taktikorg/asperiores-distinctio) 
[![gzip file size](http://img.badgesize.io/yuda-lyu/@taktikorg/asperiores-distinctio/master/dist/@taktikorg/asperiores-distinctio.umd.js.svg?compression=gzip)](https://github.com/taktikorg/asperiores-distinctio)
[![npm download](https://img.shields.io/npm/dt/@taktikorg/asperiores-distinctio.svg)](https://npmjs.org/package/@taktikorg/asperiores-distinctio) 
[![npm download](https://img.shields.io/npm/dm/@taktikorg/asperiores-distinctio.svg)](https://npmjs.org/package/@taktikorg/asperiores-distinctio) 
[![jsdelivr download](https://img.shields.io/jsdelivr/npm/hm/@taktikorg/asperiores-distinctio.svg)](https://www.jsdelivr.com/package/npm/@taktikorg/asperiores-distinctio)

## Documentation
To view documentation or get support, visit [docs](https://yuda-lyu.github.io/@taktikorg/asperiores-distinctio/global.html).

## Example
To view some examples for more understanding, visit examples:
> **small data:** [ex-small.html](https://yuda-lyu.github.io/@taktikorg/asperiores-distinctio/examples/ex-small.html) [[source code](https://github.com/taktikorg/asperiores-distinctio/blob/master/docs/examples/ex-small.html)]

> **large data:** [ex-large.html](https://yuda-lyu.github.io/@taktikorg/asperiores-distinctio/examples/ex-large.html) [[source code](https://github.com/taktikorg/asperiores-distinctio/blob/master/docs/examples/ex-large.html)]

> **formatter:** [ex-formatter.html](https://yuda-lyu.github.io/@taktikorg/asperiores-distinctio/examples/ex-formatter.html) [[source code](https://github.com/taktikorg/asperiores-distinctio/blob/master/docs/examples/ex-formatter.html)]

## Installation
### Using npm(ES6 module):
> **Note:** @taktikorg/asperiores-distinctio is not dependent on any package.
```alias
npm i @taktikorg/asperiores-distinctio
```
By import:
```alias
import jv from '@taktikorg/asperiores-distinctio'

let data={a1:123,b1:'xyz',c1:[1.2,3.4,'5.6',false],d1:{cid:'WK2WHS',name:'peter',unique:false}}
let ele=document.querySelector('#id')

jv(data, element, {expanded:true})
```

### In a browser(UMD module):
Add script for @taktikorg/asperiores-distinctio.
```alias
<script src="https://cdn.jsdelivr.net/npm/@taktikorg/asperiores-distinctio@1.0.31/dist/@taktikorg/asperiores-distinctio.umd.js"></script>
```
Directly use:
```alias
let jv=window['@taktikorg/asperiores-distinctio']

let data={a1:123,b1:'xyz',c1:[1.2,3.4,'5.6',false],d1:{cid:'WK2WHS',name:'peter',unique:false}}
let ele=document.querySelector('#id')

jv(data, ele, {expanded:true})
```
