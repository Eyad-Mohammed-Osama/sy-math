<h1>sy-math.js  -  JavaScript Library That Extends The Native Math Object With Some Powerful Methods</h1>

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

<p>These Methods Can Be Used To Check Whether The Passed Number In The Argument Is Even,Or Odd.</p>
<h4>Syntax:</h4>
```js
Math.isEven(number);
Math.isOdd(number);
Math.EvenOrOdd(number);
```

<h4>Example:</h4>
```js
Math.isEven(8); //Output false
Math.isOdd(12); //Output true
Math.EvenOrOdd(9); //Output "Even"
Math.EvenOrOdd(16); //Output "Odd"
```

<h3><code>isDividable()</code>:</h3>

<p>This Method Can Be Used To Check Whether The Passed Number In The First Argument Is Dividable On The Passed Number In The Second Number.</p>
<h4>Syntax:</h4>

```js
Math.isDividable(The_Number_To_Divide,The_Number_To_Divide_On);
```

<h4>Example:</h4>

```js
Math.isDividable(9,4); //Output false
Math.isDividable(10,2); //Output true
```

<h3><code>factorial()</code>:</h3>
<p>This Method Can Be Used To Get The Factorial Value For The Passed Number.</p>
<h4>Syntax:</h4>

```js
Math.factorial(number);
```
<h4>Example:</h4>

```js
Math.factorial(7); //Output 5040 Because 7!=7x6x5x4x3x2x1
```


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


<h3><code>sum()</code>:</h3>

<p>This Method Can Be Used To Get The Sum Of A Finite Number Of Numbers.</p>

<h4>Syntax:</h4>

```js
Math.sum(num_1,num_2,num_3,...,num_n);
```

<h4>Example:</h4>

```js
Math.sum(8,3,11,27,5); //Output 54
```


 <h3><code>multiply()</code>:</h3>

<p>This Method Can Be Used To Get The Multiplication Of A Finite Number Of Numbers.</p>

<h4>Syntax:</h4>

```js
Math.multiply(num_1,num_2,num_3,...,num_n);
```

<h4>Example:</h4>

```js
Math.multiply(8,3,2); //Output 48
```

 
 <h3><code>getAverage()</code>:</h3>

<p>This Method Can Be Used To Get The Average Of A Finite Number Of Numbers.</p>

<h4>Syntax:</h4>

```js
Math.getAverage(num_1,num_2,num_3,...,num_n);
```

<h4>Example:</h4>

```js
Math.getAverage(11,17,21,3); //Output 13
```


<h3><code>isPrimitive()</code>:</h3>
<p>This Method Can Be Used To Check Whether The Passed Number Is Primitive Or Not.</p>

<h4>Syntax:</h4>

```js
Math.isPrimitive(number);
```

<h4>Example:</h4>

```js
Math.isPrimitive(11); //Output true
Math.isPrimitive(24); //Output false
```



 <h3><code>getFloatDigits()</code>:</h3>

<p>This Method Can Be Used To Get The Digits Of A Float Type Number.</p>

<h4>Syntax:</h4>

```js
Math.getFloatDigits(number);
```

<h4>Example:</h4>

```js
Math.getFloatDigits(12.956); //Output 0.956
```


 <h3><code>factors()</code>:</h3>

<p>This Method Can Be Used To Get The Factors Of A Positive Integer.</p>

<h4>Syntax:</h4>

```js
Math.factors(number)[factor_index];
//Or
Math.factors(number);
```

<h4>Example:</h4>

```js
Math.factors(24); //Output 1,2,3,4,6,8,12,24
Math.factors(24)[0]; //Output 1
Math.factors(24)[4]; //Output 8
```


 <h3><code>factorsNegative()</code>:</h3>

<p>Much Like <code>factors()</code> Method,But This Method Can Be Used To Get The Factors (Even Negative Factors) Of A Positive Integer.</p>

<h4>Syntax:</h4>

```js
Math.factorsNegative(number)[factor_index];
//Or
Math.factorsNegative(number);
```

<h4>Example:</h4>

```js
Math.factors(24); //Output 1,2,3,4,6,8,12,24,-1,-2,-3,-4,-6,-8,-12,-24
Math.factors(24)[0]; //Output 1
Math.factors(24)[10]; //Output -3
```


<h2>New Features In Version 2.0:</h2>
<h3><code>getRemainder()</code>:</h3>
<p>This Method Can Be Used To Calculate The Remainder Of The Division Of Two Integer Numbers.</p>
<h4>Syntax:</h4>

