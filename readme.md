## ============= Interview Questions =============

### HTML

#### 1.HTML কী এবং এটি কীভাবে কাজ করে?

- ব্যাখ্যা: HTML (HyperText Markup Language) হলো ওয়েব পেজ তৈরির জন্য ব্যবহৃত একটি মার্কআপ ভাষা। এটি বিভিন্ন ট্যাগ (tags) ব্যবহার করে ওয়েবসাইটের কনটেন্ট গঠন করে। HTML ব্রাউজারের জন্য নির্দেশনা দেয় কিভাবে টেক্সট, ইমেজ, ভিডিও ইত্যাদি প্রদর্শন করতে হবে।

#### 2.ওয়েবপেজের স্ট্রাকচার কী?

- ওয়েবপেজের স্ট্রাকচার (Structure) মূলত HTML, CSS, এবং JavaScript এর সমন্বয়ে গঠিত হয়।

- ওয়েবপেজের স্ট্রাকচার ব্যাখ্যা:
  1️⃣ HTML মূলত ওয়েবপেজের মূল স্ট্রাকচার তৈরি করে।
  2️⃣ CSS ওয়েবপেজকে সুন্দর ও আকর্ষণীয় করে তোলে।
  3️⃣ JavaScript ওয়েবপেজে ডায়নামিক ফিচার যোগ করতে ব্যবহৃত হয়।

#### 3.একটি HTML ডকুমেন্টের প্রধান অংশ কী কী?

একটি HTML ডকুমেন্টের প্রধান অংশ:

1️⃣ <!DOCTYPE html>
2️⃣ <html>
3️⃣ <head>
4️⃣ <body>

- <header> → শিরোনাম, নেভিগেশন বার।
- <main> → মূল বিষয়বস্তু।
- <section> → কন্টেন্টের পৃথক বিভাগ।
- <article> → স্বাধীন কনটেন্ট ব্লক (যেমন ব্লগ পোস্ট)।
- <aside> → অতিরিক্ত তথ্য বা সাইডবার।
- <footer> → কপিরাইট, লিংক, যোগাযোগ তথ্য।

3. <!DOCTYPE html>, <html>, <head>, এবং <body> ট্যাগের কাজ কী?

✅ <!DOCTYPE html> → HTML ডকুমেন্টের ধরন নির্ধারণ করে।
✅ <html> → সম্পূর্ণ ওয়েবপেজের মূল কনটেইনার।
✅ <head> → মেটা তথ্য, টাইটেল, CSS, স্ক্রিপ্ট সংযুক্ত করা হয়।
✅ <body> → দৃশ্যমান কনটেন্ট (টেক্সট, ছবি, লিংক, ভিডিও) ধারণ করে।

4.DOCTYPE কীভাবে ব্রাউজারের জন্য গুরুত্বপূর্ণ?

✅ <!DOCTYPE html> ব্রাউজারের জন্য গুরুত্বপূর্ণ কারণ এটি—

1️⃣ ডকুমেন্টের HTML ধরন নির্ধারণ করে।
2️⃣ ব্রাউজারকে স্ট্যান্ডার্ড মোডে রেন্ডার করতে সাহায্য করে।
3️⃣ ইনকন্সিস্টেন্ট (ভুল) রেন্ডারিং প্রতিরোধ করে।
4️⃣ ওয়েবপেজের সঠিক প্রদর্শন নিশ্চিত করে।

## What is HTML Elements?

HTML Elements হল ওয়েবপেজ তৈরির মৌলিক উপাদান, যা একসাথে মিলে একটি পূর্ণাঙ্গ ওয়েবপেজ গঠন করে।

প্রতিটি HTML Element সাধারণত তিনটি অংশ নিয়ে গঠিত
✅ Opening Tag (<tag>) → এলিমেন্টের শুরু নির্দেশ করে।
✅ Content → ট্যাগের ভিতরের তথ্য (যেমন টেক্সট, ইমেজ, লিঙ্ক)।
✅ Closing Tag (</tag>) → এলিমেন্টের সমাপ্তি নির্দেশ করে (সব ক্ষেত্রে নয়)।

## Types of HTML Elements

1.Block-level Elements : এগুলো পুরো লাইনের জায়গা নেয় এবং নতুন লাইনে শুরু হয়।
Exam: <div>, <p>, <h1>–<h6>, <ul>, <ol>, <li>
2.Inline Elements : এগুলো শুধুমাত্র প্রয়োজনীয় জায়গা নেয় এবং নতুন লাইনে শুরু হয় না।
Exam : <span>, <a>, <img>, <strong>, <b>
3.Self-closing Elements : এগুলোর ক্লোজিং ট্যাগের প্রয়োজন হয় না।
Exam : <img>, <br>, <hr>

