## Basic Question

### 1. What is Rendering ?

- রেন্ডারিং হল ব্রাউজারে বা অ্যাপ্লিকেশনে ডেটাকে দৃশ্যমান আউটপুটে রূপান্তর করার প্রক্রিয়া। এটি ওয়েব ডেভেলপমেন্ট যেখানে HTML, CSS, এবং JavaScript ব্যবহার করে UI (User Interface) তৈরি ও উপস্থাপন করা হয়।

### 2. What is Client-Side Rendering (CSR) ?

Rendering Locations : User's Browser

-Client-Side Rendering (CSR) হলো এমন একটি পদ্ধতি যেখানে ব্রাউজার প্রথমে সার্ভার থেকে একটি সাধারণ HTML ফাইল নিয়ে আসে, তারপর JavaScript দিয়ে কন্টেন্ট লোড করে ও রেন্ডার করে।

-কীভাবে কাজ করে?

-ইউজার যখন ওয়েবসাইটে প্রবেশ করে, সার্ভার শুধুমাত্র একটি index.html ফাইল পাঠায়।
ব্রাউজার তারপর JavaScript (React, Vue, Angular ইত্যাদি) লোড করে।
ডাটা API থেকে ফেচ করে এবং ওয়েবসাইট রেন্ডার করে।
\*\*✔️ উপকারিতা:
✅ Dynamic ওয়েবসাইটের জন্য ভালো (যেমন: React SPA - Single Page Applications)
✅ ব্যান্ডউইথ বাঁচায়, কারণ একবার লোড হওয়ার পর নতুন পেজের জন্য সার্ভারে রিকোয়েস্ট দিতে হয় না।
✅ Frontend-heavy অ্যাপের জন্য পারফেক্ট, যেমন: Dashboard, SaaS Apps।

❌ অসুবিধা:
🚫 প্রথম লোড টাইম বেশি, কারণ ব্রাউজারকে JavaScript লোড ও রান করতে হয়।
🚫 SEO (Search Engine Optimization) এর সমস্যা, কারণ সার্চ ইঞ্জিন প্রথমে খালি HTML পায়।

### 3. What is Server-Side Rendering (SSR) ?

Rendering Locations : Web Server(প্রতিবার রিকোয়েস্ট করলে)

-Server-Side Rendering (SSR) হলো এমন পদ্ধতি যেখানে ব্রাউজারে HTML পাঠানোর আগেই সার্ভার ডাটা প্রসেস করে পুরো পেজ তৈরি করে পাঠিয়ে দেয়।

-কীভাবে কাজ করে?

-ইউজার যখন ওয়েবসাইটে প্রবেশ করে, সার্ভার ডাটাবেস থেকে ডাটা নিয়ে HTML পেজ জেনারেট করে।
সম্পূর্ণ HTML পেজ ইউজারের ব্রাউজারে পাঠিয়ে দেয়।
ব্রাউজার HTML পাওয়ার সাথে সাথে দেখাতে শুরু করে।
\*\*✔️ উপকারিতা:
✅ দ্রুত লোড হয়, কারণ ব্রাউজার রেডি HTML পায়।
✅ SEO ফ্রেন্ডলি, কারণ সার্চ ইঞ্জিন সহজেই কন্টেন্ট ক্রল করতে পারে।
✅ স্ট্যাটিক বা ইনফরমেশন-বেইজড ওয়েবসাইটের জন্য ভালো (যেমন ব্লগ, নিউজপেপার)।

❌ অসুবিধা:
🚫 প্রতিবার নতুন পেজ লোড করতে সার্ভারে রিকোয়েস্ট পাঠাতে হয়, যা সাইট স্লো করে।
🚫 বেশি ট্রাফিক হলে সার্ভার লোড বেড়ে যেতে পারে।

### 4. What is Static Stie Generation (SSG) ?

Rendering Locations : Build Process (Pre-rendered)

-Static Site Generation (SSG) হলো এমন একটি ওয়েবসাইট তৈরির পদ্ধতি যেখানে HTML ফাইলগুলো সার্ভারে আগেই জেনারেট করা থাকে এবং ইউজার যখন ওয়েবসাইটে প্রবেশ করে, তখন সরাসরি এই রেডি HTML পায়।

-SSG মূলত বিল্ড টাইমে পেজগুলো তৈরি করে এবং সার্ভারে স্ট্যাটিক ফাইল হিসেবে সংরক্ষণ করে। এটি ডাইনামিক ওয়েবসাইটের মতো প্রতিবার সার্ভারে রেন্ডার হয় না, তাই দ্রুত লোড হয়।

- SSG কিভাবে কাজ করে?

ডেভেলপার কোড লেখার পর npm run build বা অন্য কোনো বিল্ড কমান্ড চালায়।
সব পেজের জন্য HTML ফাইল বিল্ড টাইমে তৈরি হয়ে যায়।
সার্ভারে এই স্ট্যাটিক ফাইলগুলো রাখা হয়।
ইউজার যখন ওয়েবসাইট ভিজিট করে, তখন সরাসরি HTML ফাইল পায়—সার্ভারে কোনো নতুন রেন্ডারিং লাগে না।

## JavaScript Interview Questions Fof Freshers

### 1.JavaScript কী?

-JavaScript হল একটি high-level ,Interpreted programming Language,যা মূলত ওয়েব ডেভেলপমেন্টের জন্য ব্যবহৃত হয়। এটি একটি client-side scripting language ,তবে এখন Node.js এর সাহায্যে server-side কাজেও ব্যবহৃত হয়।

### 2.ECMAScript কী?

-ECMAScript(ES) JavaScript-এর জন্য নিয়ম ও স্ট্যান্ডার্ড নির্ধারণ করে। ES6 (ECMAScript 2015) থেকে শুরু করে।

### 3.JavaScript এবং ECMAScript-এর মধ্যে পার্থক্য

**JavaScript
1.এটি একটি প্রোগ্রামিং language
2.ব্রাউজারে বা সার্ভারে রান করে
**ECMAScript
1.JavaScript-এর জন্য নিয়ম/স্ট্যান্ডার্ড নির্ধারণ করে
