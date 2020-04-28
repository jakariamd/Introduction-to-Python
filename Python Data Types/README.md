# Python Basic Data Types 

পাইথনে তিনটি বেসিক ডাটা টাইপ আছে। 

  - Integers (সংখ্যার জন্য ডিফল্ট ডাটা টাইপ)
  - Floats 
  - Strings 
  
  ## Integers
  
  Integer হলো যেকোনো পূর্ণসংখ্যা। পাইথনে যেকোনো মান কোন ভেরিয়েবলে রাখার জন্য আগে থেকে ভেরিয়েবল ডিকলেয়ার করা লাগে না। সরাসরি ভেরিয়েবলের নাম লিখে মান assign করে দিলেই হয়। যেমনঃ 
  
```  
  a=5
```

উপরের a একটি ভেরিয়েবল যার মান 5. যেহেতু 5 সংখ্যাটি একটি integer, সেহেতু a ভেরিয়েবলের টাইপ ও integer. যেকোন ভেরিয়েবলের টাইপ দেখতে type() ফাংশনে ব্র্যাকেটের ভিতর ভেরিয়েবলটা লিখে দিলেই হয়। যেমনঃ

```
  type(a)
```

উল্লেখ্য, ভেরিয়েবল হচ্ছে একটি নাম মাত্র যা একটি মান কে নির্দেশ করে। পাইথনে ভেরিয়েবলের নামকরণের কনভেশন হচ্ছে মুটামুটি C এর কনভেশনের মতই। ভেরিয়েবলের নাম হতে পারে ইংরেজি একটি অক্ষর, একটি শব্দ বা একাধিক শব্দ  যা _ দিয়ে সংযুক্ত। যেমনঃ 

```
b=4*5-12+5-3-20
value=10
roll_No=24
```

##  Floats
Integer ছাড়া বাকি সব সংখ্যাই হচ্ছে Float. যেমনঃ

```
x=3.14
```
এখানে 3.14 হচ্ছে একটি float number এবং x ভেরিয়েবলের টাইপ হচ্ছে float. আগের মতই আমরা type() ফাংশন দিয়ে x ভেরিয়েবলের টাইপ চেক করে দেখতে পারি। 

```
type(x)
```
 
 ## Strings 
 
 Numbers এর পাশাপাশি পাইথন letters, words বা sentences নিয়েও কাজ করতে পারে। এগুলোকে বলা হয় strings. Strings লিখার দুটি উপায়ঃ characters গুলিকে single quotes ('...') অথবা  double quotes ("...")  দিয়ে enclose করে দেওয়া।  যেমনঃ 
 
 ```
 >>> 'spam eggs'  # single quotes
'spam eggs'
>>> 'doesn\'t'  # use \' to escape the single quote...
"doesn't"
>>> "doesn't"  # ...or use double quotes instead
"doesn't"
>>> '"Yes," they said.'
'"Yes," they said.'
>>> "\"Yes,\" they said."
'"Yes," they said.'
>>> '"Isn\'t," they said.'
'"Isn\'t," they said.'
 ```
 
