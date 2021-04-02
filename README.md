# ob-jsjiami

> decode jsjiami.com encoding javascript code



http://jsjiami.com/




## Step

1、format your code, https://beautifier.io/

2、find out the root dictionary

3、replace it in `index.js`

4、run it

```
node index.js
```

## Notice

v5 通过测试

* 部分代码可能存在转义问题


此类定义对象，需要重写 findObj 函数 -> findObjPlus

```
var _0x33598c = {};
_0x33598c[_0x1f4b('0x1b5')] = function(_0x29dfdf, _0x290572) {
    return _0x29dfdf < _0x290572;
};
_0x33598c[_0x1f4b('0x14b')] = function(_0xa955e7, _0x196b9f) {
    return _0xa955e7 === _0x196b9f;
};
_0x33598c[_0x1f4b('0x17b')] = function(_0x432c3d, _0x216369) {
    return _0x432c3d(_0x216369);
};
_0x33598c[_0x1f4b('0x21f')] = function(_0x385852, _0x5683d1) {
    return _0x385852 === _0x5683d1;
};
var _0x5ab718 = _0x33598c;

```


## Finally

IF YOU KNOW BABEL AST, TRY TO USE IT. 

## LICENSE

Copyright (c) Terry Cai. Licensed under the MIT license.
