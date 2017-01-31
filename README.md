<ul>
<li><a href="#english">English</a></li>
<li><a href="#arabic">عربي</a></li> 
</ul>
<hr>
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

<p><code>isEven()</code> Returns <span style="color:blue">true</span> If The Passed Number Is Even,And <span style="color:blue">false</span> Otherwise.</p>

<p><code>isOdd()</code> Returns <span style="color:blue">true</span> If The Passed Number Is Odd,And <span style="color:blue">false</span> Otherwise.</p>

<p><code>EvenOrOdd()</code> Returns <span style="color:blue">"Even"</span> If The Passed Number Is Even,And <span style="color:blue">"Odd"</span> Otherwise.</p>

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
<p><code>isDividable()</code> Returns <span style="color:blue">true</span> If The Passed Number In The First Argument Is Dividable On The Passed Number In The Second Number,And <span style="color:blue">false</span> Otherwise.</p>

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
<p><code>sum()</code> Returns A Number That Indicates The Sum Of The Passed Numbers.</p>


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
<p><code>multiply()</code> Returns A Number That Indicates The Multiplication Of The Passed Numbers.</p>

 
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
<p><code>getAverage()</code> Returns A Number That Indicates The Average Of The Passed Numbers.</p>


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
<p><code>isPrimitive()</code> Returns <span style="color:blue">true</span> If The Passed Number Is Primitive,And <span style="color:blue">false</span> Otherwise.</p>



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
<p><code>getFloatDigits()</code> Returns A Float Type Number That Indicates The Digits Of The Passed Float Type Number.</p>


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
<p><code>factors()</code> Returns An Array Contains The Factors Of The Passed Number,So You Might Have To Define An Index After The Parentheses,Otherwise The Whole Array Will Be Returned.</p>


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
<p><code>factorsNegative()</code> Returns An Array Contains The Factors Of The Passed Number,So You Might Have To Define An Index After The Parentheses,Otherwise The Whole Array Will Be Returned.</p>

<hr>
<h1 id="arabic" dir="rtl">sy-math.js  -  مكتبة جافاسكريبت تقوم بتوسيع الكائن Math و تضيف له بعض الدوال الفعالة.
</h1>

<h2 dir="rtl">مقدمة</h2>

<p dir="rtl"><b>sy-math.js</b> هي مكتبة جافاسكريبت بسيطة و سهلة الإستخدام و صغيرة الحجم تقوم بتوسيع الكائن
 <code dir="ltr">Math</code> ببعض الدوال الفعالة.
</p>

<p dir="rtl">
الهدف الرئيسي من وراء مكتبة
 <b dir="ltr">sy-math.js</b> هو تبسيط بعض الأعمال الرياضية في لغة جافاسكريبت،على سبيل المثال،بدل أن تكتب عدة سطور برمجية لتكتشف إذا ما كان عدد ما أوليا أم لا،توفر لك مكتبة 
 <b dir="ltr">sy-math.js</b> دالة جاهزة للقيام بهذه المهمة و هي 
<code dir="ltr">isPrimitive()</code>.
</p>

<h2 dir="rtl">التثبيت</h2>

<p dir="rtl">
مثل أي مكتبة جافاسكريبت أخرى،لتضمين مكتبة 
 <b dir="ltr">sy-math.js</b> 
فقط قم بإستخدام وسم
<code>&lt;script&gt;</code>
و قم بتوجيه الخاصية 
<code>src</code>
إلى عنوان المكتبة،على سبيل المثال:
</p>
```html
<script src="includes/sy-math.js"></script>
```
<h2 dir="rtl">الإستخدام</h2>

<p dir="rtl">
عليك إستخدام أحد الدوال المدعومة في المكتبة مع الكائن 
 <b dir="ltr">Math</b>
،على سبيل المثال،إذا أردت إستخدام الدالة 
 <code dir="ltr">sum()</code> 
فعليك القيام بما يلي:
</p>

```js
Math.sum(1,9,7); //الناتج هو  17
```

 <h2>الدوال المدعومة:</h2>

