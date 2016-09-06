/*
* 16-09-06 @wuji
*
*/


内容主要分为5个部分：

1、张鑫续为IE7，IE8写的js扩展，使其支持标准DOM和JS操作。
    注意：getElementsByClassName,
        querySelector等
    要由document开始几联使用，无法直接在某个元素上使用它们。

2、由于IE8支持访问Element类型，故在Element.prototype中添加以下方法：
    getElementsByClassName,
    addEventListener,
    removeEventListener,
    dispatchEvent,

3、使其支持HTML5元素，如：
    header, footer等。

4、Sizzle CSS Selector Engine v@VERSION
   http://sizzlejs.com/

5、json2
    使IE7，IE8支持JSON.parse 和 JSON.stringify