```js
Math.getRemainder(TheNumberYouWantToDivide,TheNumberYouWantToDivideOn);
```

<h4>Example:</h4>

```js
Math.getRemainder(9,7); //Output 2
Math.getRemainder(10,3); //Output 1
```

 <h3><code>randomPercentage()</code>:</h3>
<p>This Method Can Be Used To Get A Random Integer Number Between 0 And 100 (Including 0 And 100).</p>
<h4>Syntax:</h4>

```js
Math.randomPercentage();
```

<h4>Example:</h4>

```js
Math.randomPercentage(); //Might Output 2,Or 47,Or ...
```


 <h3><code>randomUntil()</code>:</h3>
<p>This Method Can Be Used To Get A Random Integer Number Between 0 And The Specific Limit (Including 0 And The Specific Limit).</p>
<h4>Syntax:</h4>

```js
Math.randomUntil(limit);
```

<h4>Example:</h4>

```js
Math.randomUntil(20); //Output A Random Number Between 0 And 20...
```


<h3>Trigonometric Functions:</h3>
<p>In This Version,Trigonometric Functions Were Added.</p>
<p><b>sy-math.js</b> Is Designed To Deal With Trigonometric Functions In Such A Way That Enables The User To Control The Accuracy Of The Number In The Output.<b>Optionally</b>,That Can Be Done Through The Following Line:</p>

```js
Math._GLOBAL_.Trigonometric.resolution=number;
```

<p>Where <b>number</b> Is A Positive Integer That Indicates The Accuracy Of The Calculations.</p>
<p>By Default,The Accuracy Take 8 As A Value If You Don't Specify It,So Don't Worry.</p>
<p>Also,You Might Want To Use Degrees Instead Of Radians (Because Radian Is The Default Unit),That Is Also Possible Through This Line:</p>

```js
Math._GLOBAL_.Trigonometric.angleUnit="degree";
```

<p>The Previous Line Results In Something Similar To:</p>

```js
Math.Trigonometric.sin(90); //Output 1
Math.Trigonometric.cos(60); //Output 0.5
```

<h2>A List Of Supported Trigonometric Methods:</h2>
<p>To Use These Methods,You Should Access Them From The <b>Math.Trigonometric</b> Object.</p>
 <h3><code>sin()</code>:</h3> 
<p>This Method Can Be Used To Calculate The <b>Sine</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>

```js
Math.Trigonometric.sin(angle);
```

<h4>Example:</h4>

```js
Math.Trigonometric.sin(Math.PI/4); //Output 0.70710678118654746172 
```

 <h3><code>cos()</code>:</h3> 