<h3><code>isEven()</code>,<code>isOdd()</code>,<code>EvenOrOdd()</code>:</h3>

<p dir="rtl">
تستخدم هذه الدوال في التحقق مما إذا كان العدد المرر فرديا أو زوجيا.
</p>
<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.isEven(عدد);
Math.isOdd(عدد);
Math.EvenOrOdd(عدد);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.isEven(8); //النتيجة هي false
Math.isOdd(12); //النتيجة هي true
Math.EvenOrOdd(9); //النتيجة هي "Even"
Math.EvenOrOdd(16); //النتيجة هي "Odd"
```

<p dir="rtl"><code dir="ltr">isEven()</code> تعيد القيمة <span style="color:blue">true</span> 
إذا كان العدد الممرر فرديا،و تعيد القيمة
 <span style="color:blue">false</span> فيما عدا ذلك.
</p>

<p dir="rtl"><code dir="ltr">isOdd()</code> تعيد القيمة <span style="color:blue">true</span> إذا كان العدد الممرر زوجيا،و تعيد القيمة 
 <span style="color:blue">false</span> فيما عدا ذلك.
</p>

<p dir="rtl"><code dir="ltr">EvenOrOdd()</code> تعيد النص <span style="color:blue">"Even"</span>إذا كان العدد الممرر زوجيا,و تعيد القيمة
<span style="color:blue">"Odd"</span> فيما عدا ذلك.
</p>

 <h3><code>isDividable()</code>:</h3>

<p dir="rtl">
يمكن إستخدام هذه الدالة للتحقق مما إذا كان العدد الممرر في المعامل الأول يقبل القسمة على العدد الممرر في المعامل الثاني.
</p>
<h4 dir="rtl">الصيغة النحوية:</h4>

```js
Math.isDividable(العدد المراد القسمة عليه,العدد المراد قسمته);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.isDividable(9,4); //النتيجة هي false
Math.isDividable(10,2); //النتيجة هي true
```
<p dir="rtl"><code dir="ltr">isDividable()</code> تعيد القيمة <span style="color:blue">true</span> إذا كان العدد الممرر في المعامل الأول يقبل القسمة على العدد الممرر في المعامل الثاني،و يعيد القيمة  
<span style="color:blue">false</span> فيما عدا ذلك.
</p>

<h3><code>factorial()</code>:</h3>
<p dir="rtl">تستخدم هذه الدالة في الحصول على قيمة عاملي عدد ما,مثل <span dir="ltr">6!</span></p>
<h4 dir="rtl">الصيغة النحوية:</h4>

```js
Math.factorial(عدد);
```
<h4 dir="rtl">مثال:</h4>

```js
Math.factorial(7); //النتيجة هي 5040
```
<p dir="rtl"><code dir="ltr">factorial()</code> تعيد عدد يعبر عن قيمة عاملي العدد المدخل.</p>

<h3><code>root()</code>:</h3>

<p dir="rtl">تستخدم هذه الدالة في الحصول على الجذر من المرتبة n للعدد الممرر في المعامل الأول,بينما يتم تمرير مرتبة الجذر في المعامل الثاني.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.root(مرتبة الجذر,العدد المراد حساب جذره);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.root(8,3); //النتيجة هي 2
Math.root(15625,2); //النتيجة هي 125
```
<p dir="rtl"><code dir="ltr">root()</code> تعيد عدد يعبر عن قيمة الجذر من المرتبة n للعدد الممرر في المعامل الأول.</p>

<h3><code>sum()</code>:</h3>

<p dir="rtl">يمكن إستخدام هذه الدالة لحساب مجموع عدد منتهي من الأعداد.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.sum(العدد الn,...,العدد الثالث,العدد الثاني,العدد الأول);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.sum(8,3,11,27,5); //النتيجة هي 54
```
<p dir="rtl"><code dir="ltr">sum()</code> تعيد عدد يعبر عن مجموع الأعداد الممررة ضمن معاملات الدالة.</p>

<h3><code>multiply()</code>:</h3>

<p dir="rtl">يمكن إستخدام هذه الدالة لحساب جداء عدد منتهي من الأعداد ببعضها.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.multiply(العدد الn,...,العدد الثالث,العدد الثاني,العدد الأول);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.multiply(8,3,2); //النتيجة هي 48
```
<p dir="rtl"><code dir="ltr">multiply()</code> تعيد عدد يعبر عن جداء الأعداد الممررة ضمن معاملات الدالة.</p>


