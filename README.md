# Git Cheat Sheet Bangla
আসালামু-আলাইকুম । গিটহাব এর একটা সুন্দর cheat sheet থাকলে কিন্তু খারাপ হয় না , তাও আবার বাংলাতে 👀👀 । খুব বেশি বিস্তারিত থাকবে না কিন্তু কি কাজ করা যায় ওই কমান্ড দিয়ে তাই লিখবো 🖋️

## Setup GitHub account
- টার্মিনালে এই কমান্ড গুলো দিয়ে  একাউন্ট সেট  করা যায় - 
>**git config --global "user. email"**  
>**git config --global "user. name"** 

## Project Starting
>**git init < directory name >** *নতুন ফোল্ডার এ  গিট  রাখা*
>**git clone "url"** *কারো প্রোজেক্ট নিজের কম্পিউটার এ আনা*

## Add Commands

>  **git add .**    *ওই ফোল্ডার এর ভিতরে যা কিছু আছে সব add করা যায়* 
> **git add filename** *শুধু মাত্র একটি ফাইল বা একাধিক ফাইল add করা যায়*

### Remove added files
> **git restore --staged filename** *ভুলে add করা ফাইল সরানো*

## Commit Command
> **git commit -m "Your message"** *এই কমান্ড দিয়ে কমিট করা হয়*
### Remove committed file
> **git reset --soft HEAD~1**  *এইটা দিয়ে updated কোন কমিট থাকলে সেইটা রিমুভ করা যায়* 

> **git revert "commit hash"** *এইটা দিয়ে commit করা কোন কমিট থাকলে ওইটার হ্যাশ নিয়ে বসায় দিলে আগের জায়গায় ফিরে আসে*

## Create Branch and change branch

### Create Branch
> **git branch branch-name** *এইটা দিয়ে নতুন ব্রাঞ্চ খুলা যায়*

### Delete Branch
> **git branch -D branch-name** *এইটা দিয়ে ব্রাঞ্চ ডিলেট করা যায়*

### Change Branch
>**git checkout branch-name** *ব্রাঞ্চ চেঞ্জ এর জন্য*

## Push Command
> **git push origin branch-name** *নির্দিষ্ট কোন ব্রাঞ্চ এ পুশ করা*

## Pull Command
> **git pull**  *আগে যদি কেউ  ফাইল আপডেট করে তাহলে ওই আপডেট গিট কে দেওয়া এবং নিজের কোড পুশ করতে  প্রস্তুত করা*
## Merge Command
*ধরেন আপনার কাছে  a ব্রাঞ্চ আর b ব্রাঞ্চ আছে। b তে কাজ করছেন এবার মার্জ করবেন*

> **git fetch origin**  *সর্বশেষ পরিবর্তনগুলি নিশ্চিত করুন*

> **git checkout b**  *ব্রাঞ্চ 'b' তে সুইচ করুন*

> **git merge a** *ব্রাঞ্চ 'a' কে 'b' তে মার্জ করুন*

##### যদি  প্রবলেম থাকে তবে সমাধান করুন

>**git add "< file-with-conflict >"**   *সমাধানকৃত ফাইলগুলি স্টেজ করুন*

>**git commit**   *মার্জটি কমিট করুন যদি প্রয়োজন হয়*

>**git push origin b**  *পরিবর্তনগুলি রিমোট রিপোজিটরিতে পুশ করুন*

 
## Git Status
> **git status**  *বর্তমানে ফাইলের অবস্থা জানতে ব্যবহার করা হয়। যেমন ওই ফাইল এড করতে হবে অথবা আরেকগুলো ফাইল কমিট এর অপেক্ষায়*
## Git Log
>**git log** *কতগুলো কমিট করেছি তা দেখা যায় কোন সময় করেছি এবং কোন ফাইল  করেছি সাথে কি মেসেজ দিয়েছিলাম  তাও দেখা যায় । ও হ্যাঁ  কমিট এর হ্যাশ পাওয়া যায় *

 Created by [Tousif Tasrik](https://github.com/inverse-tousif)

     

	    I just love her  🙃 💖