<p>This Method Can Be Used To Calculate The <b>Cosine</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.cos(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.cos(Math.PI/6); //Output 0.86602540378443859659 
```

 
 <h3><code>tan()</code>:</h3> 
<p>This Method Can Be Used To Calculate The <b>Tangent</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.tan(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.tan(Math.PI/3); //Output 1.73205080756887541682 
```


 <h3><code>cot()</code>:</h3> 
<p>This Method Can Be Used To Calculate The <b>Cotangent</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.cot(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.cot(Math.PI/3); //Output 0.57735026918962639719 
``` 


 <h3><code>sec()</code>:</h3> 
<p>This Method Can Be Used To Calculate The <b>Secant</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.sec(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.sec(Math.PI/3); //Output 2
``` 


 <h3><code>cosec()</code> & <code>csc()</code>:</h3> 
<p>These Two Methods Are Exactly The Same,And Both Can Be Used To Calculate The <b>Cosecant</b> Of A Specific Angle.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.cosec(angle);
//Or
Math.Trigonometric.csc(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.cosec(Math.PI/4); //Output 1.41421356237309514547 
Math.Trigonometric.csc(Math.PI/4); //Output 1.41421356237309514547 
``` 

 <h3><code>toRadian()</code>:</h3> 
<p>This Method Can Be Used To Convert A Specific Angle To Radian.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.toRadian(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.toRadian(75); //Output 1.3089969389957472 
``` 

 <h3><code>toDegree()</code>:</h3> 
<p>This Method Can Be Used To Convert A Specific Angle To Degree.</p>
<h4>Syntax:</h4>
```js
Math.Trigonometric.toDegree(angle);
```
<h4>Example:</h4>
```js
Math.Trigonometric.toDegree(Math.PI); //Output 180
Math.Trigonometric.toDegree(2.0943951023931953); //Output 120 
``` 


 <h3>Logarithmic Functions:</h3>
<p>In This Version,Logarithmic Functions Were Added.</p>
<p><b>sy-math.js</b> Is Designed To Deal With Logarithmic Functions In Such A Way That Enables The User To Control The Accuracy Of The Number In The Output.<b>Optionally</b>,That Can Be Done Through The Following Line:</p>
```js
Math._GLOBAL_.Logarithmic.resolution=number;
```
<p>Where <b>number</b> Is A Positive Integer That Indicates The Accuracy Of The Calculations.</p>
<p>By Default,The Accuracy Take 32 As A Value If You Don't Specify It,So Don't Worry.</p>
<h2>A List Of Supported Trigonometric Methods:</h2> 

<h3><code>ln()</code>:</h3>
<p>This Method Can Be Used To Calculate The Natural Logarithm (A Logarithm With Base <b>e</b>) For A Specific <b>Positive</b> Number.</p>
<h4>Syntax:</h4>
```js
Math.ln(number);
```
<h4>Example:</h4>
```js
Math.ln(2); //Output 0.69314718055308610634 
```

 <h3><code>log()</code>:</h3>
<p>This Method Can Be Used To Calculate The Logarithm With A Specific Base For A Specific <b>Positive</b> Number.</p>
<h4>Syntax:</h4>
```js
Math.log(number,base);
```
<p>This Method Has A <b>Dynamic</b> Behavior,So If You Pass One Argument To This Method,The Method Will Act Like <b>Math.ln()</b>.</p>
<h4>Example:</h4>
```js
Math.log(4); //Output 1.38628592311583864749 (Which Is The Same As Math.ln(4))
Math.log(2,10); //Output 0.30203362483321649634 
``` 


 <h3>Exponential Functions:</h3>
<p>In This Version,Exponential Functions Were Added.</p>
<p><b>sy-math.js</b> Is Designed To Deal With Exponential Functions In Such A Way That Enables The User To Control The Accuracy Of The Number In The Output.<b>Optionally</b>,That Can Be Done Through The Following Line:</p>
```js
Math._GLOBAL_.Exponential.resolution=number;
```
<p>Where <b>number</b> Is A Positive Integer That Indicates The Accuracy Of The Calculations.</p>
<p>By Default,The Accuracy Take 32 As A Value If You Don't Specify It,So Don't Worry.</p>
<h2>A List Of Supported Exponential Methods:</h2> 

<h3><code>e()</code>:</h3>
<p>This Method Can Be Used The To Calculate The Power Of Euler Number <b>e</b>.</p>
<h4>Syntax:</h4>
```js
Math.e(power);
```
<h4>Example:</h4>
```js
Math.e(1); //Output 2.71828182845904553488
Math.e(2); //Output 7.38905609893064863058 
```

 <h3><code>exp()</code>:</h3>
<p>This Method Can Be Used To Calculate The Power Of A Specific <b>Positive</b> Base.</p>
<h4>Syntax:</h4>
```js
Math.exp(base,power);
```
<p>This Method Has A <b>Dynamic</b> Behavior,So If You Pass One Argument To This Method,The Method Will Act Like <b>Math.e()</b>.</p>
<h4>Example:</h4>
```js
Math.exp(5); //Output 148.41315910257657151305 (Which Is The Same As Math.e(5))
Math.exp(2,4); //Output 16
``` 

<h2>Other Functions:</h2>

 <h3><code>isPositive()</code>:</h3>
<p>This Method Can Be Used The To Check Whether The Passed Number Is Positive Or Not.</p>
<h4>Syntax:</h4>
```js
Math.isPositive(number);
```
<h4>Example:</h4>
```js
Math.isPositive(10); //Output true
Math.isPositive(-6); //Output false
```


 <h3><code>isNegative()</code>:</h3>
<p>This Method Can Be Used The To Check Whether The Passed Number Is Negative Or Not.</p>
<h4>Syntax:</h4>
```js
Math.isNegative(number);
```
<h4>Example:</h4>
```js
Math.isNegative(-8); //Output true
Math.isNegative(17); //Output false
``` 

 <h3><code>PositiveOrNegative()</code>:</h3>
<p>This Method Can Be Used The To Check Whether The Passed Number Is Positive Or Negative.</p>
<h4>Syntax:</h4>
```js
Math.PositiveOrNegative(number);
```
<h4>Example:</h4>
```js
Math.PositiveOrNegative(15); //Output "Positive"
Math.PositiveOrNegative(-20); //Output "Negative"
``` 
<a href="http://www.wtfpl.net/" style="text-align:center;"><img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png"  width="80" height="15" alt="WTFPL" /></a>
