<ul><li><a href="#english">English</a></li><li><a href="#arabic">عربي</a></li> </ul><hr>
<h1 id="english">sy-math.js  -  JavaScript Library That Extends The Native Math Object With Some Powerful Methods</h1>

<h2>Introduction</h2>
<p><b>sy-math.js</b> Is A Simple,Easy-To-Use,Lightweight JavaScript Library That Extends The Native JavaScript <code>Math</code> Object With Some Powerful Methods.</p><p>The Main Purpose Of <b>sy-math.js</b> Is To Simplify Some Mathematician Tasks In JavaScript,For Example,Instead Of Write Several Lines To Figure Out If A Number Is Primitive Or Not,<b>sy-math.js</b> Provides You With A Built-in Method Called <code>isPrimitive()</code> To Do This.</p><h2>Installation</h2><p>Just Like Any Other JavaScript Library,To Include <b>sy-math.js</b> Just Use A <code>&lt;script&gt;</code>
Tag And Let  The <code>src</code>
Attribute Point To The Library,For Example:</p>
```html
<script src="includes/sy-math.js"></script>
```

<h2>Usage</h2><p>Take The <code>Math</code> Object Then Use One Of The Supported Methods In This Library With It,For Example,If You Want To Use The <code>sum()</code> Method,You Can Do The Following:</p>
```js
Math.sum(1,9,7); //Output 17
```
<h2>Supported Methods:</h2>
<h3><code>isEven()</code>,<code>isOdd()</code>,<code>EvenOrOdd()</code>:</h3>
<p>These Methods Can Be Used To Check Whether The Passed Number Is Even,Or Odd,For Example:</p>
```js
Math.isEven(8); //Output false
Math.isOdd(12); //Output true
Math.EvenOrOdd(9); //Output "Even"
Math.EvenOrOdd(16); //Output "Odd"
```
.
