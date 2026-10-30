TRANS GROUP Website Starter (Blue Corporate, English + Bangla)

ফোল্ডারের ভেতরে index.html আছে। এটি Netlify-তে নতুন আলাদা Project হিসেবে deploy করতে পারবেন। পুরোনো TRANS COLLECTION Project পরিবর্তন হবে না।

সতর্কতা: /admin/ পেজটি Decap CMS-এর প্রাথমিক সেটআপ। এটি এখনই সম্পূর্ণ কার্যকর Blog Dashboard নয়। CMS চালু করতে হলে:
1) একটি নতুন GitHub repository তৈরি করতে হবে: trans-group-website
2) এই ফোল্ডারের ফাইলগুলো repository-তে upload/push করতে হবে।
3) GitHub repository Netlify-তে নতুন site হিসেবে connect করতে হবে।
4) admin/config.yml-এ YOUR_GITHUB_USERNAME এবং YOUR-SITE-NAME পরিবর্তন করতে হবে।
5) নিরাপদ GitHub OAuth login server / authentication endpoint configure করতে হবে এবং সেটির URL config.yml-এর base_url-এ বসাতে হবে।
6) Netlify deploy শেষে /admin/ খুলে login পরীক্ষা করতে হবে।

গুরুত্বপূর্ণ:
- কোনো password/token এই ফাইলে লিখবেন না বা কাউকে দেবেন না।
- Contact email এখন placeholder: YOUR_BUSINESS_EMAIL। প্রকাশের আগে নিজের business email বসাবেন।
- Blog-এ প্রকাশিত তথ্য সত্য, নিজস্ব এবং যাচাই করা হওয়া উচিত।
