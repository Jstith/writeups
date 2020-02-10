__Messy JS!__
=============

By: _Jstith_

## Question:

```
Take a look at the Javascript file. Can you deobfuscate it and find the flag?
```

```javascript
var _0x3b82=['\x52\x46\x52\x53\x54\x30\x4e\x4c\x55\x79\x45\x3d','\x52\x32\x56\x30\x51\x32\x39\x31\x62\x6e\x51\x3d','\x55\x32\x46\x35\x53\x47\x56\x73\x62\x47\x38\x3d'];(function(_0x498505,_0x22bc87){var _0x3a4ef1=function(_0xe51f20){while(--_0xe51f20){_0x498505['push'](_0x498505['shift']());}};_0x3a4ef1(++_0x22bc87);}(_0x3b82,0x1db));var _0x3517=function(_0x418271,_0x3047c5){_0x418271=_0x418271-0x0;var _0x53d6e3=_0x3b82[_0x418271];if(_0x3517['sOXwmv']===undefined){(function(){var _0x4f45d5=function(){var _0x36bf25;try{_0x36bf25=Function('return\x20(function()\x20'+'{}.constructor(\x22return\x20this\x22)(\x20)'+');')();}catch(_0x2291db){_0x36bf25=window;}return _0x36bf25;};var _0x4d3009=_0x4f45d5();var _0x5f482e='ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=';_0x4d3009['atob']||(_0x4d3009['atob']=function(_0x278f59){var _0x49524a=String(_0x278f59)['replace'](/=+$/,'');for(var _0x5b340d=0x0,_0x14c5b1,_0x4c1427,_0x10efa8=0x0,_0x2b3233='';_0x4c1427=_0x49524a['charAt'](_0x10efa8++);~_0x4c1427&&(_0x14c5b1=_0x5b340d%0x4?_0x14c5b1*0x40+_0x4c1427:_0x4c1427,_0x5b340d++%0x4)?_0x2b3233+=String['fromCharCode'](0xff&_0x14c5b1>>(-0x2*_0x5b340d&0x6)):0x0){_0x4c1427=_0x5f482e['indexOf'](_0x4c1427);}return _0x2b3233;});}());_0x3517['nllZVK']=function(_0x4c256a){var _0x3d9263=atob(_0x4c256a);var _0x45cd6f=[];for(var _0x24c5f6=0x0,_0x2837be=_0x3d9263['length'];_0x24c5f6<_0x2837be;_0x24c5f6++){_0x45cd6f+='%'+('00'+_0x3d9263['charCodeAt'](_0x24c5f6)['toString'](0x10))['slice'](-0x2);}return decodeURIComponent(_0x45cd6f);};_0x3517['JlntDz']={};_0x3517['sOXwmv']=!![];}var _0x1eb3b6=_0x3517['JlntDz'][_0x418271];if(_0x1eb3b6===undefined){_0x53d6e3=_0x3517['nllZVK'](_0x53d6e3);_0x3517['JlntDz'][_0x418271]=_0x53d6e3;}else{_0x53d6e3=_0x1eb3b6;}return _0x53d6e3;};function _0x4f0f8a(_0x114d84){var _0x2be954=0x0;this['\x53\x61\x79\x48\x65\x6c\x6c\x6f']=function(_0x113df4){_0x2be954++;alert(_0x114d84+_0x113df4);};this[_0x3517('0x0')]=function(){return _0x2be954;};}var _0x4787b9=new _0x4f0f8a('\x46\x6c\x61\x67\x20\x3a\x20');_0x4787b9[_0x3517('0x1')](_0x3517('0x2'));
```

## Solution:

Yikes! That's a mess. At first glance, this file tells us nothing. However, there's a clue in the question. To `deobfuscate` means to take a program that is hard to understand and make it simple. People like to do this with javascript to hide functions they don't want users seeing. FOrtunately for us, there are tools to deobfuscate the code. Head on over [deobfuscate javascript](http://deobfuscatejavascript.com/#) and paste in the file. A bubble will pop up saying `Flag : DTROCKS!`.

```
DTROCKS!
```