# সেন্সর ক্যালিব্রেশন

## নির্দেশাবলী

এই পাঠে আমরা মাটির আর্দ্রতা সেন্সর রিডিং সংগ্রহ করেছি যা 0-1023 এর মধ্যে মান হিসাবে পরিমাপ করে। এগুলিকে প্রকৃত মাটির আর্দ্রতা হিসেবে রূপান্তর করতে, আমাদেরকে সেন্সরটি ক্যালিব্রেট করতে হবে। মাটির নমুনাগুলি থেকে রিডিং নিয়ে এটি করা যাবে, তারপরে এই নমুনাগুলি থেকে গ্র্যাভিমেট্রিক মাটির আর্দ্রতার পরিমাণ গণনা করতে হবে।

প্রতিটি সময় মাটির বিভিন্ন আর্দ্রতা সহ প্রয়োজনীয় রিডিং পেতে আমাদেরকে একাধিকবার এই পদক্ষেপগুলি পুনরাবৃত্তি করতে হবে।

1. মাটির আর্দ্রতা সেন্সর ব্যবহার করে একটি আর্দ্রতার মান নিতে হবে। এই মান লিখে রাখতে হবে।.

1. মাটির নমুনা নিয়ে এটি ওজন করতে হবে। এই মান লিখে রাখতে হবে।

1. কোন ওভেন বা উষ্ণ কিছুতে 110°C (230°F) তাপমাত্রায় কয়েক ঘন্টা রেখে মাটিকে শুকিয়ে নিতে হবে । সূর্যের আলো বা কোন উষ্ণ জায়গায় রেখেও এটা করা যাবে। শুষ্ক হয়েছে কিনা তা বোঝা যাবে যদি এটি পাউডার ধরণের হয়ে যায় এবং বেশ আলগা থাকে।

    > 💁 সর্বাধিক নির্ভুল ফলাফলের জন্য একটি ল্যাবে সাধারণত 48-72 ঘন্টা শুকানো হয়। যদি এরকম বিশেষ ওভেন থাকে, তবে আমরা আরও দীর্ঘক্ষণ শুকানোর জন্য এগুলি ব্যবহার করতে পারি। যত বেশি সময় এখানে দেয়া হবে, ততবেশি শুষ্কতা আসবে এবং ফলস্বরূপ নির্ভুল মান পাওয়া যাবে।

1. আবার মাটি ওজন পরিমাপ করতে হবে

    > 🔥 যদি চুলায় শুকানো হয়, তবে আগে নিশ্চিত করে নিতে হবে যে এটি ঠান্ড হয়েছে!

গ্র্যাভিমেট্রিক পদ্ধতিতে মাটির আর্দ্রতা গণনা :

![soil moisture % is weight wet minus weight dry, divided by weight dry, times 100](../../../../images/gsm-calculation.png)

* W<sub>wet</sub> = ভেজা মাটির ভর
* W<sub>dry</sub> = শুষ্ক মাটির ভর

উদাহরণস্বরূপ, ধরি আমাদের কাছে একটি মাটির নমুনা রয়েছে যা ভেজা অবস্থায় ২১২ গ্রাম ও শুকনো অবস্থায় ১৯৭ গ্রাম।

![The calculation filled in](../../../../images/gsm-calculation-example.png)

* W<sub>wet</sub> = 212g
* W<sub>dry</sub> = 197g
* 212 - 197 = 15
* 15 / 197 = 0.076
* 0.076 * 100 = 7.6%

এই উদাহরণে, মাটির নমুনাটির গ্র্যাভিমেট্রিক মাটির আর্দ্রতার মান 7.6%.

একবার আমাদের কাছে কমপক্ষে 3 টি নমুনা ফলাফল আসার পরে, মাটির আর্দ্রতা সেন্সর রিডিং এর জন্য মাটির আর্দ্রতা % এর একটি গ্রাফ প্লট করতে হবে এবং পয়েন্টগুলি সর্বোত্তমভাবে ফিট (Best Fit) করার জন্য লাইন টেনে যুক্ত করতে হবে। তারপরে রেখাটি ব্যবহার করে, যেকোন সেন্সর রিডিং এর জন্য জন্য গ্র্যাভিমেট্রিক মাটির আর্দ্রতার মান গণনা করা যাবে।

## এসাইনমেন্ট মূল্যায়ন মানদন্ড

| ক্রাইটেরিয়া | দৃষ্টান্তমূলক (সর্বোত্তম) | পর্যাপ্ত (মাঝারি) | আরো উন্নতির প্রয়োজন (নিম্ন) |
| -------- | ------------------------ | ------------------ | ------------------------ |
| ক্যালিব্রেশন ডেটা সংগ্রহ | কমপক্ষে ৩টি ক্যালিব্রেশন স্যাম্পল গ্রহণ করেছে | কমপক্ষে ২টি ক্যালিব্রেশন স্যাম্পল গ্রহণ করেছে |কমপক্ষে ১টি ক্যালিব্রেশন স্যাম্পল গ্রহণ করেছে |
| ক্যালিব্রেট করা রিডিং এ রুপান্তর | সফলভাবে ক্যালিব্রেট  গ্রাফ প্লট করে এবং সেন্সর থেকে রিডিং তৈরি করে এটিকে গ্র্যাভিমেট্রিক মাটির আর্দ্রতার পরিমাণে রূপান্তর করেছে |  সফলভাবে ক্যালিব্রেট  গ্রাফ প্লট করেছে | গ্রাফ প্লট করতে পারেনি |
