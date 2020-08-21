(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var l;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ca="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var fa=da(this);function n(a,b){if(b)a:{var c=fa;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ca(c,a,{configurable:!0,writable:!0,value:b})}}
n("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.i=f;ca(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.i};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
n("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=fa[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ca(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ha(aa(this))}})}return a});
function ha(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function p(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ia(a){if(!(a instanceof Array)){a=p(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
function ja(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var ka="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)ja(d,e)&&(a[e]=d[e])}return a};
n("Object.assign",function(a){return a||ka});
var ma="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},na=function(){function a(){function c(){}
new c;Reflect.construct(c,[],function(){});
return new c instanceof c}
if("undefined"!=typeof Reflect&&Reflect.construct){if(a())return Reflect.construct;var b=Reflect.construct;return function(c,d,e){c=b(c,d);e&&Reflect.setPrototypeOf(c,e.prototype);return c}}return function(c,d,e){void 0===e&&(e=c);
e=ma(e.prototype||Object.prototype);return Function.prototype.apply.call(c,e,d)||e}}(),oa;
if("function"==typeof Object.setPrototypeOf)oa=Object.setPrototypeOf;else{var pa;a:{var qa={a:!0},ra={};try{ra.__proto__=qa;pa=ra.a;break a}catch(a){}pa=!1}oa=pa?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var sa=oa;
function t(a,b){a.prototype=ma(b.prototype);a.prototype.constructor=a;if(sa)sa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.Y=b.prototype}
function ta(){this.B=!1;this.m=null;this.j=void 0;this.i=1;this.o=this.s=0;this.v=this.l=null}
function ua(a){if(a.B)throw new TypeError("Generator is already running");a.B=!0}
ta.prototype.N=function(a){this.j=a};
function va(a,b){a.l={Pb:b,Vb:!0};a.i=a.s||a.o}
ta.prototype.return=function(a){this.l={return:a};this.i=this.o};
function v(a,b,c){a.i=c;return{value:b}}
ta.prototype.u=function(a){this.i=a};
function wa(a,b,c){a.s=b;void 0!=c&&(a.o=c)}
function xa(a,b){a.i=b;a.s=0}
function ya(a){a.s=0;var b=a.l.Pb;a.l=null;return b}
function Ba(a){a.v=[a.l];a.s=0;a.o=0}
function Ca(a){var b=a.v.splice(0)[0];(b=a.l=a.l||b)?b.Vb?a.i=a.s||a.o:void 0!=b.u&&a.o<b.u?(a.i=b.u,a.l=null):a.i=a.o:a.i=0}
function Da(a){this.i=new ta;this.j=a}
function Ea(a,b){ua(a.i);var c=a.i.m;if(c)return Fa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.i.return);
a.i.return(b);return Ha(a)}
function Fa(a,b,c,d){try{var e=b.call(a.i.m,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.i.B=!1,e;var f=e.value}catch(g){return a.i.m=null,va(a.i,g),Ha(a)}a.i.m=null;d.call(a.i,f);return Ha(a)}
function Ha(a){for(;a.i.i;)try{var b=a.j(a.i);if(b)return a.i.B=!1,{value:b.value,done:!1}}catch(c){a.i.j=void 0,va(a.i,c)}a.i.B=!1;if(a.i.l){b=a.i.l;a.i.l=null;if(b.Vb)throw b.Pb;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ia(a){this.next=function(b){ua(a.i);a.i.m?b=Fa(a,a.i.m.next,b,a.i.N):(a.i.N(b),b=Ha(a));return b};
this.throw=function(b){ua(a.i);a.i.m?b=Fa(a,a.i.m["throw"],b,a.i.N):(va(a.i,b),b=Ha(a));return b};
this.return=function(b){return Ea(a,b)};
this[Symbol.iterator]=function(){return this}}
function Ja(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function w(a){return Ja(new Ia(new Da(a)))}
function Ka(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
n("Reflect",function(a){return a?a:{}});
n("Reflect.construct",function(){return na});
n("Reflect.setPrototypeOf",function(a){return a?a:sa?function(b,c){try{return sa(b,c),!0}catch(d){return!1}}:null});
n("Promise",function(a){function b(g){this.i=0;this.l=void 0;this.j=[];this.B=!1;var h=this.m();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.i=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.j=function(g){if(null==this.i){this.i=[];var h=this;this.l(function(){h.o()})}this.i.push(g)};
var e=fa.setTimeout;c.prototype.l=function(g){e(g,0)};
c.prototype.o=function(){for(;this.i&&this.i.length;){var g=this.i;this.i=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(m){this.m(m)}}}this.i=null};
c.prototype.m=function(g){this.l(function(){throw g;})};
b.prototype.m=function(){function g(m){return function(q){k||(k=!0,m.call(h,q))}}
var h=this,k=!1;return{resolve:g(this.K),reject:g(this.o)}};
b.prototype.K=function(g){if(g===this)this.o(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.R(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.J(g):this.s(g)}};
b.prototype.J=function(g){var h=void 0;try{h=g.then}catch(k){this.o(k);return}"function"==typeof h?this.T(h,g):this.s(g)};
b.prototype.o=function(g){this.N(2,g)};
b.prototype.s=function(g){this.N(1,g)};
b.prototype.N=function(g,h){if(0!=this.i)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.i);this.i=g;this.l=h;2===this.i&&this.P();this.v()};
b.prototype.P=function(){var g=this;e(function(){if(g.F()){var h=fa.console;"undefined"!==typeof h&&h.error(g.l)}},1)};
b.prototype.F=function(){if(this.B)return!1;var g=fa.CustomEvent,h=fa.Event,k=fa.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=fa.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.l;return k(g)};
b.prototype.v=function(){if(null!=this.j){for(var g=0;g<this.j.length;++g)f.j(this.j[g]);this.j=null}};
var f=new c;b.prototype.R=function(g){var h=this.m();g.Ua(h.resolve,h.reject)};
b.prototype.T=function(g,h){var k=this.m();try{g.call(h,k.resolve,k.reject)}catch(m){k.reject(m)}};
b.prototype.then=function(g,h){function k(x,u){return"function"==typeof x?function(A){try{m(x(A))}catch(D){q(D)}}:u}
var m,q,r=new b(function(x,u){m=x;q=u});
this.Ua(k(g,m),k(h,q));return r};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.Ua=function(g,h){function k(){switch(m.i){case 1:g(m.l);break;case 2:h(m.l);break;default:throw Error("Unexpected state: "+m.i);}}
var m=this;null==this.j?f.j(k):this.j.push(k);this.B=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var m=p(g),q=m.next();!q.done;q=m.next())d(q.value).Ua(h,k)})};
b.all=function(g){var h=p(g),k=h.next();return k.done?d([]):new b(function(m,q){function r(A){return function(D){x[A]=D;u--;0==u&&m(x)}}
var x=[],u=0;do x.push(void 0),u++,d(k.value).Ua(r(x.length-1),q),k=h.next();while(!k.done)})};
return b});
n("WeakMap",function(a){function b(k){this.i=(h+=Math.random()+1).toString();if(k){k=p(k);for(var m;!(m=k.next()).done;)m=m.value,this.set(m[0],m[1])}}
function c(){}
function d(k){var m=typeof k;return"object"===m&&null!==k||"function"===m}
function e(k){if(!ja(k,g)){var m=new c;ca(k,g,{value:m})}}
function f(k){var m=Object[k];m&&(Object[k]=function(q){if(q instanceof c)return q;Object.isExtensible(q)&&e(q);return m(q)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),m=Object.seal({}),q=new a([[k,2],[m,3]]);if(2!=q.get(k)||3!=q.get(m))return!1;q.delete(k);q.set(m,4);return!q.has(k)&&4==q.get(m)}catch(r){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,m){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!ja(k,g))throw Error("WeakMap key fail: "+k);k[g][this.i]=m;return this};
b.prototype.get=function(k){return d(k)&&ja(k,g)?k[g][this.i]:void 0};
b.prototype.has=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)};
b.prototype.delete=function(k){return d(k)&&ja(k,g)&&ja(k[g],this.i)?delete k[g][this.i]:!1};
return b});
n("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var m=h.i;return ha(function(){if(m){for(;m.head!=h.i;)m=m.previous;for(;m.next!=m.head;)return m=m.next,{done:!1,value:k(m)};m=null}return{done:!0,value:void 0}})}
function d(h,k){var m=k&&typeof k;"object"==m||"function"==m?f.has(k)?m=f.get(k):(m=""+ ++g,f.set(k,m)):m="p_"+k;var q=h.data_[m];if(q&&ja(h.data_,m))for(h=0;h<q.length;h++){var r=q[h];if(k!==k&&r.key!==r.key||k===r.key)return{id:m,list:q,index:h,entry:r}}return{id:m,list:q,index:-1,entry:void 0}}
function e(h){this.data_={};this.i=b();this.size=0;if(h){h=p(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(p([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var m=k.entries(),q=m.next();if(q.done||q.value[0]!=h||"s"!=q.value[1])return!1;q=m.next();return q.done||4!=q.value[0].x||"t"!=q.value[1]||!m.next().done?!1:!0}catch(r){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var m=d(this,h);m.list||(m.list=this.data_[m.id]=[]);m.entry?m.entry.value=k:(m.entry={next:this.i,previous:this.i.previous,head:this.i,key:h,value:k},m.list.push(m.entry),this.i.previous.next=m.entry,this.i.previous=m.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.i=this.i.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var m=this.entries(),q;!(q=m.next()).done;)q=q.value,h.call(k,q[1],q[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function La(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
n("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=La(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
n("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
n("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=La(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
n("Number.isFinite",function(a){return a?a:function(b){return"number"!==typeof b?!1:!isNaN(b)&&Infinity!==b&&-Infinity!==b}});
n("Number.isInteger",function(a){return a?a:function(b){return Number.isFinite(b)?b===Math.floor(b):!1}});
n("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
function Ma(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
n("Array.prototype.entries",function(a){return a?a:function(){return Ma(this,function(b,c){return[b,c]})}});
n("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
n("Array.prototype.keys",function(a){return a?a:function(){return Ma(this,function(b){return b})}});
n("Set",function(a){function b(c){this.i=new Map;if(c){c=p(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.i.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(p([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.i.set(c,c);this.size=this.i.size;return this};
b.prototype.delete=function(c){c=this.i.delete(c);this.size=this.i.size;return c};
b.prototype.clear=function(){this.i.clear();this.size=0};
b.prototype.has=function(c){return this.i.has(c)};
b.prototype.entries=function(){return this.i.entries()};
b.prototype.values=function(){return this.i.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.i.forEach(function(f){return c.call(d,f,f,e)})};
return b});
n("Array.prototype.values",function(a){return a?a:function(){return Ma(this,function(b,c){return c})}});
n("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
n("Object.setPrototypeOf",function(a){return a||sa});
n("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
n("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
n("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==La(this,b,"includes").indexOf(b,c||0)}});
n("globalThis",function(a){return a||fa});
n("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push([d,b[d]]);return c}});
n("Object.values",function(a){return a?a:function(b){var c=[],d;for(d in b)ja(b,d)&&c.push(b[d]);return c}});
var Na=Na||{},y=this||self;function z(a,b,c){a=a.split(".");c=c||y;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function B(a,b){a=a.split(".");b=b||y;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Oa(a){a.sb=void 0;a.getInstance=function(){return a.sb?a.sb:a.sb=new a}}
function Pa(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function Qa(a){var b=Pa(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function Ra(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Sa(a){return Object.prototype.hasOwnProperty.call(a,Ta)&&a[Ta]||(a[Ta]=++Ua)}
var Ta="closure_uid_"+(1E9*Math.random()>>>0),Ua=0;function Va(a,b,c){return a.call.apply(a.bind,arguments)}
function Wa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Xa(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Xa=Va:Xa=Wa;return Xa.apply(null,arguments)}
function Ya(a,b){var c=Array.prototype.slice.call(arguments,1);return function(){var d=c.slice();d.push.apply(d,arguments);return a.apply(this,d)}}
function Za(a,b){function c(){}
c.prototype=b.prototype;a.Y=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.hq=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function $a(a){return a}
;function ab(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,ab);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.cause=b)}
Za(ab,Error);ab.prototype.name="CustomError";function bb(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.l=!b&&/[?&]ae=1(&|$)/.test(a);this.m=!b&&/[?&]ae=2(&|$)/.test(a);if((this.i=/[?&]adurl=([^&]*)/.exec(a))&&this.i[1]){try{var c=decodeURIComponent(this.i[1])}catch(d){c=null}this.j=c}}
;function cb(){}
function db(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var eb=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},fb=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},gb=Array.prototype.filter?function(a,b){return Array.prototype.filter.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=[],e=0,f="string"===typeof a?a.split(""):a,g=0;g<c;g++)if(g in f){var h=f[g];
b.call(void 0,h,g,a)&&(d[e++]=h)}return d},hb=Array.prototype.map?function(a,b){return Array.prototype.map.call(a,b,void 0)}:function(a,b){for(var c=a.length,d=Array(c),e="string"===typeof a?a.split(""):a,f=0;f<c;f++)f in e&&(d[f]=b.call(void 0,e[f],f,a));
return d},ib=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
fb(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function jb(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function kb(a,b){b=eb(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function lb(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Qa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function mb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function nb(a){var b=ob,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function pb(a){for(var b in a)return!1;return!0}
function qb(a,b){if(null!==a&&b in a)throw Error('The object already contains the key "'+b+'"');a[b]=!0}
function rb(a){return null!==a&&"privembed"in a?a.privembed:!1}
function sb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function tb(a){var b={},c;for(c in a)b[c]=a[c];return b}
function ub(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=ub(a[c]);return b}
var vb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function wb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<vb.length;f++)c=vb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var xb;function yb(){if(void 0===xb){var a=null,b=y.trustedTypes;if(b&&b.createPolicy){try{a=b.createPolicy("goog#html",{createHTML:$a,createScript:$a,createScriptURL:$a})}catch(c){y.console&&y.console.error(c.message)}xb=a}else xb=a}return xb}
;function zb(a,b){this.l=a===Cb&&b||""}
zb.prototype.j=!0;zb.prototype.i=function(){return this.l};
function Db(a){return new zb(Cb,a)}
var Cb={};Db("");var Eb={};function Fb(a){this.l=Eb===Eb?a:"";this.j=!0}
Fb.prototype.toString=function(){return this.l.toString()};
Fb.prototype.i=function(){return this.l.toString()};function Gb(a,b){this.l=b===Hb?a:""}
Gb.prototype.toString=function(){return this.l+""};
Gb.prototype.j=!0;Gb.prototype.i=function(){return this.l.toString()};
function Ib(a){if(a instanceof Gb&&a.constructor===Gb)return a.l;Pa(a);return"type_error:TrustedResourceUrl"}
var Hb={};function Jb(a){var b=yb();a=b?b.createScriptURL(a):a;return new Gb(a,Hb)}
;var Kb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function Lb(a,b){return a<b?-1:a>b?1:0}
;function Mb(a,b){this.l=b===Nb?a:""}
Mb.prototype.toString=function(){return this.l.toString()};
Mb.prototype.j=!0;Mb.prototype.i=function(){return this.l.toString()};
function Ob(a){if(a instanceof Mb&&a.constructor===Mb)return a.l;Pa(a);return"type_error:SafeUrl"}
var Pb=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,Nb={},Qb=new Mb("about:invalid#zClosurez",Nb);function Rb(){var a=y.navigator;return a&&(a=a.userAgent)?a:""}
function C(a){return-1!=Rb().indexOf(a)}
;function Sb(){return C("Trident")||C("MSIE")}
function Tb(){return C("Firefox")||C("FxiOS")}
function Ub(){return C("Safari")&&!(Vb()||C("Coast")||C("Opera")||C("Edge")||C("Edg/")||C("OPR")||Tb()||C("Silk")||C("Android"))}
function Vb(){return(C("Chrome")||C("CriOS"))&&!C("Edge")||C("Silk")}
function Yb(){return C("Android")&&!(Vb()||Tb()||C("Opera")||C("Silk"))}
function Zb(a){var b={};a.forEach(function(c){b[c[0]]=c[1]});
return function(c){return b[c.find(function(d){return d in b})]||""}}
function $b(a){var b=Rb();if("Internet Explorer"===a){if(Sb())if((a=/rv: *([\d\.]*)/.exec(b))&&a[1])b=a[1];else{a="";var c=/MSIE +([\d\.]+)/.exec(b);if(c&&c[1])if(b=/Trident\/(\d.\d)/.exec(b),"7.0"==c[1])if(b&&b[1])switch(b[1]){case "4.0":a="8.0";break;case "5.0":a="9.0";break;case "6.0":a="10.0";break;case "7.0":a="11.0"}else a="7.0";else a=c[1];b=a}else b="";return b}var d=RegExp("([A-Z][\\w ]+)/([^\\s]+)\\s*(?:\\((.*?)\\))?","g");c=[];for(var e;e=d.exec(b);)c.push([e[1],e[2],e[3]||void 0]);b=Zb(c);
switch(a){case "Opera":if(C("Opera"))return b(["Version","Opera"]);if(C("OPR"))return b(["OPR"]);break;case "Microsoft Edge":if(C("Edge"))return b(["Edge"]);if(C("Edg/"))return b(["Edg"]);break;case "Chromium":if(Vb())return b(["Chrome","CriOS","HeadlessChrome"])}return"Firefox"===a&&Tb()||"Safari"===a&&Ub()||"Android Browser"===a&&Yb()||"Silk"===a&&C("Silk")?(b=c[2])&&b[1]||"":""}
function ac(a){a=$b(a);if(""===a)return NaN;a=a.split(".");return 0===a.length?NaN:Number(a[0])}
;var bc={};function cc(a){this.l=bc===bc?a:"";this.j=!0}
cc.prototype.i=function(){return this.l.toString()};
cc.prototype.toString=function(){return this.l.toString()};function dc(a,b){b instanceof Mb||b instanceof Mb||(b="object"==typeof b&&b.j?b.i():String(b),Pb.test(b)||(b="about:invalid#zClosurez"),b=new Mb(b,Nb));a.href=Ob(b)}
function ec(a,b){a.rel="stylesheet";a.href=Ib(b).toString();(b=fc('style[nonce],link[rel="stylesheet"][nonce]',a.ownerDocument&&a.ownerDocument.defaultView))&&a.setAttribute("nonce",b)}
function gc(){return fc("script[nonce]")}
var hc=/^[\w+/_-]+[=]{0,2}$/;function fc(a,b){b=(b||y).document;return b.querySelector?(a=b.querySelector(a))&&(a=a.nonce||a.getAttribute("nonce"))&&hc.test(a)?a:"":""}
;function ic(a){for(var b=0,c=0;c<a.length;++c)b=31*b+a.charCodeAt(c)>>>0;return b}
;var jc=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function kc(a){return a?decodeURI(a):a}
function lc(a,b){return b.match(jc)[a]||null}
function mc(a){return kc(lc(3,a))}
function nc(a){var b=a.match(jc);a=b[5];var c=b[6];b=b[7];var d="";a&&(d+=a);c&&(d+="?"+c);b&&(d+="#"+b);return d}
function oc(a,b){if(!b)return a;var c=a.indexOf("#");0>c&&(c=a.length);var d=a.indexOf("?");if(0>d||d>c){d=c;var e=""}else e=a.substring(d+1,c);a=[a.slice(0,d),e,a.slice(c)];c=a[1];a[1]=b?c?c+"&"+b:b:c;return a[0]+(a[1]?"?"+a[1]:"")+a[2]}
function pc(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)pc(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function qc(a,b){var c=[];for(b=b||0;b<a.length;b+=2)pc(a[b],a[b+1],c);return c.join("&")}
function rc(a){var b=[],c;for(c in a)pc(c,a[c],b);return b.join("&")}
function sc(a,b){var c=2==arguments.length?qc(arguments[1],0):qc(arguments,1);return oc(a,c)}
function tc(a,b){b=rc(b);return oc(a,b)}
function xc(a,b,c){c=null!=c?"="+encodeURIComponent(String(c)):"";return oc(a,b+c)}
function yc(a,b,c,d){for(var e=c.length;0<=(b=a.indexOf(c,b))&&b<d;){var f=a.charCodeAt(b-1);if(38==f||63==f)if(f=a.charCodeAt(b+e),!f||61==f||38==f||35==f)return b;b+=e+1}return-1}
var zc=/#|$/,Ac=/[?&]($|#)/;function Bc(a,b){for(var c=a.search(zc),d=0,e,f=[];0<=(e=yc(a,d,b,c));)f.push(a.substring(d,e)),d=Math.min(a.indexOf("&",e)+1||c,c);f.push(a.slice(d));return f.join("").replace(Ac,"$1")}
;var Cc={};function Dc(a){if(a!==Cc)throw Error("requires a valid immutable API token");}
;function Ec(){return C("iPhone")&&!C("iPod")&&!C("iPad")}
function Fc(){var a=Rb();if(C("Windows")){var b=/Windows (?:NT|Phone) ([0-9.]+)/;b.exec(a)}else Ec()||C("iPad")||C("iPod")?(b=/(?:iPhone|iPod|iPad|CPU)\s+OS\s+(\S+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):C("Macintosh")?(b=/Mac OS X ([0-9_.]+)/,(a=b.exec(a))&&a[1].replace(/_/g,".")):-1!=Rb().toLowerCase().indexOf("kaios")?(b=/(?:KaiOS)\/(\S+)/i,b.exec(a)):C("Android")?(b=/Android\s+([^\);]+)(\)|;)/,b.exec(a)):C("CrOS")&&(b=/(?:CrOS\s+(?:i686|x86_64)\s+([0-9.]+))/,b.exec(a))}
;function Gc(a){Gc[" "](a);return a}
Gc[" "]=function(){};
function Hc(a){var b=Ic;return Object.prototype.hasOwnProperty.call(b,9)?b[9]:b[9]=a(9)}
;var Jc=C("Opera"),Kc=Sb(),Lc=C("Edge"),Mc=C("Gecko")&&!(-1!=Rb().toLowerCase().indexOf("webkit")&&!C("Edge"))&&!(C("Trident")||C("MSIE"))&&!C("Edge"),Nc=-1!=Rb().toLowerCase().indexOf("webkit")&&!C("Edge"),Oc=C("Android");function Pc(){var a=y.document;return a?a.documentMode:void 0}
var Qc;a:{var Rc="",Sc=function(){var a=Rb();if(Mc)return/rv:([^\);]+)(\)|;)/.exec(a);if(Lc)return/Edge\/([\d\.]+)/.exec(a);if(Kc)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Nc)return/WebKit\/(\S+)/.exec(a);if(Jc)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Sc&&(Rc=Sc?Sc[1]:"");if(Kc){var Tc=Pc();if(null!=Tc&&Tc>parseFloat(Rc)){Qc=String(Tc);break a}}Qc=Rc}var Uc=Qc,Ic={};
function Vc(){return Hc(function(){for(var a=0,b=Kb(String(Uc)).split("."),c=Kb("9").split("."),d=Math.max(b.length,c.length),e=0;0==a&&e<d;e++){var f=b[e]||"",g=c[e]||"";do{f=/(\d*)(\D*)(.*)/.exec(f)||["","","",""];g=/(\d*)(\D*)(.*)/.exec(g)||["","","",""];if(0==f[0].length&&0==g[0].length)break;a=Lb(0==f[1].length?0:parseInt(f[1],10),0==g[1].length?0:parseInt(g[1],10))||Lb(0==f[2].length,0==g[2].length)||Lb(f[2],g[2]);f=f[3];g=g[3]}while(0==a)}return 0<=a})}
var Wc;if(y.document&&Kc){var Xc=Pc();Wc=Xc?Xc:parseInt(Uc,10)||void 0}else Wc=void 0;var Yc=Wc;var Zc=Ec()||C("iPod"),$c=C("iPad");Yb();Vb();var ad=Ub()&&!(Ec()||C("iPad")||C("iPod"));var bd={},cd=null;
function dd(a,b){Qa(a);void 0===b&&(b=0);if(!cd){cd={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));bd[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===cd[h]&&(cd[h]=g)}}}b=bd[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],m=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|m>>4];m=b[(m&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+m+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var ed="undefined"!==typeof Uint8Array,fd={};var gd;function hd(a){if(fd!==fd)throw Error("illegal external caller");this.ja=a;if(null!=a&&0===a.length)throw Error("ByteString should be constructed with non-empty values");}
hd.prototype.isEmpty=function(){return null==this.ja};var id="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function jd(a,b){Object.isFrozen(a)||(id?a[id]|=b:void 0!==a.ta?a.ta|=b:Object.defineProperties(a,{ta:{value:b,configurable:!0,writable:!0,enumerable:!1}}))}
function kd(a){var b;id?b=a[id]:b=a.ta;return null==b?0:b}
function ld(a){return Array.isArray(a)?!!(kd(a)&1):!1}
function md(a){jd(a,1);return a}
function nd(a){return Array.isArray(a)?!!(kd(a)&2):!1}
function od(a){if(!Array.isArray(a))throw Error("cannot mark non-array as immutable");jd(a,2)}
function sd(a,b){if(!Array.isArray(a))throw Error("cannot mark non-array as mutable");b?jd(a,8):Object.isFrozen(a)||(id?a[id]&=-9:void 0!==a.ta&&(a.ta&=-9))}
;function td(a){return nd(a.I)}
function ud(a){return null!==a&&"object"===typeof a&&!Array.isArray(a)&&a.constructor===Object}
var vd,wd=Object.freeze(md([]));function xd(a){if(td(a))throw Error("Cannot mutate an immutable Message");}
var yd="undefined"!=typeof Symbol&&"undefined"!=typeof Symbol.hasInstance;function zd(a){return{value:a,configurable:!1,writable:!1,enumerable:!1}}
;function Ad(a){return a.displayName||a.name||"unknown type name"}
function Bd(a,b){if(!(a instanceof b))throw Error("Expected instanceof "+Ad(b)+" but got "+(a&&Ad(a.constructor)));return a}
function Cd(a,b,c){c=void 0===c?!1:c;if(Array.isArray(a))return new b(a);if(c)return new b}
;function Dd(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(a&&!Array.isArray(a)){if(ed&&null!=a&&a instanceof Uint8Array)return dd(a);if(a instanceof hd){var b=a.ja;null!=b&&"string"!==typeof b&&(ed&&b instanceof Uint8Array?b=dd(b):(Pa(b),b=null));return null==b?"":a.ja=b}}}return a}
;function Ed(a,b){b=void 0===b?Fd:b;return Gd(a,b)}
function Hd(a,b){if(null!=a){if(Array.isArray(a))a=Gd(a,b);else if(ud(a)){var c={},d;for(d in a)c[d]=Hd(a[d],b);a=c}else a=b(a);return a}}
function Gd(a,b){for(var c=a.slice(),d=0;d<c.length;d++)c[d]=Hd(c[d],b);ld(a)&&md(c);return c}
function Id(a){if(a&&"object"==typeof a&&a.toJSON)return a.toJSON();a=Dd(a);return Array.isArray(a)?Ed(a,Id):a}
function Fd(a){return ed&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;function Jd(a){return a.j||(a.j=a.I[a.l+a.ra]={})}
function Kd(a,b,c){return-1===b?null:b>=a.l?a.j?a.j[b]:void 0:(void 0===c?0:c)&&a.j&&(c=a.j[b],null!=c)?c:a.I[b+a.ra]}
function E(a,b,c,d,e){d=void 0===d?!1:d;(void 0===e?0:e)||xd(a);b<a.l&&!d?a.I[b+a.ra]=c:Jd(a)[b]=c;return a}
function Ld(a,b,c,d){c=void 0===c?!0:c;var e=Kd(a,b,d);Array.isArray(e)||(e=wd);if(td(a))c&&(od(e),Object.freeze(e));else if(e===wd||nd(e))e=md(e.slice()),E(a,b,e,d);return e}
function Md(a,b,c){a=Kd(a,b);return null==a?c:a}
function Nd(a,b,c){null==c?c=wd:md(c);return E(a,b,c)}
function Od(a,b,c,d){xd(a);(c=Pd(a,c))&&c!==b&&null!=d&&(a.i&&c in a.i&&(a.i[c]=void 0),E(a,c));return E(a,b,d)}
function Pd(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Kd(a,e)&&(0!==c&&E(a,c,void 0,!1,!0),c=e)}return c}
function Qd(a,b,c,d,e){e=void 0===e?!1:e;var f=e;if(-1===c)d=null;else{a.i||(a.i={});var g=a.i[c];if(g)d=g;else{var h=Kd(a,c,f);b=Cd(h,b,d);void 0==b?d=g:(d&&b.I!==h&&E(a,c,b.I,f,!0),a.i[c]=b,td(a)&&od(b.I),d=b)}}if(null==d)return d;td(d)&&!td(a)&&(d=d.Ab(Cc),E(a,c,d.I,e),a.i[c]=d);return d}
function Rd(a,b,c,d,e){e=void 0===e?!0:e;a.i||(a.i={});var f=td(a),g=a.i[c];d=Ld(a,c,!0,d);var h=f||nd(d);if(!g){g=[];f=f||h;for(var k=0;k<d.length;k++){var m=d[k];f=f||nd(m);m=Cd(m,b);void 0!==m&&(g.push(m),h&&od(m.I))}a.i[c]=g;sd(d,!f)}b=h||e;e=nd(g);b&&!e&&(Object.isFrozen(g)&&(a.i[c]=g=g.slice()),od(g),Object.freeze(g));!b&&e&&(a.i[c]=g=g.slice());return g}
function Sd(a,b,c,d){d=void 0===d?!1:d;var e=td(a);b=Rd(a,b,c,d,e);a=Ld(a,c,d);if(!(c=e)&&(c=a)){if(!Array.isArray(a))throw Error("cannot check mutability state of non-array");c=!(kd(a)&8)}if(c){for(c=0;c<b.length;c++)(d=b[c])&&td(d)&&!e&&(b[c]=b[c].Ab(Cc),a[c]=b[c].I);sd(a,!0)}return b}
function G(a,b,c,d){xd(a);a.i||(a.i={});b=null!=d?Bd(d,b).I:d;a.i[c]=d;return E(a,c,b)}
function Td(a,b,c,d,e){xd(a);a.i||(a.i={});b=null!=e?Bd(e,b).I:e;a.i[c]=e;Od(a,c,d,b)}
function Ud(a,b,c,d){xd(a);if(null!=d){var e=md([]);for(var f=!1,g=0;g<d.length;g++)e[g]=Bd(d[g],b).I,f=f||nd(e[g]);a.i||(a.i={});a.i[c]=d;sd(e,!f)}else a.i&&(a.i[c]=void 0),e=wd;return E(a,c,e)}
function Vd(a,b,c,d){xd(a);var e=Rd(a,c,b,void 0,!1);c=null!=d?Bd(d,c):new c;a=Ld(a,b);e.push(c);a.push(c.I);Dc(Cc);td(c)&&sd(a,!1)}
;function Wd(a,b,c){a||(a=Xd);Xd=null;var d=this.constructor.j;a||(a=d?[d]:[]);this.ra=(d?0:-1)-(this.constructor.i||0);this.i=void 0;this.I=a;a:{d=this.I.length;a=d-1;if(d&&(d=this.I[a],ud(d))){this.l=a-this.ra;this.j=d;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.ra),this.j=void 0):this.l=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)if(a=c[b],a<this.l)a+=this.ra,(d=this.I[a])?Array.isArray(d)&&md(d):this.I[a]=wd;else{d=Jd(this);var e=d[a];e?Array.isArray(e)&&md(e):d[a]=wd}}
Wd.prototype.toJSON=function(){var a=this.I;return vd?a:Ed(a,Id)};
function Yd(a){vd=!0;try{return JSON.stringify(a.toJSON(),Zd)}finally{vd=!1}}
Wd.prototype.clone=function(){var a=Ed(this.I);Xd=a;a=new this.constructor(a);Xd=null;$d(a,this);return a};
Wd.prototype.isMutable=function(a){Dc(a);return!td(this)};
Wd.prototype.toString=function(){return this.I.toString()};
function Zd(a,b){return Dd(b)}
function $d(a,b){b.Ha&&(a.Ha=b.Ha.slice());var c=b.i;if(c){b=b.j;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=Sd(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)$d(f[g],e[g])}else(f=Qd(a,e.constructor,g,void 0,f))&&$d(f,e)}}}}
var Xd;function ae(){Wd.apply(this,arguments)}
t(ae,Wd);ae.prototype.Ab=function(){return this};
if(yd){var be={};Object.defineProperties(ae,(be[Symbol.hasInstance]=zd(function(){throw Error("Cannot perform instanceof checks for MutableMessage");}),be))};function ce(a){var b=this.i,c=this.j;return this.isRepeated?Sd(a,b,c,!0):Qd(a,b,c,void 0,!0)}
;function de(a,b,c,d,e,f){(a=a.i&&a.i[c])?Array.isArray(a)?(e=f.kb?md(a.slice()):a,Ud(b,0<e.length?e[0].constructor:void 0,c,e)):G(b,a.constructor,c,a):(ed&&d instanceof Uint8Array?e=d.length?new hd(new Uint8Array(d)):gd||(gd=new hd(null)):(Array.isArray(d)&&(e?od(d):ld(d)&&f.kb&&(d=d.slice())),e=d),E(b,c,e))}
;function I(){ae.apply(this,arguments)}
t(I,ae);I.prototype.Ab=function(a){Dc(a);if(td(this)){a={kb:!0};var b=td(this);if(b&&!a.kb)throw Error("copyRepeatedFields must be true for frozen messages");var c=new this.constructor;this.Ha&&(c.Ha=this.Ha.slice());for(var d=this.I,e=0;e<d.length;e++){var f=d[e];if(e===d.length-1&&ud(f))for(h in f){var g=+h;Number.isNaN(g)?Jd(c)[h]=f[h]:de(this,c,g,f[h],b,a)}else de(this,c,e-this.ra,f,b,a)}var h=c}else h=this;return h};
if(yd){var ee={};Object.defineProperties(I,(ee[Symbol.hasInstance]=zd(Object[Symbol.hasInstance]),ee))};function fe(a){this.Jb=a}
;function ge(a,b,c){this.j=a;this.m=b;this.i=c||[];this.xa=new Map}
l=ge.prototype;l.tc=function(a){var b=Ka.apply(1,arguments),c=this.nb(b);c?c.push(new fe(a)):this.ic(a,b)};
l.ic=function(a){this.xa.set(this.Qb(Ka.apply(1,arguments)),[new fe(a)])};
l.nb=function(){var a=this.Qb(Ka.apply(0,arguments));return this.xa.has(a)?this.xa.get(a):void 0};
l.Gc=function(){var a=this.nb(Ka.apply(0,arguments));return a&&a.length?a[0]:void 0};
l.clear=function(){this.xa.clear()};
l.Qb=function(){var a=Ka.apply(0,arguments);return a?a.join(","):"key"};function he(a,b){ge.call(this,a,3,b)}
t(he,ge);he.prototype.l=function(a){var b=Ka.apply(1,arguments),c=0,d=this.Gc(b);d&&(c=d.Jb);this.ic(c+a,b)};function ie(a,b){ge.call(this,a,2,b)}
t(ie,ge);ie.prototype.l=function(a){this.tc(a,Ka.apply(1,arguments))};function je(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function ke(a){for(var b=0,c=arguments.length;b<c;++b){var d=arguments[b];Qa(d)?ke.apply(null,d):je(d)}}
;function J(){this.N=this.N;this.B=this.B}
J.prototype.N=!1;J.prototype.i=function(){return this.N};
J.prototype.dispose=function(){this.N||(this.N=!0,this.C())};
function le(a,b){me(a,Ya(je,b))}
function me(a,b){a.N?b():(a.B||(a.B=[]),a.B.push(b))}
J.prototype.C=function(){if(this.B)for(;this.B.length;)this.B.shift()()};function ne(a,b){this.type=a;this.i=this.target=b;this.defaultPrevented=this.l=!1}
ne.prototype.stopPropagation=function(){this.l=!0};
ne.prototype.preventDefault=function(){this.defaultPrevented=!0};function oe(a){var b=B("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||y.$googDebugFname||b}catch(g){e="Not available",c=!0}b=pe(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,qe[c])c=qe[c];else{c=String(c);if(!qe[c]){var f=/function\s+([^\(]+)/m.exec(c);qe[c]=f?f[1]:"[Anonymous]"}c=qe[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function pe(a,b){b||(b={});b[re(a)]=!0;var c=a.stack||"";(a=a.cause)&&!b[re(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=pe(a,b));return c}
function re(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var qe={};var se=function(){if(!y.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{y.addEventListener("test",function(){},b),y.removeEventListener("test",function(){},b)}catch(c){}return a}();function te(a,b){ne.call(this,a?a.type:"");this.relatedTarget=this.i=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.j=null;a&&this.init(a,b)}
Za(te,ne);var xe={2:"touch",3:"pen",4:"mouse"};
te.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.i=b;if(b=a.relatedTarget){if(Mc){a:{try{Gc(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:xe[a.pointerType]||"";this.state=a.state;
this.j=a;a.defaultPrevented&&te.Y.preventDefault.call(this)};
te.prototype.stopPropagation=function(){te.Y.stopPropagation.call(this);this.j.stopPropagation?this.j.stopPropagation():this.j.cancelBubble=!0};
te.prototype.preventDefault=function(){te.Y.preventDefault.call(this);var a=this.j;a.preventDefault?a.preventDefault():a.returnValue=!1};var ye="closure_listenable_"+(1E6*Math.random()|0);var ze=0;function Ae(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.Ya=e;this.key=++ze;this.Ja=this.Ta=!1}
function Be(a){a.Ja=!0;a.listener=null;a.proxy=null;a.src=null;a.Ya=null}
;function Ce(a){this.src=a;this.listeners={};this.i=0}
Ce.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.i++);var g=De(a,b,d,e);-1<g?(b=a[g],c||(b.Ta=!1)):(b=new Ae(b,this.src,f,!!d,e),b.Ta=c,a.push(b));return b};
Ce.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=De(e,b,c,d);return-1<b?(Be(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.i--),!0):!1};
function Ee(a,b){var c=b.type;c in a.listeners&&kb(a.listeners[c],b)&&(Be(b),0==a.listeners[c].length&&(delete a.listeners[c],a.i--))}
function De(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Ja&&f.listener==b&&f.capture==!!c&&f.Ya==d)return e}return-1}
;var Fe="closure_lm_"+(1E6*Math.random()|0),Ge={},He=0;function Ie(a,b,c,d,e){if(d&&d.once)Je(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Ie(a,b[f],c,d,e);else c=Ke(c),a&&a[ye]?a.aa(b,c,Ra(d)?!!d.capture:!!d,e):Le(a,b,c,!1,d,e)}
function Le(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=Ra(e)?!!e.capture:!!e,h=Me(a);h||(a[Fe]=h=new Ce(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Ne();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)se||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Oe(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");He++}}
function Ne(){function a(c){return b.call(a.src,a.listener,c)}
var b=Pe;return a}
function Je(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Je(a,b[f],c,d,e);else c=Ke(c),a&&a[ye]?a.m.add(String(b),c,!0,Ra(d)?!!d.capture:!!d,e):Le(a,b,c,!0,d,e)}
function Qe(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Qe(a,b[f],c,d,e);else(d=Ra(d)?!!d.capture:!!d,c=Ke(c),a&&a[ye])?a.m.remove(String(b),c,d,e):a&&(a=Me(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=De(b,c,d,e)),(c=-1<a?b[a]:null)&&Re(c))}
function Re(a){if("number"!==typeof a&&a&&!a.Ja){var b=a.src;if(b&&b[ye])Ee(b.m,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Oe(c),d):b.addListener&&b.removeListener&&b.removeListener(d);He--;(c=Me(b))?(Ee(c,a),0==c.i&&(c.src=null,b[Fe]=null)):Be(a)}}}
function Oe(a){return a in Ge?Ge[a]:Ge[a]="on"+a}
function Pe(a,b){if(a.Ja)a=!0;else{b=new te(b,this);var c=a.listener,d=a.Ya||a.src;a.Ta&&Re(a);a=c.call(d,b)}return a}
function Me(a){a=a[Fe];return a instanceof Ce?a:null}
var Se="__closure_events_fn_"+(1E9*Math.random()>>>0);function Ke(a){if("function"===typeof a)return a;a[Se]||(a[Se]=function(b){return a.handleEvent(b)});
return a[Se]}
;function Te(){J.call(this);this.m=new Ce(this);this.pc=this;this.ka=null}
Za(Te,J);Te.prototype[ye]=!0;Te.prototype.addEventListener=function(a,b,c,d){Ie(this,a,b,c,d)};
Te.prototype.removeEventListener=function(a,b,c,d){Qe(this,a,b,c,d)};
function Ue(a,b){var c=a.ka;if(c){var d=[];for(var e=1;c;c=c.ka)d.push(c),++e}a=a.pc;c=b.type||b;"string"===typeof b?b=new ne(b,a):b instanceof ne?b.target=b.target||a:(e=b,b=new ne(c,a),wb(b,e));e=!0;if(d)for(var f=d.length-1;!b.l&&0<=f;f--){var g=b.i=d[f];e=Ve(g,c,!0,b)&&e}b.l||(g=b.i=a,e=Ve(g,c,!0,b)&&e,b.l||(e=Ve(g,c,!1,b)&&e));if(d)for(f=0;!b.l&&f<d.length;f++)g=b.i=d[f],e=Ve(g,c,!1,b)&&e}
Te.prototype.C=function(){Te.Y.C.call(this);if(this.m){var a=this.m,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Be(d[e]);delete a.listeners[c];a.i--}}this.ka=null};
Te.prototype.aa=function(a,b,c,d){return this.m.add(String(a),b,!1,c,d)};
function Ve(a,b,c,d){b=a.m.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.Ja&&g.capture==c){var h=g.listener,k=g.Ya||g.src;g.Ta&&Ee(a.m,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function We(a,b){this.l=a;this.m=b;this.j=0;this.i=null}
We.prototype.get=function(){if(0<this.j){this.j--;var a=this.i;this.i=a.next;a.next=null}else a=this.l();return a};
function Xe(a,b){a.m(b);100>a.j&&(a.j++,b.next=a.i,a.i=b)}
;function Ye(a,b){return a+Math.random()*(b-a)}
;function Ze(a,b){this.x=void 0!==a?a:0;this.y=void 0!==b?b:0}
l=Ze.prototype;l.clone=function(){return new Ze(this.x,this.y)};
l.equals=function(a){return a instanceof Ze&&(this==a?!0:this&&a?this.x==a.x&&this.y==a.y:!1)};
l.ceil=function(){this.x=Math.ceil(this.x);this.y=Math.ceil(this.y);return this};
l.floor=function(){this.x=Math.floor(this.x);this.y=Math.floor(this.y);return this};
l.round=function(){this.x=Math.round(this.x);this.y=Math.round(this.y);return this};
l.scale=function(a,b){this.x*=a;this.y*="number"===typeof b?b:a;return this};function $e(a,b){this.width=a;this.height=b}
l=$e.prototype;l.clone=function(){return new $e(this.width,this.height)};
l.aspectRatio=function(){return this.width/this.height};
l.isEmpty=function(){return!(this.width*this.height)};
l.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
l.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
l.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
l.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function af(a){var b=document;return"string"===typeof a?b.getElementById(a):a}
function bf(a){var b=document;a=String(a);"application/xhtml+xml"===b.contentType&&(a=a.toLowerCase());return b.createElement(a)}
function cf(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;var df;function ef(){var a=y.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!C("Presto")&&(a=function(){var e=bf("IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Xa(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!Sb()){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.Ib;c.Ib=null;e()}};
return function(e){d.next={Ib:e};d=d.next;b.port2.postMessage(0)}}return function(e){y.setTimeout(e,0)}}
;function ff(a){y.setTimeout(function(){throw a;},0)}
;function gf(){this.j=this.i=null}
gf.prototype.add=function(a,b){var c=hf.get();c.set(a,b);this.j?this.j.next=c:this.i=c;this.j=c};
gf.prototype.remove=function(){var a=null;this.i&&(a=this.i,this.i=this.i.next,this.i||(this.j=null),a.next=null);return a};
var hf=new We(function(){return new jf},function(a){return a.reset()});
function jf(){this.next=this.scope=this.i=null}
jf.prototype.set=function(a,b){this.i=a;this.scope=b;this.next=null};
jf.prototype.reset=function(){this.next=this.scope=this.i=null};var kf,lf=!1,mf=new gf;function nf(a,b){kf||of();lf||(kf(),lf=!0);mf.add(a,b)}
function of(){if(y.Promise&&y.Promise.resolve){var a=y.Promise.resolve(void 0);kf=function(){a.then(pf)}}else kf=function(){var b=pf;
"function"!==typeof y.setImmediate||y.Window&&y.Window.prototype&&!C("Edge")&&y.Window.prototype.setImmediate==y.setImmediate?(df||(df=ef()),df(b)):y.setImmediate(b)}}
function pf(){for(var a;a=mf.remove();){try{a.i.call(a.scope)}catch(b){ff(b)}Xe(hf,a)}lf=!1}
;function qf(a){this.i=0;this.B=void 0;this.m=this.j=this.l=null;this.o=this.s=!1;if(a!=cb)try{var b=this;a.call(void 0,function(c){rf(b,2,c)},function(c){rf(b,3,c)})}catch(c){rf(this,3,c)}}
function sf(){this.next=this.context=this.onRejected=this.j=this.i=null;this.l=!1}
sf.prototype.reset=function(){this.context=this.onRejected=this.j=this.i=null;this.l=!1};
var tf=new We(function(){return new sf},function(a){a.reset()});
function uf(a,b,c){var d=tf.get();d.j=a;d.onRejected=b;d.context=c;return d}
function vf(a){return new qf(function(b,c){c(a)})}
qf.prototype.then=function(a,b,c){return wf(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
qf.prototype.$goog_Thenable=!0;l=qf.prototype;l.gb=function(a,b){return wf(this,null,a,b)};
l.catch=qf.prototype.gb;l.cancel=function(a){if(0==this.i){var b=new xf(a);nf(function(){yf(this,b)},this)}};
function yf(a,b){if(0==a.i)if(a.l){var c=a.l;if(c.j){for(var d=0,e=null,f=null,g=c.j;g&&(g.l||(d++,g.i==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.i&&1==d?yf(c,b):(f?(d=f,d.next==c.m&&(c.m=d),d.next=d.next.next):zf(c),Af(c,e,3,b)))}a.l=null}else rf(a,3,b)}
function Bf(a,b){a.j||2!=a.i&&3!=a.i||Cf(a);a.m?a.m.next=b:a.j=b;a.m=b}
function wf(a,b,c,d){var e=uf(null,null,null);e.i=new qf(function(f,g){e.j=b?function(h){try{var k=b.call(d,h);f(k)}catch(m){g(m)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof xf?g(h):f(k)}catch(m){g(m)}}:g});
e.i.l=a;Bf(a,e);return e.i}
l.qd=function(a){this.i=0;rf(this,2,a)};
l.rd=function(a){this.i=0;rf(this,3,a)};
function rf(a,b,c){if(0==a.i){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.i=1;a:{var d=c,e=a.qd,f=a.rd;if(d instanceof qf){Bf(d,uf(e||cb,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(m){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(Ra(d))try{var k=d.then;if("function"===typeof k){Df(d,k,e,f,a);g=!0;break a}}catch(m){f.call(a,m);g=!0;break a}g=!1}}}g||(a.B=c,a.i=b,a.l=null,Cf(a),3!=b||c instanceof xf||Ef(a,c))}}
function Df(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Cf(a){a.s||(a.s=!0,nf(a.Ec,a))}
function zf(a){var b=null;a.j&&(b=a.j,a.j=b.next,b.next=null);a.j||(a.m=null);return b}
l.Ec=function(){for(var a;a=zf(this);)Af(this,a,this.i,this.B);this.s=!1};
function Af(a,b,c,d){if(3==c&&b.onRejected&&!b.l)for(;a&&a.o;a=a.l)a.o=!1;if(b.i)b.i.l=null,Ff(b,c,d);else try{b.l?b.j.call(b.context):Ff(b,c,d)}catch(e){Gf.call(null,e)}Xe(tf,b)}
function Ff(a,b,c){2==b?a.j.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Ef(a,b){a.o=!0;nf(function(){a.o&&Gf.call(null,b)})}
var Gf=ff;function xf(a){ab.call(this,a)}
Za(xf,ab);xf.prototype.name="cancel";function Hf(a,b){Te.call(this);this.l=a||1;this.j=b||y;this.o=Xa(this.od,this);this.s=Date.now()}
Za(Hf,Te);l=Hf.prototype;l.enabled=!1;l.ca=null;function If(a,b){a.l=b;a.ca&&a.enabled?(a.stop(),a.start()):a.ca&&a.stop()}
l.od=function(){if(this.enabled){var a=Date.now()-this.s;0<a&&a<.8*this.l?this.ca=this.j.setTimeout(this.o,this.l-a):(this.ca&&(this.j.clearTimeout(this.ca),this.ca=null),Ue(this,"tick"),this.enabled&&(this.stop(),this.start()))}};
l.start=function(){this.enabled=!0;this.ca||(this.ca=this.j.setTimeout(this.o,this.l),this.s=Date.now())};
l.stop=function(){this.enabled=!1;this.ca&&(this.j.clearTimeout(this.ca),this.ca=null)};
l.C=function(){Hf.Y.C.call(this);this.stop();delete this.j};
function Jf(a,b,c){if("function"===typeof a)c&&(a=Xa(a,c));else if(a&&"function"==typeof a.handleEvent)a=Xa(a.handleEvent,a);else throw Error("Invalid listener argument");return 2147483647<Number(b)?-1:y.setTimeout(a,b||0)}
;function Kf(a){this.B=a;this.i=new Map;this.s=new Set;this.l=0;this.m=100;this.flushInterval=3E4;this.j=new Hf(this.flushInterval);this.j.aa("tick",this.ib,!1,this);this.o=!1}
l=Kf.prototype;l.fc=function(a){this.o=a;this.m=1};
function Lf(a){a.j.enabled||a.j.start();a.l++;a.l>=a.m&&a.ib()}
l.ib=function(){var a=this.i.values();a=[].concat(ia(a)).filter(function(b){return b.xa.size});
a.length&&this.B.flush(a,this.o);Mf(a);this.l=0;this.j.enabled&&this.j.stop()};
l.uc=function(a){var b=Ka.apply(1,arguments);this.i.has(a)||this.i.set(a,new he(a,b))};
l.Gb=function(a){var b=Ka.apply(1,arguments);this.i.has(a)||this.i.set(a,new ie(a,b))};
function Nf(a,b){return a.s.has(b)?void 0:a.i.get(b)}
l.Bb=function(a){this.nc.apply(this,[a,1].concat(ia(Ka.apply(1,arguments))))};
l.nc=function(a,b){var c=Ka.apply(2,arguments),d=Nf(this,a);d&&d instanceof he&&(d.l(b,c),Lf(this))};
l.hb=function(a,b){var c=Ka.apply(2,arguments),d=Nf(this,a);d&&d instanceof ie&&(d.l(b,c),Lf(this))};
function Mf(a){for(var b=0;b<a.length;b++)a[b].clear()}
;function Of(a){this.i=a;this.i.Gb("/client_streamz/bg/fil",{mb:3,lb:"rk"})}
function Pf(a){this.i=a;this.i.uc("/client_streamz/bg/fsc",{mb:3,lb:"rk"})}
function Qf(a){this.i=a;this.i.Gb("/client_streamz/bg/fsl",{mb:3,lb:"rk"})}
;function Rf(a){I.call(this,a,-1,Sf)}
t(Rf,I);function Tf(a){I.call(this,a,-1,Uf)}
t(Tf,I);function Vf(a){I.call(this,a)}
t(Vf,I);function Wf(a){I.call(this,a)}
t(Wf,I);var Sf=[3,6,4],Uf=[1],Xf=[1,2,3],Yf=[1,2,3];function Zf(a){I.call(this,a,-1,$f)}
t(Zf,I);var $f=[1];function ag(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function bg(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;q=m=0}
function b(r){for(var x=g,u=0;64>u;u+=4)x[u/4]=r[u]<<24|r[u+1]<<16|r[u+2]<<8|r[u+3];for(u=16;80>u;u++)r=x[u-3]^x[u-8]^x[u-14]^x[u-16],x[u]=(r<<1|r>>>31)&4294967295;r=e[0];var A=e[1],D=e[2],F=e[3],N=e[4];for(u=0;80>u;u++){if(40>u)if(20>u){var O=F^A&(D^F);var Q=1518500249}else O=A^D^F,Q=1859775393;else 60>u?(O=A&D|F&(A|D),Q=2400959708):(O=A^D^F,Q=3395469782);O=((r<<5|r>>>27)&4294967295)+O+N+Q+x[u]&4294967295;N=F;F=D;D=(A<<30|A>>>2)&4294967295;A=r;r=O}e[0]=e[0]+r&4294967295;e[1]=e[1]+A&4294967295;e[2]=
e[2]+D&4294967295;e[3]=e[3]+F&4294967295;e[4]=e[4]+N&4294967295}
function c(r,x){if("string"===typeof r){r=unescape(encodeURIComponent(r));for(var u=[],A=0,D=r.length;A<D;++A)u.push(r.charCodeAt(A));r=u}x||(x=r.length);u=0;if(0==m)for(;u+64<x;)b(r.slice(u,u+64)),u+=64,q+=64;for(;u<x;)if(f[m++]=r[u++],q++,64==m)for(m=0,b(f);u+64<x;)b(r.slice(u,u+64)),u+=64,q+=64}
function d(){var r=[],x=8*q;56>m?c(h,56-m):c(h,64-(m-56));for(var u=63;56<=u;u--)f[u]=x&255,x>>>=8;b(f);for(u=x=0;5>u;u++)for(var A=24;0<=A;A-=8)r[x++]=e[u]>>A&255;return r}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var m,q;a();return{reset:a,update:c,digest:d,Ac:function(){for(var r=d(),x="",u=0;u<r.length;u++)x+="0123456789ABCDEF".charAt(Math.floor(r[u]/16))+"0123456789ABCDEF".charAt(r[u]%16);return x}}}
;function cg(a,b,c){var d=String(y.location.href);return d&&a&&b?[b,dg(ag(d),a,c||null)].join(" "):null}
function dg(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],fb(d,function(h){e.push(h)}),eg(e.join(" "));
var f=[],g=[];fb(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];fb(d,function(h){e.push(h)});
a=eg(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function eg(a){var b=bg();b.update(a);return b.Ac().toLowerCase()}
;var fg={};function gg(a){this.i=a||{cookie:""}}
l=gg.prototype;l.isEnabled=function(){if(!y.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
l.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.xq;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.ab}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.i.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
l.get=function(a,b){for(var c=a+"=",d=(this.i.cookie||"").split(";"),e=0,f;e<d.length;e++){f=Kb(d[e]);if(0==f.lastIndexOf(c,0))return f.slice(c.length);if(f==a)return""}return b};
l.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{ab:0,path:b,domain:c});return d};
l.qb=function(){return hg(this).keys};
l.isEmpty=function(){return!this.i.cookie};
l.clear=function(){for(var a=hg(this).keys,b=a.length-1;0<=b;b--)this.remove(a[b])};
function hg(a){a=(a.i.cookie||"").split(";");for(var b=[],c=[],d,e,f=0;f<a.length;f++)e=Kb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));return{keys:b,values:c}}
var ig=new gg("undefined"==typeof document?null:document);function jg(a){return!!fg.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function kg(a){a=void 0===a?!1:a;var b=y.__SAPISID||y.__APISID||y.__3PSAPISID||y.__OVERRIDE_SID;jg(a)&&(b=b||y.__1PSAPISID);if(b)return!0;var c=new gg(document);b=c.get("SAPISID")||c.get("APISID")||c.get("__Secure-3PAPISID")||c.get("SID");jg(a)&&(b=b||c.get("__Secure-1PAPISID"));return!!b}
function lg(a,b,c,d){(a=y[a])||(a=(new gg(document)).get(b));return a?cg(a,c,d):null}
function mg(a,b){b=void 0===b?!1:b;var c=ag(String(y.location.href)),d=[];if(kg(b)){c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:");var e=c?y.__SAPISID:y.__APISID;e||(e=new gg(document),e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID"));(e=e?cg(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e);c&&jg(b)&&((b=lg("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=lg("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a))}return 0==
d.length?null:d.join(" ")}
;function ng(a){I.call(this,a,-1,og)}
t(ng,I);var og=[2];function pg(a){this.i=this.j=this.l=a}
pg.prototype.reset=function(){this.i=this.j=this.l};
pg.prototype.getValue=function(){return this.j};function qg(a){var b=[];rg(new sg,a,b);return b.join("")}
function sg(){}
function rg(a,b,c){if(null==b)c.push("null");else{if("object"==typeof b){if(Array.isArray(b)){var d=b;b=d.length;c.push("[");for(var e="",f=0;f<b;f++)c.push(e),rg(a,d[f],c),e=",";c.push("]");return}if(b instanceof String||b instanceof Number||b instanceof Boolean)b=b.valueOf();else{c.push("{");e="";for(d in b)Object.prototype.hasOwnProperty.call(b,d)&&(f=b[d],"function"!=typeof f&&(c.push(e),tg(d,c),c.push(":"),rg(a,f,c),e=","));c.push("}");return}}switch(typeof b){case "string":tg(b,c);break;case "number":c.push(isFinite(b)&&
!isNaN(b)?String(b):"null");break;case "boolean":c.push(String(b));break;case "function":c.push("null");break;default:throw Error("Unknown type: "+typeof b);}}}
var ug={'"':'\\"',"\\":"\\\\","/":"\\/","\b":"\\b","\f":"\\f","\n":"\\n","\r":"\\r","\t":"\\t","\v":"\\u000b"},vg=/\uffff/.test("\uffff")?/[\\"\x00-\x1f\x7f-\uffff]/g:/[\\"\x00-\x1f\x7f-\xff]/g;function tg(a,b){b.push('"',a.replace(vg,function(c){var d=ug[c];d||(d="\\u"+(c.charCodeAt(0)|65536).toString(16).slice(1),ug[c]=d);return d}),'"')}
;function wg(){}
wg.prototype.i=null;wg.prototype.getOptions=function(){var a;(a=this.i)||(a={},xg(this)&&(a[0]=!0,a[1]=!0),a=this.i=a);return a};var yg;function zg(){}
Za(zg,wg);function Ag(a){return(a=xg(a))?new ActiveXObject(a):new XMLHttpRequest}
function xg(a){if(!a.j&&"undefined"==typeof XMLHttpRequest&&"undefined"!=typeof ActiveXObject){for(var b=["MSXML2.XMLHTTP.6.0","MSXML2.XMLHTTP.3.0","MSXML2.XMLHTTP","Microsoft.XMLHTTP"],c=0;c<b.length;c++){var d=b[c];try{return new ActiveXObject(d),a.j=d}catch(e){}}throw Error("Could not create ActiveXObject. ActiveX might be disabled, or MSXML might not be installed");}return a.j}
yg=new zg;function Bg(a){Te.call(this);this.headers=new Map;this.K=a||null;this.j=!1;this.J=this.A=null;this.o=this.T="";this.l=this.R=this.v=this.P=!1;this.s=0;this.F=null;this.da="";this.W=this.X=!1}
Za(Bg,Te);var Cg=/^https?$/i,Dg=["POST","PUT"],Gg=[];function Hg(a,b,c,d,e,f,g){var h=new Bg;Gg.push(h);b&&h.aa("complete",b);h.m.add("ready",h.yc,!0,void 0,void 0);f&&(h.s=Math.max(0,f));g&&(h.X=g);h.send(a,c,d,e)}
l=Bg.prototype;l.yc=function(){this.dispose();kb(Gg,this)};
l.send=function(a,b,c,d){if(this.A)throw Error("[goog.net.XhrIo] Object is active with another request="+this.T+"; newUri="+a);b=b?b.toUpperCase():"GET";this.T=a;this.o="";this.P=!1;this.j=!0;this.A=this.K?Ag(this.K):Ag(yg);this.J=this.K?this.K.getOptions():yg.getOptions();this.A.onreadystatechange=Xa(this.Xb,this);try{this.getStatus(),this.R=!0,this.A.open(b,String(a),!0),this.R=!1}catch(g){this.getStatus();Ig(this,g);return}a=c||"";c=new Map(this.headers);if(d)if(Object.getPrototypeOf(d)===Object.prototype)for(var e in d)c.set(e,
d[e]);else if("function"===typeof d.keys&&"function"===typeof d.get){e=p(d.keys());for(var f=e.next();!f.done;f=e.next())f=f.value,c.set(f,d.get(f))}else throw Error("Unknown input type for opt_headers: "+String(d));d=Array.from(c.keys()).find(function(g){return"content-type"==g.toLowerCase()});
e=y.FormData&&a instanceof y.FormData;!(0<=eb(Dg,b))||d||e||c.set("Content-Type","application/x-www-form-urlencoded;charset=utf-8");b=p(c);for(d=b.next();!d.done;d=b.next())c=p(d.value),d=c.next().value,c=c.next().value,this.A.setRequestHeader(d,c);this.da&&(this.A.responseType=this.da);"withCredentials"in this.A&&this.A.withCredentials!==this.X&&(this.A.withCredentials=this.X);try{Jg(this),0<this.s&&(this.W=Kg(this.A),this.getStatus(),this.W?(this.A.timeout=this.s,this.A.ontimeout=Xa(this.kc,this)):
this.F=Jf(this.kc,this.s,this)),this.getStatus(),this.v=!0,this.A.send(a),this.v=!1}catch(g){this.getStatus(),Ig(this,g)}};
function Kg(a){return Kc&&Vc()&&"number"===typeof a.timeout&&void 0!==a.ontimeout}
l.kc=function(){"undefined"!=typeof Na&&this.A&&(this.o="Timed out after "+this.s+"ms, aborting",this.getStatus(),Ue(this,"timeout"),this.abort(8))};
function Ig(a,b){a.j=!1;a.A&&(a.l=!0,a.A.abort(),a.l=!1);a.o=b;Lg(a);Mg(a)}
function Lg(a){a.P||(a.P=!0,Ue(a,"complete"),Ue(a,"error"))}
l.abort=function(){this.A&&this.j&&(this.getStatus(),this.j=!1,this.l=!0,this.A.abort(),this.l=!1,Ue(this,"complete"),Ue(this,"abort"),Mg(this))};
l.C=function(){this.A&&(this.j&&(this.j=!1,this.l=!0,this.A.abort(),this.l=!1),Mg(this,!0));Bg.Y.C.call(this)};
l.Xb=function(){this.i()||(this.R||this.v||this.l?Ng(this):this.Qc())};
l.Qc=function(){Ng(this)};
function Ng(a){if(a.j&&"undefined"!=typeof Na)if(a.J[1]&&4==Og(a)&&2==a.getStatus())a.getStatus();else if(a.v&&4==Og(a))Jf(a.Xb,0,a);else if(Ue(a,"readystatechange"),a.isComplete()){a.getStatus();a.j=!1;try{if(Pg(a))Ue(a,"complete"),Ue(a,"success");else{try{var b=2<Og(a)?a.A.statusText:""}catch(c){b=""}a.o=b+" ["+a.getStatus()+"]";Lg(a)}}finally{Mg(a)}}}
function Mg(a,b){if(a.A){Jg(a);var c=a.A,d=a.J[0]?function(){}:null;
a.A=null;a.J=null;b||Ue(a,"ready");try{c.onreadystatechange=d}catch(e){}}}
function Jg(a){a.A&&a.W&&(a.A.ontimeout=null);a.F&&(y.clearTimeout(a.F),a.F=null)}
l.isActive=function(){return!!this.A};
l.isComplete=function(){return 4==Og(this)};
function Pg(a){var b=a.getStatus();a:switch(b){case 200:case 201:case 202:case 204:case 206:case 304:case 1223:var c=!0;break a;default:c=!1}if(!c){if(b=0===b)a=lc(1,String(a.T)),!a&&y.self&&y.self.location&&(a=y.self.location.protocol.slice(0,-1)),b=!Cg.test(a?a.toLowerCase():"");c=b}return c}
function Og(a){return a.A?a.A.readyState:0}
l.getStatus=function(){try{return 2<Og(this)?this.A.status:-1}catch(a){return-1}};
l.getLastError=function(){return"string"===typeof this.o?this.o:String(this.o)};function Qg(a){I.call(this,a)}
t(Qg,I);function Rg(a){I.call(this,a,-1,Sg)}
t(Rg,I);var Sg=[1];var Tg=["platform","platformVersion","architecture","model","uaFullVersion"];new Rg;function Ug(a){I.call(this,a)}
t(Ug,I);function Vg(a){I.call(this,a,31,Wg)}
t(Vg,I);var Wg=[3,20,27];function Xg(a){I.call(this,a,17,Yg)}
t(Xg,I);var Yg=[3,5];function Zg(a){I.call(this,a,6,$g)}
t(Zg,I);var $g=[5];function ah(a){I.call(this,a)}
t(ah,I);var bh;bh=new function(a,b,c){this.j=a;this.fieldName=b;this.i=c;this.isRepeated=0;this.l=ce}(175237375,{nq:0},ah);function ch(a,b,c,d,e,f,g,h,k,m,q){Te.call(this);var r=this;this.P="";this.l=[];this.Eb="";this.Fb=this.qa=-1;this.Qa=!1;this.J=this.o=null;this.F=0;this.qc=1;this.timeoutMillis=0;this.da=!1;Te.call(this);this.Db=b||function(){};
this.v=new dh(a,f);this.oc=d;this.Pa=q;this.sc=Ya(Ye,0,1);this.T=e||null;this.K=c||null;this.W=g||!1;this.pageId=k||null;this.logger=null;this.withCredentials=!h;this.Ea=f||!1;!this.Ea&&(65<=ac("Chromium")||45<=ac("Firefox")||12<=ac("Safari")||(Ec()||C("iPad")||C("iPod"))&&Fc());a=E(new Ug,1,1);eh(this.v,a);this.s=new pg(1E4);this.j=new Hf(this.s.getValue());le(this,this.j);m=fh(this,m);Ie(this.j,"tick",m,!1,this);this.R=new Hf(6E5);le(this,this.R);Ie(this.R,"tick",m,!1,this);this.W||this.R.start();
this.Ea||(Ie(document,"visibilitychange",function(){"hidden"===document.visibilityState&&r.X()}),Ie(document,"pagehide",this.X,!1,this))}
t(ch,Te);function fh(a,b){return b?function(){b().then(function(){a.flush()})}:function(){a.flush()}}
ch.prototype.C=function(){this.X();Te.prototype.C.call(this)};
function gh(a){a.T||(a.T=.01>a.sc()?"https://www.google.com/log?format=json&hasfast=true":"https://play.google.com/log?format=json&hasfast=true");return a.T}
function hh(a,b){a.s=new pg(1>b?1:b);If(a.j,a.s.getValue())}
ch.prototype.log=function(a){a=a.clone();var b=this.qc++;E(a,21,b);this.P&&E(a,26,this.P);if(!Kd(a,1)){b=a;var c=Date.now().toString();E(b,1,c)}null!=Kd(a,15)||E(a,15,60*(new Date).getTimezoneOffset());this.o&&(b=this.o.clone(),G(a,ng,16,b));for(;1E3<=this.l.length;)this.l.shift(),++this.F;this.l.push(a);Ue(this,new ih(a));this.W||this.j.enabled||this.j.start()};
ch.prototype.flush=function(a,b){var c=this;if(0===this.l.length)a&&a();else if(this.da)jh(this);else{var d=Date.now();if(this.Fb>d&&this.qa<d)b&&b("throttled");else{var e=kh(this.v,this.l,this.F);d={};var f=this.Db();f&&(d.Authorization=f);var g=gh(this);this.K&&(d["X-Goog-AuthUser"]=this.K,g=xc(g,"authuser",this.K));this.pageId&&(d["X-Goog-PageId"]=this.pageId,g=xc(g,"pageId",this.pageId));if(f&&this.Eb===f)b&&b("stale-auth-token");else{this.l=[];this.j.enabled&&this.j.stop();this.F=0;var h=Yd(e),
k;this.J&&this.J.isSupported(h.length)&&(k=this.J.compress(h));var m={url:g,body:h,wc:1,xb:d,requestType:"POST",withCredentials:this.withCredentials,timeoutMillis:this.timeoutMillis},q=function(u){c.s.reset();If(c.j,c.s.getValue());if(u){var A=null;try{var D=JSON.parse(u.replace(")]}'\n",""));A=new Zg(D)}catch(F){}A&&(u=Number(Md(A,1,"-1")),0<u&&(c.qa=Date.now(),c.Fb=c.qa+u),A=bh.l(A))&&(A=Md(A,1,-1),-1!=A&&(c.Qa||hh(c,A)))}a&&a()},r=function(u,A){var D=Sd(e,Vg,3),F=c.s;
F.i=Math.min(3E5,2*F.i);F.j=Math.min(3E5,F.i+Math.round(.2*(Math.random()-.5)*F.i));If(c.j,c.s.getValue());401===u&&f&&(c.Eb=f);void 0===A&&(A=500<=u&&600>u||401===u||0===u);A&&(c.l=D.concat(c.l),c.W||c.j.enabled||c.j.start());b&&b("net-send-failed",u)},x=function(){c.Pa?c.Pa.send(m,q,r):c.oc(m,q,r)};
k?k.then(function(u){m.xb["Content-Encoding"]="gzip";m.xb["Content-Type"]="application/binary";m.body=u;m.wc=2;x()},function(){x()}):x()}}}};
ch.prototype.X=function(){this.flush()};
function jh(a){lh(a,function(b,c){b=xc(b,"format","json");b=window.navigator.sendBeacon(b,Yd(c));a.da&&!b&&(a.da=!1);return b})}
function lh(a,b){if(0!==a.l.length){var c=Bc(gh(a),"format");c=sc(c,"auth",a.Db(),"authuser",a.K||"0");for(var d=0;10>d&&a.l.length;++d){var e=a.l.slice(0,32),f=kh(a.v,e,a.F);if(!b(c,f))break;a.F=0;a.l=a.l.slice(e.length)}a.j.enabled&&a.j.stop()}}
function ih(){ne.call(this,"event-logged",void 0)}
t(ih,ne);function dh(a,b){this.j=b=void 0===b?!1:b;this.uach=this.locale=null;this.i=new Xg;E(this.i,2,a);b||(this.locale=document.documentElement.getAttribute("lang"));eh(this,new Ug)}
function eh(a,b){G(a.i,Ug,1,b);Kd(b,1)||E(b,1,1);a.j||(b=mh(a),Kd(b,5)||E(b,5,a.locale));a.uach&&(b=mh(a),Qd(b,Rg,9)||G(b,Rg,9,a.uach))}
function nh(a,b){var c=void 0===c?Tg:c;b(window,c).then(function(d){a.uach=d;d=mh(a);G(d,Rg,9,a.uach);return!0}).catch(function(){return!1})}
function mh(a){a=Qd(a.i,Ug,1);var b=Qd(a,Qg,11);b||(b=new Qg,G(a,Qg,11,b));return b}
function kh(a,b,c){c=void 0===c?0:c;a=a.i.clone();var d=Date.now().toString();a=E(a,4,d);b=Ud(a,Vg,3,b);c&&E(b,14,c);return b}
;function oh(a,b,c){Hg(a.url,function(d){d=d.target;if(Pg(d)){try{var e=d.A?d.A.responseText:""}catch(f){e=""}b(e)}else c(d.getStatus())},a.requestType,a.body,a.xb,a.timeoutMillis,a.withCredentials)}
;function ph(){this.l="https://play.google.com/log?format=json&hasfast=true";this.m=!1;this.s=oh;this.i=""}
;function qh(){var a=void 0===a?"":a;var b=void 0===b?!1:b;var c=void 0===c?"":c;var d=new ph;d.i="";""!=a&&(d.l=a);b&&(d.m=!0);c&&(d.j=c);a=new ch(1828,d.J?d.J:mg,"0",d.s,d.l,d.m,!1,d.R,void 0,void 0,d.B?d.B:void 0);d.v&&eh(a.v,d.v);d.j&&(b=d.j,c=mh(a.v),E(c,7,b));d.o&&(a.J=d.o);d.i&&(a.P=d.i);d.N&&((b=d.N)?(a.o||(a.o=new ng),b=Yd(b),E(a.o,4,b)):a.o&&E(a.o,4,void 0,!1));d.K&&(b=d.K,a.o||(a.o=new ng),Nd(a.o,2,b));d.F&&(b=d.F,a.Qa=!0,hh(a,b));d.P&&nh(a.v,d.P);this.i=a}
qh.prototype.flush=function(a){var b=a||[];if(b.length){a=new Zf;for(var c=[],d=0;d<b.length;d++){var e=b[d],f=e;var g=new Rf;g=E(g,1,f.j);for(var h=f,k=[],m=0;m<h.i.length;m++)k.push(h.i[m].lb);g=Nd(g,3,k);h=[];k=[];m=p(f.xa.keys());for(var q=m.next();!q.done;q=m.next())k.push(q.value.split(","));for(m=0;m<k.length;m++){q=k[m];var r=f.m;for(var x=f.nb(q)||[],u=[],A=0;A<x.length;A++){var D=x[A];D=D&&D.Jb;var F=new Wf;switch(r){case 3:Od(F,1,Yf,Number(D));break;case 2:Od(F,2,Yf,Number(D))}u.push(F)}r=
u;for(x=0;x<r.length;x++){u=r[x];A=new Tf;u=G(A,Wf,2,u);A=q;D=[];F=f;for(var N=[],O=0;O<F.i.length;O++)N.push(F.i[O].mb);F=N;for(N=0;N<F.length;N++){O=F[N];var Q=A[N],ea=new Vf;switch(O){case 3:Od(ea,1,Xf,String(Q));break;case 2:Od(ea,2,Xf,Number(Q));break;case 1:Od(ea,3,Xf,"true"==Q)}D.push(ea)}Ud(u,Vf,1,D);h.push(u)}}Ud(g,Tf,4,h);c.push(g);e.clear()}Ud(a,Rf,1,c);b=this.i;a instanceof Vg?b.log(a):(c=new Vg,a=Yd(a),a=E(c,8,a),b.log(a));this.i.flush()}};function rh(){this.o=sh();this.transport=new qh;this.i=new Kf(this.transport);this.m=new Of(this.i);this.j=new Pf(this.i);this.l=new Qf(this.i);this.Aa=window.document.location.hostname}
function sh(){var a,b,c;return null!=(c=null==(a=globalThis.performance)?void 0:null==(b=a.now)?void 0:b.call(a))?c:Date.now()}
;function th(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function uh(a){var b=this;this.Wa=!1;if(a.uq){var c;this.sa=null!=(c=a.sa)?c:new rh}c=a.program;a=a.globalName;var d=new th;this.j=d.promise;this.md=p((0,y[a].a)(c,function(e,f){Promise.resolve().then(function(){var g;if(null!=(g=b.sa)){var h=sh()-g.o;g.m.i.hb("/client_streamz/bg/fil",h,g.Aa)}d.resolve({vc:e,jd:f})})},!0)).next().value;
this.hd=d.promise.then(function(){})}
uh.prototype.snapshot=function(a){var b=this;if(this.Wa)throw Error("Already disposed");var c=sh(),d;null!=(d=this.sa)&&d.j.i.Bb("/client_streamz/bg/fsc",d.Aa);return this.j.then(function(e){var f=e.vc;return new Promise(function(g){f(function(h){var k;if(null!=(k=b.sa)){var m=sh()-c;k.l.i.hb("/client_streamz/bg/fsl",m,k.Aa)}g(h)},[a.Lb,
a.kd])})})};
uh.prototype.dispose=function(){var a;null!=(a=this.sa)&&a.i.ib();this.Wa=!0;this.j.then(function(b){(b=b.jd)&&b()})};
uh.prototype.i=function(){return this.Wa};var vh=window;Db("csi.gstatic.com");Db("googleads.g.doubleclick.net");Db("partner.googleadservices.com");Db("pubads.g.doubleclick.net");Db("securepubads.g.doubleclick.net");Db("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
function wh(a,b){a.src=Ib(b);var c,d;(c=(b=null==(d=(c=(a.ownerDocument&&a.ownerDocument.defaultView||window).document).querySelector)?void 0:d.call(c,"script[nonce]"))?b.nonce||b.getAttribute("nonce")||"":"")&&a.setAttribute("nonce",c)}
;function xh(a){var b=yh;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a(b[c],c,b)}
function zh(){var a=[];xh(function(b){a.push(b)});
return a}
var yh={Fd:"allow-forms",Gd:"allow-modals",Hd:"allow-orientation-lock",Id:"allow-pointer-lock",Jd:"allow-popups",Kd:"allow-popups-to-escape-sandbox",Ld:"allow-presentation",Md:"allow-same-origin",Nd:"allow-scripts",Od:"allow-top-navigation",Pd:"allow-top-navigation-by-user-activation"},Ah=db(function(){return zh()});
function Bh(){var a=Ch(),b={};fb(Ah(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Ch(){var a=void 0===a?document:a;return a.createElement("iframe")}
;function Dh(a){this.isValid=a}
function Eh(a){return new Dh(function(b){return b.substr(0,a.length+1).toLowerCase()===a+":"})}
var Fh=[Eh("data"),Eh("http"),Eh("https"),Eh("mailto"),Eh("ftp"),new Dh(function(a){return/^[^:]*([/?#]|$)/.test(a)})];function Gh(a){"number"==typeof a&&(a=Math.round(a)+"px");return a}
;var Hh=(new Date).getTime();var Ih="client_dev_mss_url client_dev_regex_map client_dev_root_url client_rollout_override expflag forcedCapability jsfeat jsmode mods".split(" ");ia(Ih);function Jh(a){Te.call(this);var b=this;this.v=this.l=0;this.Z=null!=a?a:{S:function(e,f){return setTimeout(e,f)},
fa:function(e){clearTimeout(e)}};
var c,d;this.j=null!=(d=null==(c=window.navigator)?void 0:c.onLine)?d:!0;this.o=function(){return w(function(e){return v(e,Kh(b),0)})};
window.addEventListener("offline",this.o);window.addEventListener("online",this.o);this.v||Lh(this)}
t(Jh,Te);function Mh(){var a=Nh;Jh.i||(Jh.i=new Jh(a));return Jh.i}
Jh.prototype.dispose=function(){window.removeEventListener("offline",this.o);window.removeEventListener("online",this.o);this.Z.fa(this.v);delete Jh.i};
Jh.prototype.L=function(){return this.j};
function Lh(a){a.v=a.Z.S(function(){var b;return w(function(c){if(1==c.i)return a.j?(null==(b=window.navigator)?0:b.onLine)?c.u(3):v(c,Kh(a),3):v(c,Kh(a),3);Lh(a);c.i=0})},3E4)}
function Kh(a,b){return a.s?a.s:a.s=new Promise(function(c){var d,e,f,g;return w(function(h){switch(h.i){case 1:return d=window.AbortController?new window.AbortController:void 0,f=null==(e=d)?void 0:e.signal,g=!1,wa(h,2,3),d&&(a.l=a.Z.S(function(){d.abort()},b||2E4)),v(h,fetch("/generate_204",{method:"HEAD",
signal:f}),5);case 5:g=!0;case 3:Ba(h);a.s=void 0;a.l&&(a.Z.fa(a.l),a.l=0);g!==a.j&&(a.j=g,a.j?Ue(a,"networkstatus-online"):Ue(a,"networkstatus-offline"));c(g);Ca(h);break;case 2:ya(h),g=!1,h.u(3)}})})}
;var Oh={Lh:"EMBEDDED_PLAYER_MODE_UNKNOWN",Ih:"EMBEDDED_PLAYER_MODE_DEFAULT",Kh:"EMBEDDED_PLAYER_MODE_PFP",Jh:"EMBEDDED_PLAYER_MODE_PFL"},Ph={Pp:"WEB_DISPLAY_MODE_UNKNOWN",Lp:"WEB_DISPLAY_MODE_BROWSER",Np:"WEB_DISPLAY_MODE_MINIMAL_UI",Op:"WEB_DISPLAY_MODE_STANDALONE",Mp:"WEB_DISPLAY_MODE_FULLSCREEN"};function Qh(){this.data_=[];this.i=-1}
Qh.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&Number.isInteger(a)&&this.data_[a]!==b&&(this.data_[a]=b,this.i=-1)};
Qh.prototype.get=function(a){return!!this.data_[a]};
function Rh(a){-1===a.i&&(a.i=ib(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function Sh(a,b){this.i=a[y.Symbol.iterator]();this.j=b}
Sh.prototype[Symbol.iterator]=function(){return this};
Sh.prototype.next=function(){var a=this.i.next();return{value:a.done?void 0:this.j.call(void 0,a.value),done:a.done}};
function Th(a,b){return new Sh(a,b)}
;function Uh(){this.blockSize=-1}
;function Vh(){this.blockSize=-1;this.blockSize=64;this.i=[];this.o=[];this.s=[];this.l=[];this.l[0]=128;for(var a=1;a<this.blockSize;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
Za(Vh,Uh);Vh.prototype.reset=function(){this.i[0]=1732584193;this.i[1]=4023233417;this.i[2]=2562383102;this.i[3]=271733878;this.i[4]=3285377520;this.m=this.j=0};
function Wh(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.i[0];c=a.i[1];var g=a.i[2],h=a.i[3],k=a.i[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var m=1518500249}else f=c^g^h,m=1859775393;else 60>e?(f=c&g|h&(c|g),m=2400959708):
(f=c^g^h,m=3395469782);f=(b<<5|b>>>27)+f+k+m+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.i[0]=a.i[0]+b&4294967295;a.i[1]=a.i[1]+c&4294967295;a.i[2]=a.i[2]+g&4294967295;a.i[3]=a.i[3]+h&4294967295;a.i[4]=a.i[4]+k&4294967295}
Vh.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.o,f=this.j;d<b;){if(0==f)for(;d<=c;)Wh(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){Wh(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){Wh(this,e);f=0;break}}this.j=f;this.m+=b}};
Vh.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.blockSize-(this.j-56));for(var c=this.blockSize-1;56<=c;c--)this.o[c]=b&255,b/=256;Wh(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.i[c]>>d&255,++b;return a};function Xh(a){return"string"==typeof a.className?a.className:a.getAttribute&&a.getAttribute("class")||""}
function Yh(a,b){"string"==typeof a.className?a.className=b:a.setAttribute&&a.setAttribute("class",b)}
function Zh(a,b){a.classList?b=a.classList.contains(b):(a=a.classList?a.classList:Xh(a).match(/\S+/g)||[],b=0<=eb(a,b));return b}
function $h(){var a=document.body;a.classList?a.classList.remove("inverted-hdpi"):Zh(a,"inverted-hdpi")&&Yh(a,Array.prototype.filter.call(a.classList?a.classList:Xh(a).match(/\S+/g)||[],function(b){return"inverted-hdpi"!=b}).join(" "))}
;function ai(){}
ai.prototype.next=function(){return bi};
var bi={done:!0,value:void 0};function ci(a){return{value:a,done:!1}}
ai.prototype.ea=function(){return this};function di(a){if(a instanceof ei||a instanceof fi||a instanceof gi)return a;if("function"==typeof a.next)return new ei(function(){return a});
if("function"==typeof a[Symbol.iterator])return new ei(function(){return a[Symbol.iterator]()});
if("function"==typeof a.ea)return new ei(function(){return a.ea()});
throw Error("Not an iterator or iterable.");}
function ei(a){this.j=a}
ei.prototype.ea=function(){return new fi(this.j())};
ei.prototype[Symbol.iterator]=function(){return new gi(this.j())};
ei.prototype.i=function(){return new gi(this.j())};
function fi(a){this.j=a}
t(fi,ai);fi.prototype.next=function(){return this.j.next()};
fi.prototype[Symbol.iterator]=function(){return new gi(this.j)};
fi.prototype.i=function(){return new gi(this.j)};
function gi(a){ei.call(this,function(){return a});
this.l=a}
t(gi,ei);gi.prototype.next=function(){return this.l.next()};function hi(a,b){this.j={};this.i=[];this.na=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof hi)for(c=a.qb(),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
l=hi.prototype;l.qb=function(){ii(this);return this.i.concat()};
l.has=function(a){return ji(this.j,a)};
l.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||ki;ii(this);for(var c,d=0;c=this.i[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function ki(a,b){return a===b}
l.isEmpty=function(){return 0==this.size};
l.clear=function(){this.j={};this.na=this.size=this.i.length=0};
l.remove=function(a){return this.delete(a)};
l.delete=function(a){return ji(this.j,a)?(delete this.j[a],--this.size,this.na++,this.i.length>2*this.size&&ii(this),!0):!1};
function ii(a){if(a.size!=a.i.length){for(var b=0,c=0;b<a.i.length;){var d=a.i[b];ji(a.j,d)&&(a.i[c++]=d);b++}a.i.length=c}if(a.size!=a.i.length){var e={};for(c=b=0;b<a.i.length;)d=a.i[b],ji(e,d)||(a.i[c++]=d,e[d]=1),b++;a.i.length=c}}
l.get=function(a,b){return ji(this.j,a)?this.j[a]:b};
l.set=function(a,b){ji(this.j,a)||(this.size+=1,this.i.push(a),this.na++);this.j[a]=b};
l.forEach=function(a,b){for(var c=this.qb(),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
l.clone=function(){return new hi(this)};
l.keys=function(){return di(this.ea(!0)).i()};
l.values=function(){return di(this.ea(!1)).i()};
l.entries=function(){var a=this;return Th(this.keys(),function(b){return[b,a.get(b)]})};
l.ea=function(a){ii(this);var b=0,c=this.na,d=this,e=new ai;e.next=function(){if(c!=d.na)throw Error("The map has changed since the iterator was created");if(b>=d.i.length)return bi;var f=d.i[b++];return ci(a?f:d.j[f])};
return e};
function ji(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;function K(a){J.call(this);this.s=1;this.m=[];this.o=0;this.j=[];this.l={};this.v=!!a}
Za(K,J);l=K.prototype;l.subscribe=function(a,b,c){var d=this.l[a];d||(d=this.l[a]=[]);var e=this.s;this.j[e]=a;this.j[e+1]=b;this.j[e+2]=c;this.s=e+3;d.push(e);return e};
function li(a,b,c,d){if(b=a.l[b]){var e=a.j;(b=b.find(function(f){return e[f+1]==c&&e[f+2]==d}))&&a.Da(b)}}
l.Da=function(a){var b=this.j[a];if(b){var c=this.l[b];0!=this.o?(this.m.push(a),this.j[a+1]=function(){}):(c&&kb(c,a),delete this.j[a],delete this.j[a+1],delete this.j[a+2])}return!!b};
l.oa=function(a,b){var c=this.l[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.v)for(e=0;e<c.length;e++){var g=c[e];mi(this.j[g+1],this.j[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f&&!this.i();e++)g=c[e],this.j[g+1].apply(this.j[g+2],d)}finally{if(this.o--,0<this.m.length&&0==this.o)for(;c=this.m.pop();)this.Da(c)}}return 0!=e}return!1};
function mi(a,b,c){nf(function(){a.apply(b,c)})}
l.clear=function(a){if(a){var b=this.l[a];b&&(b.forEach(this.Da,this),delete this.l[a])}else this.j.length=0,this.l={}};
l.C=function(){K.Y.C.call(this);this.clear();this.m.length=0};function ni(a){this.i=a}
ni.prototype.set=function(a,b){void 0===b?this.i.remove(a):this.i.set(a,qg(b))};
ni.prototype.get=function(a){try{var b=this.i.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
ni.prototype.remove=function(a){this.i.remove(a)};function oi(a){this.i=a}
Za(oi,ni);function pi(a){this.data=a}
function qi(a){return void 0===a||a instanceof pi?a:new pi(a)}
oi.prototype.set=function(a,b){oi.Y.set.call(this,a,qi(b))};
oi.prototype.j=function(a){a=oi.Y.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
oi.prototype.get=function(a){if(a=this.j(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function ri(a){this.i=a}
Za(ri,oi);ri.prototype.set=function(a,b,c){if(b=qi(b)){if(c){if(c<Date.now()){ri.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}ri.Y.set.call(this,a,b)};
ri.prototype.j=function(a){var b=ri.Y.j.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())ri.prototype.remove.call(this,a);else return b}};function si(){}
;function ti(){}
Za(ti,si);ti.prototype[Symbol.iterator]=function(){return di(this.ea(!0)).i()};
ti.prototype.clear=function(){var a=Array.from(this);a=p(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function ui(a){this.i=a}
Za(ui,ti);l=ui.prototype;l.isAvailable=function(){if(!this.i)return!1;try{return this.i.setItem("__sak","1"),this.i.removeItem("__sak"),!0}catch(a){return!1}};
l.set=function(a,b){try{this.i.setItem(a,b)}catch(c){if(0==this.i.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
l.get=function(a){a=this.i.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeItem(a)};
l.ea=function(a){var b=0,c=this.i,d=new ai;d.next=function(){if(b>=c.length)return bi;var e=c.key(b++);if(a)return ci(e);e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return ci(e)};
return d};
l.clear=function(){this.i.clear()};
l.key=function(a){return this.i.key(a)};function vi(){var a=null;try{a=window.localStorage||null}catch(b){}this.i=a}
Za(vi,ui);function wi(a,b){this.j=a;this.i=null;var c;if(c=Kc)c=!(9<=Number(Yc));if(c){xi||(xi=new hi);this.i=xi.get(a);this.i||(b?this.i=document.getElementById(b):(this.i=document.createElement("userdata"),this.i.addBehavior("#default#userData"),document.body.appendChild(this.i)),xi.set(a,this.i));try{this.i.load(this.j)}catch(d){this.i=null}}}
Za(wi,ti);var yi={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},xi=null;function zi(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return yi[b]})}
l=wi.prototype;l.isAvailable=function(){return!!this.i};
l.set=function(a,b){this.i.setAttribute(zi(a),b);Ai(this)};
l.get=function(a){a=this.i.getAttribute(zi(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
l.remove=function(a){this.i.removeAttribute(zi(a));Ai(this)};
l.ea=function(a){var b=0,c=this.i.XMLDocument.documentElement.attributes,d=new ai;d.next=function(){if(b>=c.length)return bi;var e=c[b++];if(a)return ci(decodeURIComponent(e.nodeName.replace(/\./g,"%")).slice(1));e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return ci(e)};
return d};
l.clear=function(){for(var a=this.i.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Ai(this)};
function Ai(a){try{a.i.save(a.j)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Bi(a,b){this.j=a;this.i=b+"::"}
Za(Bi,ti);Bi.prototype.set=function(a,b){this.j.set(this.i+a,b)};
Bi.prototype.get=function(a){return this.j.get(this.i+a)};
Bi.prototype.remove=function(a){this.j.remove(this.i+a)};
Bi.prototype.ea=function(a){var b=this.j[Symbol.iterator](),c=this,d=new ai;d.next=function(){var e=b.next();if(e.done)return e;for(e=e.value;e.slice(0,c.i.length)!=c.i;){e=b.next();if(e.done)return e;e=e.value}return ci(a?e.slice(c.i.length):c.j.get(e))};
return d};function Ci(a){I.call(this,a)}
t(Ci,I);function Di(a){I.call(this,a)}
t(Di,I);Di.prototype.getKey=function(){return Kd(this,1)};
Di.prototype.getValue=function(){return Kd(this,2===Pd(this,Ei)?2:-1)};
Di.prototype.setValue=function(a){return Od(this,2,Ei,a)};
var Ei=[2,3,4,5,6];function Fi(a){I.call(this,a)}
t(Fi,I);function Gi(a){I.call(this,a)}
t(Gi,I);function Hi(a){I.call(this,a,-1,Ii)}
t(Hi,I);var Ii=[2];function Ji(a){I.call(this,a,-1,Ki)}
t(Ji,I);Ji.prototype.getPlayerType=function(){return Kd(this,36)};
Ji.prototype.setHomeGroupInfo=function(a){return G(this,Hi,81,a)};
var Ki=[9,66,24,32,86,100,101];function Li(a){I.call(this,a,-1,Mi)}
t(Li,I);var Mi=[15,26,28];function Ni(a){I.call(this,a)}
t(Ni,I);Ni.prototype.setToken=function(a){return E(this,2,a)};function Oi(a){I.call(this,a,-1,Pi)}
t(Oi,I);Oi.prototype.setSafetyMode=function(a){return E(this,5,a)};
var Pi=[12];function Qi(a){I.call(this,a,-1,Ri)}
t(Qi,I);Qi.prototype.s=function(a){G(this,Ji,1,a)};
var Ri=[12];function Si(a){I.call(this,a,-1,Ti)}
t(Si,I);function Ui(a){I.call(this,a)}
t(Ui,I);Ui.prototype.getKey=function(){return Md(this,1,"")};
Ui.prototype.getValue=function(){return Md(this,2,"")};
Ui.prototype.setValue=function(a){return E(this,2,a)};
var Ti=[4,5];function Vi(a){I.call(this,a)}
t(Vi,I);function Wi(a){I.call(this,a)}
t(Wi,I);var Xi=[2,3,4];function Yi(a){I.call(this,a)}
t(Yi,I);Yi.prototype.getMessage=function(){return Md(this,1,"")};function Zi(a){I.call(this,a)}
t(Zi,I);function $i(a){I.call(this,a)}
t($i,I);function aj(a){I.call(this,a,-1,bj)}
t(aj,I);var bj=[10,17];function cj(a){I.call(this,a)}
t(cj,I);function dj(a){I.call(this,a)}
t(dj,I);dj.prototype.V=function(a){E(this,1,a)};function ej(a){I.call(this,a)}
t(ej,I);function fj(a){I.call(this,a)}
t(fj,I);function gj(a){I.call(this,a)}
t(gj,I);function hj(a){I.call(this,a,-1,ij)}
t(hj,I);hj.prototype.getVideoData=function(){return Qd(this,gj,15)};
var ij=[4];function jj(a){I.call(this,a)}
t(jj,I);function kj(a,b){G(a,ej,1,b)}
jj.prototype.V=function(a){E(this,2,a)};
function lj(a){I.call(this,a)}
t(lj,I);function mj(a,b){G(a,ej,1,b)}
;function nj(a){I.call(this,a,-1,oj)}
t(nj,I);nj.prototype.V=function(a){E(this,1,a)};
function pj(a,b){G(a,ej,2,b)}
var oj=[3];function qj(a){I.call(this,a)}
t(qj,I);qj.prototype.V=function(a){E(this,1,a)};function rj(a){I.call(this,a)}
t(rj,I);rj.prototype.V=function(a){E(this,1,a)};function sj(a){I.call(this,a)}
t(sj,I);sj.prototype.V=function(a){E(this,1,a)};function tj(a){I.call(this,a)}
t(tj,I);tj.prototype.V=function(a){E(this,1,a)};function uj(a){I.call(this,a)}
t(uj,I);function vj(a){I.call(this,a)}
t(vj,I);function wj(a){I.call(this,a,-1,xj)}
t(wj,I);function yj(a,b){return E(a,1,b)}
wj.prototype.getPlayerType=function(){return Md(this,7,0)};
wj.prototype.setVideoId=function(a){return E(this,19,a)};
function zj(a,b){return E(a,25,b)}
function Aj(a,b){Vd(a,68,Bj,b)}
function Bj(a){I.call(this,a)}
t(Bj,I);Bj.prototype.getId=function(){return Md(this,2,"")};
var xj=[83,68];function Cj(a){I.call(this,a)}
t(Cj,I);function Dj(a){I.call(this,a)}
t(Dj,I);function Ej(a){I.call(this,a)}
t(Ej,I);function Fj(a){I.call(this,a,432)}
t(Fj,I);
var Gj=[23,24,11,6,7,5,2,3,13,20,21,22,28,32,37,229,241,45,59,225,288,72,73,78,208,156,202,215,74,76,79,80,111,85,91,97,100,102,105,119,126,127,136,146,148,151,157,158,159,163,164,168,176,222,383,177,178,179,411,184,188,189,190,191,193,194,195,196,197,198,199,200,201,402,320,203,204,205,206,258,259,260,261,327,209,219,226,227,232,233,234,240,244,247,248,249,251,256,257,266,254,255,270,272,278,291,293,300,304,308,309,310,311,313,314,319,321,323,324,328,330,331,332,334,337,338,340,344,348,350,351,352,
353,354,355,356,357,358,361,363,364,368,369,370,373,374,375,378,380,381,388,389,403,410,412,429,413,414,415,416,417,418,430,423,424,425,426,427,431,117];var Hj={Li:0,wi:1,Ci:2,Di:4,Ii:8,Ei:16,Fi:32,Ki:64,Ji:128,yi:256,Ai:512,Hi:1024,zi:2048,Bi:4096,xi:8192,Gi:16384};function Ij(a){I.call(this,a)}
t(Ij,I);function Jj(a){I.call(this,a)}
t(Jj,I);Jj.prototype.setVideoId=function(a){return Od(this,1,Kj,a)};
Jj.prototype.getPlaylistId=function(){return Kd(this,2===Pd(this,Kj)?2:-1)};
var Kj=[1,2];function Lj(a){I.call(this,a,-1,hk)}
t(Lj,I);var hk=[3];function ik(a,b){1<b.length?a[b[0]]=b[1]:1===b.length&&Object.assign(a,b[0])}
;var jk=y.window,kk,lk,mk=(null==jk?void 0:null==(kk=jk.yt)?void 0:kk.config_)||(null==jk?void 0:null==(lk=jk.ytcfg)?void 0:lk.data_)||{};z("yt.config_",mk);function nk(){ik(mk,arguments)}
function L(a,b){return a in mk?mk[a]:b}
function ok(){var a=mk.EXPERIMENT_FLAGS;return a?a.web_disable_gel_stp_ecatcher_killswitch:void 0}
;function M(a){a=pk(a);return"string"===typeof a&&"false"===a?!1:!!a}
function qk(a,b){a=pk(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function rk(){return L("EXPERIMENTS_TOKEN","")}
function pk(a){var b=L("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:L("EXPERIMENT_FLAGS",{})[a]}
function sk(){var a=[],b=L("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=L("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var tk=[];function uk(a){tk.forEach(function(b){return b(a)})}
function vk(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){wk(b)}}:a}
function wk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=L("ERRORS",[]),e.push([a,"ERROR",b,c,d]),nk("ERRORS",e));uk(a)}
function xk(a,b,c,d){var e=B("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=L("ERRORS",[]),e.push([a,"WARNING",b,c,d]),nk("ERRORS",e))}
;function yk(){var a=zk;B("yt.ads.biscotti.getId_")||z("yt.ads.biscotti.getId_",a)}
function Ak(a){z("yt.ads.biscotti.lastId_",a)}
;var Bk=/^[\w.]*$/,Ck={q:!0,search_query:!0};function Dk(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=Ek(f[0]||""),h=Ek(f[1]||"");g in c?Array.isArray(c[g])?lb(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(r){var k=r,m=f[0],q=String(Dk);k.args=[{key:m,value:f[1],query:a,method:Fk==q?"unchanged":q}];Ck.hasOwnProperty(m)||xk(k)}}return c}
var Fk=String(Dk);function Gk(a){var b=[];mb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];fb(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function Hk(a){"?"==a.charAt(0)&&(a=a.substr(1));return Dk(a,"&")}
function Ik(a){return-1!=a.indexOf("?")?(a=(a||"").split("#")[0],a=a.split("?",2),Hk(1<a.length?a[1]:a[0])):{}}
function Jk(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=Hk(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);return tc(a,e)+d}
function Kk(a){if(!b)var b=window.location.href;var c=lc(1,a),d=mc(a);c&&d?(a=a.match(jc),b=b.match(jc),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?mc(b)==d&&(Number(lc(4,b))||null)==(Number(lc(4,a))||null):!0;return a}
function Ek(a){return a&&a.match(Bk)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Lk(a){var b=Mk;a=void 0===a?B("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Hh;e.flash="0";a:{try{var f=b.i.top.location.href}catch(za){f=2;break a}f=f?f===b.j.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?vh:g;try{var h=g.history.length}catch(za){h=0}e.u_his=h;var k;e.u_h=null==(k=vh.screen)?void 0:k.height;var m;e.u_w=null==(m=vh.screen)?void 0:m.width;var q;e.u_ah=null==(q=vh.screen)?void 0:q.availHeight;var r;e.u_aw=
null==(r=vh.screen)?void 0:r.availWidth;var x;e.u_cd=null==(x=vh.screen)?void 0:x.colorDepth}catch(za){}h=b.i;try{var u=h.screenX;var A=h.screenY}catch(za){}try{var D=h.outerWidth;var F=h.outerHeight}catch(za){}try{var N=h.innerWidth;var O=h.innerHeight}catch(za){}try{var Q=h.screenLeft;var ea=h.screenTop}catch(za){}try{N=h.innerWidth,O=h.innerHeight}catch(za){}try{var ba=h.screen.availWidth;var la=h.screen.availTop}catch(za){}u=[Q,ea,u,A,ba,la,D,F,N,O];try{var X=(b.i.top||window).document,Aa="CSS1Compat"==
X.compatMode?X.documentElement:X.body;var H=(new $e(Aa.clientWidth,Aa.clientHeight)).round()}catch(za){H=new $e(-12245933,-12245933)}X=H;H={};var Ga=void 0===Ga?y:Ga;Aa=new Qh;Ga.SVGElement&&Ga.document.createElementNS&&Aa.set(0);A=Bh();A["allow-top-navigation-by-user-activation"]&&Aa.set(1);A["allow-popups-to-escape-sandbox"]&&Aa.set(2);Ga.crypto&&Ga.crypto.subtle&&Aa.set(3);Ga.TextDecoder&&Ga.TextEncoder&&Aa.set(4);Ga=Rh(Aa);H.bc=Ga;H.bih=X.height;H.biw=X.width;H.brdim=u.join();b=b.j;b=(H.vis=b.prerendering?
3:{visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,H.wgl=!!vh.WebGLRenderingContext,H);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Mk=new function(){var a=window.document;this.i=window;this.j=a};
z("yt.ads_.signals_.getAdSignalsString",function(a){return Gk(Lk(a))});Date.now();var Nk="XMLHttpRequest"in y?function(){return new XMLHttpRequest}:null;
function Ok(){if(!Nk)return null;var a=Nk();return"open"in a?a:null}
function Pk(a){switch(a&&"status"in a?a.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:return!0;default:return!1}}
;function Qk(a,b){"function"===typeof a&&(a=vk(a));return window.setTimeout(a,b)}
function Rk(a){window.clearTimeout(a)}
;var Sk={Authorization:"AUTHORIZATION","X-Goog-EOM-Visitor-Id":"EOM_VISITOR_DATA","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL",
"X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Tk="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ia(Ih)),Uk=!1;
function Vk(a,b){b=void 0===b?{}:b;var c=Kk(a),d=M("web_ajax_ignore_global_headers_if_set"),e;for(e in Sk){var f=L(Sk[e]);M("enable_visitor_header_for_vss")&&"X-Goog-Visitor-Id"===e&&!f&&(f=L("VISITOR_DATA"));!f||!c&&mc(a)||d&&void 0!==b[e]||!M("enable_web_eom_visitor_data")&&"X-Goog-EOM-Visitor-Id"===e||(b[e]=f)}"X-Goog-EOM-Visitor-Id"in b&&"X-Goog-Visitor-Id"in b&&delete b["X-Goog-Visitor-Id"];if(c||!mc(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!mc(a)){try{var g=
(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!mc(a))b["X-YouTube-Ad-Signals"]=Gk(Lk());return b}
function Wk(a){var b=window.location.search,c=mc(a);M("debug_handle_relative_url_for_query_forward_killswitch")||c||!Kk(a)||(c=document.location.hostname);var d=kc(lc(5,a));d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=Hk(b),f={};fb(Tk,function(g){e[g]&&(f[g]=e[g])});
return Jk(a,f||{},!1)}
function Xk(a,b){var c=b.format||"JSON";a=Yk(a,b);var d=Zk(a,b),e=!1,f=$k(a,function(k){if(!e){e=!0;h&&Rk(h);var m=Pk(k),q=null,r=400<=k.status&&500>k.status,x=500<=k.status&&600>k.status;if(m||r||x)q=al(a,c,k,b.convertToSafeHtml);if(m)a:if(k&&204==k.status)m=!0;else{switch(c){case "XML":m=0==parseInt(q&&q.return_code,10);break a;case "RAW":m=!0;break a}m=!!q}q=q||{};r=b.context||y;m?b.onSuccess&&b.onSuccess.call(r,k,q):b.onError&&b.onError.call(r,k,q);b.onFinish&&b.onFinish.call(r,k,q)}},b.method,
d,b.headers,b.responseType,b.withCredentials);
d=b.timeout||0;if(b.onTimeout&&0<d){var g=b.onTimeout;var h=Qk(function(){e||(e=!0,f.abort(),Rk(h),g.call(b.context||y,f))},d)}return f}
function Yk(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=L("XSRF_FIELD_NAME");if(b=b.urlParams)b[c]&&delete b[c],a=Jk(a,b||{},!0);return a}
function Zk(a,b){var c=L("XSRF_FIELD_NAME"),d=L("XSRF_TOKEN"),e=b.postBody||"",f=b.postParams,g=L("XSRF_FIELD_NAME"),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||mc(a)&&!b.withCredentials&&mc(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=Hk(e),wb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):rc(e));f=e||f&&!pb(f);!Uk&&f&&"POST"!=b.method&&(Uk=
!0,wk(Error("AJAX request with postData should use POST")));return e}
function al(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,xk(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?bl(a):null)e={},fb(a.getElementsByTagName("*"),function(g){e[g.tagName]=cl(g)})}d&&dl(e);
return e}
function dl(a){if(Ra(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;Db("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=a[b],e=yb();d=e?e.createHTML(d):d;a[c]=new cc(d)}else dl(a[b])}}
function bl(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function cl(a){var b="";fb(a.childNodes,function(c){b+=c.nodeValue});
return b}
function $k(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&vk(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Ok();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;M("debug_forward_web_query_parameters")&&(a=Wk(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Vk(a,e))for(var m in e)k.setRequestHeader(m,e[m]),"content-type"==m.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;function el(a){var b=this;this.j=void 0;this.i=!1;a.addEventListener("beforeinstallprompt",function(c){c.preventDefault();b.j=c});
a.addEventListener("appinstalled",function(){b.i=!0},{once:!0})}
function fl(){if(!y.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return y.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":y.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":y.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":y.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;function gl(a,b,c,d,e){ig.set(""+a,b,{ab:c,path:"/",domain:void 0===d?"youtube.com":d,secure:void 0===e?!1:e})}
function hl(){if(!ig.isEnabled())return!1;if(!ig.isEmpty())return!0;ig.set("TESTCOOKIESENABLED","1",{ab:60});if("1"!==ig.get("TESTCOOKIESENABLED"))return!1;ig.remove("TESTCOOKIESENABLED");return!0}
;var il=B("ytglobal.prefsUserPrefsPrefs_")||{};z("ytglobal.prefsUserPrefsPrefs_",il);function jl(){this.i=L("ALT_PREF_COOKIE_NAME","PREF");this.j=L("ALT_PREF_COOKIE_DOMAIN","youtube.com");var a=ig.get(""+this.i,void 0);if(a){a=decodeURIComponent(a).split("&");for(var b=0;b<a.length;b++){var c=a[b].split("="),d=c[0];(c=c[1])&&(il[d]=c.toString())}}}
jl.prototype.get=function(a,b){kl(a);ll(a);a=void 0!==il[a]?il[a].toString():null;return null!=a?a:b?b:""};
jl.prototype.set=function(a,b){kl(a);ll(a);if(null==b)throw Error("ExpectedNotNull");il[a]=b.toString()};
function ml(a){return!!((nl("f"+(Math.floor(a/31)+1))||0)&1<<a%31)}
jl.prototype.remove=function(a){kl(a);ll(a);delete il[a]};
jl.prototype.clear=function(){for(var a in il)delete il[a]};
function ll(a){if(/^f([1-9][0-9]*)$/.test(a))throw Error("ExpectedRegexMatch: "+a);}
function kl(a){if(!/^\w+$/.test(a))throw Error("ExpectedRegexMismatch: "+a);}
function nl(a){a=void 0!==il[a]?il[a].toString():null;return null!=a&&/^[A-Fa-f0-9]+$/.test(a)?parseInt(a,16):null}
Oa(jl);var ol={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},pl={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},ql={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},rl={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function sl(){var a=y.navigator;return a?a.connection:void 0}
function tl(){var a=sl();if(a){var b=ol[a.type||"unknown"]||"CONN_UNKNOWN";a=ol[a.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===b&&"CONN_UNKNOWN"!==a&&(b=a);if("CONN_UNKNOWN"!==b)return b;if("CONN_UNKNOWN"!==a)return a}}
function ul(){var a=sl();if(null!=a&&a.effectiveType)return rl.hasOwnProperty(a.effectiveType)?rl[a.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN"}
;function vl(){return"INNERTUBE_API_KEY"in mk&&"INNERTUBE_API_VERSION"in mk}
function wl(){return{innertubeApiKey:L("INNERTUBE_API_KEY"),innertubeApiVersion:L("INNERTUBE_API_VERSION"),rb:L("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Sb:L("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),Ic:L("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:L("INNERTUBE_CONTEXT_CLIENT_VERSION"),Ub:L("INNERTUBE_CONTEXT_HL"),Tb:L("INNERTUBE_CONTEXT_GL"),Jc:L("INNERTUBE_HOST_OVERRIDE")||"",Lc:!!L("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),Kc:!!L("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:L("SERIALIZED_CLIENT_CONFIG_DATA")}}
function xl(a){var b={client:{hl:a.Ub,gl:a.Tb,clientName:a.Sb,clientVersion:a.innertubeContextClientVersion,configInfo:a.rb}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=y.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=rk();""!==c&&(b.client.experimentsToken=c);c=sk();0<c.length&&(b.request={internalExperimentFlags:c});yl(a,void 0,b);zl(void 0,b);Al(a,void 0,b);Bl(void 0,b);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(b.user={onBehalfOfUser:L("DELEGATED_SESSION_ID")});
a=Object;c=a.assign;for(var d=b.client,e={},f=p(Object.entries(Hk(L("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=p(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Cl(a){var b=new Qi,c=new Ji;E(c,1,a.Ub);E(c,2,a.Tb);E(c,16,a.Ic);E(c,17,a.innertubeContextClientVersion);if(a.rb){var d=a.rb,e=new Fi;d.coldConfigData&&E(e,1,d.coldConfigData);d.appInstallData&&E(e,6,d.appInstallData);d.coldHashData&&E(e,3,d.coldHashData);d.hotHashData&&E(e,5,d.hotHashData);G(c,Fi,62,e)}(d=y.devicePixelRatio)&&1!=d&&E(c,65,d);d=rk();""!==d&&E(c,54,d);d=sk();if(0<d.length){e=new Li;for(var f=0;f<d.length;f++){var g=new Di;E(g,1,d[f].key);g.setValue(d[f].value);Vd(e,15,Di,
g)}G(b,Li,5,e)}yl(a,c);zl(c);Al(a,c);Bl(c);L("DELEGATED_SESSION_ID")&&!M("pageid_as_header_web")&&(a=new Oi,E(a,3,L("DELEGATED_SESSION_ID")));a=p(Object.entries(Hk(L("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=p(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?E(c,12,e):"cmodel"===d?E(c,13,e):"cbr"===d?E(c,87,e):"cbrver"===d?E(c,88,e):"cos"===d?E(c,18,e):"cosver"===d?E(c,19,e):"cplatform"===d&&E(c,42,e);b.s(c);return b}
function yl(a,b,c){a=a.Sb;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Qd(b,Gi,96)||new Gi;var d=fl();d=Object.keys(Ph).indexOf(d);d=-1===d?null:d;null!==d&&E(c,3,d);G(b,Gi,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=fl())}
function zl(a,b){var c;if(M("web_log_memory_total_kbytes")&&(null==(c=y.navigator)?0:c.deviceMemory)){var d;c=null==(d=y.navigator)?void 0:d.deviceMemory;a?E(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Al(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Qd(b,Fi,62))?d:new Fi;E(c,6,a.appInstallData);G(b,Fi,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Bl(a,b){var c=tl();c&&(a?E(a,61,pl[c]):b&&(b.client.connectionType=c));M("web_log_effective_connection_type")&&(c=ul())&&(a?E(a,94,ql[c]):b&&(b.client.effectiveConnectionType=c))}
function Dl(a,b,c){c=void 0===c?{}:c;var d={};M("enable_web_eom_visitor_data")&&L("EOM_VISITOR_DATA")?d={"X-Goog-EOM-Visitor-Id":L("EOM_VISITOR_DATA")}:d={"X-Goog-Visitor-Id":c.visitorData||L("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.gq||L("AUTHORIZATION"))||(a?b="Bearer "+B("gapi.auth.getToken")().fq:b=mg([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=L("SESSION_INDEX",0),M("pageid_as_header_web")&&(d["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return d}
;function El(a){a=Object.assign({},a);delete a.Authorization;var b=mg();if(b){var c=new Vh;c.update(L("INNERTUBE_API_KEY"));c.update(b);a.hash=dd(c.digest(),3)}return a}
;function Fl(a){var b=new vi;(b=b.isAvailable()?a?new Bi(b,a):b:null)||(a=new wi(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.i=(a=b)?new ri(a):null;this.j=document.domain||window.location.hostname}
Fl.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.i)try{this.i.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(qg(b))}catch(f){return}else e=escape(b);gl(a,e,c,this.j)};
Fl.prototype.get=function(a,b){var c=void 0,d=!this.i;if(!d)try{c=this.i.get(a)}catch(e){d=!0}if(d&&(c=ig.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Fl.prototype.remove=function(a){this.i&&this.i.remove(a);var b=this.j;ig.remove(""+a,"/",void 0===b?"youtube.com":b)};var Gl=window,P=Gl.ytcsi&&Gl.ytcsi.now?Gl.ytcsi.now:Gl.performance&&Gl.performance.timing&&Gl.performance.now&&Gl.performance.timing.navigationStart?function(){return Gl.performance.timing.navigationStart+Gl.performance.now()}:function(){return(new Date).getTime()};var Hl;function Il(){Hl||(Hl=new Fl("yt.innertube"));return Hl}
function Jl(a,b,c,d){if(d)return null;d=Il().get("nextId",!0)||1;var e=Il().get("requests",!0)||{};e[d]={method:a,request:b,authState:El(c),requestTime:Math.round(P())};Il().set("nextId",d+1,86400,!0);Il().set("requests",e,86400,!0);return d}
function Kl(a){var b=Il().get("requests",!0)||{};delete b[a];Il().set("requests",b,86400,!0)}
function Ll(a){var b=Il().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(P())-d.requestTime)){var e=d.authState,f=El(Dl(!1));sb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(P())),Ml(a,d.method,e,{}));delete b[c]}}Il().set("requests",b,86400,!0)}}
;function Nl(){}
Nl.prototype.S=function(a,b){return Ol(a,1,b)};
function Pl(a,b){Ol(a,2,b)}
function Ql(a){var b=B("yt.scheduler.instance.addImmediateJob");b?b(a):a()}
;function Rl(){Nl.apply(this,arguments)}
t(Rl,Nl);function Sl(){Rl.i||(Rl.i=new Rl);return Rl.i}
function Ol(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=B("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):Qk(a,c||0)}
Rl.prototype.fa=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=B("yt.scheduler.instance.cancelJob");b?b(a):Rk(a)}};
Rl.prototype.start=function(){var a=B("yt.scheduler.instance.start");a&&a()};
Rl.prototype.pause=function(){var a=B("yt.scheduler.instance.pause");a&&a()};var Nh=Sl();var Tl=Zc||$c;function Ul(a){var b=Rb();return b?0<=b.toLowerCase().indexOf(a):!1}
;var Vl=function(){var a;return function(){a||(a=new Fl("ytidb"));return a}}();
function Wl(){var a;return null==(a=Vl())?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var Xl=[],Yl,Zl=!1;function $l(){var a={};for(Yl=new am(void 0===a.handleError?bm:a.handleError,void 0===a.logEvent?cm:a.logEvent);0<Xl.length;)switch(a=Xl.shift(),a.type){case "ERROR":Yl.handleError(a.payload);break;case "EVENT":Yl.logEvent(a.eventType,a.payload)}}
function dm(a){Zl||(Yl?Yl.handleError(a):(Xl.push({type:"ERROR",payload:a}),10<Xl.length&&Xl.shift()))}
function em(a,b){Zl||(Yl?Yl.logEvent(a,b):(Xl.push({type:"EVENT",eventType:a,payload:b}),10<Xl.length&&Xl.shift()))}
;function R(a){var b=Ka.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ia(b))}
t(R,Error);function fm(){try{return gm(),!0}catch(a){return!1}}
function gm(a){if(void 0!==L("DATASYNC_ID"))return L("DATASYNC_ID");throw new R("Datasync ID not set",void 0===a?"unknown":a);}
;function hm(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function im(a){return a.substr(0,a.indexOf(":"))||a}
;var jm={},km=(jm.AUTH_INVALID="No user identifier specified.",jm.EXPLICIT_ABORT="Transaction was explicitly aborted.",jm.IDB_NOT_SUPPORTED="IndexedDB is not supported.",jm.MISSING_INDEX="Index not created.",jm.MISSING_OBJECT_STORES="Object stores not created.",jm.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",jm.DB_REOPENED_BY_MISSING_OBJECT_STORES="Database is reopened because expected object stores were not created.",jm.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",
jm.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",jm.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",jm.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",jm.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",jm),lm={},mm=(lm.AUTH_INVALID="ERROR",lm.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",lm.EXPLICIT_ABORT="IGNORED",lm.IDB_NOT_SUPPORTED="ERROR",lm.MISSING_INDEX=
"WARNING",lm.MISSING_OBJECT_STORES="ERROR",lm.DB_DELETED_BY_MISSING_OBJECT_STORES="WARNING",lm.DB_REOPENED_BY_MISSING_OBJECT_STORES="WARNING",lm.QUOTA_EXCEEDED="WARNING",lm.QUOTA_MAYBE_EXCEEDED="WARNING",lm.UNKNOWN_ABORT="WARNING",lm.INCOMPATIBLE_DB_VERSION="WARNING",lm),nm={},om=(nm.AUTH_INVALID=!1,nm.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,nm.EXPLICIT_ABORT=!1,nm.IDB_NOT_SUPPORTED=!1,nm.MISSING_INDEX=!1,nm.MISSING_OBJECT_STORES=!1,nm.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,nm.DB_REOPENED_BY_MISSING_OBJECT_STORES=
!1,nm.QUOTA_EXCEEDED=!1,nm.QUOTA_MAYBE_EXCEEDED=!0,nm.UNKNOWN_ABORT=!0,nm.INCOMPATIBLE_DB_VERSION=!1,nm);function pm(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?km[a]:c;d=void 0===d?mm[a]:d;e=void 0===e?om[a]:e;R.call(this,c,Object.assign({},{name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.i=e;Object.setPrototypeOf(this,pm.prototype)}
t(pm,R);function qm(a,b){pm.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},km.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,qm.prototype)}
t(qm,pm);function rm(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,rm.prototype)}
t(rm,Error);var sm=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function tm(a,b,c,d){b=im(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof pm)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new pm("QUOTA_EXCEEDED",a);if(ad&&"UnknownError"===e.name)return new pm("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof rm)return new pm("MISSING_INDEX",Object.assign({},a,{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&sm.some(function(f){return e.message.includes(f)}))return new pm("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new pm("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign({},a,{name:"IdbError",Yb:e.name})];e.level="WARNING";return e}
function um(a,b,c){var d=Wl();return new pm("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null==d?void 0:d.hasSucceededOnce}})}
;function vm(a){if(!a)throw Error();throw a;}
function wm(a){return a}
function xm(a){this.i=a}
function ym(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=p(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=p(d.i);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.i=[];this.onRejected=[];a=a.i;try{a(c,b)}catch(e){b(e)}}
ym.all=function(a){return new ym(new xm(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={wa:0};f.wa<a.length;f={wa:f.wa},++f.wa)ym.resolve(a[f.wa]).then(function(g){return function(h){d[g.wa]=h;e--;0===e&&b(d)}}(f)).catch(function(g){c(g)})}))};
ym.resolve=function(a){return new ym(new xm(function(b,c){a instanceof ym?a.then(b,c):b(a)}))};
ym.reject=function(a){return new ym(new xm(function(b,c){c(a)}))};
ym.prototype.then=function(a,b){var c=this,d=null!=a?a:wm,e=null!=b?b:vm;return new ym(new xm(function(f,g){"PENDING"===c.state.status?(c.i.push(function(){zm(c,c,d,f,g)}),c.onRejected.push(function(){Am(c,c,e,f,g)})):"FULFILLED"===c.state.status?zm(c,c,d,f,g):"REJECTED"===c.state.status&&Am(c,c,e,f,g)}))};
ym.prototype.catch=function(a){return this.then(void 0,a)};
function zm(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof ym?Bm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Am(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof ym?Bm(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Bm(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof ym?Bm(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Cm(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Dm(a){return new Promise(function(b,c){Cm(a,b,c)})}
function Em(a){return new ym(new xm(function(b,c){Cm(a,b,c)}))}
;function Fm(a,b){return new ym(new xm(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Gm(a,b){this.i=a;this.options=b;this.transactionCount=0;this.l=Math.round(P());this.j=!1}
l=Gm.prototype;l.add=function(a,b,c){return Hm(this,[a],{mode:"readwrite",U:!0},function(d){return d.objectStore(a).add(b,c)})};
l.clear=function(a){return Hm(this,[a],{mode:"readwrite",U:!0},function(b){return b.objectStore(a).clear()})};
l.close=function(){this.i.close();var a;(null==(a=this.options)?0:a.closed)&&this.options.closed()};
l.count=function(a,b){return Hm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).count(b)})};
function Im(a,b,c){a=a.i.createObjectStore(b,c);return new Jm(a)}
l.delete=function(a,b){return Hm(this,[a],{mode:"readwrite",U:!0},function(c){return c.objectStore(a).delete(b)})};
l.get=function(a,b){return Hm(this,[a],{mode:"readonly",U:!0},function(c){return c.objectStore(a).get(b)})};
function Km(a,b){return Hm(a,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(c){c=c.objectStore("LogsRequestsStore");return Em(c.i.put(b,void 0))})}
l.objectStoreNames=function(){return Array.from(this.i.objectStoreNames)};
function Hm(a,b,c,d){var e,f,g,h,k,m,q,r,x,u,A,D;return w(function(F){switch(F.i){case 1:var N={mode:"readonly",U:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?N.mode=c:Object.assign(N,c);e=N;a.transactionCount++;f=e.U?3:1;g=0;case 2:if(h){F.u(3);break}g++;k=Math.round(P());wa(F,4);m=a.i.transaction(b,e.mode);N=new Lm(m);N=Mm(N,d);return v(F,N,6);case 6:return q=F.j,r=Math.round(P()),Nm(a,k,r,g,void 0,b.join(),e),F.return(q);case 4:x=ya(F);u=Math.round(P());A=tm(x,a.i.name,b.join(),a.i.version);
if((D=A instanceof pm&&!A.i)||g>=f)Nm(a,k,u,g,A,b.join(),e),h=A;F.u(2);break;case 3:return F.return(Promise.reject(h))}})}
function Nm(a,b,c,d,e,f,g){b=c-b;e?(e instanceof pm&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&em("QUOTA_EXCEEDED",{dbName:im(a.i.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof pm&&"UNKNOWN_ABORT"===e.type&&(c-=a.l,0>c&&c>=Math.pow(2,31)&&(c=0),em("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.j=!0),Om(a,!1,d,f,b,g.tag),dm(e)):Om(a,!0,d,f,b,g.tag)}
function Om(a,b,c,d,e,f){em("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.j,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
l.getName=function(){return this.i.name};
function Jm(a){this.i=a}
l=Jm.prototype;l.add=function(a,b){return Em(this.i.add(a,b))};
l.autoIncrement=function(){return this.i.autoIncrement};
l.clear=function(){return Em(this.i.clear()).then(function(){})};
l.count=function(a){return Em(this.i.count(a))};
function Pm(a,b){return Qm(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
l.delete=function(a){return a instanceof IDBKeyRange?Pm(this,a):Em(this.i.delete(a))};
l.get=function(a){return Em(this.i.get(a))};
l.index=function(a){try{return new Rm(this.i.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new rm(a,this.i.name);throw b;}};
l.getName=function(){return this.i.name};
l.keyPath=function(){return this.i.keyPath};
function Qm(a,b,c){a=a.i.openCursor(b.query,b.direction);return Sm(a).then(function(d){return Fm(d,c)})}
function Lm(a){var b=this;this.i=a;this.l=new Map;this.j=!1;this.done=new Promise(function(c,d){b.i.addEventListener("complete",function(){c()});
b.i.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.i.error)});
b.i.addEventListener("abort",function(){var e=b.i.error;if(e)d(e);else if(!b.j){e=pm;for(var f=b.i.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.i.db.name,mode:b.i.mode});d(e)}})})}
function Mm(a,b){var c=new Promise(function(d,e){try{b(a).then(function(f){d(f)}).catch(e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return p(d).next().value})}
Lm.prototype.abort=function(){this.i.abort();this.j=!0;throw new pm("EXPLICIT_ABORT");};
Lm.prototype.objectStore=function(a){a=this.i.objectStore(a);var b=this.l.get(a);b||(b=new Jm(a),this.l.set(a,b));return b};
function Rm(a){this.i=a}
l=Rm.prototype;l.count=function(a){return Em(this.i.count(a))};
l.delete=function(a){return Tm(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
l.get=function(a){return Em(this.i.get(a))};
l.getKey=function(a){return Em(this.i.getKey(a))};
l.keyPath=function(){return this.i.keyPath};
l.unique=function(){return this.i.unique};
function Tm(a,b,c){a=a.i.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Sm(a).then(function(d){return Fm(d,c)})}
function Um(a,b){this.request=a;this.cursor=b}
function Sm(a){return Em(a).then(function(b){return b?new Um(a,b):null})}
l=Um.prototype;l.advance=function(a){this.cursor.advance(a);return Sm(this.request)};
l.continue=function(a){this.cursor.continue(a);return Sm(this.request)};
l.delete=function(){return Em(this.cursor.delete()).then(function(){})};
l.getKey=function(){return this.cursor.key};
l.getValue=function(){return this.cursor.value};
l.update=function(a){return Em(this.cursor.update(a))};function Vm(a,b,c){return new Promise(function(d,e){function f(){x||(x=new Gm(g.result,{closed:r}));return x}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,m=c.nd,q=c.upgrade,r=c.closed,x;g.addEventListener("upgradeneeded",function(u){try{if(null===u.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");u.dataLoss&&"none"!==u.dataLoss&&em("IDB_DATA_CORRUPTED",{reason:u.dataLossMessage||"unknown reason",dbName:im(a)});var A=f(),D=new Lm(g.transaction);
q&&q(A,function(F){return u.oldVersion<F&&u.newVersion>=F},D);
D.done.catch(function(F){e(F)})}catch(F){e(F)}});
g.addEventListener("success",function(){var u=g.result;k&&u.addEventListener("versionchange",function(){k(f())});
u.addEventListener("close",function(){em("IDB_UNEXPECTEDLY_CLOSED",{dbName:im(a),dbVersion:u.version});m&&m()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Wm(a,b,c){c=void 0===c?{}:c;return Vm(a,b,c)}
function Xm(a,b){b=void 0===b?{}:b;var c,d,e,f;return w(function(g){if(1==g.i)return wa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),v(g,Dm(c),4);
if(2!=g.i)return xa(g,0);f=ya(g);throw tm(f,a,"",-1);})}
;function Ym(a){return new Promise(function(b){Pl(function(){b()},a)})}
function Zm(a,b){this.name=a;this.options=b;this.m=!0;this.s=this.o=0;this.j=500}
Zm.prototype.l=function(a,b,c){c=void 0===c?{}:c;return Wm(a,b,c)};
Zm.prototype.delete=function(a){a=void 0===a?{}:a;return Xm(this.name,a)};
function $m(a,b){return new pm("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function an(a,b){if(!b)throw um("openWithToken",im(a.name));return bn(a)}
function bn(a){function b(){var f,g,h,k,m,q,r,x,u,A;return w(function(D){switch(D.i){case 1:return g=null!=(f=Error().stack)?f:"",wa(D,2),v(D,a.l(a.name,a.options.version,d),4);case 4:h=D.j;for(var F=a.options,N=[],O=p(Object.keys(F.Ia)),Q=O.next();!Q.done;Q=O.next()){Q=Q.value;var ea=F.Ia[Q],ba=void 0===ea.Vc?Number.MAX_VALUE:ea.Vc;!(h.i.version>=ea.jb)||h.i.version>=ba||h.i.objectStoreNames.contains(Q)||N.push(Q)}k=N;if(0===k.length){D.u(5);break}m=Object.keys(a.options.Ia);q=h.objectStoreNames();
if(a.s<qk("ytidb_reopen_db_retries",0))return a.s++,h.close(),dm(new pm("DB_REOPENED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),D.return(b());if(!(a.o<qk("ytidb_remake_db_retries",1))){D.u(6);break}a.o++;if(!M("ytidb_remake_db_enable_backoff_delay")){D.u(7);break}return v(D,Ym(a.j),8);case 8:a.j*=2;case 7:return v(D,a.delete(),9);case 9:return dm(new pm("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:a.name,expectedObjectStores:m,foundObjectStores:q})),D.return(b());
case 6:throw new qm(q,m);case 5:return D.return(h);case 2:r=ya(D);if(r instanceof DOMException?"VersionError"!==r.name:"DOMError"in self&&r instanceof DOMError?"VersionError"!==r.name:!(r instanceof Object&&"message"in r)||"An attempt was made to open a database using a lower version than the existing version."!==r.message){D.u(10);break}return v(D,a.l(a.name,void 0,Object.assign({},d,{upgrade:void 0})),11);case 11:x=D.j;u=x.i.version;if(void 0!==a.options.version&&u>a.options.version+1)throw x.close(),
a.m=!1,$m(a,u);return D.return(x);case 10:throw c(),r instanceof Error&&!M("ytidb_async_stack_killswitch")&&(r.stack=r.stack+"\n"+g.substring(g.indexOf("\n")+1)),tm(r,a.name,"",null!=(A=a.options.version)?A:-1);}})}
function c(){a.i===e&&(a.i=void 0)}
if(!a.m)throw $m(a);if(a.i)return a.i;var d={blocking:function(f){f.close()},
closed:c,nd:c,upgrade:a.options.upgrade};var e=b();a.i=e;return a.i}
;var cn=new Zm("YtIdbMeta",{Ia:{databases:{jb:1}},upgrade:function(a,b){b(1)&&Im(a,"databases",{keyPath:"actualName"})}});
function dn(a,b){var c;return w(function(d){if(1==d.i)return v(d,an(cn,b),2);c=d.j;return d.return(Hm(c,["databases"],{U:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return Em(f.i.put(a,void 0)).then(function(){})})}))})}
function en(a,b){var c;return w(function(d){if(1==d.i)return a?v(d,an(cn,b),2):d.return();c=d.j;return d.return(c.delete("databases",a))})}
function fn(a,b){var c,d;return w(function(e){return 1==e.i?(c=[],v(e,an(cn,b),2)):3!=e.i?(d=e.j,v(e,Hm(d,["databases"],{U:!0,mode:"readonly"},function(f){c.length=0;return Qm(f.objectStore("databases"),{},function(g){a(g.getValue())&&c.push(g.getValue());return g.continue()})}),3)):e.return(c)})}
function gn(a){return fn(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
function hn(a,b,c){return fn(function(d){return c?void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)&&c.includes(d.publicName):void 0!==d.userIdentifier&&!a.includes(d.userIdentifier)},b)}
function jn(a){var b,c;return w(function(d){if(1==d.i)return b=gm("YtIdbMeta hasAnyMeta other"),v(d,fn(function(e){return void 0!==e.userIdentifier&&e.userIdentifier!==b},a),2);
c=d.j;return d.return(0<c.length)})}
;var kn,ln=new function(){}(new function(){});
function mn(){var a,b,c,d;return w(function(e){switch(e.i){case 1:a=Wl();if(null==(b=a)?0:b.hasSucceededOnce)return e.return(!0);var f;if(f=Tl)f=/WebKit\/([0-9]+)/.exec(Rb()),f=!!(f&&600<=parseInt(f[1],10));f&&(f=/WebKit\/([0-9]+)/.exec(Rb()),f=!(f&&602<=parseInt(f[1],10)));if(f||Lc)return e.return(!1);try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return e.return(!1)}catch(g){return e.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return e.return(!1);
wa(e,2);d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return v(e,dn(d,ln),4);case 4:return v(e,en("yt-idb-test-do-not-use",ln),5);case 5:return e.return(!0);case 2:return ya(e),e.return(!1)}})}
function nn(){if(void 0!==kn)return kn;Zl=!0;return kn=mn().then(function(a){Zl=!1;var b;if(null!=(b=Vl())&&b.i){var c;b={hasSucceededOnce:(null==(c=Wl())?void 0:c.hasSucceededOnce)||a};var d;null==(d=Vl())||d.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0)}return a})}
function on(){return B("ytglobal.idbToken_")||void 0}
function pn(){var a=on();return a?Promise.resolve(a):nn().then(function(b){(b=b?ln:void 0)&&z("ytglobal.idbToken_",b);return b})}
;var qn=0;function rn(a,b){qn||(qn=Nh.S(function(){var c,d,e,f,g;return w(function(h){switch(h.i){case 1:return v(h,pn(),2);case 2:c=h.j;if(!c)return h.return();d=!0;wa(h,3);return v(h,hn(a,c,b),5);case 5:e=h.j;if(!e.length){d=!1;h.u(6);break}f=e[0];return v(h,Xm(f.actualName),7);case 7:return v(h,en(f.actualName,c),6);case 6:xa(h,4);break;case 3:g=ya(h),dm(g),d=!1;case 4:Nh.fa(qn),qn=0,d&&rn(a,b),h.i=0}})}))}
function sn(){var a;return w(function(b){return 1==b.i?v(b,pn(),2):(a=b.j)?b.return(jn(a)):b.return(!1)})}
new th;function tn(a){if(!fm())throw a=new pm("AUTH_INVALID",{dbName:a}),dm(a),a;var b=gm();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function un(a,b,c,d){var e,f,g,h,k,m;return w(function(q){switch(q.i){case 1:return f=null!=(e=Error().stack)?e:"",v(q,pn(),2);case 2:g=q.j;if(!g)throw h=um("openDbImpl",a,b),M("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),dm(h),h;hm(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:tn(a);wa(q,3);return v(q,dn(k,g),5);case 5:return v(q,Wm(k.actualName,b,d),6);case 6:return q.return(q.j);case 3:return m=ya(q),wa(q,7),v(q,en(k.actualName,g),9);case 9:xa(q,
8);break;case 7:ya(q);case 8:throw m;}})}
function vn(a,b,c){c=void 0===c?{}:c;return un(a,b,!1,c)}
function wn(a,b,c){c=void 0===c?{}:c;return un(a,b,!0,c)}
function xn(a,b){b=void 0===b?{}:b;var c,d;return w(function(e){if(1==e.i)return v(e,pn(),2);if(3!=e.i){c=e.j;if(!c)return e.return();hm(a);d=tn(a);return v(e,Xm(d.actualName,b),3)}return v(e,en(d.actualName,c),0)})}
function yn(a,b,c){a=a.map(function(d){return w(function(e){return 1==e.i?v(e,Xm(d.actualName,b),2):v(e,en(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function zn(){var a=void 0===a?{}:a;var b,c;return w(function(d){if(1==d.i)return v(d,pn(),2);if(3!=d.i){b=d.j;if(!b)return d.return();hm("LogsDatabaseV2");return v(d,gn(b),3)}c=d.j;return v(d,yn(c,a,b),0)})}
function An(a,b){b=void 0===b?{}:b;var c;return w(function(d){if(1==d.i)return v(d,pn(),2);if(3!=d.i){c=d.j;if(!c)return d.return();hm(a);return v(d,Xm(a,b),3)}return v(d,en(a,c),0)})}
;function Bn(a){this.Sa=this.i=!1;this.potentialEsfErrorCounter=this.j=0;this.handleError=function(){};
this.za=function(){};
this.now=Date.now;this.Ga=!1;var b;this.jc=null!=(b=a.jc)?b:100;var c;this.ec=null!=(c=a.ec)?c:1;var d;this.cc=null!=(d=a.cc)?d:2592E6;var e;this.Zb=null!=(e=a.Zb)?e:12E4;var f;this.dc=null!=(f=a.dc)?f:5E3;var g;this.G=null!=(g=a.G)?g:void 0;this.Xa=!!a.Xa;var h;this.Va=null!=(h=a.Va)?h:.1;var k;this.cb=null!=(k=a.cb)?k:10;a.handleError&&(this.handleError=a.handleError);a.za&&(this.za=a.za);a.Ga&&(this.Ga=a.Ga);a.Sa&&(this.Sa=a.Sa);this.H=a.H;this.Z=a.Z;this.O=a.O;this.M=a.M;this.ia=a.ia;this.wb=
a.wb;this.vb=a.vb;Cn(this)&&(!this.H||this.H("networkless_logging"))&&Dn(this)}
function Dn(a){Cn(a)&&!a.Ga&&(a.i=!0,a.Xa&&Math.random()<=a.Va&&a.O.xc(a.G),En(a),a.M.L()&&a.Ma(),a.M.aa(a.wb,a.Ma.bind(a)),a.M.aa(a.vb,a.Hb.bind(a)))}
l=Bn.prototype;l.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(Cn(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.O.set(d,this.G).then(function(e){d.id=e;c.M.L()&&Fn(c,d)}).catch(function(e){Fn(c,d);
Gn(c,e)})}else this.ia(a,b)};
l.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(Cn(this)&&this.i){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.H&&this.H("nwl_skip_retry")&&(e.skipRetry=c);if(this.M.L()||this.H&&this.H("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return w(function(k){if(1==k.i)return v(k,d.O.set(e,d.G).catch(function(m){Gn(d,m)}),2);
f(g,h);k.i=0})}}this.ia(a,b,e.skipRetry)}else this.O.set(e,this.G).catch(function(g){d.ia(a,b,e.skipRetry);
Gn(d,g)})}else this.ia(a,b,this.H&&this.H("nwl_skip_retry")&&c)};
l.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(Cn(this)&&this.i){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.O.ya(d.id,c.G):e=!0;c.M.ha&&c.H&&c.H("vss_network_hint")&&c.M.ha(!0);f(g,h)};
this.ia(d.url,d.options);this.O.set(d,this.G).then(function(g){d.id=g;e&&c.O.ya(d.id,c.G)}).catch(function(g){Gn(c,g)})}else this.ia(a,b)};
l.Ma=function(){var a=this;if(!Cn(this))throw um("throttleSend");this.j||(this.j=this.Z.S(function(){var b;return w(function(c){if(1==c.i)return v(c,a.O.Rb("NEW",a.G),2);if(3!=c.i)return b=c.j,b?v(c,Fn(a,b),3):(a.Hb(),c.return());a.j&&(a.j=0,a.Ma());c.i=0})},this.jc))};
l.Hb=function(){this.Z.fa(this.j);this.j=0};
function Fn(a,b){var c,d;return w(function(e){switch(e.i){case 1:if(!Cn(a))throw c=um("immediateSend"),c;if(void 0===b.id){e.u(2);break}return v(e,a.O.Nc(b.id,a.G),3);case 3:(d=e.j)?b=d:a.za(Error("The request cannot be found in the database."));case 2:if(Hn(a,b,a.cc)){e.u(4);break}a.za(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.u(5);break}return v(e,a.O.ya(b.id,a.G),5);case 5:return e.return();case 4:b.skipRetry||(b=In(a,b));if(!b){e.u(0);break}if(!b.skipRetry||
void 0===b.id){e.u(8);break}return v(e,a.O.ya(b.id,a.G),8);case 8:a.ia(b.url,b.options,!!b.skipRetry),e.i=0}})}
function In(a,b){if(!Cn(a))throw um("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g,h,k;return w(function(m){switch(m.i){case 1:g=Jn(f);if(!(a.H&&a.H("nwl_consider_error_code")&&g||a.H&&!a.H("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.cb)){m.u(2);break}if(!a.M.Ka){m.u(3);break}return v(m,a.M.Ka(),3);case 3:if(a.M.L()){m.u(2);break}c(e,f);if(!a.H||!a.H("nwl_consider_error_code")||void 0===(null==(h=b)?void 0:h.id)){m.u(6);break}return v(m,a.O.yb(b.id,a.G,!1),6);case 6:return m.return();case 2:if(a.H&&a.H("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.cb)return m.return();a.potentialEsfErrorCounter++;if(void 0===(null==(k=b)?void 0:k.id)){m.u(8);break}return b.sendCount<a.ec?v(m,a.O.yb(b.id,a.G),12):v(m,a.O.ya(b.id,a.G),8);case 12:a.Z.S(function(){a.M.L()&&a.Ma()},a.dc);
case 8:c(e,f),m.i=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){var g;return w(function(h){if(1==h.i)return void 0===(null==(g=b)?void 0:g.id)?h.u(2):v(h,a.O.ya(b.id,a.G),2);a.M.ha&&a.H&&a.H("vss_network_hint")&&a.M.ha(!0);d(e,f);h.i=0})};
return b}
function Hn(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function En(a){if(!Cn(a))throw um("retryQueuedRequests");a.O.Rb("QUEUED",a.G).then(function(b){b&&!Hn(a,b,a.Zb)?a.Z.S(function(){return w(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,a.O.yb(b.id,a.G),2);En(a);c.i=0})}):a.M.L()&&a.Ma()})}
function Gn(a,b){a.mc&&!a.M.L()?a.mc(b):a.handleError(b)}
function Cn(a){return!!a.G||a.Sa}
function Jn(a){var b;return(a=null==a?void 0:null==(b=a.error)?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;function Kn(a,b){this.version=a;this.args=b}
;function Ln(a,b){this.topic=a;this.i=b}
Ln.prototype.toString=function(){return this.topic};var Mn=B("ytPubsub2Pubsub2Instance")||new K;K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Da;K.prototype.publish=K.prototype.oa;K.prototype.clear=K.prototype.clear;z("ytPubsub2Pubsub2Instance",Mn);var Nn=B("ytPubsub2Pubsub2SubscribedKeys")||{};z("ytPubsub2Pubsub2SubscribedKeys",Nn);var On=B("ytPubsub2Pubsub2TopicToKeys")||{};z("ytPubsub2Pubsub2TopicToKeys",On);var Pn=B("ytPubsub2Pubsub2IsAsync")||{};z("ytPubsub2Pubsub2IsAsync",Pn);
z("ytPubsub2Pubsub2SkipSubKey",null);function Qn(a,b){var c=Rn();c&&c.publish.call(c,a.toString(),a,b)}
function Sn(a){var b=Tn,c=Rn();if(!c)return 0;var d=c.subscribe(b.toString(),function(e,f){var g=B("ytPubsub2Pubsub2SkipSubKey");g&&g==d||(g=function(){if(Nn[d])try{if(f&&b instanceof Ln&&b!=e)try{var h=b.i,k=f;if(!k.args||!k.version)throw Error("yt.pubsub2.Data.deserialize(): serializedData is incomplete.");try{if(!h.na){var m=new h;h.na=m.version}var q=h.na}catch(F){}if(!q||k.version!=q)throw Error("yt.pubsub2.Data.deserialize(): serializedData version is incompatible.");try{q=Reflect;var r=q.construct;
var x=k.args,u=x.length;if(0<u){var A=Array(u);for(k=0;k<u;k++)A[k]=x[k];var D=A}else D=[];f=r.call(q,h,D)}catch(F){throw F.message="yt.pubsub2.Data.deserialize(): "+F.message,F;}}catch(F){throw F.message="yt.pubsub2.pubsub2 cross-binary conversion error for "+b.toString()+": "+F.message,F;}a.call(window,f)}catch(F){wk(F)}},Pn[b.toString()]?B("yt.scheduler.instance")?Nh.S(g):Qk(g,0):g())});
Nn[d]=!0;On[b.toString()]||(On[b.toString()]=[]);On[b.toString()].push(d);return d}
function Un(){var a=Vn,b=Sn(function(c){a.apply(void 0,arguments);Wn(b)});
return b}
function Wn(a){var b=Rn();b&&("number"===typeof a&&(a=[a]),fb(a,function(c){b.unsubscribeByKey(c);delete Nn[c]}))}
function Rn(){return B("ytPubsub2Pubsub2Instance")}
;function Xn(a,b){Zm.call(this,a,b);this.options=b;hm(a)}
t(Xn,Zm);function Yn(a,b){var c;return function(){c||(c=new Xn(a,b));return c}}
Xn.prototype.l=function(a,b,c){c=void 0===c?{}:c;return(this.options.zb?wn:vn)(a,b,Object.assign({},c))};
Xn.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.zb?An:xn)(this.name,a)};
function Zn(a,b){return Yn(a,b)}
;var $n;
function ao(){if($n)return $n();var a={};$n=Zn("LogsDatabaseV2",{Ia:(a.LogsRequestsStore={jb:2},a),zb:!1,upgrade:function(b,c,d){c(2)&&Im(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.i.indexNames.contains("newRequest")&&d.i.deleteIndex("newRequest"),d.i.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.i.objectStoreNames.contains("sapisid")&&b.i.deleteObjectStore("sapisid");c(9)&&b.i.objectStoreNames.contains("SWHealthLog")&&b.i.deleteObjectStore("SWHealthLog")},
version:9});return $n()}
;function bo(a){return an(ao(),a)}
function co(a,b){var c,d,e,f;return w(function(g){if(1==g.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},v(g,bo(b),2);if(3!=g.i)return d=g.j,e=Object.assign({},a,{options:JSON.parse(JSON.stringify(a.options)),interface:L("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),v(g,Km(d,e),3);f=g.j;c.pd=P();eo(c);return g.return(f)})}
function fo(a,b){var c,d,e,f,g,h,k;return w(function(m){if(1==m.i)return c={startTime:P(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},v(m,bo(b),2);if(3!=m.i)return d=m.j,e=L("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,P()],h=IDBKeyRange.bound(f,g),k=void 0,v(m,Hm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(q){return Tm(q.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(r){r.getValue()&&(k=r.getValue(),"NEW"===a&&(k.status="QUEUED",
r.update(k)))})}),3);
c.pd=P();eo(c);return m.return(k)})}
function go(a,b){var c;return w(function(d){if(1==d.i)return v(d,bo(b),2);c=d.j;return d.return(Hm(c,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",Em(f.i.put(g,void 0)).then(function(){return g})})}))})}
function ho(a,b,c){c=void 0===c?!0:c;var d;return w(function(e){if(1==e.i)return v(e,bo(b),2);d=e.j;return e.return(Hm(d,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),Em(g.i.put(h,void 0)).then(function(){return h})):ym.resolve(void 0)})}))})}
function io(a,b){var c;return w(function(d){if(1==d.i)return v(d,bo(b),2);c=d.j;return d.return(c.delete("LogsRequestsStore",a))})}
function jo(a){var b,c;return w(function(d){if(1==d.i)return v(d,bo(a),2);b=d.j;c=P()-2592E6;return v(d,Hm(b,["LogsRequestsStore"],{mode:"readwrite",U:!0},function(e){return Qm(e.objectStore("LogsRequestsStore"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function ko(){return w(function(a){return v(a,zn(),0)})}
function eo(a){M("nwl_csi_killswitch")||.01>=Math.random()&&Qn("nwl_transaction_latency_payload",a)}
;var lo={},mo=Zn("ServiceWorkerLogsDatabase",{Ia:(lo.SWHealthLog={jb:1},lo),zb:!0,upgrade:function(a,b){b(1)&&Im(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).i.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function no(a){return an(mo(),a)}
function oo(a){var b,c;return w(function(d){if(1==d.i)return v(d,no(a),2);b=d.j;c=P()-2592E6;return v(d,Hm(b,["SWHealthLog"],{mode:"readwrite",U:!0},function(e){return Qm(e.objectStore("SWHealthLog"),{},function(f){if(f.getValue().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function po(a){var b;return w(function(c){if(1==c.i)return v(c,no(a),2);b=c.j;return v(c,b.clear("SWHealthLog"),0)})}
;var qo={},ro=0;
function so(a){var b=void 0===b?"":b;var c=void 0===c?!1:c;if(a)if(b)$k(a,void 0,"POST",b);else if(L("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))$k(a,void 0,"GET","",void 0,void 0,c);else{b:{try{var d=new bb({url:a});if(d.l&&d.j||d.m){var e=kc(lc(5,a)),f;if(!(f=!e||!e.endsWith("/aclk"))){var g=a.search(zc),h=yc(a,0,"ri",g);if(0>h)var k=null;else{var m=a.indexOf("&",h);if(0>m||m>g)m=g;k=decodeURIComponent(a.slice(h+3,-1!==m?m:0).replace(/\+/g," "))}f="1"!==k}var q=!f;break b}}catch(x){}q=!1}if(q){b:{try{if(window.navigator&&
window.navigator.sendBeacon&&window.navigator.sendBeacon(a,"")){var r=!0;break b}}catch(x){}r=!1}b=r?!0:!1}else b=!1;b||to(a)}}
function to(a){var b=new Image,c=""+ro++;qo[c]=b;b.onload=b.onerror=function(){delete qo[c]};
b.src=a}
;function uo(){this.i=new Map;this.j=!1}
function vo(){if(!uo.i){var a=B("yt.networkRequestMonitor.instance")||new uo;z("yt.networkRequestMonitor.instance",a);uo.i=a}return uo.i}
uo.prototype.requestComplete=function(a,b){b&&(this.j=!0);a=this.removeParams(a);this.i.get(a)||this.i.set(a,b)};
uo.prototype.isEndpointCFR=function(a){a=this.removeParams(a);return(a=this.i.get(a))?!1:!1===a&&this.j?!0:null};
uo.prototype.removeParams=function(a){return a.split("?")[0]};
uo.prototype.removeParams=uo.prototype.removeParams;uo.prototype.isEndpointCFR=uo.prototype.isEndpointCFR;uo.prototype.requestComplete=uo.prototype.requestComplete;uo.getInstance=vo;var wo;function xo(){wo||(wo=new Fl("yt.offline"));return wo}
function yo(a){if(M("offline_error_handling")){var b=xo().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);xo().set("errors",b,2592E3,!0)}}
;function zo(){Te.call(this);var a=this;this.l=!1;this.j=Mh();this.j.aa("networkstatus-online",function(){if(a.l&&M("offline_error_handling")){var b=xo().get("errors",!0);if(b){for(var c in b)if(b[c]){var d=new R(c,"sent via offline_errors");d.name=b[c].name;d.stack=b[c].stack;d.level=b[c].level;wk(d)}xo().set("errors",{},2592E3,!0)}}})}
t(zo,Te);function Ao(){if(!zo.i){var a=B("yt.networkStatusManager.instance")||new zo;z("yt.networkStatusManager.instance",a);zo.i=a}return zo.i}
l=zo.prototype;l.L=function(){return this.j.L()};
l.ha=function(a){this.j.j=a};
l.Oc=function(){};
l.Hc=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
l.Bc=function(){this.l=!0};
l.aa=function(a,b){return this.j.aa(a,b)};
l.Ka=function(a){a=Kh(this.j,a);a.then(function(b){M("use_cfr_monitor")&&vo().requestComplete("generate_204",b)});
return a};
zo.prototype.sendNetworkCheckRequest=zo.prototype.Ka;zo.prototype.listen=zo.prototype.aa;zo.prototype.enableErrorFlushing=zo.prototype.Bc;zo.prototype.getWindowStatus=zo.prototype.Hc;zo.prototype.monitorNetworkStatusChange=zo.prototype.Oc;zo.prototype.networkStatusHint=zo.prototype.ha;zo.prototype.isNetworkAvailable=zo.prototype.L;zo.getInstance=Ao;function Bo(a){a=void 0===a?{}:a;Te.call(this);var b=this;this.j=this.s=0;this.l=Ao();var c=B("yt.networkStatusManager.instance.listen").bind(this.l);c&&(a.fb?(this.fb=a.fb,c("networkstatus-online",function(){Co(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Co(b,"publicytnetworkstatus-offline")})):(c("networkstatus-online",function(){Ue(b,"publicytnetworkstatus-online")}),c("networkstatus-offline",function(){Ue(b,"publicytnetworkstatus-offline")})))}
t(Bo,Te);Bo.prototype.L=function(){var a=B("yt.networkStatusManager.instance.isNetworkAvailable");return a?a.bind(this.l)():!0};
Bo.prototype.ha=function(a){var b=B("yt.networkStatusManager.instance.networkStatusHint").bind(this.l);b&&b(a)};
Bo.prototype.Ka=function(a){var b=this,c;return w(function(d){c=B("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.l);return M("skip_network_check_if_cfr")&&vo().isEndpointCFR("generate_204")?d.return(new Promise(function(e){var f;b.ha((null==(f=window.navigator)?void 0:f.onLine)||!0);e(b.L())})):c?d.return(c(a)):d.return(!0)})};
function Co(a,b){a.fb?a.j?(Nh.fa(a.s),a.s=Nh.S(function(){a.o!==b&&(Ue(a,b),a.o=b,a.j=P())},a.fb-(P()-a.j))):(Ue(a,b),a.o=b,a.j=P()):Ue(a,b)}
;var Do;function Eo(){Bn.call(this,{O:{xc:jo,ya:io,Rb:fo,Nc:go,yb:ho,set:co},M:Fo(),handleError:wk,za:xk,ia:Go,now:P,mc:yo,Z:Sl(),wb:"publicytnetworkstatus-online",vb:"publicytnetworkstatus-offline",Xa:!0,Va:.1,cb:qk("potential_esf_error_limit",10),H:M,Ga:!(fm()&&Ho())});this.l=new th;M("networkless_immediately_drop_all_requests")&&ko();An("LogsDatabaseV2")}
t(Eo,Bn);function Io(){var a=B("yt.networklessRequestController.instance");a||(a=new Eo,z("yt.networklessRequestController.instance",a),M("networkless_logging")&&pn().then(function(b){a.G=b;Dn(a);a.l.resolve();a.Xa&&Math.random()<=a.Va&&a.G&&oo(a.G);M("networkless_immediately_drop_sw_health_store")&&Jo(a)}));
return a}
Eo.prototype.writeThenSend=function(a,b){b||(b={});fm()||(this.i=!1);Bn.prototype.writeThenSend.call(this,a,b)};
Eo.prototype.sendThenWrite=function(a,b,c){b||(b={});fm()||(this.i=!1);Bn.prototype.sendThenWrite.call(this,a,b,c)};
Eo.prototype.sendAndWrite=function(a,b){b||(b={});fm()||(this.i=!1);Bn.prototype.sendAndWrite.call(this,a,b)};
Eo.prototype.awaitInitialization=function(){return this.l.promise};
function Jo(a){var b;w(function(c){if(!a.G)throw b=um("clearSWHealthLogsDb"),b;return c.return(po(a.G).catch(function(d){a.handleError(d)}))})}
function Go(a,b,c){M("use_cfr_monitor")&&Ko(a,b);var d;if(null==(d=b.postParams)?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(P());c&&0===Object.keys(b).length?so(a):Xk(a,b)}
function Fo(){Do||(Do=new Bo({Mc:!0,Cc:!0}));return Do}
function Ko(a,b){var c=b.onError?b.onError:function(){};
b.onError=function(e,f){vo().requestComplete(a,!1);c(e,f)};
var d=b.onSuccess?b.onSuccess:function(){};
b.onSuccess=function(e,f){vo().requestComplete(a,!0);d(e,f)}}
function Ho(){return"www.youtube-nocookie.com"!==mc(document.location.toString())}
;var Lo=!1,Mo=0,No=0,Oo,Po=y.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:Lo,potentialEsfErrorCounter:No};z("ytNetworklessLoggingInitializationOptions",Po);
function Qo(){var a;w(function(b){switch(b.i){case 1:return v(b,pn(),2);case 2:a=b.j;if(!a||!fm()&&!M("nwl_init_require_datasync_id_killswitch")||!Ho()){b.u(0);break}Lo=!0;Po.isNwlInitialized=Lo;if(!M("use_new_nwl_initialization")){b.u(4);break}return v(b,Io().awaitInitialization(),5);case 5:return b.return();case 4:return v(b,An("LogsDatabaseV2"),6);case 6:if(!(.1>=Math.random())){b.u(7);break}return v(b,jo(a),8);case 8:return v(b,oo(a),7);case 7:Ro();So().L()&&To();So().aa("publicytnetworkstatus-online",
To);So().aa("publicytnetworkstatus-offline",Uo);if(!M("networkless_immediately_drop_sw_health_store")){b.u(10);break}return v(b,Vo(),10);case 10:if(M("networkless_immediately_drop_all_requests"))return v(b,ko(),0);b.u(0)}})}
function Wo(a,b){function c(d){var e=So().L();if(!Xo()||!d||e&&M("vss_networkless_bypass_write"))Yo(a,b);else{var f={url:a,options:b,timestamp:P(),status:"NEW",sendCount:0};co(f,d).then(function(g){f.id=g;So().L()&&Zo(f)}).catch(function(g){Zo(f);
So().L()?wk(g):yo(g)})}}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?pn().then(function(d){c(d)}):c(on())}
function $o(a,b){function c(d){if(Xo()&&d){var e={url:a,options:b,timestamp:P(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(k,m){M("use_cfr_monitor")&&vo().requestComplete(e.url,!0);void 0!==e.id?io(e.id,d):f=!0;M("vss_network_hint")&&So().ha(!0);g(k,m)};
if(M("use_cfr_monitor")){var h=b.onError?b.onError:function(){};
e.options.onError=function(k,m){vo().requestComplete(e.url,!1);h(k,m)}}Yo(e.url,e.options);
co(e,d).then(function(k){e.id=k;f&&io(e.id,d)}).catch(function(k){So().L()?wk(k):yo(k)})}else Yo(a,b)}
b=void 0===b?{}:b;M("skip_is_supported_killswitch")?pn().then(function(d){c(d)}):c(on())}
function To(){var a=on();if(!a)throw um("throttleSend");Mo||(Mo=Nh.S(function(){var b;return w(function(c){if(1==c.i)return v(c,fo("NEW",a),2);if(3!=c.i)return b=c.j,b?v(c,Zo(b),3):(Uo(),c.return());Mo&&(Mo=0,To());c.i=0})},100))}
function Uo(){Nh.fa(Mo);Mo=0}
function Zo(a){var b,c,d;return w(function(e){switch(e.i){case 1:b=on();if(!b)throw c=um("immediateSend"),c;if(void 0===a.id){e.u(2);break}return v(e,go(a.id,b),3);case 3:(d=e.j)?a=d:xk(Error("The request cannot be found in the database."));case 2:if(ap(a,2592E6)){e.u(4);break}xk(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.u(5);break}return v(e,io(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=bp(a));var f=a,g,h;if(null==f?0:null==(g=f.options)?
0:null==(h=g.postParams)?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(P());a=f;if(!a){e.u(0);break}if(!a.skipRetry||void 0===a.id){e.u(8);break}return v(e,io(a.id,b),8);case 8:Yo(a.url,a.options,!!a.skipRetry),e.i=0}})}
function bp(a){var b=on();if(!b)throw um("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g,h,k;return w(function(m){switch(m.i){case 1:M("use_cfr_monitor")&&vo().requestComplete(a.url,!1);g=Jn(f);if(!(M("nwl_consider_error_code")&&g||!M("nwl_consider_error_code")&&cp()<=qk("potential_esf_error_limit",10))){m.u(2);break}if(M("skip_checking_network_on_cfr_failure")&&(!M("skip_checking_network_on_cfr_failure")||vo().isEndpointCFR(a.url))){m.u(3);break}return v(m,So().Ka(),3);case 3:if(So().L()){m.u(2);break}c(e,f);if(!M("nwl_consider_error_code")||void 0===
(null==(h=a)?void 0:h.id)){m.u(6);break}return v(m,ho(a.id,b,!1),6);case 6:return m.return();case 2:if(M("nwl_consider_error_code")&&!g&&cp()>qk("potential_esf_error_limit",10))return m.return();B("ytNetworklessLoggingInitializationOptions")&&Po.potentialEsfErrorCounter++;No++;if(void 0===(null==(k=a)?void 0:k.id)){m.u(8);break}return 1>a.sendCount?v(m,ho(a.id,b),12):v(m,io(a.id,b),8);case 12:Nh.S(function(){So().L()&&To()},5E3);
case 8:c(e,f),m.i=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){var g;return w(function(h){if(1==h.i)return M("use_cfr_monitor")&&vo().requestComplete(a.url,!0),void 0===(null==(g=a)?void 0:g.id)?h.u(2):v(h,io(a.id,b),2);M("vss_network_hint")&&So().ha(!0);d(e,f);h.i=0})};
return a}
function ap(a,b){a=a.timestamp;return P()-a>=b?!1:!0}
function Ro(){var a=on();if(!a)throw um("retryQueuedRequests");fo("QUEUED",a).then(function(b){b&&!ap(b,12E4)?Nh.S(function(){return w(function(c){if(1==c.i)return void 0===b.id?c.u(2):v(c,ho(b.id,a),2);Ro();c.i=0})}):So().L()&&To()})}
function Vo(){var a,b;return w(function(c){a=on();if(!a)throw b=um("clearSWHealthLogsDb"),b;return c.return(po(a).catch(function(d){wk(d)}))})}
function So(){if(M("use_new_nwl"))return Fo();Oo||(Oo=new Bo({Mc:!0,Cc:!0}));return Oo}
function Yo(a,b,c){c&&0===Object.keys(b).length?so(a):Xk(a,b)}
function Xo(){return B("ytNetworklessLoggingInitializationOptions")?Po.isNwlInitialized:Lo}
function cp(){return B("ytNetworklessLoggingInitializationOptions")?Po.potentialEsfErrorCounter:No}
;function dp(a){var b=this;this.config_=null;a?this.config_=a:vl()&&(this.config_=wl());Ol(function(){Ll(b)},0,5E3)}
dp.prototype.isReady=function(){!this.config_&&vl()&&(this.config_=wl());return!!this.config_};
function Ml(a,b,c,d){function e(A){A=void 0===A?!1:A;var D;if(d.retry&&"www.youtube-nocookie.com"!=h&&(A||M("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(D=Jl(b,c,m,k)),D)){var F=g.onSuccess,N=g.onFetchSuccess;g.onSuccess=function(O,Q){Kl(D);F(O,Q)};
c.onFetchSuccess=function(O,Q){Kl(D);N(O,Q)}}try{A&&d.retry&&!d.Wb.bypassNetworkless?(g.method="POST",d.Wb.writeThenSend?M("use_new_nwl_wts")?Io().writeThenSend(u,g):Wo(u,g):M("use_new_nwl_saw")?Io().sendAndWrite(u,g):$o(u,g)):(g.method="POST",g.postParams||(g.postParams={}),Xk(u,g))}catch(O){if("InvalidAccessError"==O.name)D&&(Kl(D),D=0),xk(Error("An extension is blocking network request."));
else throw O;}D&&Ol(function(){Ll(a)},0,5E3)}
!L("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&xk(new R("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new R("innertube xhrclient not ready",b,c,d);wk(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(A,D){if(d.onSuccess)d.onSuccess(D)},
onFetchSuccess:function(A){if(d.onSuccess)d.onSuccess(A)},
onError:function(A,D){if(d.onError)d.onError(D)},
onFetchError:function(A){if(d.onError)d.onError(A)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.Jc)&&(h=f);var k=a.config_.Lc||!1,m=Dl(k,h,d);Object.assign(g.headers,m);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var q="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,r={alt:"json"},x=a.config_.Kc&&f;x=x&&f.startsWith("Bearer");x||(r.key=a.config_.innertubeApiKey);var u=Jk(""+h+q,r||{},!0);M("use_new_nwl")&&Io().i||!M("use_new_nwl")&&
Xo()?nn().then(function(A){e(A)}):e(!1)}
;var ep=0,fp=Nc?"webkit":Mc?"moz":Kc?"ms":Jc?"o":"";z("ytDomDomGetNextId",B("ytDomDomGetNextId")||function(){return++ep});var gp={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function xp(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in gp||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.i=a.pageX;this.j=a.pageY}}catch(e){}}
function Wp(a){if(document.body&&document.documentElement){var b=document.body.scrollTop+document.documentElement.scrollTop;a.i=a.clientX+(document.body.scrollLeft+document.documentElement.scrollLeft);a.j=a.clientY+b}}
xp.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
xp.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
xp.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var ob=y.ytEventsEventsListeners||{};z("ytEventsEventsListeners",ob);var Xp=y.ytEventsEventsCounter||{count:0};z("ytEventsEventsCounter",Xp);
function Yp(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return nb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=Ra(e[4])&&Ra(d)&&sb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
var Zp=db(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function $p(a,b,c,d){d=void 0===d?{}:d;if(!a||!a.addEventListener&&!a.attachEvent)return"";var e=Yp(a,b,c,d);if(e)return e;e=++Xp.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new xp(h);if(!cf(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new xp(h);
h.currentTarget=a;return c.call(a,h)};
g=vk(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),Zp()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);ob[e]=[a,b,c,g,d];return e}
function aq(a){a&&("string"==typeof a&&(a=[a]),fb(a,function(b){if(b in ob){var c=ob[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?Zp()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete ob[b]}}))}
;var bq=window.ytcsi&&window.ytcsi.now?window.ytcsi.now:window.performance&&window.performance.timing&&window.performance.now&&window.performance.timing.navigationStart?function(){return window.performance.timing.navigationStart+window.performance.now()}:function(){return(new Date).getTime()};function cq(a){this.F=a;this.j=null;this.o=0;this.v=null;this.s=0;this.l=[];for(a=0;4>a;a++)this.l.push(0);this.m=0;this.K=$p(window,"mousemove",Xa(this.P,this));a=Xa(this.J,this);"function"===typeof a&&(a=vk(a));this.R=window.setInterval(a,25)}
Za(cq,J);cq.prototype.P=function(a){void 0===a.i&&Wp(a);var b=a.i;void 0===a.j&&Wp(a);this.j=new Ze(b,a.j)};
cq.prototype.J=function(){if(this.j){var a=bq();if(0!=this.o){var b=this.v,c=this.j,d=b.x-c.x;b=b.y-c.y;d=Math.sqrt(d*d+b*b)/(a-this.o);this.l[this.m]=.5<Math.abs((d-this.s)/this.s)?1:0;for(c=b=0;4>c;c++)b+=this.l[c]||0;3<=b&&this.F();this.s=d}this.o=a;this.v=this.j;this.m=(this.m+1)%4}};
cq.prototype.C=function(){window.clearInterval(this.R);aq(this.K)};var dq={};
function eq(a){var b=void 0===a?{}:a;a=void 0===b.Sc?!1:b.Sc;b=void 0===b.Dc?!0:b.Dc;if(null==B("_lact",window)){var c=parseInt(L("LACT"),10);c=isFinite(c)?Date.now()-Math.max(c,0):-1;z("_lact",c,window);z("_fact",c,window);-1==c&&fq();$p(document,"keydown",fq);$p(document,"keyup",fq);$p(document,"mousedown",fq);$p(document,"mouseup",fq);a?$p(window,"touchmove",function(){gq("touchmove",200)},{passive:!0}):($p(window,"resize",function(){gq("resize",200)}),b&&$p(window,"scroll",function(){gq("scroll",200)}));
new cq(function(){gq("mouse",100)});
$p(document,"touchstart",fq,{passive:!0});$p(document,"touchend",fq,{passive:!0})}}
function gq(a,b){dq[a]||(dq[a]=!0,Nh.S(function(){fq();dq[a]=!1},b))}
function fq(){null==B("_lact",window)&&eq();var a=Date.now();z("_lact",a,window);-1==B("_fact",window)&&z("_fact",a,window);(a=B("ytglobal.ytUtilActivityCallback_"))&&a()}
function hq(){var a=B("_lact",window);return null==a?-1:Math.max(Date.now()-a,0)}
;var iq=y.ytPubsubPubsubInstance||new K,jq=y.ytPubsubPubsubSubscribedKeys||{},kq=y.ytPubsubPubsubTopicToKeys||{},lq=y.ytPubsubPubsubIsSynchronous||{};function mq(a,b){var c=nq();if(c&&b){var d=c.subscribe(a,function(){var e=arguments;var f=function(){jq[d]&&b.apply&&"function"==typeof b.apply&&b.apply(window,e)};
try{lq[a]?f():Qk(f,0)}catch(g){wk(g)}},void 0);
jq[d]=!0;kq[a]||(kq[a]=[]);kq[a].push(d);return d}return 0}
function oq(a){var b=nq();b&&("number"===typeof a?a=[a]:"string"===typeof a&&(a=[parseInt(a,10)]),fb(a,function(c){b.unsubscribeByKey(c);delete jq[c]}))}
function pq(a,b){var c=nq();c&&c.publish.apply(c,arguments)}
function qq(a){var b=nq();if(b)if(b.clear(a),a)rq(a);else for(var c in kq)rq(c)}
function nq(){return y.ytPubsubPubsubInstance}
function rq(a){kq[a]&&(a=kq[a],fb(a,function(b){jq[b]&&delete jq[b]}),a.length=0)}
K.prototype.subscribe=K.prototype.subscribe;K.prototype.unsubscribeByKey=K.prototype.Da;K.prototype.publish=K.prototype.oa;K.prototype.clear=K.prototype.clear;z("ytPubsubPubsubInstance",iq);z("ytPubsubPubsubTopicToKeys",kq);z("ytPubsubPubsubIsSynchronous",lq);z("ytPubsubPubsubSubscribedKeys",jq);var sq=y.window;sq.ytExports||(sq.ytExports={logging:{transport:{leaderQueueLength:0,leaderChosen:!1}}});var tq=qk("initial_gel_batch_timeout",2E3),uq=Math.pow(2,16)-1,vq=!1,wq=void 0;function xq(){this.l=this.i=this.j=0}
var yq=new xq,zq=new xq,Aq=!0,Bq=y.ytLoggingTransportGELQueue_||new Map;z("ytLoggingTransportGELQueue_",Bq);var Cq=new Map,Dq=y.ytLoggingTransportGELProtoQueue_||new Map;z("ytLoggingTransportGELProtoQueue_",Dq);var Eq=y.ytLoggingTransportTokensToCttTargetIds_||{};z("ytLoggingTransportTokensToCttTargetIds_",Eq);var Fq=y.ytLoggingTransportTokensToJspbCttTargetIds_||{};z("ytLoggingTransportTokensToJspbCttTargetIds_",Fq);
function Gq(){M("jspb_with_transport_leader")&&!sq.ytExports.logging.transport.leaderChosen&&(vq=sq.ytExports.logging.transport.leaderChosen=!0,document.addEventListener("FLUSH_REQUEST",function(){Hq(void 0,void 0,!0)}))}
function Iq(a,b){Gq();if("log_event"===a.endpoint){Jq(a);var c=Kq(a),d=Bq.get(c)||[];Bq.set(c,d);d.push(a.payload);Lq(b,d,c)}}
function Mq(a,b){Gq();if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0);if(M("jspb_with_transport_leader")&&vq){var d=Cq.get(c)||[];Cq.set(c,d);sq.ytExports.logging.transport.leaderQueueLength++;d.push(a.payload);Lq(b,d,c,!0)}else d=Dq.get(c)||[],Dq.set(c,d),a=a.payload.toJSON(),d.push(a),Lq(b,d,c,!0)}}
function Lq(a,b,c,d){d=void 0===d?!1:d;a&&(wq=new a);a=qk("tvhtml5_logging_max_batch")||qk("web_logging_max_batch")||100;var e=P(),f=d?zq.l:yq.l,g=Dq.get(c)||[];M("jspb_with_transport_leader")&&(vq&&b.length+g.length>=a||!vq&&sq.ytExports.logging.transport.leaderQueueLength+b.length>=a)||b.length>=a?Hq({writeThenSend:!0},M("flush_only_full_queue")?c:void 0,d):10<=e-f&&(Nq(d),d?zq.l=e:yq.l=e)}
function Oq(a,b){Gq();if("log_event"===a.endpoint){Jq(a);var c=Kq(a),d=new Map;d.set(c,[a.payload]);b&&(wq=new b);return new qf(function(e,f){wq&&wq.isReady()?Pq(d,e,f,{bypassNetworkless:!0},!0):e()})}}
function Qq(a,b){Gq();if("log_event"===a.endpoint){Jq(void 0,a);var c=Kq(a,!0),d=new Map,e=new Map;M("jspb_with_transport_leader")&&vq?e.set(c,[a.payload]):d.set(c,[a.payload.toJSON()]);b&&(wq=new b);return new qf(function(f){wq&&wq.isReady()?Rq(d,e,f,{bypassNetworkless:!0},!0):f()})}}
function Kq(a,b){var c="";if(a.Fa)c="visitorOnlyApprovedKey";else if(a.cttAuthInfo){if(void 0===b?0:b){b=a.cttAuthInfo.token;c=a.cttAuthInfo;var d=new Jj;c.videoId?d.setVideoId(c.videoId):c.playlistId&&Od(d,2,Kj,c.playlistId);Fq[b]=d}else b=a.cttAuthInfo,c={},b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId),Eq[a.cttAuthInfo.token]=c;c=a.cttAuthInfo.token}return c}
function Hq(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new qf(function(d,e){c?(Rk(zq.j),Rk(zq.i),zq.i=0):(Rk(yq.j),Rk(yq.i),yq.i=0);if(M("jspb_with_transport_leader")&&!vq&&c)document.dispatchEvent(new CustomEvent("FLUSH_REQUEST")),d();else if(wq&&wq.isReady())if(void 0!==b)if(c){e=new Map;var f=new Map,g=Dq.get(b)||[];e.set(b,g);M("jspb_with_transport_leader")&&(g=Cq.get(b)||[],f.set(b,g));Rq(e,f,d,a);M("jspb_with_transport_leader")&&Cq.delete(b);Dq.delete(b)}else f=new Map,g=Bq.get(b)||[],f.set(b,
g),Pq(f,d,e,a),Bq.delete(b);else c?(Rq(Dq,Cq,d,a),Dq.clear(),M("jspb_with_transport_leader")&&Cq.clear()):(Pq(Bq,d,e,a),Bq.clear());else Nq(c),d()})}
function Nq(a){a=void 0===a?!1:a;if(M("web_gel_timeout_cap")&&(!a&&!yq.i||a&&!zq.i)){var b=Qk(function(){Hq({writeThenSend:!0},void 0,a)},6E4);
a?zq.i=b:yq.i=b}Rk(a?zq.j:yq.j);b=L("LOGGING_BATCH_TIMEOUT",qk("web_gel_debounce_ms",1E4));M("shorten_initial_gel_batch_timeout")&&Aq&&(b=tq);b=Qk(function(){Hq({writeThenSend:!0},void 0,a)},b);
a?zq.j=b:yq.j=b}
function Pq(a,b,c,d,e){var f=wq;d=void 0===d?{}:d;var g=Math.round(P()),h=a.size;a=p(a);for(var k=a.next();!k.done;k=a.next()){var m=p(k.value);k=m.next().value;var q=m.next().value;m=k;k=ub({context:xl(f.config_||wl())});k.events=q;(q=Eq[m])&&Sq(k,m,q);delete Eq[m];m="visitorOnlyApprovedKey"===m;Tq(k,g,m);Uq(d);q=function(){h--;h||b()};
var r=function(){h--;h||b()};
try{Ml(f,"log_event",k,Vq(d,m,q,r,e)),Aq=!1}catch(x){wk(x),c()}}}
function Rq(a,b,c,d,e){var f=wq;d=void 0===d?{}:d;var g=Math.round(P()),h=a.size+b.size,k=new Map([].concat(ia(a),ia(b)));k=p(k);for(var m=k.next();!m.done;m=k.next()){var q=p(m.value).next().value,r=a.get(q),x=b.get(q)||[];m=new Lj;var u=Cl(f.config_||wl());G(m,Qi,1,u);r=r?Wq(r):[];r=p(r);for(u=r.next();!u.done;u=r.next())Vd(m,3,Fj,u.value);x=p(x);for(r=x.next();!r.done;r=x.next())Vd(m,3,Fj,r.value);(x=Fq[q])&&Xq(m,q,x);delete Fq[q];q="visitorOnlyApprovedKey"===q;Yq(m,g,q);Uq(d);m=Yd(m);q=Vq(d,q,
function(){sq.ytExports.logging.transport.leaderQueueLength=0;h--;h||c()},function(){sq.ytExports.logging.transport.leaderQueueLength=0;
h--;h||c()},e);
q.headers={"Content-Type":"application/json+protobuf"};q.postBodyFormat="JSPB";q.postBody=m;Ml(f,"log_event","",q);Aq=!1}}
function Uq(a){M("always_send_and_write")&&(a.writeThenSend=!1)}
function Vq(a,b,c,d,e){return{retry:!0,onSuccess:c,onError:d,Wb:a,Fa:b,iq:!!e,headers:{},postBodyFormat:"",postBody:""}}
function Tq(a,b,c){a.requestTimeMs=String(b);M("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=L("EVENT_ID"))&&(c=Zq(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Yq(a,b,c){E(a,2,b);if(!c&&(b=L("EVENT_ID"))){c=Zq();var d=new Ij;E(d,1,b);E(d,2,c);G(a,Ij,5,d)}}
function Zq(){var a=L("BATCH_CLIENT_COUNTER")||0;a||(a=Math.floor(Math.random()*uq/2));a++;a>uq&&(a=1);nk("BATCH_CLIENT_COUNTER",a);return a}
function Sq(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Xq(a,b,c){if(Kd(c,1===Pd(c,Kj)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;G(a,Jj,4,c);a=Qd(a,Qi,1)||new Qi;c=Qd(a,Oi,3)||new Oi;var e=new Ni;e.setToken(b);E(e,1,d);Vd(c,12,Ni,e);G(a,Oi,3,c)}
function Wq(a){for(var b=[],c=0;c<a.length;c++)try{b.push(new Fj(a[c]))}catch(d){wk(new R("Transport failed to deserialize "+String(a[c])))}return b}
function Jq(a,b){if(B("yt.logging.transport.enableScrapingForTest")){var c=B("yt.logging.transport.scrapedPayloadsForTesting"),d=B("yt.logging.transport.payloadToScrape","");b&&(b=B("yt.logging.transport.getScrapedPayloadFromClientEventsFunction").bind(b.payload)())&&c.push(b);a&&a.payload[d]&&c.push((null==a?void 0:a.payload)[d]);z("yt.logging.transport.scrapedPayloadsForTesting",c)}}
;var $q=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",$q);function ar(a,b,c,d){d=void 0===d?{}:d;var e={},f=Math.round(d.timestamp||P());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=hq();e.context={lastActivityMs:String(d.timestamp||!isFinite(a)?-1:a)};M("log_sequence_info_on_gel_web")&&d.ba&&(a=e.context,b=d.ba,b={index:br(b),groupKey:b},a.sequence=b,d.Ob&&delete $q[d.ba]);(d.fc?Oq:Iq)({endpoint:"log_event",payload:e,cttAuthInfo:d.cttAuthInfo,Fa:d.Fa},c)}
function cr(a){Hq(void 0,void 0,void 0===a?!1:a)}
function br(a){$q[a]=a in $q?$q[a]+1:0;return $q[a]}
;var dr=y.ytLoggingGelSequenceIdObj_||{};z("ytLoggingGelSequenceIdObj_",dr);function er(a,b,c){c=void 0===c?{}:c;var d=Math.round(c.timestamp||P());E(a,1,d<Number.MAX_SAFE_INTEGER?d:0);var e=hq();d=new Ej;E(d,1,c.timestamp||!isFinite(e)?-1:e);if(M("log_sequence_info_on_gel_web")&&c.ba){e=c.ba;var f=br(e),g=new Dj;E(g,2,f);E(g,1,e);G(d,Dj,3,g);c.Ob&&delete dr[c.ba]}G(a,Ej,33,d);(c.fc?Qq:Mq)({endpoint:"log_event",payload:a,cttAuthInfo:c.cttAuthInfo,Fa:c.Fa},b)}
;function fr(a,b){b=void 0===b?{}:b;var c=!1;L("ytLoggingEventsDefaultDisabled",!1)&&(c=!0);er(a,c?null:dp,b)}
;function gr(a,b){var c=new Fj;Td(c,sj,72,Gj,a);fr(c,b)}
function hr(a,b,c){var d=new Fj;Td(d,rj,73,Gj,a);c?er(d,c,b):fr(d,b)}
function ir(a,b,c){var d=new Fj;Td(d,qj,78,Gj,a);c?er(d,c,b):fr(d,b)}
function jr(a,b,c){var d=new Fj;Td(d,tj,208,Gj,a);c?er(d,c,b):fr(d,b)}
function kr(a,b,c){var d=new Fj;Td(d,jj,156,Gj,a);c?er(d,c,b):fr(d,b)}
function lr(a,b,c){var d=new Fj;Td(d,nj,215,Gj,a);c?er(d,c,b):fr(d,b)}
function mr(a,b,c){var d=new Fj;Td(d,fj,111,Gj,a);c?er(d,c,b):fr(d,b)}
;function cm(a,b,c){c=void 0===c?{}:c;var d=dp;L("ytLoggingEventsDefaultDisabled",!1)&&dp==dp&&(d=null);ar(a,b,d,c)}
;var nr=[{ub:function(a){return"Cannot read property '"+a.key+"'"},
bb:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{ub:function(a){return"Cannot call '"+a.key+"'"},
bb:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{ub:function(a){return a.key+" is not defined"},
bb:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var pr={ma:[],la:[{callback:or,weight:500}]};function or(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function qr(){this.la=[];this.ma=[]}
var rr;function sr(){if(!rr){var a=rr=new qr;a.ma.length=0;a.la.length=0;pr.ma&&a.ma.push.apply(a.ma,pr.ma);pr.la&&a.la.push.apply(a.la,pr.la)}return rr}
;var tr=new K;function ur(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=vr(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=vr(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=vr(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function vr(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function wr(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=xr(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=ur(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?xr(e+".ve",f,g,h):0;d+=g;d+=xr(e,a[e],b,c);if(500<d)break}}else c[b]=yr(a),d+=c[b].length;else c[b]=yr(a),d+=c[b].length;return d}
function xr(a,b,c,d){c+="."+a;a=yr(b);d[c]=a;return c.length+a.length}
function yr(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var zr=new Set,Ar=0,Br=0,Cr=0,Dr=[],Er=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];function bm(a){Fr(a)}
function Gr(a){Fr(a,"WARNING")}
function Fr(a,b,c,d,e,f){f=void 0===f?{}:f;f.name=c||L("INNERTUBE_CONTEXT_CLIENT_NAME",1);f.version=d||L("INNERTUBE_CONTEXT_CLIENT_VERSION");var g=f||{},h=void 0===b?"ERROR":b;h=void 0===h?"ERROR":h;if(a){a.hasOwnProperty("level")&&a.level&&(h=a.level);if(M("console_log_js_exceptions")){var k=[];k.push("Name: "+a.name);k.push("Message: "+a.message);a.hasOwnProperty("params")&&k.push("Error Params: "+JSON.stringify(a.params));a.hasOwnProperty("args")&&k.push("Error args: "+JSON.stringify(a.args));
k.push("File name: "+a.fileName);k.push("Stacktrace: "+a.stack);window.console.log(k.join("\n"),a)}if(!(5<=Ar)){var m=Dr,q=oe(a),r=q.message||"Unknown Error",x=q.name||"UnknownError",u=q.stack||a.j||"Not available";if(u.startsWith(x+": "+r)){var A=u.split("\n");A.shift();u=A.join("\n")}var D=q.lineNumber||"Not available",F=q.fileName||"Not available",N=u,O=0;if(a.hasOwnProperty("args")&&a.args&&a.args.length)for(var Q=0;Q<a.args.length&&!(O=wr(a.args[Q],"params."+Q,g,O),500<=O);Q++);else if(a.hasOwnProperty("params")&&
a.params){var ea=a.params;if("object"===typeof a.params)for(var ba in ea){if(ea[ba]){var la="params."+ba,X=yr(ea[ba]);g[la]=X;O+=la.length+X.length;if(500<O)break}}else g.params=yr(ea)}if(m.length)for(var Aa=0;Aa<m.length&&!(O=wr(m[Aa],"params.context."+Aa,g,O),500<=O);Aa++);navigator.vendor&&!g.hasOwnProperty("vendor")&&(g["device.vendor"]=navigator.vendor);var H={message:r,name:x,lineNumber:D,fileName:F,stack:N,params:g,sampleWeight:1},Ga=Number(a.columnNumber);isNaN(Ga)||(H.lineNumber=H.lineNumber+
":"+Ga);if("IGNORED"===a.level)var za=0;else a:{for(var hp=sr(),ip=p(hp.ma),Mj=ip.next();!Mj.done;Mj=ip.next()){var jp=Mj.value;if(H.message&&H.message.match(jp.qq)){za=jp.weight;break a}}for(var kp=p(hp.la),Nj=kp.next();!Nj.done;Nj=kp.next()){var lp=Nj.value;if(lp.callback(H)){za=lp.weight;break a}}za=1}H.sampleWeight=za;for(var mp=p(nr),Oj=mp.next();!Oj.done;Oj=mp.next()){var Pj=Oj.value;if(Pj.bb[H.name])for(var np=p(Pj.bb[H.name]),Qj=np.next();!Qj.done;Qj=np.next()){var op=Qj.value,Eg=H.message.match(op.regexp);
if(Eg){H.params["params.error.original"]=Eg[0];for(var Rj=op.groups,pp={},pd=0;pd<Rj.length;pd++)pp[Rj[pd]]=Eg[pd+1],H.params["params.error."+Rj[pd]]=Eg[pd+1];H.message=Pj.ub(pp);break}}}H.params||(H.params={});var qp=sr();H.params["params.errorServiceSignature"]="msg="+qp.ma.length+"&cb="+qp.la.length;H.params["params.serviceWorker"]="false";y.document&&y.document.querySelectorAll&&(H.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));Db("sample").constructor!==
zb&&(H.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(H);if(0!==H.sampleWeight&&!zr.has(H.message)){if("ERROR"===h){tr.oa("handleError",H);if(M("record_app_crashed_web")&&0===Cr&&1===H.sampleWeight)if(Cr++,M("errors_via_jspb")){var Sj=new cj;E(Sj,1,1);if(!M("report_client_error_with_app_crash_ks")){var rp=new Yi;E(rp,1,H.message);var sp=new Zi;G(sp,Yi,3,rp);var tp=new $i;G(tp,Zi,5,sp);var up=new aj;G(up,$i,9,tp);G(Sj,aj,4,up)}var vp=new Fj;Td(vp,cj,20,
Gj,Sj);fr(vp)}else{var wp={appCrashType:"APP_CRASH_TYPE_BREAKPAD"};M("report_client_error_with_app_crash_ks")||(wp.systemHealth={crashData:{clientError:{logMessage:{message:H.message}}}});cm("appCrashed",wp)}Br++}else"WARNING"===h&&tr.oa("handleWarning",H);if(M("kevlar_gel_error_routing"))a:{var ue=h;if(M("errors_via_jspb")){if(Hr())var yp=void 0;else{var qd=new Vi;E(qd,1,H.stack);H.fileName&&E(qd,4,H.fileName);var Ab=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Ab.length&&(1!==
Ab.length||isNaN(Number(Ab[0]))?2!==Ab.length||isNaN(Number(Ab[0]))||isNaN(Number(Ab[1]))||(E(qd,2,Number(Ab[0])),E(qd,3,Number(Ab[1]))):E(qd,2,Number(Ab[0])));var uc=new Yi;E(uc,1,H.message);E(uc,3,H.name);E(uc,6,H.sampleWeight);"ERROR"===ue?E(uc,2,2):"WARNING"===ue?E(uc,2,1):E(uc,2,0);var Tj=new Wi;E(Tj,1,!0);Td(Tj,Vi,3,Xi,qd);var Wb=new Si;E(Wb,3,window.location.href);for(var zp=L("FEXP_EXPERIMENTS",[]),Uj=0;Uj<zp.length;Uj++){var sv=zp[Uj];xd(Wb);Ld(Wb,5).push(sv)}var Vj=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");
if(!ok()&&Vj)for(var Ap=p(Object.keys(Vj)),vc=Ap.next();!vc.done;vc=Ap.next()){var Bp=vc.value,Wj=new Ui;E(Wj,1,Bp);Wj.setValue(String(Vj[Bp]));Vd(Wb,4,Ui,Wj)}var Xj=H.params;if(Xj){var Cp=p(Object.keys(Xj));for(vc=Cp.next();!vc.done;vc=Cp.next()){var Dp=vc.value,Yj=new Ui;E(Yj,1,"client."+Dp);Yj.setValue(String(Xj[Dp]));Vd(Wb,4,Ui,Yj)}}var Ep=L("SERVER_NAME"),Fp=L("SERVER_VERSION");if(Ep&&Fp){var Zj=new Ui;E(Zj,1,"server.name");Zj.setValue(Ep);Vd(Wb,4,Ui,Zj);var ak=new Ui;E(ak,1,"server.version");
ak.setValue(Fp);Vd(Wb,4,Ui,ak)}var Fg=new Zi;G(Fg,Si,1,Wb);G(Fg,Wi,2,Tj);G(Fg,Yi,3,uc);yp=Fg}var Gp=yp;if(!Gp)break a;var Hp=new Fj;Td(Hp,Zi,163,Gj,Gp);fr(Hp)}else{if(Hr())var Ip=void 0;else{var ve={stackTrace:H.stack};H.fileName&&(ve.filename=H.fileName);var Bb=H.lineNumber&&H.lineNumber.split?H.lineNumber.split(":"):[];0!==Bb.length&&(1!==Bb.length||isNaN(Number(Bb[0]))?2!==Bb.length||isNaN(Number(Bb[0]))||isNaN(Number(Bb[1]))||(ve.lineNumber=Number(Bb[0]),ve.columnNumber=Number(Bb[1])):ve.lineNumber=
Number(Bb[0]));var bk={level:"ERROR_LEVEL_UNKNOWN",message:H.message,errorClassName:H.name,sampleWeight:H.sampleWeight};"ERROR"===ue?bk.level="ERROR_LEVEL_ERROR":"WARNING"===ue&&(bk.level="ERROR_LEVEL_WARNNING");var tv={isObfuscated:!0,browserStackInfo:ve},rd={pageUrl:window.location.href,kvPairs:[]};L("FEXP_EXPERIMENTS")&&(rd.experimentIds=L("FEXP_EXPERIMENTS"));var ck=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(!ok()&&ck)for(var Jp=p(Object.keys(ck)),wc=Jp.next();!wc.done;wc=Jp.next()){var Kp=
wc.value;rd.kvPairs.push({key:Kp,value:String(ck[Kp])})}var dk=H.params;if(dk){var Lp=p(Object.keys(dk));for(wc=Lp.next();!wc.done;wc=Lp.next()){var Mp=wc.value;rd.kvPairs.push({key:"client."+Mp,value:String(dk[Mp])})}}var Np=L("SERVER_NAME"),Op=L("SERVER_VERSION");Np&&Op&&(rd.kvPairs.push({key:"server.name",value:Np}),rd.kvPairs.push({key:"server.version",value:Op}));Ip={errorMetadata:rd,stackTrace:tv,logMessage:bk}}var Pp=Ip;if(!Pp)break a;cm("clientError",Pp)}if("ERROR"===ue||M("errors_flush_gel_always_killswitch"))b:{if(M("web_fp_via_jspb")&&
(cr(!0),!M("web_fp_via_jspb_and_json")))break b;cr()}}if(!M("suppress_error_204_logging")){var we=H.params||{},Xb={urlParams:{a:"logerror",t:"jserror",type:H.name,msg:H.message.substr(0,250),line:H.lineNumber,level:h,"client.name":we.name},postParams:{url:L("PAGE_NAME",window.location.href),file:H.fileName},method:"POST"};we.version&&(Xb["client.version"]=we.version);if(Xb.postParams){H.stack&&(Xb.postParams.stack=H.stack);for(var Qp=p(Object.keys(we)),ek=Qp.next();!ek.done;ek=Qp.next()){var Rp=ek.value;
Xb.postParams["client."+Rp]=we[Rp]}var fk=L("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS");if(fk)for(var Sp=p(Object.keys(fk)),gk=Sp.next();!gk.done;gk=Sp.next()){var Tp=gk.value;Xb.postParams[Tp]=fk[Tp]}var Up=L("SERVER_NAME"),Vp=L("SERVER_VERSION");Up&&Vp&&(Xb.postParams["server.name"]=Up,Xb.postParams["server.version"]=Vp)}Xk(L("ECATCHER_REPORT_HOST","")+"/error_204",Xb)}try{zr.add(H.message)}catch(Sw){}Ar++}}}}
function Hr(){for(var a=p(Er),b=a.next();!b.done;b=a.next())if(Ul(b.value.toLowerCase()))return!0;return!1}
function Ir(a){var b=Ka.apply(1,arguments);a.args||(a.args=[]);a.args.push.apply(a.args,ia(b))}
;function Jr(){this.register=new Map}
function Kr(a){a=p(a.register.values());for(var b=a.next();!b.done;b=a.next())b.value.tq("ABORTED")}
Jr.prototype.clear=function(){Kr(this);this.register.clear()};
var Lr=new Jr;var Mr=Date.now().toString();
function Nr(){a:{if(window.crypto&&window.crypto.getRandomValues)try{var a=Array(16),b=new Uint8Array(16);window.crypto.getRandomValues(b);for(var c=0;c<a.length;c++)a[c]=b[c];var d=a;break a}catch(e){}d=Array(16);for(a=0;16>a;a++){b=Date.now();for(c=0;c<b%23;c++)d[a]=Math.random();d[a]=Math.floor(256*Math.random())}if(Mr)for(a=1,b=0;b<Mr.length;b++)d[a%16]=d[a%16]^d[(a-1)%16]/4^Mr.charCodeAt(b),a++}a=[];for(b=0;b<d.length;b++)a.push("ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_".charAt(d[b]&63));
return a.join("")}
;var Or=y.ytLoggingDocDocumentNonce_;Or||(Or=Nr(),z("ytLoggingDocDocumentNonce_",Or));var Pr=Or;var Qr={xh:0,je:1,te:2,pl:3,zh:4,Cp:5,fm:6,Ln:7,fn:8,zn:9,0:"DEFAULT",1:"CHAT",2:"CONVERSATIONS",3:"MINIPLAYER",4:"DIALOG",5:"VOZ",6:"MUSIC_WATCH_TABS",7:"SHARE",8:"PUSH_NOTIFICATIONS",9:"RICH_GRID_WATCH"};function Rr(a){this.i=a}
function Sr(a){return new Rr({trackingParams:a})}
Rr.prototype.getAsJson=function(){var a={};void 0!==this.i.trackingParams?a.trackingParams=this.i.trackingParams:(a.veType=this.i.veType,void 0!==this.i.veCounter&&(a.veCounter=this.i.veCounter),void 0!==this.i.elementIndex&&(a.elementIndex=this.i.elementIndex));void 0!==this.i.dataElement&&(a.dataElement=this.i.dataElement.getAsJson());void 0!==this.i.youtubeData&&(a.youtubeData=this.i.youtubeData);return a};
Rr.prototype.getAsJspb=function(){var a=new ej;void 0!==this.i.trackingParams?E(a,1,this.i.trackingParams):(void 0!==this.i.veType&&E(a,2,this.i.veType),void 0!==this.i.veCounter&&E(a,6,this.i.veCounter),void 0!==this.i.elementIndex&&E(a,3,this.i.elementIndex));if(void 0!==this.i.dataElement){var b=this.i.dataElement.getAsJspb();G(a,ej,7,b)}void 0!==this.i.youtubeData&&G(a,Ci,8,this.i.jspbYoutubeData);return a};
Rr.prototype.toString=function(){return JSON.stringify(this.getAsJson())};
Rr.prototype.isClientVe=function(){return!this.i.trackingParams&&!!this.i.veType};function Tr(a){a=void 0===a?0:a;return 0===a?"client-screen-nonce":"client-screen-nonce."+a}
function Ur(a){a=void 0===a?0:a;return 0===a?"ROOT_VE_TYPE":"ROOT_VE_TYPE."+a}
function Vr(a){return L(Ur(void 0===a?0:a))}
z("yt_logging_screen.getRootVeType",Vr);function Wr(a){return(a=Vr(void 0===a?0:a))?new Rr({veType:a,youtubeData:void 0,jspbYoutubeData:void 0}):null}
function Xr(){var a=L("csn-to-ctt-auth-info");a||(a={},nk("csn-to-ctt-auth-info",a));return a}
function Yr(a){a=L(Tr(void 0===a?0:a));if(!a&&!L("USE_CSN_FALLBACK",!0))return null;a||(a="UNDEFINED_CSN");return a?a:null}
z("yt_logging_screen.getCurrentCsn",Yr);function Zr(a,b,c){var d=Xr();(c=Yr(c))&&delete d[c];b&&(d[a]=b)}
function $r(a){return Xr()[a]}
z("yt_logging_screen.getCttAuthInfo",$r);
function as(a,b,c,d){c=void 0===c?0:c;if(a!==L(Tr(c))||b!==L(Ur(c)))if(Zr(a,d,c),nk(Tr(c),a),nk(Ur(c),b),b=function(){setTimeout(function(){if(a)if(M("web_time_via_jspb")){var e=new fj;E(e,1,Pr);E(e,2,a);M("use_default_heartbeat_client")?mr(e):mr(e,void 0,dp)}else e={clientDocumentNonce:Pr,clientScreenNonce:a},M("use_default_heartbeat_client")?cm("foregroundHeartbeatScreenAssociated",e):ar("foregroundHeartbeatScreenAssociated",e,dp)},0)},"requestAnimationFrame"in window)try{window.requestAnimationFrame(b)}catch(e){b()}else b()}
z("yt_logging_screen.setCurrentScreen",as);var bs=window.yt&&window.yt.msgs_||window.ytcfg&&window.ytcfg.msgs||{};z("yt.msgs_",bs);function cs(a){ik(bs,arguments)}
;var ds={ie:3611,ud:27686,vd:85013,wd:23462,yd:42016,zd:62407,Ad:26926,xd:43781,Bd:51236,Cd:79148,Dd:50160,Ed:77504,Qd:153587,Rd:87907,Sd:18630,Td:54445,Ud:80935,Vd:152172,Wd:105675,Xd:150723,Yd:37521,Zd:147285,ae:47786,be:98349,ce:123695,de:6827,ee:29434,ge:7282,he:124448,le:32276,ke:76278,me:147868,ne:147869,oe:93911,pe:106531,qe:27259,re:27262,se:27263,ue:21759,we:27107,xe:62936,ye:49568,ze:38408,Ae:80637,Be:68727,Ce:68728,De:80353,Ee:80356,Fe:74610,Ge:45707,He:83962,Ie:83970,Je:46713,Ke:89711,
Le:74612,Me:93265,Ne:74611,Oe:131380,Qe:128979,Re:139311,Se:128978,Pe:131391,Te:105350,Ve:139312,We:134800,Ue:131392,Ye:113533,Ze:93252,af:99357,cf:94521,df:114252,ef:113532,ff:94522,bf:94583,gf:88E3,hf:139580,jf:93253,kf:93254,lf:94387,mf:94388,nf:93255,pf:97424,Xe:72502,qf:110111,rf:76019,tf:117092,uf:117093,sf:89431,vf:110466,wf:77240,xf:60508,yf:148123,zf:148124,Af:137401,Bf:137402,Cf:137046,Df:73393,Ef:113534,Ff:92098,Gf:131381,Hf:84517,If:83759,Jf:80357,Kf:86113,Lf:72598,Mf:72733,Nf:107349,
Of:124275,Pf:118203,Qf:133275,Rf:152569,Sf:133274,Tf:133272,Uf:133273,Vf:133276,Wf:144507,Xf:143247,Yf:143248,Zf:143249,ag:143250,cg:143251,dg:144401,fg:117431,eg:133797,gg:153964,hg:128572,ig:133405,jg:117429,kg:117430,lg:117432,mg:120080,ng:117259,og:121692,pg:145656,qg:145655,rg:145653,sg:145654,tg:145657,ug:132972,vg:133051,wg:133658,xg:132971,yg:97615,Ag:143359,zg:143356,Cg:143361,Bg:143358,Eg:143360,Dg:143357,Fg:142303,Gg:143353,Hg:143354,Ig:144479,Jg:143355,Kg:31402,Mg:133624,Ng:146477,Og:133623,
Pg:133622,Lg:133621,Qg:84774,Rg:95117,Sg:150497,Tg:98930,Ug:98931,Vg:98932,Wg:43347,Xg:129889,Yg:149123,Zg:45474,ah:100352,bh:84758,dh:98443,eh:117985,fh:74613,gh:74614,hh:64502,ih:136032,jh:74615,kh:74616,lh:122224,mh:74617,nh:77820,oh:74618,ph:93278,qh:93274,rh:93275,sh:93276,th:22110,uh:29433,vh:133798,wh:132295,yh:120541,Ah:82047,Bh:113550,Ch:75836,Dh:75837,Eh:42352,Fh:84512,Gh:76065,Hh:75989,Mh:16623,Nh:32594,Oh:27240,Ph:32633,Qh:74858,Sh:3945,Rh:16989,Th:45520,Uh:25488,Vh:25492,Wh:25494,Xh:55760,
Yh:14057,Zh:18451,ai:57204,bi:57203,ci:17897,di:57205,fi:18198,gi:17898,hi:17909,ii:43980,ji:46220,ki:11721,li:147994,mi:49954,ni:96369,oi:3854,ri:151633,si:56251,ti:25624,vi:152036,Mi:16906,Ni:99999,Oi:68172,Pi:27068,Qi:47973,Ri:72773,Si:26970,Ti:26971,Ui:96805,Vi:17752,Wi:73233,Xi:109512,Yi:22256,Zi:14115,aj:22696,bj:89278,cj:89277,dj:109513,ej:43278,fj:43459,gj:43464,hj:89279,ij:43717,jj:55764,kj:22255,lj:147912,mj:89281,nj:40963,oj:43277,pj:43442,qj:91824,rj:120137,sj:96367,tj:36850,uj:72694,
vj:37414,wj:36851,yj:124863,xj:121343,zj:73491,Aj:54473,Bj:43375,Cj:46674,Dj:143815,Ej:139095,Fj:144402,Gj:149968,Hj:149969,Ij:32473,Jj:72901,Kj:72906,Lj:50947,Mj:50612,Nj:50613,Oj:50942,Pj:84938,Qj:84943,Rj:84939,Sj:84941,Tj:84944,Uj:84940,Vj:84942,Wj:35585,Xj:51926,Yj:79983,Zj:63238,ak:18921,bk:63241,ck:57893,dk:41182,ek:135732,fk:33424,gk:22207,hk:42993,ik:36229,jk:22206,kk:22205,lk:18993,mk:19001,nk:18990,pk:18991,qk:18997,rk:18725,sk:19003,tk:36874,uk:44763,vk:33427,wk:67793,xk:22182,yk:37091,
zk:34650,Ak:50617,Bk:47261,Ck:22287,Dk:25144,Ek:97917,Fk:62397,Gk:150871,Hk:150874,Ik:125598,Jk:137935,Kk:36961,Lk:108035,Mk:27426,Nk:27857,Ok:27846,Pk:27854,Qk:69692,Rk:61411,Sk:39299,Tk:38696,Uk:62520,Vk:36382,Wk:108701,Xk:50663,Yk:36387,Zk:14908,al:37533,bl:105443,dl:61635,fl:62274,il:133818,jl:65702,kl:65703,ll:65701,ml:76256,nl:37671,ol:49953,ql:36216,rl:28237,sl:39553,ul:29222,vl:26107,wl:38050,xl:26108,zl:120745,yl:26109,Al:26110,Bl:66881,Cl:28236,Dl:14586,El:57929,Fl:74723,Gl:44098,Hl:44099,
Kl:23528,Ll:61699,Il:134104,Jl:134103,Ml:59149,Nl:101951,Ol:97346,Pl:118051,Ql:95102,Rl:64882,Sl:119505,Tl:63595,Ul:63349,Vl:95101,Wl:75240,Xl:27039,Yl:68823,Zl:21537,am:83464,bm:75707,cm:83113,dm:101952,em:101953,gm:79610,hm:125755,im:24402,jm:24400,km:32925,lm:57173,mm:122502,nm:145268,om:138480,pm:64423,qm:64424,rm:33986,sm:100828,tm:129089,um:21409,ym:135155,zm:135156,Am:135157,Bm:135158,Cm:135159,Dm:135160,Em:135161,Fm:135162,Gm:135163,Hm:135164,Im:135165,Jm:135166,vm:11070,wm:11074,xm:17880,
Km:14001,Mm:30709,Nm:30707,Om:30711,Pm:30710,Qm:30708,Lm:26984,Rm:146143,Sm:63648,Tm:63649,Um:51879,Vm:111059,Wm:5754,Xm:20445,Ym:151308,Zm:151152,bn:130975,an:130976,cn:110386,dn:113746,en:66557,gn:17310,hn:28631,jn:21589,kn:154946,ln:68012,mn:60480,nn:138664,pn:141121,qn:31571,rn:141978,sn:150105,tn:150106,un:150107,vn:150108,wn:76980,xn:41577,yn:45469,An:38669,Bn:13768,Cn:13777,Dn:141842,En:62985,Fn:4724,Gn:59369,Hn:43927,In:43928,Jn:12924,Kn:100355,Nn:56219,On:27669,Pn:10337,Mn:47896,Qn:122629,
Sn:139723,Rn:139722,Tn:121258,Un:107598,Vn:127991,Wn:96639,Xn:107536,Yn:130169,Zn:96661,ao:145188,bo:96658,co:116646,eo:121122,fo:96660,ho:127738,jo:127083,ko:147842,lo:104443,mo:96659,no:147595,oo:106442,po:134840,qo:63667,ro:63668,so:63669,to:130686,uo:147036,vo:78314,wo:147799,xo:148649,yo:55761,zo:127098,Ao:134841,Bo:96368,Co:67374,Do:48992,Eo:146176,Fo:49956,Go:31961,Ho:26388,Io:23811,Jo:5E4,Ko:126250,Lo:96370,Mo:47355,No:47356,Oo:37935,Po:45521,Qo:21760,Ro:83769,So:49977,To:49974,Uo:93497,Vo:93498,
Wo:34325,Xo:140759,Yo:115803,Zo:123707,ap:100081,bp:35309,cp:68314,ep:25602,fp:100339,gp:143516,hp:59018,ip:18248,jp:50625,kp:9729,lp:37168,mp:37169,np:21667,qp:16749,rp:18635,sp:39305,tp:18046,up:53969,vp:8213,wp:93926,xp:102852,yp:110099,zp:22678,Ap:69076,Bp:137575,Dp:139224,Ep:100856,Fp:154430,Gp:17736,Hp:3832,Ip:147111,Jp:55759,Kp:64031,Qp:93044,Rp:93045,Sp:34388,Tp:17657,Up:17655,Vp:39579,Wp:39578,Xp:77448,Yp:8196,Zp:11357,aq:69877,bq:8197,cq:82039};function es(){var a=tb(fs),b;return(new qf(function(c,d){a.onSuccess=function(e){Pk(e)?c(new gs(e)):d(new hs("Request failed, status="+(e&&"status"in e?e.status:-1),"net.badstatus",e))};
a.onError=function(e){d(new hs("Unknown request error","net.unknown",e))};
a.onTimeout=function(e){d(new hs("Request timed out","net.timeout",e))};
b=Xk("//googleads.g.doubleclick.net/pagead/id",a)})).gb(function(c){c instanceof xf&&b.abort();
return vf(c)})}
function hs(a,b,c){ab.call(this,a+", errorCode="+b);this.errorCode=b;this.xhr=c;this.name="PromiseAjaxError"}
t(hs,ab);function gs(a){this.xhr=a}
;function is(){this.i=0;this.ja=null}
is.prototype.then=function(a,b,c){return 1===this.i&&a?(a=a.call(c,this.ja))&&"function"===typeof a.then?a:js(a):2===this.i&&b?(a=b.call(c,this.ja))&&"function"===typeof a.then?a:ks(a):this};
is.prototype.getValue=function(){return this.ja};
is.prototype.$goog_Thenable=!0;function ks(a){var b=new is;a=void 0===a?null:a;b.i=2;b.ja=void 0===a?null:a;return b}
function js(a){var b=new is;a=void 0===a?null:a;b.i=1;b.ja=void 0===a?null:a;return b}
;function ls(a,b){return{method:void 0===b?"POST":b,mode:Kk(a)?"same-origin":"cors",credentials:Kk(a)?"same-origin":"include"}}
;function ms(){return kg()||Tl&&Ul("applewebkit")&&!Ul("version")&&(!Ul("safari")||Ul("gsa/"))||Oc&&Ul("version/")?!0:L("EOM_VISITOR_DATA")?!1:!0}
;function ns(a){a:{var b=a.raw_embedded_player_response;if(!b&&(a=a.embedded_player_response))try{b=JSON.parse(a)}catch(d){b="EMBEDDED_PLAYER_MODE_UNKNOWN";break a}if(b)b:{for(var c in Oh)if(Oh[c]==b.embeddedPlayerMode){b=Oh[c];break b}b="EMBEDDED_PLAYER_MODE_UNKNOWN"}else b="EMBEDDED_PLAYER_MODE_UNKNOWN"}return"EMBEDDED_PLAYER_MODE_PFL"===b}
;function os(a){ab.call(this,a.message||a.description||a.name);this.isMissing=a instanceof ps;this.isTimeout=a instanceof hs&&"net.timeout"==a.errorCode;this.isCanceled=a instanceof xf}
t(os,ab);os.prototype.name="BiscottiError";function ps(){ab.call(this,"Biscotti ID is missing from server")}
t(ps,ab);ps.prototype.name="BiscottiMissingError";var fs={format:"RAW",method:"GET",timeout:5E3,withCredentials:!0},qs=null;
function zk(){if(M("disable_biscotti_fetch_entirely_for_all_web_clients"))return vf(Error("Biscotti id fetching has been disabled entirely."));if(!ms())return vf(Error("User has not consented - not fetching biscotti id."));var a=L("PLAYER_VARS",{});if("1"==rb(a))return vf(Error("Biscotti ID is not available in private embed mode"));if(M("embeds_web_disable_ads_for_pfl")&&ns(a))return vf(Error("Biscotti id fetching has been disabled for pfl."));qs||(qs=es().then(rs).gb(function(b){return ss(2,b)}));
return qs}
function rs(a){a=a.xhr.responseText;if(0!=a.lastIndexOf(")]}'",0))throw new ps;a=JSON.parse(a.substr(4));if(1<(a.type||1))throw new ps;a=a.id;Ak(a);qs=js(a);ts(18E5,2);return a}
function ss(a,b){b=new os(b);Ak("");qs=ks(b);0<a&&ts(12E4,a-1);throw b;}
function ts(a,b){Qk(function(){es().then(rs,function(c){return ss(b,c)}).gb(cb)},a)}
function us(){try{var a=B("yt.ads.biscotti.getId_");return a?a():zk()}catch(b){return vf(b)}}
;function vs(a){if("1"!=rb(L("PLAYER_VARS",{}))){a&&yk();try{us().then(function(){},function(){}),Qk(vs,18E5)}catch(b){wk(b)}}}
;function ws(){this.ld=!0}
function xs(a){var b={},c=mg([]);c&&(b.Authorization=c,c=a=null==a?void 0:a.sessionIndex,void 0===c&&(c=Number(L("SESSION_INDEX",0)),c=isNaN(c)?0:c),M("voice_search_auth_header_removal")||(b["X-Goog-AuthUser"]=c),"INNERTUBE_HOST_OVERRIDE"in mk||(b["X-Origin"]=window.location.origin),void 0===a&&"DELEGATED_SESSION_ID"in mk&&(b["X-Goog-PageId"]=L("DELEGATED_SESSION_ID")));return b}
;var ys=Symbol("injectionDeps");function zs(a){this.name=a}
zs.prototype.toString=function(){return"InjectionToken("+this.name+")"};
function As(){this.key=Bs}
function Cs(){this.providers=new Map;this.i=new Map}
Cs.prototype.resolve=function(a){return a instanceof As?Ds(this,a.key,[],!0):Ds(this,a,[])};
function Ds(a,b,c,d){d=void 0===d?!1:d;if(-1<c.indexOf(b))throw Error("Deps cycle for: "+b);if(a.i.has(b))return a.i.get(b);if(!a.providers.has(b)){if(d)return;throw Error("No provider for: "+b);}d=a.providers.get(b);c.push(b);if(d.td)var e=d.td;else if(d.sd)e=d[ys]?Es(a,d[ys],c):[],e=d.sd.apply(d,ia(e));else if(d.lc){e=d.lc;var f=e[ys]?Es(a,e[ys],c):[];e=new (Function.prototype.bind.apply(e,[null].concat(ia(f))))}else throw Error("Could not resolve providers for: "+b);c.pop();d.Aq||a.i.set(b,e);
return e}
function Es(a,b,c){return b?b.map(function(d){return d instanceof As?Ds(a,d.key,c,!0):Ds(a,d,c)}):[]}
;var Fs;var Gs={identityType:"UNAUTHENTICATED_IDENTITY_TYPE_UNKNOWN"};var Hs=new Map([["dark","USER_INTERFACE_THEME_DARK"],["light","USER_INTERFACE_THEME_LIGHT"]]);function Is(){var a=void 0===a?window.location.href:a;if(M("kevlar_disable_theme_param"))return null;kc(lc(5,a));try{var b=Ik(a).theme;return Hs.get(b)||null}catch(c){}return null}
;function Js(){this.i={};if(this.j=hl()){var a=ig.get("CONSISTENCY",void 0);a&&Ks(this,{encryptedTokenJarContents:a})}}
Js.prototype.handleResponse=function(a,b){if(!b)throw Error("request needs to be passed into ConsistencyService");var c,d;b=(null==(c=b.ga.context)?void 0:null==(d=c.request)?void 0:d.consistencyTokenJars)||[];var e;if(a=null==(e=a.responseContext)?void 0:e.consistencyTokenJar){e=p(b);for(c=e.next();!c.done;c=e.next())delete this.i[c.value.encryptedTokenJarContents];Ks(this,a)}};
function Ks(a,b){if(b.encryptedTokenJarContents&&(a.i[b.encryptedTokenJarContents]=b,"string"===typeof b.expirationSeconds)){var c=Number(b.expirationSeconds);setTimeout(function(){delete a.i[b.encryptedTokenJarContents]},1E3*c);
a.j&&gl("CONSISTENCY",b.encryptedTokenJarContents,c,void 0,!0)}}
;var Ls=window.location.hostname.split(".").slice(-2).join(".");function Ms(){var a=L("LOCATION_PLAYABILITY_TOKEN");"TVHTML5"===L("INNERTUBE_CLIENT_NAME")&&(this.i=Ns(this))&&(a=this.i.get("yt-location-playability-token"));a&&(this.locationPlayabilityToken=a,this.j=void 0)}
var Os;Ms.getInstance=function(){Os=B("yt.clientLocationService.instance");Os||(Os=new Ms,z("yt.clientLocationService.instance",Os));return Os};
Ms.prototype.setLocationOnInnerTubeContext=function(a){a.client||(a.client={});this.j?(a.client.locationInfo||(a.client.locationInfo={}),a.client.locationInfo.latitudeE7=Math.floor(1E7*this.j.coords.latitude),a.client.locationInfo.longitudeE7=Math.floor(1E7*this.j.coords.longitude),a.client.locationInfo.horizontalAccuracyMeters=Math.round(this.j.coords.accuracy),a.client.locationInfo.forceLocationPlayabilityTokenRefresh=!0):this.locationPlayabilityToken&&(a.client.locationPlayabilityToken=this.locationPlayabilityToken)};
Ms.prototype.handleResponse=function(a){var b;a=null==(b=a.responseContext)?void 0:b.locationPlayabilityToken;void 0!==a&&(this.locationPlayabilityToken=a,this.j=void 0,"TVHTML5"===L("INNERTUBE_CLIENT_NAME")?(this.i=Ns(this))&&this.i.set("yt-location-playability-token",a,15552E3):gl("YT_CL",JSON.stringify({loctok:a}),15552E3,Ls,!0))};
function Ns(a){return void 0===a.i?new Fl("yt-client-location"):a.i}
Ms.prototype.getCurrentPositionFromGeolocation=function(){var a=this;if(!(navigator&&navigator.geolocation&&navigator.geolocation.getCurrentPosition)||!M("web_enable_browser_geolocation_api")&&!M("enable_handoff_location_2fa_on_mweb"))return Promise.reject(Error("Geolocation unsupported"));var b=!1,c=1E4;M("enable_handoff_location_2fa_on_mweb")&&(b=!0,c=15E3);return new Promise(function(d,e){navigator.geolocation.getCurrentPosition(function(f){a.j=f;d(f)},function(f){e(f)},{enableHighAccuracy:b,
maximumAge:0,timeout:c})})};
Ms.prototype.createUnpluggedLocationInfo=function(a){var b={};a=a.coords;if(null==a?0:a.latitude)b.latitudeE7=Math.floor(1E7*a.latitude);if(null==a?0:a.longitude)b.longitudeE7=Math.floor(1E7*a.longitude);if(null==a?0:a.accuracy)b.locationRadiusMeters=Math.round(a.accuracy);return b};function Ps(a,b){var c;if((null==(c=a.signalServiceEndpoint)?0:c.signal)&&b.La&&(c=b.La[a.signalServiceEndpoint.signal]))return c();var d;if((null==(d=a.continuationCommand)?0:d.request)&&b.zc&&(d=b.zc[a.continuationCommand.request]))return d();for(var e in a)if(b.Kb[e]&&(a=b.Kb[e]))return a()}
;function Qs(a){return function(){return new a}}
;var Rs={},Ss=(Rs.WEB_UNPLUGGED="^unplugged/",Rs.WEB_UNPLUGGED_ONBOARDING="^unplugged/",Rs.WEB_UNPLUGGED_OPS="^unplugged/",Rs.WEB_UNPLUGGED_PUBLIC="^unplugged/",Rs.WEB_CREATOR="^creator/",Rs.WEB_KIDS="^kids/",Rs.WEB_EXPERIMENTS="^experiments/",Rs.WEB_MUSIC="^music/",Rs.WEB_REMIX="^music/",Rs.WEB_MUSIC_EMBEDDED_PLAYER="^music/",Rs.WEB_MUSIC_EMBEDDED_PLAYER="^main_app/|^sfv/",Rs);
function Ts(a){var b=void 0===b?"UNKNOWN_INTERFACE":b;if(1===a.length)return a[0];var c=Ss[b];if(c){var d=new RegExp(c),e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,d.exec(c))return c}var f=[];Object.entries(Ss).forEach(function(g){var h=p(g);g=h.next().value;h=h.next().value;b!==g&&f.push(h)});
d=new RegExp(f.join("|"));a.sort(function(g,h){return g.length-h.length});
e=p(a);for(c=e.next();!c.done;c=e.next())if(c=c.value,!d.exec(c))return c;return a[0]}
;function Us(){}
Us.prototype.o=function(a,b,c){b=void 0===b?{}:b;c=void 0===c?Gs:c;var d=a.clickTrackingParams,e=this.m,f=!1;f=void 0===f?!1:f;e=void 0===e?!1:e;var g=L("INNERTUBE_CONTEXT");if(g){g=ub(g);M("web_no_tracking_params_in_shell_killswitch")||delete g.clickTracking;g.client||(g.client={});var h=g.client;"MWEB"===h.clientName&&(h.clientFormFactor=L("IS_TABLET")?"LARGE_FORM_FACTOR":"SMALL_FORM_FACTOR");h.screenWidthPoints=window.innerWidth;h.screenHeightPoints=window.innerHeight;h.screenPixelDensity=Math.round(window.devicePixelRatio||
1);h.screenDensityFloat=window.devicePixelRatio||1;h.utcOffsetMinutes=-Math.floor((new Date).getTimezoneOffset());var k=void 0===k?!1:k;jl.getInstance();var m="USER_INTERFACE_THEME_LIGHT";ml(165)?m="USER_INTERFACE_THEME_DARK":ml(174)?m="USER_INTERFACE_THEME_LIGHT":!M("kevlar_legacy_browsers")&&window.matchMedia&&window.matchMedia("(prefers-color-scheme)").matches&&window.matchMedia("(prefers-color-scheme: dark)").matches&&(m="USER_INTERFACE_THEME_DARK");k=k?m:Is()||m;h.userInterfaceTheme=k;if(!f){if(k=
tl())h.connectionType=k;M("web_log_effective_connection_type")&&(k=ul())&&(g.client.effectiveConnectionType=k)}var q;if(M("web_log_memory_total_kbytes")&&(null==(q=y.navigator)?0:q.deviceMemory)){var r;q=null==(r=y.navigator)?void 0:r.deviceMemory;g.client.memoryTotalKbytes=""+1E6*q}r=Ik(y.location.href);!M("web_populate_internal_geo_killswitch")&&r.internalcountrycode&&(h.internalGeo=r.internalcountrycode);"MWEB"===h.clientName||"WEB"===h.clientName?(h.mainAppWebInfo={graftUrl:y.location.href},M("kevlar_woffle")&&
el.i&&(r=el.i,h.mainAppWebInfo.pwaInstallabilityStatus=!r.i&&r.j?"PWA_INSTALLABILITY_STATUS_CAN_BE_INSTALLED":"PWA_INSTALLABILITY_STATUS_UNKNOWN"),h.mainAppWebInfo.webDisplayMode=fl(),h.mainAppWebInfo.isWebNativeShareAvailable=navigator&&void 0!==navigator.share):"TVHTML5"===h.clientName&&(!M("web_lr_app_quality_killswitch")&&(r=L("LIVING_ROOM_APP_QUALITY"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||{},{appQuality:r})),r=L("LIVING_ROOM_CERTIFICATION_SCOPE"))&&(h.tvAppInfo=Object.assign(h.tvAppInfo||
{},{certificationScope:r}));if(!M("web_populate_time_zone_itc_killswitch")){b:{if("undefined"!==typeof Intl)try{var x=(new Intl.DateTimeFormat).resolvedOptions().timeZone;break b}catch(X){}x=void 0}x&&(h.timeZone=x)}(x=rk())?h.experimentsToken=x:delete h.experimentsToken;x=sk();Js.i||(Js.i=new Js);h=Js.i.i;r=[];q=0;for(var u in h)r[q++]=h[u];g.request=Object.assign({},g.request,{internalExperimentFlags:x,consistencyTokenJars:r});!M("web_prequest_context_killswitch")&&(u=L("INNERTUBE_CONTEXT_PREQUEST_CONTEXT"))&&
(g.request.externalPrequestContext=u);x=jl.getInstance();u=ml(58);x=x.get("gsml","");g.user=Object.assign({},g.user);u&&(g.user.enableSafetyMode=u);x&&(g.user.lockedSafetyMode=!0);M("warm_op_csn_cleanup")?e&&(f=Yr())&&(g.clientScreenNonce=f):!f&&(f=Yr())&&(g.clientScreenNonce=f);d&&(g.clickTracking={clickTrackingParams:d});if(d=B("yt.mdx.remote.remoteClient_"))g.remoteClient=d;M("web_enable_client_location_service")&&Ms.getInstance().setLocationOnInnerTubeContext(g);try{var A=Lk(),D=A.bid;delete A.bid;
g.adSignalsInfo={params:[],bid:D};var F=p(Object.entries(A));for(var N=F.next();!N.done;N=F.next()){var O=p(N.value),Q=O.next().value,ea=O.next().value;A=Q;D=ea;d=void 0;null==(d=g.adSignalsInfo.params)||d.push({key:A,value:""+D})}}catch(X){Fr(X)}F=g}else Fr(Error("Error: No InnerTubeContext shell provided in ytconfig.")),F={};F={context:F};if(N=this.i(a)){this.j(F,N,b);var ba;b="/youtubei/v1/"+Ts(this.l());var la;(N=null==(ba=a.commandMetadata)?void 0:null==(la=ba.webCommandMetadata)?void 0:la.apiUrl)&&
(b=N);ba=b;(la=L("INNERTUBE_HOST_OVERRIDE"))&&(ba=String(la)+String(nc(ba)));la={};la.key=L("INNERTUBE_API_KEY");M("json_condensed_response")&&(la.prettyPrint="false");ba=Jk(ba,la||{},!1);a=M("kevlar_response_command_processor_page")?Object.assign({},{command:a},void 0):Object.assign({},void 0);a={input:ba,Ba:ls(ba),ga:F,config:a};a.config.Ra?a.config.Ra.identity=c:a.config.Ra={identity:c};return a}Fr(new R("Error: Failed to create Request from Command.",a))};
fa.Object.defineProperties(Us.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!1}}});function Vs(){}
t(Vs,Us);Vs.prototype.o=function(){return{input:"/getDatasyncIdsEndpoint",Ba:ls("/getDatasyncIdsEndpoint","GET"),ga:{}}};
Vs.prototype.l=function(){return[]};
Vs.prototype.i=function(){};
Vs.prototype.j=function(){};var Ws={},Xs=(Ws.GET_DATASYNC_IDS=Qs(Vs),Ws);function Ys(a){var b=Ka.apply(1,arguments);if(!Zs(a)||b.some(function(d){return!Zs(d)}))throw Error("Only objects may be merged.");
b=p(b);for(var c=b.next();!c.done;c=b.next())$s(a,c.value);return a}
function $s(a,b){for(var c in b)if(Zs(b[c])){if(c in a&&!Zs(a[c]))throw Error("Cannot merge an object into a non-object.");c in a||(a[c]={});$s(a[c],b[c])}else if(at(b[c])){if(c in a&&!at(a[c]))throw Error("Cannot merge an array into a non-array.");c in a||(a[c]=[]);bt(a[c],b[c])}else a[c]=b[c];return a}
function bt(a,b){b=p(b);for(var c=b.next();!c.done;c=b.next())c=c.value,Zs(c)?a.push($s({},c)):at(c)?a.push(bt([],c)):a.push(c);return a}
function Zs(a){return"object"===typeof a&&!Array.isArray(a)}
function at(a){return"object"===typeof a&&Array.isArray(a)}
;function ct(a,b){Kn.call(this,1,arguments);this.timer=b}
t(ct,Kn);var dt=new Ln("aft-recorded",ct);var et=window;function ft(){this.timing={};this.clearResourceTimings=function(){};
this.webkitClearResourceTimings=function(){};
this.mozClearResourceTimings=function(){};
this.msClearResourceTimings=function(){};
this.oClearResourceTimings=function(){}}
var S=et.performance||et.mozPerformance||et.msPerformance||et.webkitPerformance||new ft;var gt=!1,ht={'script[name="scheduler/scheduler"]':"sj",'script[name="player/base"]':"pj",'link[rel="stylesheet"][name="www-player"]':"pc",'link[rel="stylesheet"][name="player/www-player"]':"pc",'script[name="desktop_polymer/desktop_polymer"]':"dpj",'link[rel="import"][name="desktop_polymer"]':"dph",'script[name="mobile-c3"]':"mcj",'link[rel="stylesheet"][name="mobile-c3"]':"mcc",'script[name="player-plasma-ias-phone/base"]':"mcppj",'script[name="player-plasma-ias-tablet/base"]':"mcptj",'link[rel="stylesheet"][name="mobile-polymer-player-ias"]':"mcpc",
'link[rel="stylesheet"][name="mobile-polymer-player-svg-ias"]':"mcpsc",'script[name="mobile_blazer_core_mod"]':"mbcj",'link[rel="stylesheet"][name="mobile_blazer_css"]':"mbc",'script[name="mobile_blazer_logged_in_users_mod"]':"mbliuj",'script[name="mobile_blazer_logged_out_users_mod"]':"mblouj",'script[name="mobile_blazer_noncore_mod"]':"mbnj","#player_css":"mbpc",'script[name="mobile_blazer_desktopplayer_mod"]':"mbpj",'link[rel="stylesheet"][name="mobile_blazer_tablet_css"]':"mbtc",'script[name="mobile_blazer_watch_mod"]':"mbwj"};
Xa(S.clearResourceTimings||S.webkitClearResourceTimings||S.mozClearResourceTimings||S.msClearResourceTimings||S.oClearResourceTimings||cb,S);function jt(a){var b=kt(a);if(b.aft)return b.aft;a=L((a||"")+"TIMING_AFT_KEYS",["ol"]);for(var c=a.length,d=0;d<c;d++){var e=b[a[d]];if(e)return e}return NaN}
function lt(){var a;if(M("csi_use_performance_navigation_timing")||M("csi_use_performance_navigation_timing_tvhtml5")){var b,c,d,e=null==S?void 0:null==(a=S.getEntriesByType)?void 0:null==(b=a.call(S,"navigation"))?void 0:null==(c=b[0])?void 0:null==(d=c.toJSON)?void 0:d.call(c);e?(e.requestStart=mt(e.requestStart),e.responseEnd=mt(e.responseEnd),e.redirectStart=mt(e.redirectStart),e.redirectEnd=mt(e.redirectEnd),e.domainLookupEnd=mt(e.domainLookupEnd),e.connectStart=mt(e.connectStart),e.connectEnd=
mt(e.connectEnd),e.responseStart=mt(e.responseStart),e.secureConnectionStart=mt(e.secureConnectionStart),e.domainLookupStart=mt(e.domainLookupStart),e.isPerformanceNavigationTiming=!0,a=e):a=S.timing}else a=S.timing;return a}
function nt(){return(M("csi_use_time_origin")||M("csi_use_time_origin_tvhtml5"))&&S.timeOrigin?Math.floor(S.timeOrigin):S.timing.navigationStart}
function mt(a){return Math.round(nt()+a)}
function ot(a){var b;(b=B("ytcsi."+(a||"")+"data_"))||(b={tick:{},info:{}},z("ytcsi."+(a||"")+"data_",b));return b}
function pt(a){a=ot(a);a.info||(a.info={});return a.info}
function kt(a){a=ot(a);a.tick||(a.tick={});return a.tick}
function qt(a){a=ot(a);if(a.gel){var b=a.gel;b.gelInfos||(b.gelInfos={});b.gelTicks||(b.gelTicks={})}else a.gel={gelTicks:{},gelInfos:{}};return a.gel}
function rt(a){a=qt(a);a.gelInfos||(a.gelInfos={});return a.gelInfos}
function st(a){var b=ot(a).nonce;b||(b=Nr(),ot(a).nonce=b);return b}
function tt(a){var b=kt(a||""),c=jt(a);c&&!gt&&(Qn(dt,new ct(Math.round(c-b._start),a)),gt=!0)}
function ut(a,b){for(var c=p(Object.keys(b)),d=c.next();!d.done;d=c.next())if(d=d.value,!Object.keys(a).includes(d)||"object"===typeof b[d]&&!ut(a[d],b[d]))return!1;return!0}
;function vt(){if(S.getEntriesByType){var a=S.getEntriesByType("paint");if(a=jb(a,function(b){return"first-paint"===b.name}))return mt(a.startTime)}a=S.timing;
return a.Pc?Math.max(0,a.Pc):0}
;function wt(){var a=B("ytcsi.debug");a||(a=[],z("ytcsi.debug",a),z("ytcsi.reference",{}));return a}
function xt(a){a=a||"";var b=B("ytcsi.reference");b||(wt(),b=B("ytcsi.reference"));if(b[a])return b[a];var c=wt(),d={timerName:a,info:{},tick:{},span:{},jspbInfo:[]};c.push(d);return b[a]=d}
;var T={},zt=(T.auto_search="LATENCY_ACTION_AUTO_SEARCH",T.ad_to_ad="LATENCY_ACTION_AD_TO_AD",T.ad_to_video="LATENCY_ACTION_AD_TO_VIDEO",T["analytics.explore"]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE",T.app_startup="LATENCY_ACTION_APP_STARTUP",T["artist.analytics"]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS",T["artist.events"]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS",T["artist.presskit"]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE",T["song.analytics"]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS",T.browse="LATENCY_ACTION_BROWSE",
T.cast_splash="LATENCY_ACTION_CAST_SPLASH",T.channels="LATENCY_ACTION_CHANNELS",T.creator_channel_dashboard="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD",T["channel.analytics"]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS",T["channel.comments"]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS",T["channel.content"]="LATENCY_ACTION_CREATOR_POST_LIST",T["channel.copyright"]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT",T["channel.editing"]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING",T["channel.monetization"]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION",
T["channel.music"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC",T["channel.music_storefront"]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT",T["channel.playlists"]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS",T["channel.translations"]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS",T["channel.videos"]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS",T["channel.live_streaming"]="LATENCY_ACTION_CREATOR_LIVE_STREAMING",T.chips="LATENCY_ACTION_CHIPS",T["dialog.copyright_strikes"]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES",
T["dialog.video_copyright"]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT",T["dialog.uploads"]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS",T.direct_playback="LATENCY_ACTION_DIRECT_PLAYBACK",T.embed="LATENCY_ACTION_EMBED",T.entity_key_serialization_perf="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF",T.entity_key_deserialization_perf="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF",T.explore="LATENCY_ACTION_EXPLORE",T.home="LATENCY_ACTION_HOME",T.library="LATENCY_ACTION_LIBRARY",T.live="LATENCY_ACTION_LIVE",
T.live_pagination="LATENCY_ACTION_LIVE_PAGINATION",T.onboarding="LATENCY_ACTION_ONBOARDING",T.parent_profile_settings="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS",T.parent_tools_collection="LATENCY_ACTION_PARENT_TOOLS_COLLECTION",T.parent_tools_dashboard="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD",T.player_att="LATENCY_ACTION_PLAYER_ATTESTATION",T["post.comments"]="LATENCY_ACTION_CREATOR_POST_COMMENTS",T["post.edit"]="LATENCY_ACTION_CREATOR_POST_EDIT",T.prebuffer="LATENCY_ACTION_PREBUFFER",T.prefetch=
"LATENCY_ACTION_PREFETCH",T.profile_settings="LATENCY_ACTION_KIDS_PROFILE_SETTINGS",T.profile_switcher="LATENCY_ACTION_LOGIN",T.reel_watch="LATENCY_ACTION_REEL_WATCH",T.results="LATENCY_ACTION_RESULTS",T.search_ui="LATENCY_ACTION_SEARCH_UI",T.search_suggest="LATENCY_ACTION_SUGGEST",T.search_zero_state="LATENCY_ACTION_SEARCH_ZERO_STATE",T.secret_code="LATENCY_ACTION_KIDS_SECRET_CODE",T.seek="LATENCY_ACTION_PLAYER_SEEK",T.settings="LATENCY_ACTION_SETTINGS",T.store="LATENCY_ACTION_STORE",T.tenx="LATENCY_ACTION_TENX",
T.video_to_ad="LATENCY_ACTION_VIDEO_TO_AD",T.watch="LATENCY_ACTION_WATCH",T.watch_it_again="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN",T["watch,watch7"]="LATENCY_ACTION_WATCH",T["watch,watch7_html5"]="LATENCY_ACTION_WATCH",T["watch,watch7ad"]="LATENCY_ACTION_WATCH",T["watch,watch7ad_html5"]="LATENCY_ACTION_WATCH",T.wn_comments="LATENCY_ACTION_LOAD_COMMENTS",T.ww_rqs="LATENCY_ACTION_WHO_IS_WATCHING",T["video.analytics"]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS",T["video.comments"]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS",
T["video.edit"]="LATENCY_ACTION_CREATOR_VIDEO_EDIT",T["video.editor"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR",T["video.editor_async"]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC",T["video.live_settings"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS",T["video.live_streaming"]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING",T["video.monetization"]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION",T["video.translations"]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS",T.voice_assistant="LATENCY_ACTION_VOICE_ASSISTANT",
T.cast_load_by_entity_to_watch="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH",T.networkless_performance="LATENCY_ACTION_NETWORKLESS_PERFORMANCE",T),U={},At=(U.ad_allowed="adTypesAllowed",U.yt_abt="adBreakType",U.ad_cpn="adClientPlaybackNonce",U.ad_docid="adVideoId",U.yt_ad_an="adNetworks",U.ad_at="adType",U.aida="appInstallDataAgeMs",U.browse_id="browseId",U.p="httpProtocol",U.t="transportProtocol",U.cs="commandSource",U.cpn="clientPlaybackNonce",U.ccs="creatorInfo.creatorCanaryState",U.ctop="creatorInfo.topEntityType",
U.csn="clientScreenNonce",U.docid="videoId",U.GetHome_rid="requestIds",U.GetSearch_rid="requestIds",U.GetPlayer_rid="requestIds",U.GetWatchNext_rid="requestIds",U.GetBrowse_rid="requestIds",U.GetLibrary_rid="requestIds",U.is_continuation="isContinuation",U.is_nav="isNavigation",U.b_p="kabukiInfo.browseParams",U.is_prefetch="kabukiInfo.isPrefetch",U.is_secondary_nav="kabukiInfo.isSecondaryNav",U.nav_type="kabukiInfo.navigationType",U.prev_browse_id="kabukiInfo.prevBrowseId",U.query_source="kabukiInfo.querySource",
U.voz_type="kabukiInfo.vozType",U.yt_lt="loadType",U.mver="creatorInfo.measurementVersion",U.yt_ad="isMonetized",U.nr="webInfo.navigationReason",U.nrsu="navigationRequestedSameUrl",U.pnt="performanceNavigationTiming",U.prt="playbackRequiresTap",U.plt="playerInfo.playbackType",U.pis="playerInfo.playerInitializedState",U.paused="playerInfo.isPausedOnLoad",U.yt_pt="playerType",U.fmt="playerInfo.itag",U.yt_pl="watchInfo.isPlaylist",U.yt_pre="playerInfo.preloadType",U.yt_ad_pr="prerollAllowed",U.pa="previousAction",
U.yt_red="isRedSubscriber",U.rce="mwebInfo.responseContentEncoding",U.rc="resourceInfo.resourceCache",U.scrh="screenHeight",U.scrw="screenWidth",U.st="serverTimeMs",U.ssdm="shellStartupDurationMs",U.br_trs="tvInfo.bedrockTriggerState",U.kebqat="kabukiInfo.earlyBrowseRequestInfo.abandonmentType",U.kebqa="kabukiInfo.earlyBrowseRequestInfo.adopted",U.label="tvInfo.label",U.is_mdx="tvInfo.isMdx",U.preloaded="tvInfo.isPreloaded",U.aac_type="tvInfo.authAccessCredentialType",U.upg_player_vis="playerInfo.visibilityState",
U.query="unpluggedInfo.query",U.upg_chip_ids_string="unpluggedInfo.upgChipIdsString",U.yt_vst="videoStreamType",U.vph="viewportHeight",U.vpw="viewportWidth",U.yt_vis="isVisible",U.rcl="mwebInfo.responseContentLength",U.GetSettings_rid="requestIds",U.GetTrending_rid="requestIds",U.GetMusicSearchSuggestions_rid="requestIds",U.REQUEST_ID="requestIds",U),Bt="isContinuation isNavigation kabukiInfo.earlyBrowseRequestInfo.adopted kabukiInfo.isPrefetch kabukiInfo.isSecondaryNav isMonetized navigationRequestedSameUrl performanceNavigationTiming playerInfo.isPausedOnLoad prerollAllowed isRedSubscriber tvInfo.isMdx tvInfo.isPreloaded isVisible watchInfo.isPlaylist playbackRequiresTap".split(" "),
Ct={},Dt=(Ct.ccs="CANARY_STATE_",Ct.mver="MEASUREMENT_VERSION_",Ct.pis="PLAYER_INITIALIZED_STATE_",Ct.yt_pt="LATENCY_PLAYER_",Ct.pa="LATENCY_ACTION_",Ct.ctop="TOP_ENTITY_TYPE_",Ct.yt_vst="VIDEO_STREAM_TYPE_",Ct),Et="all_vc ap aq c cbr cbrand cbrver cmodel cos cosver cplatform ctheme cver ei l_an l_mm plid srt yt_fss yt_li vpst vpni2 vpil2 icrc icrt pa GetAccountOverview_rid GetHistory_rid cmt d_vpct d_vpnfi d_vpni nsru pc pfa pfeh pftr pnc prerender psc rc start tcrt tcrc ssr vpr vps yt_abt yt_fn yt_fs yt_pft yt_pre yt_pt yt_pvis ytu_pvis yt_ref yt_sts tds".split(" ");
function Ft(a){return zt[a]||"LATENCY_ACTION_UNKNOWN"}
function Gt(a,b,c){c=qt(c);if(c.gelInfos)c.gelInfos[a]=!0;else{var d={};c.gelInfos=(d[a]=!0,d)}if(a.match("_rid")){var e=a.split("_rid")[0];a="REQUEST_ID"}if(a in At){c=At[a];0<=eb(Bt,c)&&(b=!!b);a in Dt&&"string"===typeof b&&(b=Dt[a]+b.toUpperCase());a=b;b=c.split(".");for(var f=d={},g=0;g<b.length-1;g++){var h=b[g];f[h]={};f=f[h]}f[b[b.length-1]]="requestIds"===c?[{id:a,endpoint:e}]:a;return Ys({},d)}0<=eb(Et,a)||Gr(new R("Unknown label logged with GEL CSI",a))}
;var V={LATENCY_ACTION_KIDS_PROFILE_SWITCHER:90,LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER:100,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC:46,LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR:37,LATENCY_ACTION_SPINNER_DISPLAYED:14,LATENCY_ACTION_PLAYABILITY_CHECK:10,LATENCY_ACTION_PROCESS:9,LATENCY_ACTION_APP_STARTUP:5,LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING:179,LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC:173,LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC:172,LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC:171,
LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC:170,LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC:169,LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC:168,LATENCY_ACTION_GET_OFFERS_RPC:167,LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC:166,LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC:165,LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC:164,LATENCY_ACTION_GET_OFFER_DETAILS_RPC:163,LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC:162,LATENCY_ACTION_GET_TIP_MODULE_RPC:161,LATENCY_ACTION_HANDLE_TRANSACTION_RPC:160,LATENCY_ACTION_COMPLETE_TRANSACTION_RPC:159,
LATENCY_ACTION_GET_CART_RPC:158,LATENCY_ACTION_THUMBNAIL_FETCH:156,LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK:154,LATENCY_ACTION_SHARE_VIDEO:153,LATENCY_ACTION_AD_TO_VIDEO_INT:152,LATENCY_ACTION_ABANDONED_BROWSE:151,LATENCY_ACTION_PLAYER_ROTATION:150,LATENCY_ACTION_SHOPPING_IN_APP:124,LATENCY_ACTION_PLAYER_ATTESTATION:121,LATENCY_ACTION_PLAYER_SEEK:119,LATENCY_ACTION_SUPER_STICKER_BUY_FLOW:114,LATENCY_ACTION_DOWNLOADS_DATA_ACCESS:180,LATENCY_ACTION_BLOCKS_PERFORMANCE:148,LATENCY_ACTION_ASSISTANT_QUERY:138,
LATENCY_ACTION_ASSISTANT_SETTINGS:137,LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF:129,LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF:128,LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE:127,LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION:123,LATENCY_ACTION_NETWORKLESS_PERFORMANCE:122,LATENCY_ACTION_DOWNLOADS_EXPANSION:133,LATENCY_ACTION_ENTITY_TRANSFORM:131,LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER:96,LATENCY_ACTION_EMBEDS_SET_VIDEO:95,LATENCY_ACTION_SETTINGS:93,LATENCY_ACTION_ABANDONED_STARTUP:81,LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY:80,
LATENCY_ACTION_MEDIA_BROWSER_SEARCH:79,LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE:78,LATENCY_ACTION_WHO_IS_WATCHING:77,LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH:76,LATENCY_ACTION_LITE_SWITCH_ACCOUNT:73,LATENCY_ACTION_ELEMENTS_PERFORMANCE:70,LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION:69,LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION:65,LATENCY_ACTION_OFFLINE_STORE_START:61,LATENCY_ACTION_REEL_EDITOR:58,LATENCY_ACTION_CHANNEL_SUBSCRIBE:56,LATENCY_ACTION_CHANNEL_PREVIEW:55,LATENCY_ACTION_PREFETCH:52,LATENCY_ACTION_ABANDONED_WATCH:45,
LATENCY_ACTION_LOAD_COMMENT_REPLIES:26,LATENCY_ACTION_LOAD_COMMENTS:25,LATENCY_ACTION_EDIT_COMMENT:24,LATENCY_ACTION_NEW_COMMENT:23,LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING:19,LATENCY_ACTION_EMBED:18,LATENCY_ACTION_MDX_LAUNCH:15,LATENCY_ACTION_RESOLVE_URL:13,LATENCY_ACTION_CAST_SPLASH:149,LATENCY_ACTION_MDX_STREAM_TRANSFER:178,LATENCY_ACTION_MDX_CAST:120,LATENCY_ACTION_MDX_COMMAND:12,LATENCY_ACTION_REEL_SELECT_SEGMENT:136,LATENCY_ACTION_ACCELERATED_EFFECTS:145,LATENCY_ACTION_UPLOAD_AUDIO_MIXER:147,
LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING:157,LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING:146,LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK:130,LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD:125,LATENCY_ACTION_SHORTS_VIDEO_INGESTION:155,LATENCY_ACTION_SHORTS_GALLERY:107,LATENCY_ACTION_SHORTS_TRIM:105,LATENCY_ACTION_SHORTS_EDIT:104,LATENCY_ACTION_SHORTS_CAMERA:103,LATENCY_ACTION_PARENT_TOOLS_DASHBOARD:102,LATENCY_ACTION_PARENT_TOOLS_COLLECTION:101,LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS:116,LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS:115,
LATENCY_ACTION_MUSIC_ALBUM_DETAIL:72,LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL:71,LATENCY_ACTION_STORE:175,LATENCY_ACTION_CHIPS:68,LATENCY_ACTION_SEARCH_ZERO_STATE:67,LATENCY_ACTION_LIVE_PAGINATION:117,LATENCY_ACTION_LIVE:20,LATENCY_ACTION_PREBUFFER:40,LATENCY_ACTION_TENX:39,LATENCY_ACTION_KIDS_PROFILE_SETTINGS:94,LATENCY_ACTION_KIDS_WATCH_IT_AGAIN:92,LATENCY_ACTION_KIDS_SECRET_CODE:91,LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS:89,LATENCY_ACTION_KIDS_ONBOARDING:88,LATENCY_ACTION_KIDS_VOICE_SEARCH:82,
LATENCY_ACTION_KIDS_CURATED_COLLECTION:62,LATENCY_ACTION_KIDS_LIBRARY:53,LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS:38,LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION:74,LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING:141,LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS:142,LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC:51,LATENCY_ACTION_CREATOR_VIDEO_EDITOR:50,LATENCY_ACTION_CREATOR_VIDEO_EDIT:36,LATENCY_ACTION_CREATOR_VIDEO_COMMENTS:34,LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS:33,LATENCY_ACTION_CREATOR_SONG_ANALYTICS:176,
LATENCY_ACTION_CREATOR_POST_LIST:112,LATENCY_ACTION_CREATOR_POST_EDIT:110,LATENCY_ACTION_CREATOR_POST_COMMENTS:111,LATENCY_ACTION_CREATOR_LIVE_STREAMING:108,LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT:174,LATENCY_ACTION_CREATOR_DIALOG_UPLOADS:86,LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES:87,LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS:32,LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS:48,LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS:139,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT:177,LATENCY_ACTION_CREATOR_CHANNEL_MUSIC:99,
LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION:43,LATENCY_ACTION_CREATOR_CHANNEL_EDITING:113,LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD:49,LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT:44,LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS:66,LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS:31,LATENCY_ACTION_CREATOR_ARTIST_PROFILE:85,LATENCY_ACTION_CREATOR_ARTIST_CONCERTS:84,LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS:83,LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE:140,LATENCY_ACTION_STORYBOARD_THUMBNAILS:118,LATENCY_ACTION_SEARCH_THUMBNAILS:59,
LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD:54,LATENCY_ACTION_VOICE_ASSISTANT:47,LATENCY_ACTION_SEARCH_UI:35,LATENCY_ACTION_SUGGEST:30,LATENCY_ACTION_AUTO_SEARCH:126,LATENCY_ACTION_DOWNLOADS:98,LATENCY_ACTION_EXPLORE:75,LATENCY_ACTION_VIDEO_LIST:63,LATENCY_ACTION_HOME_RESUME:60,LATENCY_ACTION_SUBSCRIPTIONS_LIST:57,LATENCY_ACTION_THUMBNAIL_LOAD:42,LATENCY_ACTION_FIRST_THUMBNAIL_LOAD:29,LATENCY_ACTION_SUBSCRIPTIONS_FEED:109,LATENCY_ACTION_SUBSCRIPTIONS:28,LATENCY_ACTION_TRENDING:27,LATENCY_ACTION_LIBRARY:21,
LATENCY_ACTION_VIDEO_THUMBNAIL:8,LATENCY_ACTION_SHOW_MORE:7,LATENCY_ACTION_VIDEO_PREVIEW:6,LATENCY_ACTION_PREBUFFER_VIDEO:144,LATENCY_ACTION_PREFETCH_VIDEO:143,LATENCY_ACTION_DIRECT_PLAYBACK:132,LATENCY_ACTION_REEL_WATCH:41,LATENCY_ACTION_AD_TO_AD:22,LATENCY_ACTION_VIDEO_TO_AD:17,LATENCY_ACTION_AD_TO_VIDEO:16,LATENCY_ACTION_ONBOARDING:135,LATENCY_ACTION_LOGIN:97,LATENCY_ACTION_BROWSE:11,LATENCY_ACTION_CHANNELS:4,LATENCY_ACTION_WATCH:3,LATENCY_ACTION_RESULTS:2,LATENCY_ACTION_HOME:1,LATENCY_ACTION_STARTUP:106,
LATENCY_ACTION_UNKNOWN:0};V[V.LATENCY_ACTION_KIDS_PROFILE_SWITCHER]="LATENCY_ACTION_KIDS_PROFILE_SWITCHER";V[V.LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER]="LATENCY_ACTION_OFFLINE_THUMBNAIL_TRANSFER";V[V.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR_ASYNC";V[V.LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_VIDEO_EDITOR";V[V.LATENCY_ACTION_SPINNER_DISPLAYED]="LATENCY_ACTION_SPINNER_DISPLAYED";
V[V.LATENCY_ACTION_PLAYABILITY_CHECK]="LATENCY_ACTION_PLAYABILITY_CHECK";V[V.LATENCY_ACTION_PROCESS]="LATENCY_ACTION_PROCESS";V[V.LATENCY_ACTION_APP_STARTUP]="LATENCY_ACTION_APP_STARTUP";V[V.LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION_TRANSCODING";V[V.LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC]="LATENCY_ACTION_LOG_PAYMENT_SERVER_ANALYTICS_RPC";V[V.LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC]="LATENCY_ACTION_GET_PAYMENT_INSTRUMENTS_PARAMS_RPC";
V[V.LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC]="LATENCY_ACTION_GET_FIX_INSTRUMENT_PARAMS_RPC";V[V.LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC]="LATENCY_ACTION_RESUME_SUBSCRIPTION_RPC";V[V.LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC]="LATENCY_ACTION_PAUSE_SUBSCRIPTION_RPC";V[V.LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC]="LATENCY_ACTION_GET_OFFLINE_UPSELL_RPC";V[V.LATENCY_ACTION_GET_OFFERS_RPC]="LATENCY_ACTION_GET_OFFERS_RPC";V[V.LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_YT_FLOW_RPC";
V[V.LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC]="LATENCY_ACTION_GET_CANCELLATION_FLOW_RPC";V[V.LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC]="LATENCY_ACTION_UPDATE_CROSS_DEVICE_OFFLINE_STATE_RPC";V[V.LATENCY_ACTION_GET_OFFER_DETAILS_RPC]="LATENCY_ACTION_GET_OFFER_DETAILS_RPC";V[V.LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC]="LATENCY_ACTION_CANCEL_RECURRENCE_TRANSACTION_RPC";V[V.LATENCY_ACTION_GET_TIP_MODULE_RPC]="LATENCY_ACTION_GET_TIP_MODULE_RPC";
V[V.LATENCY_ACTION_HANDLE_TRANSACTION_RPC]="LATENCY_ACTION_HANDLE_TRANSACTION_RPC";V[V.LATENCY_ACTION_COMPLETE_TRANSACTION_RPC]="LATENCY_ACTION_COMPLETE_TRANSACTION_RPC";V[V.LATENCY_ACTION_GET_CART_RPC]="LATENCY_ACTION_GET_CART_RPC";V[V.LATENCY_ACTION_THUMBNAIL_FETCH]="LATENCY_ACTION_THUMBNAIL_FETCH";V[V.LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK]="LATENCY_ACTION_ABANDONED_DIRECT_PLAYBACK";V[V.LATENCY_ACTION_SHARE_VIDEO]="LATENCY_ACTION_SHARE_VIDEO";V[V.LATENCY_ACTION_AD_TO_VIDEO_INT]="LATENCY_ACTION_AD_TO_VIDEO_INT";
V[V.LATENCY_ACTION_ABANDONED_BROWSE]="LATENCY_ACTION_ABANDONED_BROWSE";V[V.LATENCY_ACTION_PLAYER_ROTATION]="LATENCY_ACTION_PLAYER_ROTATION";V[V.LATENCY_ACTION_SHOPPING_IN_APP]="LATENCY_ACTION_SHOPPING_IN_APP";V[V.LATENCY_ACTION_PLAYER_ATTESTATION]="LATENCY_ACTION_PLAYER_ATTESTATION";V[V.LATENCY_ACTION_PLAYER_SEEK]="LATENCY_ACTION_PLAYER_SEEK";V[V.LATENCY_ACTION_SUPER_STICKER_BUY_FLOW]="LATENCY_ACTION_SUPER_STICKER_BUY_FLOW";V[V.LATENCY_ACTION_DOWNLOADS_DATA_ACCESS]="LATENCY_ACTION_DOWNLOADS_DATA_ACCESS";
V[V.LATENCY_ACTION_BLOCKS_PERFORMANCE]="LATENCY_ACTION_BLOCKS_PERFORMANCE";V[V.LATENCY_ACTION_ASSISTANT_QUERY]="LATENCY_ACTION_ASSISTANT_QUERY";V[V.LATENCY_ACTION_ASSISTANT_SETTINGS]="LATENCY_ACTION_ASSISTANT_SETTINGS";V[V.LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_DESERIALIZATION_PERF";V[V.LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF]="LATENCY_ACTION_ENTITY_KEY_SERIALIZATION_PERF";V[V.LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE]="LATENCY_ACTION_PROOF_OF_ORIGIN_TOKEN_CREATE";
V[V.LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION]="LATENCY_ACTION_EMBEDS_SDK_INITIALIZATION";V[V.LATENCY_ACTION_NETWORKLESS_PERFORMANCE]="LATENCY_ACTION_NETWORKLESS_PERFORMANCE";V[V.LATENCY_ACTION_DOWNLOADS_EXPANSION]="LATENCY_ACTION_DOWNLOADS_EXPANSION";V[V.LATENCY_ACTION_ENTITY_TRANSFORM]="LATENCY_ACTION_ENTITY_TRANSFORM";V[V.LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER]="LATENCY_ACTION_DOWNLOADS_COMPATIBILITY_LAYER";V[V.LATENCY_ACTION_EMBEDS_SET_VIDEO]="LATENCY_ACTION_EMBEDS_SET_VIDEO";
V[V.LATENCY_ACTION_SETTINGS]="LATENCY_ACTION_SETTINGS";V[V.LATENCY_ACTION_ABANDONED_STARTUP]="LATENCY_ACTION_ABANDONED_STARTUP";V[V.LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY]="LATENCY_ACTION_MEDIA_BROWSER_ALARM_PLAY";V[V.LATENCY_ACTION_MEDIA_BROWSER_SEARCH]="LATENCY_ACTION_MEDIA_BROWSER_SEARCH";V[V.LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE]="LATENCY_ACTION_MEDIA_BROWSER_LOAD_TREE";V[V.LATENCY_ACTION_WHO_IS_WATCHING]="LATENCY_ACTION_WHO_IS_WATCHING";V[V.LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH]="LATENCY_ACTION_CAST_LOAD_BY_ENTITY_TO_WATCH";
V[V.LATENCY_ACTION_LITE_SWITCH_ACCOUNT]="LATENCY_ACTION_LITE_SWITCH_ACCOUNT";V[V.LATENCY_ACTION_ELEMENTS_PERFORMANCE]="LATENCY_ACTION_ELEMENTS_PERFORMANCE";V[V.LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION]="LATENCY_ACTION_LOCATION_SIGNAL_COLLECTION";V[V.LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION]="LATENCY_ACTION_MODIFY_CHANNEL_NOTIFICATION";V[V.LATENCY_ACTION_OFFLINE_STORE_START]="LATENCY_ACTION_OFFLINE_STORE_START";V[V.LATENCY_ACTION_REEL_EDITOR]="LATENCY_ACTION_REEL_EDITOR";
V[V.LATENCY_ACTION_CHANNEL_SUBSCRIBE]="LATENCY_ACTION_CHANNEL_SUBSCRIBE";V[V.LATENCY_ACTION_CHANNEL_PREVIEW]="LATENCY_ACTION_CHANNEL_PREVIEW";V[V.LATENCY_ACTION_PREFETCH]="LATENCY_ACTION_PREFETCH";V[V.LATENCY_ACTION_ABANDONED_WATCH]="LATENCY_ACTION_ABANDONED_WATCH";V[V.LATENCY_ACTION_LOAD_COMMENT_REPLIES]="LATENCY_ACTION_LOAD_COMMENT_REPLIES";V[V.LATENCY_ACTION_LOAD_COMMENTS]="LATENCY_ACTION_LOAD_COMMENTS";V[V.LATENCY_ACTION_EDIT_COMMENT]="LATENCY_ACTION_EDIT_COMMENT";
V[V.LATENCY_ACTION_NEW_COMMENT]="LATENCY_ACTION_NEW_COMMENT";V[V.LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING]="LATENCY_ACTION_OFFLINE_SHARING_RECEIVER_PAIRING";V[V.LATENCY_ACTION_EMBED]="LATENCY_ACTION_EMBED";V[V.LATENCY_ACTION_MDX_LAUNCH]="LATENCY_ACTION_MDX_LAUNCH";V[V.LATENCY_ACTION_RESOLVE_URL]="LATENCY_ACTION_RESOLVE_URL";V[V.LATENCY_ACTION_CAST_SPLASH]="LATENCY_ACTION_CAST_SPLASH";V[V.LATENCY_ACTION_MDX_STREAM_TRANSFER]="LATENCY_ACTION_MDX_STREAM_TRANSFER";V[V.LATENCY_ACTION_MDX_CAST]="LATENCY_ACTION_MDX_CAST";
V[V.LATENCY_ACTION_MDX_COMMAND]="LATENCY_ACTION_MDX_COMMAND";V[V.LATENCY_ACTION_REEL_SELECT_SEGMENT]="LATENCY_ACTION_REEL_SELECT_SEGMENT";V[V.LATENCY_ACTION_ACCELERATED_EFFECTS]="LATENCY_ACTION_ACCELERATED_EFFECTS";V[V.LATENCY_ACTION_UPLOAD_AUDIO_MIXER]="LATENCY_ACTION_UPLOAD_AUDIO_MIXER";V[V.LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING]="LATENCY_ACTION_SHORTS_CLIENT_SIDE_RENDERING";V[V.LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING]="LATENCY_ACTION_SHORTS_SEG_IMP_TRANSCODING";
V[V.LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK]="LATENCY_ACTION_SHORTS_AUDIO_PICKER_PLAYBACK";V[V.LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD]="LATENCY_ACTION_SHORTS_WAVEFORM_DOWNLOAD";V[V.LATENCY_ACTION_SHORTS_VIDEO_INGESTION]="LATENCY_ACTION_SHORTS_VIDEO_INGESTION";V[V.LATENCY_ACTION_SHORTS_GALLERY]="LATENCY_ACTION_SHORTS_GALLERY";V[V.LATENCY_ACTION_SHORTS_TRIM]="LATENCY_ACTION_SHORTS_TRIM";V[V.LATENCY_ACTION_SHORTS_EDIT]="LATENCY_ACTION_SHORTS_EDIT";V[V.LATENCY_ACTION_SHORTS_CAMERA]="LATENCY_ACTION_SHORTS_CAMERA";
V[V.LATENCY_ACTION_PARENT_TOOLS_DASHBOARD]="LATENCY_ACTION_PARENT_TOOLS_DASHBOARD";V[V.LATENCY_ACTION_PARENT_TOOLS_COLLECTION]="LATENCY_ACTION_PARENT_TOOLS_COLLECTION";V[V.LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_RECOMMENDED_MEDIA_ITEMS";V[V.LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS]="LATENCY_ACTION_MUSIC_LOAD_MEDIA_ITEMS";V[V.LATENCY_ACTION_MUSIC_ALBUM_DETAIL]="LATENCY_ACTION_MUSIC_ALBUM_DETAIL";V[V.LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL]="LATENCY_ACTION_MUSIC_PLAYLIST_DETAIL";
V[V.LATENCY_ACTION_STORE]="LATENCY_ACTION_STORE";V[V.LATENCY_ACTION_CHIPS]="LATENCY_ACTION_CHIPS";V[V.LATENCY_ACTION_SEARCH_ZERO_STATE]="LATENCY_ACTION_SEARCH_ZERO_STATE";V[V.LATENCY_ACTION_LIVE_PAGINATION]="LATENCY_ACTION_LIVE_PAGINATION";V[V.LATENCY_ACTION_LIVE]="LATENCY_ACTION_LIVE";V[V.LATENCY_ACTION_PREBUFFER]="LATENCY_ACTION_PREBUFFER";V[V.LATENCY_ACTION_TENX]="LATENCY_ACTION_TENX";V[V.LATENCY_ACTION_KIDS_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PROFILE_SETTINGS";
V[V.LATENCY_ACTION_KIDS_WATCH_IT_AGAIN]="LATENCY_ACTION_KIDS_WATCH_IT_AGAIN";V[V.LATENCY_ACTION_KIDS_SECRET_CODE]="LATENCY_ACTION_KIDS_SECRET_CODE";V[V.LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS]="LATENCY_ACTION_KIDS_PARENT_PROFILE_SETTINGS";V[V.LATENCY_ACTION_KIDS_ONBOARDING]="LATENCY_ACTION_KIDS_ONBOARDING";V[V.LATENCY_ACTION_KIDS_VOICE_SEARCH]="LATENCY_ACTION_KIDS_VOICE_SEARCH";V[V.LATENCY_ACTION_KIDS_CURATED_COLLECTION]="LATENCY_ACTION_KIDS_CURATED_COLLECTION";
V[V.LATENCY_ACTION_KIDS_LIBRARY]="LATENCY_ACTION_KIDS_LIBRARY";V[V.LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS]="LATENCY_ACTION_CREATOR_VIDEO_TRANSLATIONS";V[V.LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION]="LATENCY_ACTION_CREATOR_VIDEO_MONETIZATION";V[V.LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_STREAMING";V[V.LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS]="LATENCY_ACTION_CREATOR_VIDEO_LIVE_SETTINGS";V[V.LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR_ASYNC";
V[V.LATENCY_ACTION_CREATOR_VIDEO_EDITOR]="LATENCY_ACTION_CREATOR_VIDEO_EDITOR";V[V.LATENCY_ACTION_CREATOR_VIDEO_EDIT]="LATENCY_ACTION_CREATOR_VIDEO_EDIT";V[V.LATENCY_ACTION_CREATOR_VIDEO_COMMENTS]="LATENCY_ACTION_CREATOR_VIDEO_COMMENTS";V[V.LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS]="LATENCY_ACTION_CREATOR_VIDEO_ANALYTICS";V[V.LATENCY_ACTION_CREATOR_SONG_ANALYTICS]="LATENCY_ACTION_CREATOR_SONG_ANALYTICS";V[V.LATENCY_ACTION_CREATOR_POST_LIST]="LATENCY_ACTION_CREATOR_POST_LIST";
V[V.LATENCY_ACTION_CREATOR_POST_EDIT]="LATENCY_ACTION_CREATOR_POST_EDIT";V[V.LATENCY_ACTION_CREATOR_POST_COMMENTS]="LATENCY_ACTION_CREATOR_POST_COMMENTS";V[V.LATENCY_ACTION_CREATOR_LIVE_STREAMING]="LATENCY_ACTION_CREATOR_LIVE_STREAMING";V[V.LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT]="LATENCY_ACTION_CREATOR_DIALOG_VIDEO_COPYRIGHT";V[V.LATENCY_ACTION_CREATOR_DIALOG_UPLOADS]="LATENCY_ACTION_CREATOR_DIALOG_UPLOADS";V[V.LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES]="LATENCY_ACTION_CREATOR_DIALOG_COPYRIGHT_STRIKES";
V[V.LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS]="LATENCY_ACTION_CREATOR_CHANNEL_VIDEOS";V[V.LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS]="LATENCY_ACTION_CREATOR_CHANNEL_TRANSLATIONS";V[V.LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS]="LATENCY_ACTION_CREATOR_CHANNEL_PLAYLISTS";V[V.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC_STOREFRONT";V[V.LATENCY_ACTION_CREATOR_CHANNEL_MUSIC]="LATENCY_ACTION_CREATOR_CHANNEL_MUSIC";V[V.LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION]="LATENCY_ACTION_CREATOR_CHANNEL_MONETIZATION";
V[V.LATENCY_ACTION_CREATOR_CHANNEL_EDITING]="LATENCY_ACTION_CREATOR_CHANNEL_EDITING";V[V.LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD]="LATENCY_ACTION_CREATOR_CHANNEL_DASHBOARD";V[V.LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT]="LATENCY_ACTION_CREATOR_CHANNEL_COPYRIGHT";V[V.LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS]="LATENCY_ACTION_CREATOR_CHANNEL_COMMENTS";V[V.LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS]="LATENCY_ACTION_CREATOR_CHANNEL_ANALYTICS";V[V.LATENCY_ACTION_CREATOR_ARTIST_PROFILE]="LATENCY_ACTION_CREATOR_ARTIST_PROFILE";
V[V.LATENCY_ACTION_CREATOR_ARTIST_CONCERTS]="LATENCY_ACTION_CREATOR_ARTIST_CONCERTS";V[V.LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS]="LATENCY_ACTION_CREATOR_ARTIST_ANALYTICS";V[V.LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE]="LATENCY_ACTION_CREATOR_ANALYTICS_EXPLORE";V[V.LATENCY_ACTION_STORYBOARD_THUMBNAILS]="LATENCY_ACTION_STORYBOARD_THUMBNAILS";V[V.LATENCY_ACTION_SEARCH_THUMBNAILS]="LATENCY_ACTION_SEARCH_THUMBNAILS";V[V.LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD]="LATENCY_ACTION_ON_DEVICE_MODEL_DOWNLOAD";
V[V.LATENCY_ACTION_VOICE_ASSISTANT]="LATENCY_ACTION_VOICE_ASSISTANT";V[V.LATENCY_ACTION_SEARCH_UI]="LATENCY_ACTION_SEARCH_UI";V[V.LATENCY_ACTION_SUGGEST]="LATENCY_ACTION_SUGGEST";V[V.LATENCY_ACTION_AUTO_SEARCH]="LATENCY_ACTION_AUTO_SEARCH";V[V.LATENCY_ACTION_DOWNLOADS]="LATENCY_ACTION_DOWNLOADS";V[V.LATENCY_ACTION_EXPLORE]="LATENCY_ACTION_EXPLORE";V[V.LATENCY_ACTION_VIDEO_LIST]="LATENCY_ACTION_VIDEO_LIST";V[V.LATENCY_ACTION_HOME_RESUME]="LATENCY_ACTION_HOME_RESUME";
V[V.LATENCY_ACTION_SUBSCRIPTIONS_LIST]="LATENCY_ACTION_SUBSCRIPTIONS_LIST";V[V.LATENCY_ACTION_THUMBNAIL_LOAD]="LATENCY_ACTION_THUMBNAIL_LOAD";V[V.LATENCY_ACTION_FIRST_THUMBNAIL_LOAD]="LATENCY_ACTION_FIRST_THUMBNAIL_LOAD";V[V.LATENCY_ACTION_SUBSCRIPTIONS_FEED]="LATENCY_ACTION_SUBSCRIPTIONS_FEED";V[V.LATENCY_ACTION_SUBSCRIPTIONS]="LATENCY_ACTION_SUBSCRIPTIONS";V[V.LATENCY_ACTION_TRENDING]="LATENCY_ACTION_TRENDING";V[V.LATENCY_ACTION_LIBRARY]="LATENCY_ACTION_LIBRARY";
V[V.LATENCY_ACTION_VIDEO_THUMBNAIL]="LATENCY_ACTION_VIDEO_THUMBNAIL";V[V.LATENCY_ACTION_SHOW_MORE]="LATENCY_ACTION_SHOW_MORE";V[V.LATENCY_ACTION_VIDEO_PREVIEW]="LATENCY_ACTION_VIDEO_PREVIEW";V[V.LATENCY_ACTION_PREBUFFER_VIDEO]="LATENCY_ACTION_PREBUFFER_VIDEO";V[V.LATENCY_ACTION_PREFETCH_VIDEO]="LATENCY_ACTION_PREFETCH_VIDEO";V[V.LATENCY_ACTION_DIRECT_PLAYBACK]="LATENCY_ACTION_DIRECT_PLAYBACK";V[V.LATENCY_ACTION_REEL_WATCH]="LATENCY_ACTION_REEL_WATCH";V[V.LATENCY_ACTION_AD_TO_AD]="LATENCY_ACTION_AD_TO_AD";
V[V.LATENCY_ACTION_VIDEO_TO_AD]="LATENCY_ACTION_VIDEO_TO_AD";V[V.LATENCY_ACTION_AD_TO_VIDEO]="LATENCY_ACTION_AD_TO_VIDEO";V[V.LATENCY_ACTION_ONBOARDING]="LATENCY_ACTION_ONBOARDING";V[V.LATENCY_ACTION_LOGIN]="LATENCY_ACTION_LOGIN";V[V.LATENCY_ACTION_BROWSE]="LATENCY_ACTION_BROWSE";V[V.LATENCY_ACTION_CHANNELS]="LATENCY_ACTION_CHANNELS";V[V.LATENCY_ACTION_WATCH]="LATENCY_ACTION_WATCH";V[V.LATENCY_ACTION_RESULTS]="LATENCY_ACTION_RESULTS";V[V.LATENCY_ACTION_HOME]="LATENCY_ACTION_HOME";
V[V.LATENCY_ACTION_STARTUP]="LATENCY_ACTION_STARTUP";V[V.LATENCY_ACTION_UNKNOWN]="LATENCY_ACTION_UNKNOWN";var Ht={LATENCY_NETWORK_MOBILE:2,LATENCY_NETWORK_WIFI:1,LATENCY_NETWORK_UNKNOWN:0};Ht[Ht.LATENCY_NETWORK_MOBILE]="LATENCY_NETWORK_MOBILE";Ht[Ht.LATENCY_NETWORK_WIFI]="LATENCY_NETWORK_WIFI";Ht[Ht.LATENCY_NETWORK_UNKNOWN]="LATENCY_NETWORK_UNKNOWN";
var W={CONN_INVALID:31,CONN_CELLULAR_5G_NSA:12,CONN_CELLULAR_5G_SA:11,CONN_WIFI_METERED:10,CONN_CELLULAR_5G:9,CONN_DISCO:8,CONN_CELLULAR_UNKNOWN:7,CONN_CELLULAR_4G:6,CONN_CELLULAR_3G:5,CONN_CELLULAR_2G:4,CONN_WIFI:3,CONN_NONE:2,CONN_UNKNOWN:1,CONN_DEFAULT:0};W[W.CONN_INVALID]="CONN_INVALID";W[W.CONN_CELLULAR_5G_NSA]="CONN_CELLULAR_5G_NSA";W[W.CONN_CELLULAR_5G_SA]="CONN_CELLULAR_5G_SA";W[W.CONN_WIFI_METERED]="CONN_WIFI_METERED";W[W.CONN_CELLULAR_5G]="CONN_CELLULAR_5G";W[W.CONN_DISCO]="CONN_DISCO";
W[W.CONN_CELLULAR_UNKNOWN]="CONN_CELLULAR_UNKNOWN";W[W.CONN_CELLULAR_4G]="CONN_CELLULAR_4G";W[W.CONN_CELLULAR_3G]="CONN_CELLULAR_3G";W[W.CONN_CELLULAR_2G]="CONN_CELLULAR_2G";W[W.CONN_WIFI]="CONN_WIFI";W[W.CONN_NONE]="CONN_NONE";W[W.CONN_UNKNOWN]="CONN_UNKNOWN";W[W.CONN_DEFAULT]="CONN_DEFAULT";
var Y={DETAILED_NETWORK_TYPE_NR_NSA:126,DETAILED_NETWORK_TYPE_NR_SA:125,DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED:124,DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT:123,DETAILED_NETWORK_TYPE_DISCONNECTED:122,DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN:121,DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN:120,DETAILED_NETWORK_TYPE_WIMAX:119,DETAILED_NETWORK_TYPE_ETHERNET:118,DETAILED_NETWORK_TYPE_BLUETOOTH:117,DETAILED_NETWORK_TYPE_WIFI:116,DETAILED_NETWORK_TYPE_LTE:115,DETAILED_NETWORK_TYPE_HSPAP:114,DETAILED_NETWORK_TYPE_EHRPD:113,
DETAILED_NETWORK_TYPE_EVDO_B:112,DETAILED_NETWORK_TYPE_UMTS:111,DETAILED_NETWORK_TYPE_IDEN:110,DETAILED_NETWORK_TYPE_HSUPA:109,DETAILED_NETWORK_TYPE_HSPA:108,DETAILED_NETWORK_TYPE_HSDPA:107,DETAILED_NETWORK_TYPE_EVDO_A:106,DETAILED_NETWORK_TYPE_EVDO_0:105,DETAILED_NETWORK_TYPE_CDMA:104,DETAILED_NETWORK_TYPE_1_X_RTT:103,DETAILED_NETWORK_TYPE_GPRS:102,DETAILED_NETWORK_TYPE_EDGE:101,DETAILED_NETWORK_TYPE_UNKNOWN:0};Y[Y.DETAILED_NETWORK_TYPE_NR_NSA]="DETAILED_NETWORK_TYPE_NR_NSA";
Y[Y.DETAILED_NETWORK_TYPE_NR_SA]="DETAILED_NETWORK_TYPE_NR_SA";Y[Y.DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED]="DETAILED_NETWORK_TYPE_INTERNAL_WIFI_IMPAIRED";Y[Y.DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT]="DETAILED_NETWORK_TYPE_APP_WIFI_HOTSPOT";Y[Y.DETAILED_NETWORK_TYPE_DISCONNECTED]="DETAILED_NETWORK_TYPE_DISCONNECTED";Y[Y.DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_NON_MOBILE_UNKNOWN";Y[Y.DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN]="DETAILED_NETWORK_TYPE_MOBILE_UNKNOWN";
Y[Y.DETAILED_NETWORK_TYPE_WIMAX]="DETAILED_NETWORK_TYPE_WIMAX";Y[Y.DETAILED_NETWORK_TYPE_ETHERNET]="DETAILED_NETWORK_TYPE_ETHERNET";Y[Y.DETAILED_NETWORK_TYPE_BLUETOOTH]="DETAILED_NETWORK_TYPE_BLUETOOTH";Y[Y.DETAILED_NETWORK_TYPE_WIFI]="DETAILED_NETWORK_TYPE_WIFI";Y[Y.DETAILED_NETWORK_TYPE_LTE]="DETAILED_NETWORK_TYPE_LTE";Y[Y.DETAILED_NETWORK_TYPE_HSPAP]="DETAILED_NETWORK_TYPE_HSPAP";Y[Y.DETAILED_NETWORK_TYPE_EHRPD]="DETAILED_NETWORK_TYPE_EHRPD";Y[Y.DETAILED_NETWORK_TYPE_EVDO_B]="DETAILED_NETWORK_TYPE_EVDO_B";
Y[Y.DETAILED_NETWORK_TYPE_UMTS]="DETAILED_NETWORK_TYPE_UMTS";Y[Y.DETAILED_NETWORK_TYPE_IDEN]="DETAILED_NETWORK_TYPE_IDEN";Y[Y.DETAILED_NETWORK_TYPE_HSUPA]="DETAILED_NETWORK_TYPE_HSUPA";Y[Y.DETAILED_NETWORK_TYPE_HSPA]="DETAILED_NETWORK_TYPE_HSPA";Y[Y.DETAILED_NETWORK_TYPE_HSDPA]="DETAILED_NETWORK_TYPE_HSDPA";Y[Y.DETAILED_NETWORK_TYPE_EVDO_A]="DETAILED_NETWORK_TYPE_EVDO_A";Y[Y.DETAILED_NETWORK_TYPE_EVDO_0]="DETAILED_NETWORK_TYPE_EVDO_0";Y[Y.DETAILED_NETWORK_TYPE_CDMA]="DETAILED_NETWORK_TYPE_CDMA";
Y[Y.DETAILED_NETWORK_TYPE_1_X_RTT]="DETAILED_NETWORK_TYPE_1_X_RTT";Y[Y.DETAILED_NETWORK_TYPE_GPRS]="DETAILED_NETWORK_TYPE_GPRS";Y[Y.DETAILED_NETWORK_TYPE_EDGE]="DETAILED_NETWORK_TYPE_EDGE";Y[Y.DETAILED_NETWORK_TYPE_UNKNOWN]="DETAILED_NETWORK_TYPE_UNKNOWN";var It={LATENCY_PLAYER_RTSP:7,LATENCY_PLAYER_HTML5_INLINE:6,LATENCY_PLAYER_HTML5_FULLSCREEN:5,LATENCY_PLAYER_HTML5:4,LATENCY_PLAYER_FRAMEWORK:3,LATENCY_PLAYER_FLASH:2,LATENCY_PLAYER_EXO:1,LATENCY_PLAYER_UNKNOWN:0};It[It.LATENCY_PLAYER_RTSP]="LATENCY_PLAYER_RTSP";
It[It.LATENCY_PLAYER_HTML5_INLINE]="LATENCY_PLAYER_HTML5_INLINE";It[It.LATENCY_PLAYER_HTML5_FULLSCREEN]="LATENCY_PLAYER_HTML5_FULLSCREEN";It[It.LATENCY_PLAYER_HTML5]="LATENCY_PLAYER_HTML5";It[It.LATENCY_PLAYER_FRAMEWORK]="LATENCY_PLAYER_FRAMEWORK";It[It.LATENCY_PLAYER_FLASH]="LATENCY_PLAYER_FLASH";It[It.LATENCY_PLAYER_EXO]="LATENCY_PLAYER_EXO";It[It.LATENCY_PLAYER_UNKNOWN]="LATENCY_PLAYER_UNKNOWN";
var Jt={LATENCY_AD_BREAK_TYPE_POSTROLL:3,LATENCY_AD_BREAK_TYPE_MIDROLL:2,LATENCY_AD_BREAK_TYPE_PREROLL:1,LATENCY_AD_BREAK_TYPE_UNKNOWN:0};Jt[Jt.LATENCY_AD_BREAK_TYPE_POSTROLL]="LATENCY_AD_BREAK_TYPE_POSTROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_MIDROLL]="LATENCY_AD_BREAK_TYPE_MIDROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_PREROLL]="LATENCY_AD_BREAK_TYPE_PREROLL";Jt[Jt.LATENCY_AD_BREAK_TYPE_UNKNOWN]="LATENCY_AD_BREAK_TYPE_UNKNOWN";var Kt={LATENCY_ACTION_ERROR_STARTUP_TIMEOUT:1,LATENCY_ACTION_ERROR_UNSPECIFIED:0};
Kt[Kt.LATENCY_ACTION_ERROR_STARTUP_TIMEOUT]="LATENCY_ACTION_ERROR_STARTUP_TIMEOUT";Kt[Kt.LATENCY_ACTION_ERROR_UNSPECIFIED]="LATENCY_ACTION_ERROR_UNSPECIFIED";var Lt={LIVE_STREAM_MODE_WINDOW:5,LIVE_STREAM_MODE_POST:4,LIVE_STREAM_MODE_LP:3,LIVE_STREAM_MODE_LIVE:2,LIVE_STREAM_MODE_DVR:1,LIVE_STREAM_MODE_UNKNOWN:0};Lt[Lt.LIVE_STREAM_MODE_WINDOW]="LIVE_STREAM_MODE_WINDOW";Lt[Lt.LIVE_STREAM_MODE_POST]="LIVE_STREAM_MODE_POST";Lt[Lt.LIVE_STREAM_MODE_LP]="LIVE_STREAM_MODE_LP";
Lt[Lt.LIVE_STREAM_MODE_LIVE]="LIVE_STREAM_MODE_LIVE";Lt[Lt.LIVE_STREAM_MODE_DVR]="LIVE_STREAM_MODE_DVR";Lt[Lt.LIVE_STREAM_MODE_UNKNOWN]="LIVE_STREAM_MODE_UNKNOWN";var Mt={VIDEO_STREAM_TYPE_VOD:3,VIDEO_STREAM_TYPE_DVR:2,VIDEO_STREAM_TYPE_LIVE:1,VIDEO_STREAM_TYPE_UNSPECIFIED:0};Mt[Mt.VIDEO_STREAM_TYPE_VOD]="VIDEO_STREAM_TYPE_VOD";Mt[Mt.VIDEO_STREAM_TYPE_DVR]="VIDEO_STREAM_TYPE_DVR";Mt[Mt.VIDEO_STREAM_TYPE_LIVE]="VIDEO_STREAM_TYPE_LIVE";Mt[Mt.VIDEO_STREAM_TYPE_UNSPECIFIED]="VIDEO_STREAM_TYPE_UNSPECIFIED";
var Nt={YT_IDB_TRANSACTION_TYPE_READ:2,YT_IDB_TRANSACTION_TYPE_WRITE:1,YT_IDB_TRANSACTION_TYPE_UNKNOWN:0};Nt[Nt.YT_IDB_TRANSACTION_TYPE_READ]="YT_IDB_TRANSACTION_TYPE_READ";Nt[Nt.YT_IDB_TRANSACTION_TYPE_WRITE]="YT_IDB_TRANSACTION_TYPE_WRITE";Nt[Nt.YT_IDB_TRANSACTION_TYPE_UNKNOWN]="YT_IDB_TRANSACTION_TYPE_UNKNOWN";var Ot={PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN:2,PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT:1,PLAYER_ROTATION_TYPE_UNKNOWN:0};Ot[Ot.PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN]="PLAYER_ROTATION_TYPE_PORTRAIT_TO_FULLSCREEN";
Ot[Ot.PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT]="PLAYER_ROTATION_TYPE_FULLSCREEN_TO_PORTRAIT";Ot[Ot.PLAYER_ROTATION_TYPE_UNKNOWN]="PLAYER_ROTATION_TYPE_UNKNOWN";var Pt="actionVisualElement spinnerInfo resourceInfo playerInfo commentInfo mdxInfo watchInfo thumbnailLoadInfo creatorInfo unpluggedInfo reelInfo subscriptionsFeedInfo requestIds mediaBrowserActionInfo musicLoadActionInfo shoppingInfo prefetchInfo accelerationSession webInfo tvInfo kabukiInfo mwebInfo musicInfo".split(" ");var Qt=y.ytLoggingLatencyUsageStats_||{};z("ytLoggingLatencyUsageStats_",Qt);function Rt(){this.i=0}
function St(){Rt.i||(Rt.i=new Rt);return Rt.i}
Rt.prototype.tick=function(a,b,c,d){Tt(this,"tick_"+a+"_"+b)||(c={timestamp:c,cttAuthInfo:d},M("web_csi_via_jspb")?(d=new Cj,E(d,1,a),E(d,2,b),a=new Fj,Td(a,Cj,5,Gj,d),fr(a,c)):cm("latencyActionTicked",{tickName:a,clientActionNonce:b},c))};
Rt.prototype.info=function(a,b,c){var d=Object.keys(a).join("");Tt(this,"info_"+d+"_"+b)||(a=Object.assign({},a),a.clientActionNonce=b,cm("latencyActionInfo",a,{cttAuthInfo:c}))};
Rt.prototype.jspbInfo=function(a,b,c){for(var d="",e=0;e<a.toJSON().length;e++)void 0!==a.toJSON()[e]&&(d=0===e?d.concat(""+e):d.concat("_"+e));Tt(this,"info_"+d+"_"+b)||(E(a,2,b),b={cttAuthInfo:c},c=new Fj,Td(c,wj,7,Gj,a),fr(c,b))};
Rt.prototype.span=function(a,b,c){var d=Object.keys(a).join("");Tt(this,"span_"+d+"_"+b)||(a.clientActionNonce=b,cm("latencyActionSpan",a,{cttAuthInfo:c}))};
function Tt(a,b){Qt[b]=Qt[b]||{count:0};var c=Qt[b];c.count++;c.time=P();a.i||(a.i=Ol(function(){var d=P(),e;for(e in Qt)Qt[e]&&6E4<d-Qt[e].time&&delete Qt[e];a&&(a.i=0)},0,5E3));
return 5<c.count?(6===c.count&&1>1E5*Math.random()&&(c=new R("CSI data exceeded logging limit with key",b.split("_")),0<=b.indexOf("plev")||Gr(c)),!0):!1}
;function Ut(){var a=["ol"];xt("").info.actionType="embed";a&&nk("TIMING_AFT_KEYS",a);nk("TIMING_ACTION","embed");Vt();a=pt();var b=rt();if("cold"===a.yt_lt||"cold"===b.loadType){var c=kt(),d=qt();d=d.gelTicks?d.gelTicks:d.gelTicks={};for(var e in c)e in d||Z(e,c[e]);e={};c=!1;d=p(Object.keys(a));for(var f=d.next();!f.done;f=d.next())f=f.value,(f=Gt(f,a[f]))&&!ut(rt(),f)&&(Ys(b,f),Ys(e,f),c=!0);c&&Wt(e)}z("ytglobal.timingready_",!0);a=L("TIMING_ACTION");B("ytglobal.timingready_")&&a&&"_start"in kt()&&
jt()&&tt()}
function Xt(a,b,c,d){null!==b&&(pt(c)[a]=b,(a=Gt(a,b,c))&&Wt(a,c,d))}
function Wt(a,b,c){if(!M("web_csi_via_jspb")||(void 0===c?0:c))c=xt(b||""),Ys(c.info,a),Ys(rt(b),a),c=st(b),b=ot(b).cttAuthInfo,St().info(a,c,b);else{c=new wj;var d=Object.keys(a);a=Object.values(a);for(var e=0;e<d.length;e++){var f=d[e];try{switch(f){case "actionType":yj(c,V[a[e]]);break;case "clientActionNonce":E(c,2,a[e]);break;case "clientScreenNonce":E(c,4,a[e]);break;case "loadType":E(c,3,a[e]);break;case "isPrewarmedLaunch":E(c,92,a[e]);break;case "isFirstInstall":E(c,55,a[e]);break;case "networkType":E(c,
5,Ht[a[e]]);break;case "connectionType":E(c,26,W[a[e]]);break;case "detailedConnectionType":E(c,27,Y[a[e]]);break;case "isVisible":E(c,6,a[e]);break;case "playerType":E(c,7,It[a[e]]);break;case "clientPlaybackNonce":E(c,8,a[e]);break;case "adClientPlaybackNonce":E(c,28,a[e]);break;case "previousCpn":E(c,77,a[e]);break;case "targetCpn":E(c,76,a[e]);break;case "isMonetized":E(c,9,a[e]);break;case "isPrerollAllowed":E(c,16,a[e]);break;case "isPrerollShown":E(c,17,a[e]);break;case "adType":E(c,12,a[e]);
break;case "adTypesAllowed":E(c,36,a[e]);break;case "adNetworks":E(c,37,a[e]);break;case "previousAction":E(c,13,V[a[e]]);break;case "isRedSubscriber":E(c,14,a[e]);break;case "serverTimeMs":E(c,15,a[e]);break;case "videoId":c.setVideoId(a[e]);break;case "adVideoId":E(c,20,a[e]);break;case "targetVideoId":E(c,78,a[e]);break;case "adBreakType":E(c,21,Jt[a[e]]);break;case "isNavigation":zj(c,a[e]);break;case "viewportHeight":E(c,29,a[e]);break;case "viewportWidth":E(c,30,a[e]);break;case "screenHeight":E(c,
84,a[e]);break;case "screenWidth":E(c,85,a[e]);break;case "browseId":E(c,31,a[e]);break;case "isCacheHit":E(c,32,a[e]);break;case "httpProtocol":E(c,33,a[e]);break;case "transportProtocol":E(c,34,a[e]);break;case "searchQuery":E(c,41,a[e]);break;case "isContinuation":E(c,42,a[e]);break;case "availableProcessors":E(c,43,a[e]);break;case "sdk":E(c,44,a[e]);break;case "isLocalStream":E(c,45,a[e]);break;case "navigationRequestedSameUrl":E(c,64,a[e]);break;case "shellStartupDurationMs":E(c,70,a[e]);break;
case "appInstallDataAgeMs":E(c,73,a[e]);break;case "latencyActionError":E(c,71,Kt[a[e]]);break;case "actionStep":E(c,79,a[e]);break;case "jsHeapSizeLimit":E(c,80,a[e]);break;case "totalJsHeapSize":E(c,81,a[e]);break;case "usedJsHeapSize":E(c,82,a[e]);break;case "sourceVideoDurationMs":E(c,90,a[e]);break;case "videoOutputFrames":E(c,93,a[e]);break;case "isResume":E(c,104,a[e]);break;case "adPrebufferedTimeSecs":E(c,39,a[e]);break;case "isLivestream":E(c,47,a[e]);break;case "liveStreamMode":E(c,91,
Lt[a[e]]);break;case "adCpn2":E(c,48,a[e]);break;case "adDaiDriftMillis":E(c,49,a[e]);break;case "videoStreamType":E(c,53,Mt[a[e]]);break;case "playbackRequiresTap":E(c,56,a[e]);break;case "performanceNavigationTiming":E(c,67,a[e]);break;case "transactionType":E(c,74,Nt[a[e]]);break;case "playerRotationType":E(c,101,Ot[a[e]]);break;case "allowedPreroll":E(c,10,a[e]);break;case "shownPreroll":E(c,11,a[e]);break;case "getHomeRequestId":E(c,57,a[e]);break;case "getSearchRequestId":E(c,60,a[e]);break;
case "getPlayerRequestId":E(c,61,a[e]);break;case "getWatchNextRequestId":E(c,62,a[e]);break;case "getBrowseRequestId":E(c,63,a[e]);break;case "getLibraryRequestId":E(c,66,a[e]);break;default:Pt.includes(f)&&wk(new R("Codegen laipb translator asked to translate message field",""+f))}}catch(g){wk(Error("Codegen laipb translator failed to set "+f))}}Yt(c,b)}}
function Yt(a,b){var c=qt(b);c.jspbInfos||(c.jspbInfos=[]);c.jspbInfos.push(a);xt(b||"").jspbInfo.push(a);c=st(b);b=ot(b).cttAuthInfo;St().jspbInfo(a,c,b)}
function Z(a,b,c){if(!b&&"_"!==a[0]){var d=a;S.mark&&(0==d.lastIndexOf("mark_",0)||(d="mark_"+d),c&&(d+=" ("+c+")"),S.mark(d))}d=xt(c||"");d.tick[a]=b||P();if(d.callback&&d.callback[a]){d=p(d.callback[a]);for(var e=d.next();!e.done;e=d.next())e=e.value,e()}d=qt(c);d.gelTicks&&(d.gelTicks[a]=!0);d=kt(c);e=b||P();d[a]=e;e=st(c);var f=ot(c).cttAuthInfo;if("_start"===a){var g=St();Tt(g,"baseline_"+e)||(b={timestamp:b,cttAuthInfo:f},M("web_csi_via_jspb")?(f=new uj,E(f,1,e),e=new Fj,Td(e,uj,6,Gj,f),fr(e,
b)):cm("latencyActionBaselined",{clientActionNonce:e},b))}else St().tick(a,e,b,f);tt(c);return d[a]}
function Zt(){var a=st();requestAnimationFrame(function(){setTimeout(function(){a===st()&&Z("ol",void 0,void 0)},0)})}
function $t(){var a=document;if("visibilityState"in a)a=a.visibilityState;else{var b=fp+"VisibilityState";a=b in a?a[b]:void 0}switch(a){case "hidden":return 0;case "visible":return 1;case "prerender":return 2;case "unloaded":return 3;default:return-1}}
function Vt(){function a(f){var g=lt(),h=nt(),k=L("CSI_START_TIMESTAMP_MILLIS",0);0<k&&!M("embeds_web_enable_csi_start_override_killswitch")&&(h=k);h&&(Z("srt",g.responseStart),1!==f.prerender&&Z("_start",h,void 0));f=vt();0<f&&Z("fpt",f);f=lt();f.isPerformanceNavigationTiming&&Wt({performanceNavigationTiming:!0});Z("nreqs",f.requestStart,void 0);Z("nress",f.responseStart,void 0);Z("nrese",f.responseEnd,void 0);0<f.redirectEnd-f.redirectStart&&(Z("nrs",f.redirectStart,void 0),Z("nre",f.redirectEnd,
void 0));0<f.domainLookupEnd-f.domainLookupStart&&(Z("ndnss",f.domainLookupStart,void 0),Z("ndnse",f.domainLookupEnd,void 0));0<f.connectEnd-f.connectStart&&(Z("ntcps",f.connectStart,void 0),Z("ntcpe",f.connectEnd,void 0));f.secureConnectionStart>=nt()&&0<f.connectEnd-f.secureConnectionStart&&(Z("nstcps",f.secureConnectionStart,void 0),Z("ntcpe",f.connectEnd,void 0));S&&"getEntriesByType"in S&&au()}
var b=L("TIMING_INFO",{});if(M("web_csi_via_jspb")){b=bu(b);Yt(b);b=yj(zj(new wj,!0),V[Ft(L("TIMING_ACTION"))]);var c=L("PREVIOUS_ACTION");c&&E(b,13,V[Ft(c)]);(c=L("CLIENT_PROTOCOL"))&&E(b,33,c);(c=L("CLIENT_TRANSPORT"))&&E(b,34,c);(c=Yr())&&"UNDEFINED_CSN"!==c&&E(b,4,c);c=$t();1!==c&&-1!==c||E(b,6,!0);c=pt();E(b,3,"cold");a(c);c=cu();if(0<c.length){c=p(c);for(var d=c.next();!d.done;d=c.next()){d=d.value;var e=new vj;E(e,1,d);Vd(b,83,vj,e)}}Yt(b)}else{for(c in b)b.hasOwnProperty(c)&&Xt(c,b[c]);b=
{isNavigation:!0,actionType:Ft(L("TIMING_ACTION"))};if(c=L("PREVIOUS_ACTION"))b.previousAction=Ft(c);if(c=L("CLIENT_PROTOCOL"))b.httpProtocol=c;if(c=L("CLIENT_TRANSPORT"))b.transportProtocol=c;(c=Yr())&&"UNDEFINED_CSN"!==c&&(b.clientScreenNonce=c);c=$t();if(1===c||-1===c)b.isVisible=!0;c=pt();b.loadType="cold";a(c);c=cu();if(0<c.length)for(b.resourceInfo=[],c=p(c),d=c.next();!d.done;d=c.next())b.resourceInfo.push({resourceCache:d.value});Wt(b)}}
function bu(a){var b=new wj;a=p(Object.entries(a));for(var c=a.next();!c.done;c=a.next()){var d=p(c.value);c=d.next().value;d=d.next().value;switch(c){case "GetBrowse_rid":var e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetGuide_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetHome_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetPlayer_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetSearch_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;
case "GetSettings_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetTrending_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "GetWatchNext_rid":e=new Bj;E(e,1,c);E(e,2,String(d));Aj(b,e);break;case "yt_red":E(b,14,!!d);break;case "yt_ad":E(b,9,!!d)}}return b}
function du(a,b){a=document.querySelector(a);if(!a)return!1;var c="",d=a.nodeName;"SCRIPT"===d?(c=a.src,c||(c=a.getAttribute("data-timing-href"))&&(c=window.location.protocol+c)):"LINK"===d&&(c=a.href);gc()&&a.setAttribute("nonce",gc());return c?(a=S.getEntriesByName(c))&&a[0]&&(a=a[0],c=nt(),Z("rsf_"+b,c+Math.round(a.fetchStart)),Z("rse_"+b,c+Math.round(a.responseEnd)),void 0!==a.transferSize&&0===a.transferSize)?!0:!1:!1}
function cu(){var a=[];if(document.querySelector&&S&&S.getEntriesByName)for(var b in ht)if(ht.hasOwnProperty(b)){var c=ht[b];du(b,c)&&a.push(c)}return a}
function au(){var a=window.location.protocol,b=S.getEntriesByType("resource");b=gb(b,function(c){return 0===c.name.indexOf(a+"//fonts.gstatic.com/s/")});
(b=ib(b,function(c,d){return d.duration>c.duration?d:c},{duration:0}))&&0<b.startTime&&0<b.responseEnd&&(Z("wffs",mt(b.startTime)),Z("wffe",mt(b.responseEnd)))}
var eu=window;eu.ytcsi&&(eu.ytcsi.info=Xt,eu.ytcsi.tick=Z);var fu="tokens consistency mss client_location entities response_received_commands store PLAYER_PRELOAD".split(" ");function gu(a,b,c,d){this.o=a;this.M=b;this.m=c;this.l=d;this.j=void 0;this.i=new Map;a.La||(a.La={});a.La=Object.assign({},Xs,a.La)}
function hu(a,b,c,d){if(void 0!==gu.i){if(d=gu.i,a=[a!==d.o,b!==d.M,c!==d.m,!1,!1,void 0!==d.j],a.some(function(e){return e}))throw new R("InnerTubeTransportService is already initialized",a);
}else gu.i=new gu(a,b,c,d)}
function iu(a){var b={signalServiceEndpoint:{signal:"GET_DATASYNC_IDS"}};var c=void 0===c?Gs:c;var d=Ps(b,a.o);if(!d)return vf(new R("Error: No request builder found for command.",b));var e=d.o(b,void 0,c);return e?new qf(function(f){var g,h,k;return w(function(m){if(1==m.i){h="cors"===(null==(g=e.Ba)?void 0:g.mode)?"cors":void 0;if(a.m.ld){var q=e.config,r;q=null==q?void 0:null==(r=q.Ra)?void 0:r.sessionIndex;r=xs({sessionIndex:q});k=Object.assign({},ju(h),r);return m.u(2)}return v(m,ku(e.config,
h),3)}2!=m.i&&(k=m.j);f(lu(a,e,k));m.i=0})}):vf(new R("Error: Failed to build request for command.",b))}
function lu(a,b,c){var d,e,f,g,h,k,m,q,r,x,u,A,D,F,N,O,Q,ea,ba,la;return w(function(X){switch(X.i){case 1:X.u(2);break;case 3:if((d=X.j)&&!d.isExpired())return X.return(Promise.resolve(d.i()));case 2:if(null==(e=b)?0:null==(f=e.ga)?0:f.context)for(g=p([]),h=g.next();!h.done;h=g.next())k=h.value,k.sq(b.ga.context);if(null==(m=a.j)?0:m.zq(b.input,b.ga))return X.return(a.j.pq(b.input,b.ga));(x=null==(r=b.config)?void 0:r.Aa)&&a.i.has(x)&&M("web_memoize_inflight_requests")?q=a.i.get(x):(u=JSON.stringify(b.ga),
b.Ba=Object.assign({},b.Ba,{headers:c}),A=Object.assign({},b.Ba),"POST"===b.Ba.method&&(A=Object.assign({},A,{body:u})),(null==(D=b.config)?0:D.Wc)&&Z(b.config.Wc),F=function(){return a.M.fetch(b.input,A,b.config)},q=F(),x&&a.i.set(x,q));
return v(X,q,4);case 4:N=X.j;x&&a.i.has(x)&&a.i.delete(x);(null==(O=b.config)?0:O.Xc)&&Z(b.config.Xc);if(N||null==(Q=a.j)||!Q.jq(b.input,b.ga)){X.u(5);break}return v(X,a.j.oq(b.input,b.ga),6);case 6:N=X.j;case 5:if(N&&(null==(ea=N.yq)||!ea.Bq)&&a.l)for(ba=p(fu),h=ba.next();!h.done;h=ba.next())la=h.value,a.l[la]&&a.l[la].handleResponse(N,b);return X.return(N)}})}
function ku(a,b){var c,d,e,f;return w(function(g){if(1==g.i){e=null==(c=a)?void 0:null==(d=c.Ra)?void 0:d.sessionIndex;var h=xs({sessionIndex:e});if(!(h instanceof qf)){var k=new qf(cb);rf(k,2,h);h=k}return v(g,h,2)}f=g.j;return g.return(Promise.resolve(Object.assign({},ju(b),f)))})}
function ju(a){var b={"Content-Type":"application/json"};M("enable_web_eom_visitor_data")&&L("EOM_VISITOR_DATA")?b["X-Goog-EOM-Visitor-Id"]=L("EOM_VISITOR_DATA"):L("VISITOR_DATA")&&(b["X-Goog-Visitor-Id"]=L("VISITOR_DATA"));M("track_webfe_innertube_auth_mismatch")&&(b["X-Youtube-Bootstrap-Logged-In"]=L("LOGGED_IN",!1));"cors"!==a&&((a=L("INNERTUBE_CONTEXT_CLIENT_NAME"))&&(b["X-Youtube-Client-Name"]=a),(a=L("INNERTUBE_CONTEXT_CLIENT_VERSION"))&&(b["X-Youtube-Client-Version"]=a),(a=L("CHROME_CONNECTED_HEADER"))&&
(b["X-Youtube-Chrome-Connected"]=a),(a=L("DOMAIN_ADMIN_STATE"))&&(b["X-Youtube-Domain-Admin-State"]=a));return b}
;var mu=["share/get_web_player_share_panel"],nu=["feedback"],ou=["notification/modify_channel_preference"],pu=["browse/edit_playlist"],qu=["subscription/subscribe"],ru=["subscription/unsubscribe"];function su(){}
t(su,Us);su.prototype.l=function(){return qu};
su.prototype.i=function(a){return a.subscribeEndpoint};
su.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params);c.botguardResponse&&(a.botguardResponse=c.botguardResponse);c.feature&&(a.clientFeature=c.feature)};
fa.Object.defineProperties(su.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function tu(){}
t(tu,Us);tu.prototype.l=function(){return ru};
tu.prototype.i=function(a){return a.unsubscribeEndpoint};
tu.prototype.j=function(a,b){b.channelIds&&(a.channelIds=b.channelIds);b.siloName&&(a.siloName=b.siloName);b.params&&(a.params=b.params)};
fa.Object.defineProperties(tu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function uu(){}
t(uu,Us);uu.prototype.l=function(){return nu};
uu.prototype.i=function(a){return a.feedbackEndpoint};
uu.prototype.j=function(a,b,c){a.feedbackTokens=[];b.feedbackToken&&a.feedbackTokens.push(b.feedbackToken);if(b=b.cpn||c.cpn)a.feedbackContext={cpn:b};a.isFeedbackTokenUnencrypted=!!c.is_feedback_token_unencrypted;a.shouldMerge=!1;c.extra_feedback_tokens&&(a.shouldMerge=!0,a.feedbackTokens=a.feedbackTokens.concat(c.extra_feedback_tokens))};
fa.Object.defineProperties(uu.prototype,{m:{configurable:!0,enumerable:!0,get:function(){return!0}}});function vu(){}
t(vu,Us);vu.prototype.l=function(){return ou};
vu.prototype.i=function(a){return a.modifyChannelNotificationPreferenceEndpoint};
vu.prototype.j=function(a,b){b.params&&(a.params=b.params);b.secondaryParams&&(a.secondaryParams=b.secondaryParams)};function wu(){}
t(wu,Us);wu.prototype.l=function(){return pu};
wu.prototype.i=function(a){return a.playlistEditEndpoint};
wu.prototype.j=function(a,b){b.actions&&(a.actions=b.actions);b.params&&(a.params=b.params);b.playlistId&&(a.playlistId=b.playlistId)};function xu(){}
t(xu,Us);xu.prototype.l=function(){return mu};
xu.prototype.i=function(a){return a.webPlayerShareEntityServiceEndpoint};
xu.prototype.j=function(a,b,c){c=void 0===c?{}:c;b.serializedShareEntity&&(a.serializedSharedEntity=b.serializedShareEntity);c.includeListId&&(a.includeListId=!0)};var Bs=new zs("NETWORK_SLI_TOKEN");function yu(a){this.i=a}
yu.prototype.fetch=function(a,b){var c=this,d,e;return w(function(f){c.i&&(d=kc(lc(5,Bc(a,"key")))||"/UNKNOWN_PATH",c.i.start(d));e=new window.Request(a,b);return M("web_fetch_promise_cleanup_killswitch")?f.return(Promise.resolve(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Gr(g)}))):f.return(fetch(e).then(function(g){return c.handleResponse(g)}).catch(function(g){Gr(g)}))})};
yu.prototype.handleResponse=function(a){var b=a.text().then(function(c){return JSON.parse(c.replace(")]}'",""))});
a.redirected||a.ok?this.i&&this.i.success():(this.i&&this.i.failure(),b=b.then(function(c){Gr(new R("Error: API fetch failed",a.status,a.url,c));return Object.assign({},c,{errorMetadata:{status:a.status}})}));
return b};
yu[ys]=[new As];var zu=new zs("NETWORK_MANAGER_TOKEN");var Au;function Bu(a){Kn.call(this,1,arguments);this.csn=a}
t(Bu,Kn);var Tn=new Ln("screen-created",Bu),Cu=[],Eu=Du,Fu=0;function Gu(a,b,c,d,e,f,g){function h(){Gr(new R("newScreen() parent element does not have a VE - rootVe",b))}
var k=Eu();f=new Rr({veType:b,youtubeData:f,jspbYoutubeData:void 0});e={cttAuthInfo:e,ba:k};if(M("il_via_jspb")){var m=new jj;m.V(k);kj(m,f.getAsJspb());c&&c.visualElement?(f=new lj,c.clientScreenNonce&&E(f,2,c.clientScreenNonce),mj(f,c.visualElement.getAsJspb()),g&&E(f,4,Hj[g]),G(m,lj,5,f)):c&&h();d&&E(m,3,d);kr(m,e,a)}else f={csn:k,pageVe:f.getAsJson()},c&&c.visualElement?(f.implicitGesture={parentCsn:c.clientScreenNonce,gesturedVe:c.visualElement.getAsJson()},g&&(f.implicitGesture.gestureType=
g)):c&&h(),d&&(f.cloneCsn=d),a?ar("screenCreated",f,a,e):cm("screenCreated",f,e);Qn(Tn,new Bu(k));return k}
function Hu(a,b,c,d){var e=d.filter(function(k){k.csn!==b?(k.csn=b,k=!0):k=!1;return k}),f={cttAuthInfo:$r(b),
ba:b};d=p(d);for(var g=d.next();!g.done;g=d.next())g=g.value.getAsJson(),(pb(g)||!g.trackingParams&&!g.veType)&&Gr(Error("Child VE logged with no data"));if(M("il_via_jspb")){var h=new nj;h.V(b);pj(h,c.getAsJspb());hb(e,function(k){k=k.getAsJspb();Vd(h,3,ej,k)});
"UNDEFINED_CSN"==b?Iu("visualElementAttached",h,f):lr(h,f,a)}else c={csn:b,parentVe:c.getAsJson(),childVes:hb(e,function(k){return k.getAsJson()})},"UNDEFINED_CSN"==b?Iu("visualElementAttached",c,f):a?ar("visualElementAttached",c,a,f):cm("visualElementAttached",c,f)}
function Du(){for(var a=Math.random()+"",b=[],c=0,d=0;d<a.length;d++){var e=a.charCodeAt(d);255<e&&(b[c++]=e&255,e>>=8);b[c++]=e}return dd(b,3)}
function Iu(a,b,c){Cu.push({payloadName:a,payload:b,options:c});Fu||(Fu=Un())}
function Vn(a){if(Cu){for(var b=p(Cu),c=b.next();!c.done;c=b.next())if(c=c.value,c.payload)if(M("il_via_jspb"))switch(c.payload.V(a.csn),c.payloadName){case "screenCreated":kr(c.payload,c.options);break;case "visualElementAttached":lr(c.payload,c.options);break;case "visualElementShown":gr(c.payload,c.options);break;case "visualElementHidden":hr(c.payload,c.options);break;case "visualElementGestured":ir(c.payload,c.options);break;case "visualElementStateChanged":jr(c.payload,c.options);break;default:Gr(new R("flushQueue unable to map payloadName to JSPB setter"))}else c.payload.csn=
a.csn,ar(c.payloadName,c.payload,null,c.options);Cu.length=0}Fu=0}
;function Ju(){this.j=new Set;this.i=new Set;this.l=new Map}
Ju.prototype.s=function(){};
Ju.prototype.clear=function(){this.j.clear();this.i.clear();this.l.clear()};
Oa(Ju);function Ku(){this.o=[];this.N=[];this.i=[];this.m=[];this.B=[];this.j=new Set;this.v=new Map}
Ku.prototype.s=function(a){this.client=a};
function Lu(a,b,c){c=void 0===c?0:c;b.then(function(d){a.j.has(c)&&a.l&&a.l();var e=Yr(c),f=Wr(c);if(e&&f){var g;(null==d?0:null==(g=d.response)?0:g.trackingParams)&&Hu(a.client,e,f,[Sr(d.response.trackingParams)]);var h;(null==d?0:null==(h=d.playerResponse)?0:h.trackingParams)&&Hu(a.client,e,f,[Sr(d.playerResponse.trackingParams)])}})}
function Mu(a,b,c,d){d=void 0===d?0:d;if(a.j.has(d))a.o.push([b,c]);else{var e=Yr(d);c=c||Wr(d);e&&c&&Hu(a.client,e,c,[b])}}
Ku.prototype.clickCommand=function(a,b,c){var d=a.clickTrackingParams;c=void 0===c?0:c;if(d)if(c=Yr(void 0===c?0:c)){a=this.client;var e=Sr(d);d={cttAuthInfo:$r(c),ba:c};if(M("il_via_jspb")){var f=new qj;f.V(c);e=e.getAsJspb();G(f,ej,2,e);E(f,4,Hj.INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK);b&&G(f,hj,3);"UNDEFINED_CSN"==c?Iu("visualElementGestured",f,d):ir(f,d,a)}else f={csn:c,ve:e.getAsJson(),gestureType:"INTERACTION_LOGGING_GESTURE_TYPE_GENERIC_CLICK"},b&&(f.clientData=b),"UNDEFINED_CSN"==c?
Iu("visualElementGestured",f,d):a?ar("visualElementGestured",f,a,d):cm("visualElementGestured",f,d);b=!0}else b=!1;else b=!1;return b};
function Nu(a,b,c){c=void 0===c?{}:c;a.j.add(c.layer||0);a.l=function(){Ou(a,b,c);var f=Wr(c.layer);if(f){for(var g=p(a.o),h=g.next();!h.done;h=g.next())h=h.value,Mu(a,h[0],h[1]||f,c.layer);f=p(a.N);for(g=f.next();!g.done;g=f.next()){var k=g.value;g=void 0;g=void 0===g?0:g;h=Yr(g);var m=k[0]||Wr(g);if(h&&m){g=a.client;var q=k[1];k={cttAuthInfo:$r(h),ba:h};M("il_via_jspb")?(q=new tj,q.V(h),m=m.getAsJspb(),G(q,ej,2,m),"UNDEFINED_CSN"==h?Iu("visualElementStateChanged",q,k):jr(q,k,g)):(m={csn:h,ve:m.getAsJson(),
clientData:q},"UNDEFINED_CSN"==h?Iu("visualElementStateChanged",m,k):g?ar("visualElementStateChanged",m,g,k):cm("visualElementStateChanged",m,k))}}}};
Yr(c.layer)||a.l();if(c.Nb)for(var d=p(c.Nb),e=d.next();!e.done;e=d.next())Lu(a,e.value,c.layer);else Fr(Error("Delayed screen needs a data promise."))}
function Ou(a,b,c){c=void 0===c?{}:c;c.layer||(c.layer=0);var d=void 0!==c.Rc?c.Rc:c.layer;var e=Yr(d);d=Wr(d);var f;d&&(void 0!==c.parentCsn?f={clientScreenNonce:c.parentCsn,visualElement:d}:e&&"UNDEFINED_CSN"!==e&&(f={clientScreenNonce:e,visualElement:d}));var g,h=L("EVENT_ID");"UNDEFINED_CSN"===e&&h&&(g={servletData:{serializedServletEventId:h}});try{var k=Gu(a.client,b,f,c.Mb,c.cttAuthInfo,g,c.mq)}catch(m){Ir(m,{wq:b,rootVe:d,parentVisualElement:void 0,kq:e,rq:f,Mb:c.Mb});Fr(m);return}as(k,b,
c.layer,c.cttAuthInfo);if(b=e&&"UNDEFINED_CSN"!==e&&d){a:{b=p(Object.values(Qr));for(f=b.next();!f.done;f=b.next())if(Yr(f.value)===e){b=!0;break a}b=!1}b=!b}b&&(b=a.client,g=!0,h=(g=void 0===g?!1:g)?16:8,f={cttAuthInfo:$r(e),ba:e,Ob:g},M("il_via_jspb")?(h=new rj,h.V(e),d=d.getAsJspb(),G(h,ej,2,d),E(h,4,g?16:8),"UNDEFINED_CSN"==e?Iu("visualElementHidden",h,f):hr(h,f,b)):(d={csn:e,ve:d.getAsJson(),eventType:h},"UNDEFINED_CSN"==e?Iu("visualElementHidden",d,f):b?ar("visualElementHidden",d,b,f):cm("visualElementHidden",
d,f)));a.i[a.i.length-1]&&!a.i[a.i.length-1].csn&&(a.i[a.i.length-1].csn=k||"");Wt({clientScreenNonce:k});Ju.getInstance().clear();d=Wr(c.layer);e&&"UNDEFINED_CSN"!==e&&d&&(M("web_mark_root_visible")||M("music_web_mark_root_visible"))&&(e=k,k={cttAuthInfo:$r(e),ba:e},M("il_via_jspb")?(b=new sj,b.V(e),f=d.getAsJspb(),G(b,ej,2,f),E(b,4,1),"UNDEFINED_CSN"==e?Iu("visualElementShown",b,k):gr(b,k)):(b={csn:e,ve:d.getAsJson(),eventType:1},"UNDEFINED_CSN"==e?Iu("visualElementShown",b,k):cm("visualElementShown",
b,k)));a.j.delete(c.layer||0);a.l=void 0;e=p(a.v);for(k=e.next();!k.done;k=e.next())b=p(k.value),k=b.next().value,b=b.next().value,b.has(c.layer)&&d&&Mu(a,k,d,c.layer);for(c=0;c<a.m.length;c++){e=a.m[c];try{e()}catch(m){Fr(m)}}for(c=a.m.length=0;c<a.B.length;c++){e=a.B[c];try{e()}catch(m){Fr(m)}}}
;function Pu(){var a,b;return w(function(c){if(1==c.i)return a=gu.i,a?v(c,iu(a),2):(Gr(Error("InnertubeTransportService unavailable in fetchDatasyncIds")),c.return(void 0));if(b=c.j)return b.errorMetadata?(Gr(Error("Datasync IDs fetch responded with "+b.errorMetadata.status+": "+b.error)),c.return(void 0)):c.return(b.lq);Gr(Error("Network request to get Datasync IDs failed."));return c.return(void 0)})}
;var Qu=y.caches,Ru;function Su(a){var b=a.indexOf(":");return-1===b?{Yb:a}:{Yb:a.substring(0,b),datasyncId:a.substring(b+1)}}
function Tu(){return w(function(a){if(void 0!==Ru)return a.return(Ru);Ru=new Promise(function(b){var c;return w(function(d){switch(d.i){case 1:return wa(d,2),v(d,Qu.open("test-only"),4);case 4:return v(d,Qu.delete("test-only"),5);case 5:xa(d,3);break;case 2:if(c=ya(d),c instanceof Error&&"SecurityError"===c.name)return b(!1),d.return();case 3:b("caches"in window),d.i=0}})});
return a.return(Ru)})}
function Uu(a){var b,c,d,e,f,g,h;w(function(k){if(1==k.i)return v(k,Tu(),2);if(3!=k.i){if(!k.j)return k.return(!1);b=[];return v(k,Qu.keys(),3)}c=k.j;d=p(c);for(e=d.next();!e.done;e=d.next())f=e.value,g=Su(f),h=g.datasyncId,!h||a.includes(h)||b.push(Qu.delete(f));return k.return(Promise.all(b).then(function(m){return m.some(function(q){return q})}))})}
function Vu(){var a,b,c,d,e,f,g;return w(function(h){if(1==h.i)return v(h,Tu(),2);if(3!=h.i){if(!h.j)return h.return(!1);a=gm("cache contains other");return v(h,Qu.keys(),3)}b=h.j;c=p(b);for(d=c.next();!d.done;d=c.next())if(e=d.value,f=Su(e),(g=f.datasyncId)&&g!==a)return h.return(!0);return h.return(!1)})}
;function Wu(){try{return!!self.localStorage}catch(a){return!1}}
;function Xu(a){a=a.match(/(.*)::.*::.*/);if(null!==a)return a[1]}
function Yu(a){if(Wu()){var b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next()){c=c.value;var d=Xu(c);void 0===d||a.includes(d)||self.localStorage.removeItem(c)}}}
function Zu(){if(!Wu())return!1;var a=gm(),b=Object.keys(window.localStorage);b=p(b);for(var c=b.next();!c.done;c=b.next())if(c=Xu(c.value),void 0!==c&&c!==a)return!0;return!1}
;function $u(){Pu().then(function(a){a&&(rn(a),Uu(a),Yu(a))})}
function av(){var a=new Bo;Nh.S(function(){var b,c,d,e;return w(function(f){switch(f.i){case 1:if(M("ytidb_clear_optimizations_killswitch")){f.u(2);break}b=gm("clear");if(b.startsWith("V")){var g=[b];rn(g);Uu(g);Yu(g);return f.return()}c=Zu();return v(f,Vu(),3);case 3:return d=f.j,v(f,sn(),4);case 4:if(e=f.j,!c&&!d&&!e)return f.return();case 2:a.L()?$u():a.m.add("publicytnetworkstatus-online",$u,!0,void 0,void 0),f.i=0}})})}
;function bv(a){a&&(a.dataset?a.dataset[cv("loaded")]="true":a.setAttribute("data-loaded","true"))}
function dv(a,b){return a?a.dataset?a.dataset[cv(b)]:a.getAttribute("data-"+b):null}
var ev={};function cv(a){return ev[a]||(ev[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var fv=/\.vflset|-vfl[a-zA-Z0-9_+=-]+/,gv=/-[a-zA-Z]{2,3}_[a-zA-Z]{2,3}(?=(\/|$))/;function hv(a,b,c){c=void 0===c?null:c;if(window.spf&&spf.script){c="";if(a){var d=a.indexOf("jsbin/"),e=a.lastIndexOf(".js"),f=d+6;-1<d&&-1<e&&e>f&&(c=a.substring(f,e),c=c.replace(fv,""),c=c.replace(gv,""),c=c.replace("debug-",""),c=c.replace("tracing-",""))}spf.script.load(a,c,b)}else iv(a,b,c)}
function iv(a,b,c){c=void 0===c?null:c;var d=jv(a),e=document.getElementById(d),f=e&&dv(e,"loaded"),g=e&&!f;f?b&&b():(b&&(f=mq(d,b),b=""+Sa(b),kv[b]=f),g||(e=lv(a,d,function(){dv(e,"loaded")||(bv(e),pq(d),Qk(Ya(qq,d),0))},c)))}
function lv(a,b,c,d){d=void 0===d?null:d;var e=bf("SCRIPT");e.id=b;e.onload=function(){c&&setTimeout(c,0)};
e.onreadystatechange=function(){switch(e.readyState){case "loaded":case "complete":e.onload()}};
d&&e.setAttribute("nonce",d);wh(e,Jb(a));a=document.getElementsByTagName("head")[0]||document.body;a.insertBefore(e,a.firstChild);return e}
function mv(a){a=jv(a);var b=document.getElementById(a);b&&(qq(a),b.parentNode.removeChild(b))}
function nv(a,b){a&&b&&(a=""+Sa(b),(a=kv[a])&&oq(a))}
function jv(a){var b=document.createElement("a");dc(b,a);a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"js-"+ic(a)}
var kv={};var ov=[],pv=!1;function qv(){if(!M("disable_biscotti_fetch_for_ad_blocker_detection")&&!M("disable_biscotti_fetch_entirely_for_all_web_clients")&&ms()){var a=L("PLAYER_VARS",{});if(!("1"==rb(a)||M("embeds_web_disable_ads_for_pfl")&&ns(a))){var b=function(){pv=!0;"google_ad_status"in window?nk("DCLKSTAT",1):nk("DCLKSTAT",2)};
try{hv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}ov.push(Nh.S(function(){if(!(pv||"google_ad_status"in window)){try{nv("//static.doubleclick.net/instream/ad_status.js",b)}catch(c){}pv=!0;nk("DCLKSTAT",3)}},5E3))}}}
function rv(){var a=Number(L("DCLKSTAT",0));return isNaN(a)?0:a}
;function uv(){this.state=1;this.i=null}
uv.prototype.initialize=function(a,b,c){if(a.program){var d,e=null!=(d=a.interpreterScript)?d:null,f;d=null!=(f=a.interpreterUrl)?f:null;a.interpreterSafeScript&&(e=a.interpreterSafeScript,Db("From proto message. b/166824318"),e=e.privateDoNotAccessOrElseSafeScriptWrappedValue||"",e=(f=yb())?f.createScript(e):e,e=(new Fb(e)).toString());a.interpreterSafeUrl&&(d=a.interpreterSafeUrl,Db("From proto message. b/166824318"),d=Jb(d.privateDoNotAccessOrElseTrustedResourceUrlWrappedValue||"").toString());
vv(this,e,d,a.program,b,c)}else Gr(Error("Cannot initialize botguard without program"))};
function vv(a,b,c,d,e,f){var g=void 0===g?"trayride":g;c?(a.state=2,hv(c,function(){window[g]?wv(a,d,g,e):(a.state=3,mv(c),Gr(new R("Unable to load Botguard","from "+c)))},f)):b?(f=bf("SCRIPT"),f.textContent=b,f.nonce=gc(),document.head.appendChild(f),document.head.removeChild(f),window[g]?wv(a,d,g,e):(a.state=4,Gr(new R("Unable to load Botguard from JS")))):Gr(new R("Unable to load VM; no url or JS provided"))}
uv.prototype.isInitialized=function(){return!!this.i};
function wv(a,b,c,d){a.state=5;try{var e=new uh({program:b,globalName:c});e.hd.then(function(){a.state=6;d&&d(b)});
xv(a,e)}catch(f){a.state=7,f instanceof Error&&Gr(f)}}
uv.prototype.invoke=function(a){a=void 0===a?{}:a;var b=this.i;if(b){var c={Lb:a};if(b.Wa)throw Error("Already disposed");a=sh();var d;null!=(d=b.sa)&&d.j.i.Bb("/client_streamz/bg/fsc",d.Aa);d=b.md([c.Lb,c.kd]);null!=(b=b.sa)&&(a=sh()-a,b.l.i.hb("/client_streamz/bg/fsl",a,b.Aa));b=d}else b=null;return b};
uv.prototype.dispose=function(){xv(this,null);this.state=8};
function xv(a,b){je(a.i);a.i=b}
;var yv=new uv;function zv(){return yv.isInitialized()}
function Av(a){a=void 0===a?{}:a;return yv.invoke(a)}
;function Bv(a){var b=this;var c=void 0===c?0:c;var d=void 0===d?Sl():d;this.m=c;this.l=d;this.j=new th;this.i=a;a={};c=p(this.i.entries());for(d=c.next();!d.done;a={Ca:a.Ca,Na:a.Na},d=c.next()){var e=p(d.value);d=e.next().value;e=e.next().value;a.Na=d;a.Ca=e;d=function(f){return function(){f.Ca.tb();b.i[f.Na].eb=!0;b.i.every(function(g){return!0===g.eb})&&b.j.resolve()}}(a);
e=Ol(d,Cv(this,a.Ca));this.i[a.Na]=Object.assign({},a.Ca,{tb:d,Za:e})}}
function Dv(a){var b=Array.from(a.i.keys()).sort(function(d,e){return Cv(a,a.i[e])-Cv(a,a.i[d])});
b=p(b);for(var c=b.next();!c.done;c=b.next())c=a.i[c.value],void 0===c.Za||c.eb||(a.l.fa(c.Za),Ol(c.tb,10))}
Bv.prototype.cancel=function(){for(var a=p(this.i),b=a.next();!b.done;b=a.next())b=b.value,void 0===b.Za||b.eb||this.l.fa(b.Za),b.eb=!0;this.j.resolve()};
function Cv(a,b){var c;return null!=(c=b.priority)?c:a.m}
;function Ev(a){this.state=a;this.plugins=[];this.s=void 0}
Ev.prototype.install=function(){this.plugins.push.apply(this.plugins,ia(Ka.apply(0,arguments)))};
Ev.prototype.transition=function(a,b){var c=this,d=this.B.find(function(f){return f.from===c.state&&f.D===a});
if(d){this.l&&(Dv(this.l),this.l=void 0);this.state=a;d=d.action.bind(this);var e=this.plugins.filter(function(f){return f[a]}).map(function(f){return f[a]});
d(Fv(this,e,this.s),b)}else throw Error("no transition specified from "+this.state+" to "+a);};
function Fv(a,b,c){return function(){var d=Ka.apply(0,arguments),e=b.filter(function(k){var m;return 10===(null!=(m=null!=c?c:k.priority)?m:0)}),f=b.filter(function(k){var m;
return 10!==(null!=(m=null!=c?c:k.priority)?m:0)});
Sl();var g={};e=p(e);for(var h=e.next();!h.done;g={Oa:g.Oa},h=e.next())g.Oa=h.value,Ql(function(k){return function(){k.Oa.callback.apply(k.Oa,ia(d))}}(g));
f=f.map(function(k){var m;return{tb:function(){k.callback.apply(k,ia(d))},
priority:null!=(m=null!=c?c:k.priority)?m:0}});
f.length&&(a.l=new Bv(f))}}
fa.Object.defineProperties(Ev.prototype,{currentState:{configurable:!0,enumerable:!0,get:function(){return this.state}}});function Gv(a){Ev.call(this,void 0===a?"document_active":a);var b=this;this.s=10;this.i=new Map;this.B=[{from:"document_active",D:"document_disposed_preventable",action:this.N},{from:"document_active",D:"document_disposed",action:this.m},{from:"document_disposed_preventable",D:"document_disposed",action:this.m},{from:"document_disposed_preventable",D:"flush_logs",action:this.o},{from:"document_disposed_preventable",D:"document_active",action:this.j},{from:"document_disposed",D:"flush_logs",action:this.o},
{from:"document_disposed",D:"document_active",action:this.j},{from:"document_disposed",D:"document_disposed",action:function(){}},
{from:"flush_logs",D:"document_active",action:this.j}];window.addEventListener("pagehide",function(c){b.transition("document_disposed",{event:c})});
window.addEventListener("beforeunload",function(c){b.transition("document_disposed_preventable",{event:c})})}
t(Gv,Ev);Gv.prototype.N=function(a,b){if(!this.i.get("document_disposed_preventable")){a(null==b?void 0:b.event);var c,d;if((null==b?0:null==(c=b.event)?0:c.defaultPrevented)||(null==b?0:null==(d=b.event)?0:d.returnValue)){b.event.returnValue||(b.event.returnValue=!0);b.event.defaultPrevented||b.event.preventDefault();this.i=new Map;this.transition("document_active");return}}this.i.set("document_disposed_preventable",!0);this.i.get("document_disposed")?this.transition("flush_logs"):this.transition("document_disposed")};
Gv.prototype.m=function(a,b){this.i.get("document_disposed")?this.transition("document_active"):(a(null==b?void 0:b.event),this.i.set("document_disposed",!0),this.transition("flush_logs"))};
Gv.prototype.o=function(a,b){a(null==b?void 0:b.event);this.transition("document_active")};
Gv.prototype.j=function(){this.i=new Map};function Hv(a){Ev.call(this,void 0===a?"document_visibility_unknown":a);var b=this;this.B=[{from:"document_visibility_unknown",D:"document_visible",action:this.j},{from:"document_visibility_unknown",D:"document_hidden",action:this.i},{from:"document_visibility_unknown",D:"document_foregrounded",action:this.o},{from:"document_visibility_unknown",D:"document_backgrounded",action:this.m},{from:"document_visible",D:"document_hidden",action:this.i},{from:"document_visible",D:"document_foregrounded",action:this.o},
{from:"document_visible",D:"document_visible",action:this.j},{from:"document_foregrounded",D:"document_visible",action:this.j},{from:"document_foregrounded",D:"document_hidden",action:this.i},{from:"document_foregrounded",D:"document_foregrounded",action:this.o},{from:"document_hidden",D:"document_visible",action:this.j},{from:"document_hidden",D:"document_backgrounded",action:this.m},{from:"document_hidden",D:"document_hidden",action:this.i},{from:"document_backgrounded",D:"document_hidden",action:this.i},
{from:"document_backgrounded",D:"document_backgrounded",action:this.m},{from:"document_backgrounded",D:"document_visible",action:this.j}];document.addEventListener("visibilitychange",function(c){"visible"===document.visibilityState?b.transition("document_visible",{event:c}):b.transition("document_hidden",{event:c})});
M("visibility_lifecycles_dynamic_backgrounding")&&(window.addEventListener("blur",function(c){b.transition("document_backgrounded",{event:c})}),window.addEventListener("focus",function(c){b.transition("document_foregrounded",{event:c})}))}
t(Hv,Ev);Hv.prototype.j=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_foregrounded")};
Hv.prototype.i=function(a,b){a(null==b?void 0:b.event);M("visibility_lifecycles_dynamic_backgrounding")&&this.transition("document_backgrounded")};
Hv.prototype.m=function(a,b){a(null==b?void 0:b.event)};
Hv.prototype.o=function(a,b){a(null==b?void 0:b.event)};function Iv(){this.i=new Gv;this.j=new Hv}
Iv.prototype.install=function(){var a=Ka.apply(0,arguments);this.i.install.apply(this.i,ia(a));this.j.install.apply(this.j,ia(a))};function Jv(){Iv.call(this);var a={};this.install((a.document_disposed={callback:this.l},a));a={};this.install((a.flush_logs={callback:this.m},a))}
var Kv;t(Jv,Iv);Jv.prototype.m=function(){if(M("web_fp_via_jspb")){var a=new dj,b=Yr();b&&a.V(b);b=new Fj;Td(b,dj,380,Gj,a);fr(b);M("web_fp_via_jspb_and_json")&&cm("finalPayload",{csn:Yr()})}else cm("finalPayload",{csn:Yr()})};
Jv.prototype.l=function(){Kr(Lr)};function Lv(){}
Lv.getInstance=function(){var a=B("ytglobal.storage_");a||(a=new Lv,z("ytglobal.storage_",a));return a};
Lv.prototype.estimate=function(){var a,b,c;return w(function(d){a=navigator;return(null==(b=a.storage)?0:b.estimate)?d.return(a.storage.estimate()):(null==(c=a.webkitTemporaryStorage)?0:c.queryUsageAndQuota)?d.return(Mv()):d.return()})};
function Mv(){var a=navigator;return new Promise(function(b,c){var d;null!=(d=a.webkitTemporaryStorage)&&d.queryUsageAndQuota?a.webkitTemporaryStorage.queryUsageAndQuota(function(e,f){b({usage:e,quota:f})},function(e){c(e)}):c(Error("webkitTemporaryStorage is not supported."))})}
z("ytglobal.storageClass_",Lv);function am(a,b){var c=this;this.handleError=a;this.i=b;this.j=!1;void 0===self.document||self.addEventListener("beforeunload",function(){c.j=!0});
this.l=Math.random()<=qk("ytidb_transaction_ended_event_rate_limit",.02)}
am.prototype.logEvent=function(a,b){switch(a){case "IDB_DATA_CORRUPTED":M("idb_data_corrupted_killswitch")||this.i("idbDataCorrupted",b);break;case "IDB_UNEXPECTEDLY_CLOSED":this.i("idbUnexpectedlyClosed",b);break;case "IS_SUPPORTED_COMPLETED":M("idb_is_supported_completed_killswitch")||this.i("idbIsSupportedCompleted",b);break;case "QUOTA_EXCEEDED":Nv(this,b);break;case "TRANSACTION_ENDED":this.l&&this.i("idbTransactionEnded",b);break;case "TRANSACTION_UNEXPECTEDLY_ABORTED":a=Object.assign({},b,
{hasWindowUnloaded:this.j}),this.i("idbTransactionAborted",a)}};
function Nv(a,b){Lv.getInstance().estimate().then(function(c){c=Object.assign({},b,{isSw:void 0===self.document,isIframe:self!==self.top,deviceStorageUsageMbytes:Ov(null==c?void 0:c.usage),deviceStorageQuotaMbytes:Ov(null==c?void 0:c.quota)});a.i("idbQuotaExceeded",c)})}
function Ov(a){return"undefined"===typeof a?"-1":String(Math.ceil(a/1048576))}
;function Pv(a,b,c){J.call(this);var d=this;c=c||L("POST_MESSAGE_ORIGIN")||window.document.location.protocol+"//"+window.document.location.hostname;this.l=b||null;this.targetOrigin="*";this.m=c;this.sessionId=null;this.channel="widget";this.F=!!a;this.v=function(e){a:if(!("*"!=d.m&&e.origin!=d.m||d.l&&e.source!=d.l||"string"!==typeof e.data)){try{var f=JSON.parse(e.data)}catch(g){break a}if(!(null==f||d.F&&(d.sessionId&&d.sessionId!=f.id||d.channel&&d.channel!=f.channel))&&f)switch(f.event){case "listening":"null"!=
e.origin&&(d.m=d.targetOrigin=e.origin);d.l=e.source;d.sessionId=f.id;d.j&&(d.j(),d.j=null);break;case "command":d.o&&(!d.s||0<=eb(d.s,f.func))&&d.o(f.func,f.args,e.origin)}}};
this.s=this.j=this.o=null;window.addEventListener("message",this.v)}
t(Pv,J);Pv.prototype.sendMessage=function(a,b){if(b=b||this.l){this.sessionId&&(a.id=this.sessionId);this.channel&&(a.channel=this.channel);try{var c=JSON.stringify(a);b.postMessage(c,this.targetOrigin)}catch(d){xk(d)}}};
Pv.prototype.C=function(){window.removeEventListener("message",this.v);J.prototype.C.call(this)};function Qv(){this.j=[];this.isReady=!1;this.l={};var a=this.i=new Pv(!!L("WIDGET_ID_ENFORCE")),b=this.Uc.bind(this);a.o=b;a.s=null;this.i.channel="widget";if(a=L("WIDGET_ID"))this.i.sessionId=a}
l=Qv.prototype;l.Uc=function(a,b,c){"addEventListener"===a&&b?(a=b[0],this.l[a]||"onReady"===a||(this.addEventListener(a,Rv(this,a)),this.l[a]=!0)):this.Cb(a,b,c)};
l.Cb=function(){};
function Rv(a,b){return function(c){return a.sendMessage(b,c)}}
l.addEventListener=function(){};
l.Fc=function(){this.isReady=!0;this.sendMessage("initialDelivery",this.pb());this.sendMessage("onReady");fb(this.j,this.hc,this);this.j=[]};
l.pb=function(){return null};
function Sv(a,b){a.sendMessage("infoDelivery",b)}
l.hc=function(a){this.isReady?this.i.sendMessage(a):this.j.push(a)};
l.sendMessage=function(a,b){this.hc({event:a,info:void 0===b?null:b})};
l.dispose=function(){this.i=null};function Tv(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Uv(a,b,c){if("string"===typeof a)return{videoId:a,startSeconds:b,suggestedQuality:c};b=["endSeconds","startSeconds","mediaContentUrl","suggestedQuality","videoId"];c={};for(var d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}
function Vv(a,b,c,d){if(Ra(a)&&!Array.isArray(a)){b="playlist list listType index startSeconds suggestedQuality".split(" ");c={};for(d=0;d<b.length;d++){var e=b[d];a[e]&&(c[e]=a[e])}return c}b={index:b,startSeconds:c,suggestedQuality:d};"string"===typeof a&&16===a.length?b.list="PL"+a:b.playlist=a;return b}
;function Wv(a){Qv.call(this);this.listeners=[];this.api=a;this.addEventListener("onReady",this.onReady.bind(this));this.addEventListener("onVideoProgress",this.ed.bind(this));this.addEventListener("onVolumeChange",this.fd.bind(this));this.addEventListener("onApiChange",this.Yc.bind(this));this.addEventListener("onPlaybackQualityChange",this.bd.bind(this));this.addEventListener("onPlaybackRateChange",this.cd.bind(this));this.addEventListener("onStateChange",this.dd.bind(this));this.addEventListener("onWebglSettingsChanged",
this.gd.bind(this))}
t(Wv,Qv);l=Wv.prototype;
l.Cb=function(a,b,c){if(this.api.isExternalMethodAvailable(a,c)){b=b||[];if(0<b.length&&Tv(a)){var d=b;if(Ra(d[0])&&!Array.isArray(d[0]))var e=d[0];else switch(e={},a){case "loadVideoById":case "cueVideoById":e=Uv(d[0],void 0!==d[1]?Number(d[1]):void 0,d[2]);break;case "loadVideoByUrl":case "cueVideoByUrl":e=d[0];"string"===typeof e&&(e={mediaContentUrl:e,startSeconds:void 0!==d[1]?Number(d[1]):void 0,suggestedQuality:d[2]});b:{if((d=e.mediaContentUrl)&&(d=/\/([ve]|embed)\/([^#?]+)/.exec(d))&&d[2]){d=
d[2];break b}d=null}e.videoId=d;e=Uv(e);break;case "loadPlaylist":case "cuePlaylist":e=Vv(d[0],d[1],d[2],d[3])}b.length=1;b[0]=e}this.api.handleExternalCall(a,b,c);Tv(a)&&Sv(this,this.pb())}};
l.onReady=function(){var a=this.Fc.bind(this);this.i.j=a};
l.addEventListener=function(a,b){this.listeners.push({eventType:a,listener:b});this.api.addEventListener(a,b)};
l.pb=function(){if(!this.api)return null;var a=this.api.getApiInterface();kb(a,"getVideoData");for(var b={apiInterface:a},c=0,d=a.length;c<d;c++){var e=a[c];if(0===e.search("get")||0===e.search("is")){var f=0;0===e.search("get")?f=3:0===e.search("is")&&(f=2);f=e.charAt(f).toLowerCase()+e.substr(f+1);try{var g=this.api[e]();b[f]=g}catch(h){}}}b.videoData=this.api.getVideoData();b.currentTimeLastUpdated_=Date.now()/1E3;return b};
l.dd=function(a){a={playerState:a,currentTime:this.api.getCurrentTime(),duration:this.api.getDuration(),videoData:this.api.getVideoData(),videoStartBytes:0,videoBytesTotal:this.api.getVideoBytesTotal(),videoLoadedFraction:this.api.getVideoLoadedFraction(),playbackQuality:this.api.getPlaybackQuality(),availableQualityLevels:this.api.getAvailableQualityLevels(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getVideoUrl&&
(a.videoUrl=this.api.getVideoUrl());this.api.getVideoContentRect&&(a.videoContentRect=this.api.getVideoContentRect());this.api.getProgressState&&(a.progressState=this.api.getProgressState());this.api.getPlaylist&&(a.playlist=this.api.getPlaylist());this.api.getPlaylistIndex&&(a.playlistIndex=this.api.getPlaylistIndex());this.api.getStoryboardFormat&&(a.storyboardFormat=this.api.getStoryboardFormat());Sv(this,a)};
l.bd=function(a){Sv(this,{playbackQuality:a})};
l.cd=function(a){Sv(this,{playbackRate:a})};
l.Yc=function(){for(var a=this.api.getOptions(),b={namespaces:a},c=0,d=a.length;c<d;c++){var e=a[c],f=this.api.getOptions(e);b[e]={options:f};for(var g=0,h=f.length;g<h;g++){var k=f[g],m=this.api.getOption(e,k);b[e][k]=m}}this.sendMessage("apiInfoDelivery",b)};
l.fd=function(){Sv(this,{muted:this.api.isMuted(),volume:this.api.getVolume()})};
l.ed=function(a){a={currentTime:a,videoBytesLoaded:this.api.getVideoBytesLoaded(),videoLoadedFraction:this.api.getVideoLoadedFraction(),currentTimeLastUpdated_:Date.now()/1E3,playbackRate:this.api.getPlaybackRate(),mediaReferenceTime:this.api.getMediaReferenceTime()};this.api.getProgressState&&(a.progressState=this.api.getProgressState());Sv(this,a)};
l.gd=function(){var a={sphericalProperties:this.api.getSphericalProperties()};Sv(this,a)};
l.dispose=function(){Qv.prototype.dispose.call(this);for(var a=0;a<this.listeners.length;a++){var b=this.listeners[a];this.api.removeEventListener(b.eventType,b.listener)}this.listeners=[]};function Xv(a){J.call(this);this.j={};this.started=!1;this.connection=a;this.connection.subscribe("command",this.ac,this)}
t(Xv,J);l=Xv.prototype;l.start=function(){this.started||this.i()||(this.started=!0,this.connection.va("RECEIVING"))};
l.va=function(a,b){this.started&&!this.i()&&this.connection.va(a,b)};
l.ac=function(a,b,c){if(this.started&&!this.i()){var d=b||{};switch(a){case "addEventListener":"string"===typeof d.event&&this.addListener(d.event);break;case "removeEventListener":"string"===typeof d.event&&this.removeListener(d.event);break;default:this.api.isReady()&&this.api.isExternalMethodAvailable(a,c||null)&&(b=Yv(a,b||{}),c=this.api.handleExternalCall(a,b,c||null),(c=Zv(a,c))&&this.va(a,c))}}};
l.addListener=function(a){if(!(a in this.j)){var b=this.Zc.bind(this,a);this.j[a]=b;this.addEventListener(a,b)}};
l.Zc=function(a,b){this.started&&!this.i()&&this.connection.va(a,this.ob(a,b))};
l.ob=function(a,b){if(null!=b)return{value:b}};
l.removeListener=function(a){a in this.j&&(this.removeEventListener(a,this.j[a]),delete this.j[a])};
l.C=function(){var a=this.connection;a.i()||li(a.j,"command",this.ac,this);this.connection=null;for(var b in this.j)this.j.hasOwnProperty(b)&&this.removeListener(b);J.prototype.C.call(this)};function $v(a,b){Xv.call(this,b);this.api=a;this.start()}
t($v,Xv);$v.prototype.addEventListener=function(a,b){this.api.addEventListener(a,b)};
$v.prototype.removeEventListener=function(a,b){this.api.removeEventListener(a,b)};
function Yv(a,b){switch(a){case "loadVideoById":return a=Uv(b),[a];case "cueVideoById":return a=Uv(b),[a];case "loadVideoByPlayerVars":return[b];case "cueVideoByPlayerVars":return[b];case "loadPlaylist":return a=Vv(b),[a];case "cuePlaylist":return a=Vv(b),[a];case "seekTo":return[b.seconds,b.allowSeekAhead];case "playVideoAt":return[b.index];case "setVolume":return[b.volume];case "setPlaybackQuality":return[b.suggestedQuality];case "setPlaybackRate":return[b.suggestedRate];case "setLoop":return[b.loopPlaylists];
case "setShuffle":return[b.shufflePlaylist];case "getOptions":return[b.module];case "getOption":return[b.module,b.option];case "setOption":return[b.module,b.option,b.value];case "handleGlobalKeyDown":return[b.keyCode,b.shiftKey,b.ctrlKey,b.altKey,b.metaKey,b.key,b.code]}return[]}
function Zv(a,b){switch(a){case "isMuted":return{muted:b};case "getVolume":return{volume:b};case "getPlaybackRate":return{playbackRate:b};case "getAvailablePlaybackRates":return{availablePlaybackRates:b};case "getVideoLoadedFraction":return{videoLoadedFraction:b};case "getPlayerState":return{playerState:b};case "getCurrentTime":return{currentTime:b};case "getPlaybackQuality":return{playbackQuality:b};case "getAvailableQualityLevels":return{availableQualityLevels:b};case "getDuration":return{duration:b};
case "getVideoUrl":return{videoUrl:b};case "getVideoEmbedCode":return{videoEmbedCode:b};case "getPlaylist":return{playlist:b};case "getPlaylistIndex":return{playlistIndex:b};case "getOptions":return{options:b};case "getOption":return{option:b}}}
$v.prototype.ob=function(a,b){switch(a){case "onReady":return;case "onStateChange":return{playerState:b};case "onPlaybackQualityChange":return{playbackQuality:b};case "onPlaybackRateChange":return{playbackRate:b};case "onError":return{errorCode:b}}return Xv.prototype.ob.call(this,a,b)};
$v.prototype.C=function(){Xv.prototype.C.call(this);delete this.api};function aw(a){a=void 0===a?!1:a;J.call(this);this.j=new K(a);le(this,this.j)}
Za(aw,J);aw.prototype.subscribe=function(a,b,c){return this.i()?0:this.j.subscribe(a,b,c)};
aw.prototype.m=function(a,b){this.i()||this.j.oa.apply(this.j,arguments)};function bw(a,b,c){aw.call(this);this.l=a;this.destination=b;this.id=c}
t(bw,aw);bw.prototype.va=function(a,b){this.i()||this.l.va(this.destination,this.id,a,b)};
bw.prototype.C=function(){this.destination=this.l=null;aw.prototype.C.call(this)};function cw(a,b,c){J.call(this);this.destination=a;this.origin=c;this.j=$p(window,"message",this.l.bind(this));this.connection=new bw(this,a,b);le(this,this.connection)}
t(cw,J);cw.prototype.va=function(a,b,c,d){this.i()||a!==this.destination||(a={id:b,command:c},d&&(a.data=d),this.destination.postMessage(qg(a),this.origin))};
cw.prototype.l=function(a){var b;if(b=!this.i())if(b=a.origin===this.origin)a:{b=this.destination;do{b:{var c=a.source;do{if(c===b){c=!0;break b}if(c===c.parent)break;c=c.parent}while(null!=c);c=!1}if(c){b=!0;break a}b=b.opener}while(null!=b);b=!1}if(b&&(b=a.data,"string"===typeof b)){try{b=JSON.parse(b)}catch(d){return}b.command&&(c=this.connection,c.i()||c.m("command",b.command,b.data,a.origin))}};
cw.prototype.C=function(){aq(this.j);this.destination=null;J.prototype.C.call(this)};function dw(a){a=a||{};var b={},c={};this.url=a.url||"";this.args=a.args||tb(b);this.assets=a.assets||{};this.attrs=a.attrs||tb(c);this.fallback=a.fallback||null;this.fallbackMessage=a.fallbackMessage||null;this.html5=!!a.html5;this.disable=a.disable||{};this.loaded=!!a.loaded;this.messages=a.messages||{}}
dw.prototype.clone=function(){var a=new dw,b;for(b in this)if(this.hasOwnProperty(b)){var c=this[b];"object"==Pa(c)?a[b]=tb(c):a[b]=c}return a};var ew=/cssbin\/(?:debug-)?([a-zA-Z0-9_-]+?)(?:-2x|-web|-rtl|-vfl|.css)/;function fw(a){a=a||"";if(window.spf){var b=a.match(ew);spf.style.load(a,b?b[1]:"",void 0)}else gw(a)}
function gw(a){var b=hw(a),c=document.getElementById(b),d=c&&dv(c,"loaded");d||c&&!d||(c=iw(a,b,function(){dv(c,"loaded")||(bv(c),pq(b),Qk(Ya(qq,b),0))}))}
function iw(a,b,c){var d=document.createElement("link");d.id=b;d.onload=function(){c&&setTimeout(c,0)};
a=Jb(a);ec(d,a);(document.getElementsByTagName("head")[0]||document.body).appendChild(d);return d}
function hw(a){var b=bf("A");Db("This URL is never added to the DOM");dc(b,new Mb(a,Nb));a=b.href.replace(/^[a-zA-Z]+:\/\//,"//");return"css-"+ic(a)}
;function jw(){J.call(this);this.j=[]}
t(jw,J);jw.prototype.C=function(){for(;this.j.length;){var a=this.j.pop();a.target.removeEventListener(a.name,a.callback,void 0)}J.prototype.C.call(this)};function kw(){jw.apply(this,arguments)}
t(kw,jw);function lw(a,b,c,d){J.call(this);var e=this;this.v=b;this.webPlayerContextConfig=d;this.da=!1;this.api={};this.W=this.s=null;this.K=new K;this.j={};this.R=this.X=this.elementId=this.qa=this.config=null;this.P=!1;this.m=this.F=null;this.ka={};this.Pa=["onReady"];this.lastError=null;this.Ea=NaN;this.J={};this.Qa=new kw(this);this.T=0;this.l=this.o=a;le(this,this.K);mw(this);nw(this);le(this,this.Qa);c?this.T=Qk(function(){e.loadNewVideoConfig(c)},0):d&&(ow(this),pw(this))}
t(lw,J);l=lw.prototype;l.getId=function(){return this.v};
l.loadNewVideoConfig=function(a){if(!this.i()){this.T&&(Rk(this.T),this.T=0);var b=a||{};b instanceof dw||(b=new dw(b));this.config=b;this.setConfig(a);pw(this);this.isReady()&&qw(this)}};
function ow(a){var b;a.webPlayerContextConfig?b=a.webPlayerContextConfig.rootElementId:b=a.config.attrs.id;a.elementId=b||a.elementId;"video-player"===a.elementId&&(a.elementId=a.v,a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.v:a.config.attrs.id=a.v);var c;(null==(c=a.l)?void 0:c.id)===a.elementId&&(a.elementId+="-player",a.webPlayerContextConfig?a.webPlayerContextConfig.rootElementId=a.elementId:a.config.attrs.id=a.elementId)}
l.setConfig=function(a){this.qa=a;this.config=rw(a);ow(this);if(!this.X){var b;this.X=sw(this,(null==(b=this.config.args)?void 0:b.jsapicallback)||"onYouTubePlayerReady")}this.config.args?this.config.args.jsapicallback=null:this.config.args={jsapicallback:null};var c;if(null==(c=this.config)?0:c.attrs)a=this.config.attrs,(b=a.width)&&this.l&&(this.l.style.width=Gh(Number(b)||b)),(a=a.height)&&this.l&&(this.l.style.height=Gh(Number(a)||a))};
function qw(a){if(a.config&&!0!==a.config.loaded)if(a.config.loaded=!0,!a.config.args||"0"!==a.config.args.autoplay&&0!==a.config.args.autoplay&&!1!==a.config.args.autoplay){var b;a.api.loadVideoByPlayerVars(null!=(b=a.config.args)?b:null)}else a.api.cueVideoByPlayerVars(a.config.args)}
function tw(a){var b=!0,c=uw(a);c&&a.config&&(a=vw(a),b=dv(c,"version")===a);return b&&!!B("yt.player.Application.create")}
function pw(a){if(!a.i()&&!a.P){var b=tw(a);if(b&&"html5"===(uw(a)?"html5":null))a.R="html5",a.isReady()||ww(a);else if(xw(a),a.R="html5",b&&a.m&&a.o)a.o.appendChild(a.m),ww(a);else{a.config&&(a.config.loaded=!0);var c=!1;a.F=function(){c=!0;var d=yw(a,"player_bootstrap_method")?B("yt.player.Application.createAlternate")||B("yt.player.Application.create"):B("yt.player.Application.create");var e=a.config?rw(a.config):void 0;d&&d(a.o,e,a.webPlayerContextConfig);ww(a)};
a.P=!0;b?a.F():(hv(vw(a),a.F),(b=zw(a))&&fw(b),Aw(a)&&!c&&z("yt.player.Application.create",null))}}}
function uw(a){var b=af(a.elementId);!b&&a.l&&a.l.querySelector&&(b=a.l.querySelector("#"+a.elementId));return b}
function ww(a){if(!a.i()){var b=uw(a),c=!1;b&&b.getApiInterface&&b.getApiInterface()&&(c=!0);if(c){a.P=!1;if(!yw(a,"html5_remove_not_servable_check_killswitch")){var d;if((null==b?0:b.isNotServable)&&a.config&&(null==b?0:b.isNotServable(null==(d=a.config.args)?void 0:d.video_id)))return}Bw(a)}else a.Ea=Qk(function(){ww(a)},50)}}
function Bw(a){mw(a);a.da=!0;var b=uw(a);if(b){a.s=Cw(a,b,"addEventListener");a.W=Cw(a,b,"removeEventListener");var c=b.getApiInterface();c=c.concat(b.getInternalApiInterface());for(var d=a.api,e=0;e<c.length;e++){var f=c[e];d[f]||(d[f]=Cw(a,b,f))}}for(var g in a.j)a.j.hasOwnProperty(g)&&a.s&&a.s(g,a.j[g]);qw(a);a.X&&a.X(a.api);a.K.oa("onReady",a.api)}
function Cw(a,b,c){var d=b[c];return function(){var e=Ka.apply(0,arguments);try{return a.lastError=null,d.apply(b,e)}catch(f){"sendAbandonmentPing"!==c&&(f.params=c,a.lastError=f,Gr(f))}}}
function mw(a){a.da=!1;if(a.W)for(var b in a.j)a.j.hasOwnProperty(b)&&a.W(b,a.j[b]);for(var c in a.J)a.J.hasOwnProperty(c)&&Rk(Number(c));a.J={};a.s=null;a.W=null;b=a.api;for(var d in b)b.hasOwnProperty(d)&&(b[d]=null);b.addEventListener=function(e,f){a.addEventListener(e,f)};
b.removeEventListener=function(e,f){a.removeEventListener(e,f)};
b.destroy=function(){a.dispose()};
b.getLastError=function(){return a.getLastError()};
b.getPlayerType=function(){return a.getPlayerType()};
b.getCurrentVideoConfig=function(){return a.qa};
b.loadNewVideoConfig=function(e){a.loadNewVideoConfig(e)};
b.isReady=function(){return a.isReady()}}
l.isReady=function(){return this.da};
function nw(a){a.addEventListener("WATCH_LATER_VIDEO_ADDED",function(b){pq("WATCH_LATER_VIDEO_ADDED",b)});
a.addEventListener("WATCH_LATER_VIDEO_REMOVED",function(b){pq("WATCH_LATER_VIDEO_REMOVED",b)})}
l.addEventListener=function(a,b){var c=this,d=sw(this,b);d&&(0<=eb(this.Pa,a)||this.j[a]||(b=Dw(this,a),this.s&&this.s(a,b)),this.K.subscribe(a,d),"onReady"===a&&this.isReady()&&Qk(function(){d(c.api)},0))};
l.removeEventListener=function(a,b){this.i()||(b=sw(this,b))&&li(this.K,a,b)};
function sw(a,b){var c=b;if("string"===typeof b){if(a.ka[b])return a.ka[b];c=function(){var d=Ka.apply(0,arguments),e=B(b);if(e)try{e.apply(y,d)}catch(f){Fr(f)}};
a.ka[b]=c}return c?c:null}
function Dw(a,b){var c="ytPlayer"+b+a.v;a.j[b]=c;y[c]=function(d){var e=Qk(function(){if(!a.i()){try{a.K.oa(b,null!=d?d:void 0)}catch(h){Gr(new R("PlayerProxy error when creating global callback",{error:h,event:b,playerId:a.v,data:d}))}var f=a.J,g=String(e);g in f&&delete f[g]}},0);
qb(a.J,String(e))};
return c}
l.getPlayerType=function(){return this.R||(uw(this)?"html5":null)};
l.getLastError=function(){return this.lastError};
function xw(a){a.cancel();mw(a);a.R=null;a.config&&(a.config.loaded=!1);var b=uw(a);b&&(tw(a)||!Aw(a)?a.m=b:(b&&b.destroy&&b.destroy(),a.m=null));if(a.o)for(a=a.o;b=a.firstChild;)a.removeChild(b)}
l.cancel=function(){this.F&&nv(vw(this),this.F);Rk(this.Ea);this.P=!1};
l.C=function(){xw(this);if(this.m&&this.config&&this.m.destroy)try{this.m.destroy()}catch(b){Fr(b)}this.ka=null;for(var a in this.j)this.j.hasOwnProperty(a)&&(y[this.j[a]]=null);this.qa=this.config=this.api=null;delete this.o;delete this.l;J.prototype.C.call(this)};
function Aw(a){var b,c;a=null==(b=a.config)?void 0:null==(c=b.args)?void 0:c.fflags;return!!a&&-1!==a.indexOf("player_destroy_old_version=true")}
function vw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.jsUrl:(a=a.config.assets)?a.js:""}
function zw(a){return a.webPlayerContextConfig?a.webPlayerContextConfig.cssUrl:(a=a.config.assets)?a.css:""}
function yw(a,b){if(a.webPlayerContextConfig)var c=a.webPlayerContextConfig.serializedExperimentFlags;else{var d;if(null==(d=a.config)?0:d.args)c=a.config.args.fflags}return"true"===Dk(c||"","&")[b]}
function rw(a){for(var b={},c=p(Object.keys(a)),d=c.next();!d.done;d=c.next()){d=d.value;var e=a[d];b[d]="object"===typeof e?tb(e):e}return b}
;var Ew={},Fw="player_uid_"+(1E9*Math.random()>>>0);function Gw(a,b,c){var d="player";c=void 0===c?!0:c;d="string"===typeof d?af(d):d;var e=Fw+"_"+Sa(d),f=Ew[e];if(f&&c)return Hw(a,b)?f.api.loadVideoByPlayerVars(a.args||null):f.loadNewVideoConfig(a),f.api;f=new lw(d,e,a,b);Ew[e]=f;pq("player-added",f.api);me(f,function(){delete Ew[f.getId()]});
return f.api}
function Hw(a,b){return b&&b.serializedExperimentFlags?b.serializedExperimentFlags.includes("web_player_remove_playerproxy=true"):a&&a.args&&a.args.fflags?a.args.fflags.includes("web_player_remove_playerproxy=true"):!1}
;var Iw=null,Jw=null,Kw=null;function Lw(){Mw()}
function Nw(){Mw()}
function Mw(){var a=Iw.getVideoData(1);a=a.title?a.title+" - YouTube":"YouTube";document.title!==a&&(document.title=a)}
;function Ow(a,b,c){a="ST-"+ic(a).toString(36);b=b?rc(b):"";c=c||5;ms()&&gl(a,b,c)}
;function Pw(a,b,c){b=void 0===b?{}:b;c=void 0===c?!1:c;var d=L("EVENT_ID");d&&(b.ei||(b.ei=d));if(b){d=a;var e=void 0===e?!0:e;var f=L("VALID_SESSION_TEMPDATA_DOMAINS",[]),g=mc(window.location.href);g&&f.push(g);g=mc(d);if(0<=eb(f,g)||!g&&0==d.lastIndexOf("/",0))if(M("autoescape_tempdata_url")&&(f=document.createElement("a"),dc(f,d),d=f.href),d&&(d=nc(d),f=d.indexOf("#"),d=0>f?d:d.slice(0,f)))if(e&&!b.csn&&(b.itct||b.ved)&&(b=Object.assign({csn:Yr()},b)),h){var h=parseInt(h,10);isFinite(h)&&0<h&&
Ow(d,b,h)}else Ow(d,b)}if(c)return!1;if((window.ytspf||{}).enabled)spf.navigate(a);else{var k=void 0===k?{}:k;var m=void 0===m?"":m;var q=void 0===q?window:q;c=q.location;a=tc(a,k)+m;var r=void 0===r?Fh:r;a:{r=void 0===r?Fh:r;for(k=0;k<r.length;++k)if(m=r[k],m instanceof Dh&&m.isValid(a)){r=new Mb(a,Nb);break a}r=void 0}c.href=Ob(r||Qb)}return!0}
;z("yt.setConfig",nk);z("yt.config.set",nk);z("yt.setMsg",cs);z("yt.msgs.set",cs);z("yt.logging.errors.log",Fr);
z("writeEmbed",function(){var a=L("PLAYER_CONFIG");if(!a){var b=L("PLAYER_VARS");b&&(a={args:b})}vs(!0);"gvn"===a.args.ps&&(document.body.style.backgroundColor="transparent");a.attrs||(a.attrs={width:"100%",height:"100%",id:"video-player"});var c=document.referrer;b=L("POST_MESSAGE_ORIGIN");window!==window.top&&c&&c!==document.URL&&(a.args.loaderUrl=c);M("embeds_js_api_set_1p_cookie")&&(c=Ik(window.location.href),c.embedsTokenValue&&(a.args.embedsTokenValue=c.embedsTokenValue));Ut();if((c=L("WEB_PLAYER_CONTEXT_CONFIGS"))&&
"WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER"in c){c=c.WEB_PLAYER_CONTEXT_CONFIG_ID_EMBEDDED_PLAYER;if(!c.serializedForcedExperimentIds){var d=Ik(window.location.href);d.forced_experiments&&(c.serializedForcedExperimentIds=d.forced_experiments)}Iw=Gw(a,c,!1)}else Iw=Gw(a);Iw.addEventListener("onVideoDataChange",Lw);Iw.addEventListener("onReady",Nw);a=L("POST_MESSAGE_ID","player");L("ENABLE_JS_API")?Kw=new Wv(Iw):L("ENABLE_POST_API")&&"string"===typeof a&&"string"===typeof b&&(Jw=new cw(window.parent,
a,b),Kw=new $v(Iw,Jw.connection));qv();M("ytidb_create_logger_embed_killswitch")||$l();a={};Kv||(Kv=new Jv);Kv.install((a.flush_logs={callback:function(){Hq()}},a));
M("embeds_web_enable_new_nwl")?Io():Qo();M("ytidb_clear_embedded_player")&&Nh.S(function(){var e;if(!Au){Fs||(Fs=new Cs);var f=Fs;var g={Tc:zu,lc:yu};f.providers.set(g.Tc,g);g={Kb:{feedbackEndpoint:Qs(uu),modifyChannelNotificationPreferenceEndpoint:Qs(vu),playlistEditEndpoint:Qs(wu),subscribeEndpoint:Qs(su),unsubscribeEndpoint:Qs(tu),webPlayerShareEntityServiceEndpoint:Qs(xu)}};var h=M("web_enable_client_location_service")?Ms.getInstance():void 0,k={};h&&(k.client_location=h);if(void 0===m){ws.i||
(ws.i=new ws);var m=ws.i}void 0===e&&(e=f.resolve(zu));hu(g,e,m,k);Au=gu.i}av()})});
var Qw=vk(function(){Zt();var a=jl.getInstance(),b=ml(119),c=1<window.devicePixelRatio;if(document.body&&Zh(document.body,"exp-invert-logo"))if(c&&!Zh(document.body,"inverted-hdpi")){var d=document.body;if(d.classList)d.classList.add("inverted-hdpi");else if(!Zh(d,"inverted-hdpi")){var e=Xh(d);Yh(d,e+(0<e.length?" inverted-hdpi":"inverted-hdpi"))}}else!c&&Zh(document.body,"inverted-hdpi")&&$h();if(b!=c){b="f"+(Math.floor(119/31)+1);d=nl(b)||0;d=c?d|67108864:d&-67108865;0==d?delete il[b]:(c=d.toString(16),
il[b]=c.toString());c=!0;M("web_secure_pref_cookie_killswitch")&&(c=!1);b=a.i;d=[];for(var f in il)d.push(f+"="+encodeURIComponent(String(il[f])));gl(b,d.join("&"),63072E3,a.j,c)}Ku.i||(Ku.i=new Ku);a=Ku.i;f=16623;var g=void 0===g?{}:g;Object.values(ds).includes(f)||(Gr(new R("createClientScreen() called with a non-page VE",f)),f=83769);g.isHistoryNavigation||a.i.push({rootVe:f,key:g.key||""});a.o=[];a.N=[];g.Nb?Nu(a,f,g):Ou(a,f,g)}),Rw=vk(function(){Iw&&Iw.sendAbandonmentPing&&Iw.sendAbandonmentPing();
L("PL_ATT")&&yv.dispose();for(var a=Nh,b=0,c=ov.length;b<c;b++)a.fa(ov[b]);ov.length=0;mv("//static.doubleclick.net/instream/ad_status.js");pv=!1;nk("DCLKSTAT",0);ke(Kw,Jw);Iw&&(Iw.removeEventListener("onVideoDataChange",Lw),Iw.destroy())});
window.addEventListener?(window.addEventListener("load",Qw),window.addEventListener("pagehide",Rw)):window.attachEvent&&(window.attachEvent("onload",Qw),window.attachEvent("onunload",Rw));z("yt.abuse.player.botguardInitialized",B("yt.abuse.player.botguardInitialized")||zv);z("yt.abuse.player.invokeBotguard",B("yt.abuse.player.invokeBotguard")||Av);z("yt.abuse.dclkstatus.checkDclkStatus",B("yt.abuse.dclkstatus.checkDclkStatus")||rv);z("yt.player.exports.navigate",B("yt.player.exports.navigate")||Pw);
z("yt.util.activity.init",B("yt.util.activity.init")||eq);z("yt.util.activity.getTimeSinceActive",B("yt.util.activity.getTimeSinceActive")||hq);z("yt.util.activity.setTimestamp",B("yt.util.activity.setTimestamp")||fq);}).call(this);
