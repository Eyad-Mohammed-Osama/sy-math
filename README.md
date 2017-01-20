<ul>
<li><a href="#english">English</a></li>
<li><a href="#arabic">عربي</a></li> 
</ul>
<hr/>
<h1 id="english">sy-math.js  -  JavaScript Library That Extends The Native Math Object With Some Powerful Methods</h1>
<h2>Introduction</h2>
<p><b>sy-math.js</b> Is A Simple,Easy-To-Use,Lightweight JavaScript Library That Extends The Native JavaScript <code>Math</code> Object With Some Powerful Methods.</p>
<p>The Main Purpose Of <b>sy-math.js</b> Is To Simplify Some Mathematician Tasks In JavaScript,For Example,Instead Of Write Several Lines To Figure Out If A Number Is Primitive Or Not,<b>sy-math.js</b> Provides You With A Built-in Method Called <code>isPrimitive()</code> To Do This.</p>
<h2>Installation</h2>
<p>Just Like Any Other JavaScript Library,To Include <b>sy-math.js</b> Just Use A <code>&lt;script&gt;</code> Tag And Let  The <code>src</code> Attribute Point To The Library,For Example:</p>
```html
<script src="includes/sy-math.js"></script>
```
<h2>Usage</h2>
<p>Take The <code>Math</code> Object Then Use One Of The Supported Methods In This Library With It,For Example,If You Want To Use The <code>sum()</code> Method,You Can Do The Following:</p>
```js
Math.sum(1,9,7); //Output 17
```
<h2>Supported Methods:</h2>
<h3><code>isEven()</code>,<code>isOdd()</code>,<code>EvenOrOdd()</code>:</h3>
<p>These Methods Can Be Used To Check Whether The Passed Number In The Argument Is Even,Or Odd,For Example:</p>
```js
Math.isEven(8); //Output false
Math.isOdd(12); //Output true
Math.EvenOrOdd(9); //Output "Even"
Math.EvenOrOdd(16); //Output "Odd"
```
<p><code>isEven()</code> Returns <span style="color:blue">true</span> If The Passed Number Is Even,And <span style="color:blue">false</span> Otherwise.</p>
<p><code>isOdd()</code> Returns <span style="color:blue">true</span> If The Passed Number Is Odd,And <span style="color:blue">false</span> Otherwise.</p>
<p><code>EvenOrOdd()</code> Returns <span style="color:blue">"Even"</span> If The Passed Number Is Even,And <span style="color:blue">"Odd"</span> Otherwise.</p>

<h3><code>isDividable()</code>:</h3>
<p>This Method Can Be Used To Check Whether The Passed Number In The First Argument Is Dividable On The Passed Number In The Second Number.</p><h4>Syntax:</h4>
```js
Math.isDividable(The_Number_To_Divide,The_Number_To_Divide_On);
```
<h4>Example:</h4>
```js
Math.isDividable(9,4); //Output false
Math.isDividable(10,2); //Output true
```
<p><code>isDividable()</code> Returns <span style="color:blue">true</span> If The Passed Number In The First Argument Is Dividable On The Passed Number In The Second Number,And <span style="color:blue">false</span> Otherwise.</p>

<h3><code>factorial()</code>:</h3>
<p>This Method Can Be Used To Get The Factorial Value For The Passed Number.</p><h4>Syntax:</h4>
```js
Math.factorial(number);
```
<h4>Example:</h4>
```js
Math.factorial(7); //Output 5040 Because 7!=7x6x5x4x3x2x1
```
<p><code>factorial()</code> Returns A Number That Indicates The Factorial Value For The Passed Number.</p>

<h3><code>root()</code>:</h3>
<p>This Method Can Be Used To Get The Nth Root For The Passed Number In The First Argument,While The Degree Of The Root Can Be Passed In The Second Argument.</p>
<h4>Syntax:</h4>
```js
Math.root(number,root_degree);
```
<h4>Example:</h4>
```js
Math.root(8,3); //Output 2
Math.root(15625,2); //Output 125
```
<p><code>root()</code> Returns A Number That Indicates The Nth Root For The Passed Number.</p>