## HTML Tag (ট্যাগ) কি?

HTML Tag হল কোডের সেই অংশ যা ব্রাউজারকে বলে একটি এলিমেন্ট শুরু বা শেষ হয়েছে।

## Types of HTML Tag

1.Opening Tag <p>
2.Closing Tag </p>

## JavaScript

- 1.What is ES6?
  Answer: ES6 (ECMAScript 2015) is a major update to JavaScript that introduced new features like let, const, arrow functions, template literals, destructuring, and modules.

- 2.What is the difference between let, const, and var?
  var: Function-scoped, can be redeclared, hoisted.
  let: Block-scoped, cannot be redeclared, but its value can be reassigned(mutable)
  const: Block-scoped, cannot be redeclared or reassigned(immutable)

- 3.What is an Arrow Function?
  Answer: Arrow functions allow a short syntax for writing function expressions.
  You don't need the function keyword, the return keyword, and the curly brackets

- 4.Template Literals কী?
  Answer: Template Literals ব্যাকটিক (`) ব্যবহার করে স্ট্রিং লেখার সুবিধা দেয় এবং when you need to include variables or expressions inside a string.
  Answer: Template Literals (``) ডাইনামিক স্ট্রিং তৈরির জন্য ব্যবহার হয়।

- 5. Spread এবং Rest Operator এর পার্থক্য কী?
     Answer:
     Spread (...): অ্যারে বা অবজেক্ট কপি বা মিশানোর জন্য ব্যবহৃত হয়।
     Rest Operator (...): ফাংশনে অবশিষ্ট আর্গুমেন্ট গ্রহণ/recive করতে ব্যবহৃত হয়। এটি একটি ফাংশনে পাস করা সকল অতিরিক্ত আর্গুমেন্টকে একটি অ্যারেতে রূপান্তরিত করে। এই ফিচারটি তখন ব্যবহার করা হয় যখন ফাংশনে পাস করা আর্গুমেন্টের সংখ্যা অজানা থাকে।

- 6.Destructuring কী?
  Answer: Destructuring ব্যবহার করে Array বা Object থেকে নির্দিষ্ট মান সহজেই বের করা যায়। Array Destructuring use = [ ] , Object Destructuring use = { }

- 7.JavaScript-এর Class কীভাবে কাজ করে?
  Answer: ES6-এ OOP (Object-Oriented Programming) সহজ করতে class ইন্ট্রোডিউস করা হয়েছে।

- 8. Default Parameters কী?
     Answer: ডিফল্ট প্যারামিটার (Default Parameters) হলো একটি JavaScript ফিচার যেখানে আপনি ফাংশনের প্যারামিটারগুলোর জন্য ডিফল্ট মান নির্ধারণ করতে পারেন। এর মানে হলো, যখন আপনি ফাংশন কল করবেন, কিন্তু কোনো প্যারামিটার পাস না করবেন, তখন সেই প্যারামিটারটির জন্য নির্দিষ্ট ডিফল্ট মান ব্যবহার হবে।
- 9.ES6 Modules কী?
  Answer: ES6 Modules হলো JavaScript-এর একটি ফিচার যা কোডের reusability and organization উন্নত করতে সাহায্য করে | ES6 (ECMAScript 2015) এর সাথে JavaScript-এ মডিউল ব্যবস্থাপনা চালু হয়, যা আমাদের আলাদা ফাইলগুলোকে মডিউল হিসেবে ব্যবহার করতে দেয় এবং এক ফাইল থেকে অন্য ফাইলে কোড export ও import করতে পারে।

  ES6 Modules-এ প্রধান দুটি অংশ রয়েছে:
  Export: কোনো ফাংশন, ভ্যারিয়েবল এক ফাইল থেকে অন্য ফাইলে ব্যবহার করার জন্য এক্সপোর্ট করা হয়।
  Import: অন্য ফাইল থেকে এক্সপোর্ট করা ডেটা বা কোড Import করা হয়।

- 10. Promise কী এবং এটি কীভাবে কাজ করে?
      Answer: Promise হল asynchronous operation পরিচালনার জন্য ES6 এর একটি ফিচার। এটি তিনটি স্টেট থাকতে পারে: Pending, Fulfilled/Resolved, Rejected।