<h3><code>getAverage()</code>:</h3>
<p dir="rtl">يمكن إستخدام هذه الدالة لإيجاد المتوسط الحسابي لعدد منتهي من الأعداد.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.getAverage(العدد الn,...,العدد الثالث,العدد الثاني,العدد الأول);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.getAverage(11,17,21,3); //النتيجة هي 13
```
<p dir="rtl"><code dir="ltr">getAverage()</code> تعيد عدد يعبر عن المتوسط الحسابي للأعداد الممررة ضمن معاملات الدالة.</p>

<h3><code>isPrimitive()</code>:</h3>

<p dir="rtl">
يمكن إستخدام هذه الدالة في التحقق مما إذا كان العدد الممرر هو عدد أولي أم لا.
</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.isPrimitive(عدد);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.isPrimitive(11); //النتيجة هي true
Math.isPrimitive(24); //النتيجة هي false
```
<p dir="rtl"><code dir="ltr">isPrimitive()</code> تعيد القيمة <span style="color:blue">true</span> في حال إذا كان العدد الممرر أولياً,و  <span style="color:blue">false</span> فيما عدا ذلك.</p>

<h3><code>getFloatDigits()</code>:</h3>

<p dir="rtl">تستخدم هذه الدالة في الحصول على فواصل عدد ما.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.getFloatDigits(عدد);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.getFloatDigits(12.956); //النتيجة هي 0.956
```
<p dir="rtl"><code dir="ltr">getFloatDigits()</code> تعيد عدداً عائماً يعبر عن فواصل العدد الممرر ضمن معامل الدالة.</p>

<h3><code>factors()</code>:</h3>

<p dir="rtl">تستخدم هذه الدالة في تحليل العدد الصحيح الموجب الممرر ضمن معامل الدالة إلى عوامله.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.factors(number)[موضع العامل];
//أو
Math.factors(عدد);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.factors(24); //النتيجة هي 1,2,3,4,6,8,12,24
Math.factors(24)[0]; //النتيجة هي 1
Math.factors(24)[4]; //النتيجة هي 8
```
<p dir="rtl"><code dir="ltr">factors()</code> تعيد مصفوفة تحتوي على عوامل العدد الممرر,لذلك قد يتوجب عليك تحديد موضع بعد القوسين المغلقين للحصول على عامل محدد,و إلا,فإنه سيتم إعادة كامل المصفوفة.</p>

<h3><code>factorsNegative()</code>:</h3>

<p dir="rtl">تقوم بنفس عمل الدالة <code dir="ltr">factors()</code> تقريباً,و لكن بإمكان هذه الدالة أيضاً تحليل العدد الصحيح الموجب الممرر ضمن معامل الدالة و إعطاء القيم السالبة ضمن النتيجة.</p>

<h4 dir="rtl">الصيغة النحوية:</h4>
```js
Math.factorsNegative(عدد)[موضع العامل];
//أو
Math.factorsNegative(عدد);
```
<h4 dir="rtl">مثال:</h4>
```js
Math.factors(24); //النتيجة هي 1,2,3,4,6,8,12,24,-1,-2,-3,-4,-6,-8,-12,-24
Math.factors(24)[0]; //النتيجة هي 1
Math.factors(24)[10]; //النتيجة هي -3
```
<p dir="rtl"><code dir="ltr">factorsNegative()</code>  تعيد مصفوفة تحتوي على عوامل العدد الممرر,لذلك قد يتوجب عليك تحديد موضع بعد القوسين المغلقين للحصول على عامل محدد,و إلا,فإنه سيتم إعادة كامل المصفوفة.</p>
<a href="http://www.wtfpl.net/" style="text-align:center;"><img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png"  width="80" height="15" alt="WTFPL" /></a>
