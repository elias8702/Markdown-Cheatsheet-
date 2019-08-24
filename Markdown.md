<div dir=rtl>



محتوای جداول

[سرایند](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#a)


[تاکیدها](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#b)


[لیست‌ها](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#c) 


[پیوندها](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#d)


[عکس](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#f)


[جدل‌سازی کد‌ها](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#g)


[جداول](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#h) 


[بلوک‌های نقل‌قل](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#i)


[اچ‌تی‌ام‌ال در مارک‌دون](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#j)


[روش افقی](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#k)


[خطوط براکت‌ها](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#l)


[ویدو‌های‌ یوتیوب](https://github.com/elias8702/Markdown-Cheatsheet-/blob/master/Markdown.md#m)



{#a}

# سرایند‌ها

```
# سر۱
## سر۲
### سر۳
#### سر۳
##### سر۵
###### سر۶

روش دیگر برای استفاده از سرایند روش زیر است:

سرایند ۱
======

سرایند۲
------

```



# سر۱
## سر۲
### سر۳
#### سر۳
##### سر۵
###### سر۶

روش دیگر برای استفاده از سرایند روش زیر است:

سرایند ۱
======

سرایند۲
------
```
برای تاکید کردن
کافی از علامت _من تاکید شدم _ یا *من تاکید شدم * استفاده کنیم.

برای تاکید بیشتر *من خیلی تاکید شدم** ویا __ من خیلی تاکید شدم__

تاکید با ترکیب از دو علامت ** ـ من تایکد ترکیبی هستم ـ**

خط کشید روی متن با علامت ~~ خط روی من ~~
```

برای تاکید کردن
کافی از علامت _من تاکید شدم _ یا *من تاکید شدم * استفاده کنیم.

برای تاکید بیشتر *من خیلی تاکید شدم** ویا __ من خیلی تاکید شدم__

تاکید با ترکیب از دو علامت ** ـ من تایکد ترکیبی هستم ـ**

خط کشید روی متن با علامت ~~ خط روی من ~~

{#b}

# لیست‌ها

در این مرحله سعی می‌کنیم فضا‌ها را با نقطه نمایش دهیم
```
1. یک مورد لیست شده
2. یک دیگر
 چ‌* زیر لیست

1. عدد واقعی بودن مهم نیست. فقط یک عدده
..1. یک لیست سفارش شده
4. یک مورد دیگه

... با این روش می‌توانید پارگراف بندی کنید. به خط اول توجه کنید منظورم اون فضای خالی است. برای تراز کردن از علامت سه نقطه `...`  استفاده کردیم که مارک‌دون را تراز کنیم.

برای داشتن یک خط پارگراف ولی نداشتن پارگراف در کد باید  از علامت `.. .. ` استفاده کنید.  ...به این خط دقت کنید .. 

* علامت گذاری با ستاره
- علامت گذاری با منفی
+ علامت کذاری با مثبت
```
1. یک مورد لیست شده
2. یک دیگر
   * زیر لیست

1. عدد واقعی بودن مهم نیست. فقط یک عدده
  1. یک لیست سفارش شده
4. یک مورد دیگه

    با این روش می‌توانید پارگراف بندی کنید. به خط اول توجه کنید منظورم اون فضای خالی است. برای تراز کردن از علامت سه نقطه `...`  استفاده کردیم که مارک‌دون را تراز کنیم.

برای داشتن یک خط پارگراف ولی نداشتن پارگراف در کد باید  از علامت `.. .. ` استفاده کنید.
به این خط دقت کنید  

* علامت گذاری با ستاره
- علامت گذاری با منفی
+ علامت کذاری با مثبت

{#c}

# لینک‌ها 

```
[من یک لینکم رومن کلید کن](https://www.google.com/)

[منم یک لینکم فقط اگه روی من چند دقیقه نگهداری پیامی هم نشان می‌دهم](https://www.google.com/ "لینک گوگلم")

[منم یک لینکم فقط من ادرس از یک فایل متنی می‌خونم](text)

[منم یک لینکم من به یک ادرس پوشه می‌رم](../master/README.md)

[منم یک لینکم اما به جای می‌رم] پس می‌توانید از متن خودتون استفاده کنید

[منم یک لینکم البته لینکم یک مقدار عددی است](1)

لینک‌ها استفاده شده در اینجا همه برای مثال است


[text]: https://www.mozilla.org
[1]: http://slashdot.org
[منم یک لینکم اما به جای می‌رم]: http://www.reddit.com

```

[من یک لینکم رومن کلید کن](https://www.google.com/)

[منم یک لینکم فقط اگه روی من چند دقیقه نگهداری پیامی هم نشان می‌دهم](https://www.google.com/ "لینک گوگلم")

[منم یک لینکم فقط من ادرس از یک فایل متنی می‌خونم](text)

[منم یک لینکم من به یک ادرس پوشه می‌رم](../master/README.md)

[منم یک لینکم اما به جای می‌رم] پس می‌توانید از متن خودتون استفاده کنید

[منم یک لینکم البته لینکم یک مقدار عددی است](1)

لینک‌ها استفاده شده در اینجا همه برای مثال است


[text]: https://www.mozilla.org
[1]: http://slashdot.org
[منم یک لینکم اما به جای می‌رم]: http://www.reddit.com

{#d}

# عکس

اینجا یک لوگو داریم به همراه متون:
```
لوگو با دارس لینکی
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "متون لوگو۱")

لوگو با متغییر 
![alt text][logo]


[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "متون لوگو۲"
```

لوگو با دارس لینکی
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "متون لوگو۱")

لوگو با متغییر 
![alt text][logo]


[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "متون لوگو۲"

<div dir=ltr>
{#f}
<div dir=rtl>
# برجسته کردن کدها

بلوک‌های کدها بخشی از مارک‌دون (Markdown spec) است اما هایلات کردن کد از مارک‌دون نیست. ولی بسیار از مفسرها همانند گیت‌هاب و مارک‌دون‌ها (Markdown Here) از هالایت کردن پشتبانی می‌کنند. کدام زبان‌ها پشتبانی می‌شود کدام‌ها نمی‌شود بستگی به مفسرها دارد.
مارک‌دون(Markdown Here) ده‌هازبان‌برنامه‌نویسی را پشتبانی می‌کند. برای دیدن لیست و چگونگی نوشتن اسم‌ها به لینک زیر مراجعه کنید:

[ highlight.js demo](http://softwaremaniacs.org/media/soft/highlight/test.html)


```

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
```
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

{#g}

# جدول‌ها

جدول جزئی از مشخصات مارک‌دون(Markdown spec) نستند اما جز GFM و Markdown Here هستند. این روشی ساده است برای استفاده از جدول بدون برنامه اضافی در برنامه است.
```


از علامت `:` می‌توان برای تراز کردن جدول استفاده کرد

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

باید حداقل ۳ تا خط فاصله از هر سلول جدا شوند.
لوله‌های پایپ `|` اختیاری است
استفاده کردن raw Markdown برای زیبا کردن خوب است هم چنین می‌توانید از inline Markdown استفاده کنید

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


```


از علامت `:` می‌توان برای تراز کردن جدول استفاده کرد

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

باید حداقل ۳ تا خط فاصله از هر سلول جدا شوند.
لوله‌های پایپ `|` اختیاری است
استفاده کردن مارک‌دون ‌ها مثل `** **`برای زیبا کردن خوب است هم چنین می‌توانید از ` `` ` استفاده کنید

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

{#h}

# بلوک‌های نقل‌قول (Blockquotes)

```

> بلوک‌های نقل‌قول برای شبیه‌سازی برای پاسخ دادن به ایمیل بسیار مفید است. 
> ای خط بخشی از همین نقل‌قول است

بستن نقل‌قول.

> این هم یک متن طولانی در در نقل قول است. پس در نتیجه باید به نوشتن خود ادامه بدهیم  که به اندازه کافی طولانی است به نظرتون بسه یا نه بزاید کمی دیگر پیش بریم فکر کنم کافی باشه می‌تونید **داخلش * **مارک‌دون** بزاردید 

```

> بلوک‌های نقل‌قول برای شبیه‌سازی برای پاسخ دادن به ایمیل بسیار مفید است. 
> ای خط بخشی از همین نقل‌قول است

بستن نقل‌قول.

> این هم یک متن طولانی در در نقل قول است. پس در نتیجه باید به نوشتن خود ادامه بدهیم  که به اندازه کافی طولانی است به نظرتون بسه یا نه بزاید کمی دیگر پیش بریم فکر کنم کافی باشه می‌تونید **داخلش * **مارک‌دون** بزاردی


{#i}

# اچ‌تی‌ام‌ال در مارک‌دون

همچنین می توانید از تک‌های اچ‌تی‌ام‌ال در مارک‌دون استفاده کنید. خیل هم خوش‌کار می کنه
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

```

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

{#j}

# روش افقی

```

بیشتربیشترکن...

---

خوش‌حالی

***

ستاره استریک

___

```


بیشتربیشترکن...

---

خوش‌حالی

***

ستاره استریک

___


{#k}

# خطوط براکت‌ها

توسعه من به شما برای بهتر درک کردن این موضوع سیخ زدن و بازی کردن با این روش است تا بهتر بفهمید.یکبار یک چیزی بنویسید و <enter> بزنید یک بار دیگه بنویسید و دو تا <enter> بزنید ببنید چه اتفاقی می‌افتد. به زودی به این موضوع می رسید که مارک‌دون (Markdown Toggle) دشمنتان نیست بلکه  رفقیتان است.

این‌ها هم یکسری از بازی کردن با مارک‌دون است

```
این خط از خط بالا جدا خواهد بود بنابراین یک *پاراگراف جداگانه* خواهد بود


این خط هم یک پارگراف جداگانه است

```

این خط از خط بالا جدا خواهد بود بنابراین یک *پاراگراف جداگانه* خواهد بود


این خط هم یک پارگراف جداگانه است

{#m}

# ویدو‌های یوتوب

البته نمی‌توانید به طور مستقیم اضافه کنید

```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
یا در (pure Markdown) که اندزه و عکس را از دست می دهید

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

تحت لیسانس : [CC-BY](https://creativecommons.org/licenses/by/3.0/)

تمامی محتوایت بالا برگفته شده و ترجمه شده از این [لینک](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) می‌باشد.


