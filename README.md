একটা প্রজেক্ট কিভাবে গিট এর মদ্ধে কিভাবে আপলোড করব ঃ


Follow these steps to upload your project to Github


1) git init

2) git add .

3) git commit -m "Add all my files"

4) git remote add origin https://github.com/yourusername/your-repo-name.git

Upload of project from scratch require git pull origin master.

5) git pull origin master

6) git push origin master

If any problem occurs in pushing use git push --force origin master

======================================*****======================================================
 কিভাবে আমরা একটি ব্রাঞ্চ তৈরি করবও এবং আপ্লয়াদ করব এবং কন্ট্রোল করব ঃ
 
 ব্রাঞ্চ তৈরি ঃ
 
	1. git branch brachName
	
কিভাবে আমরা ব্রাঞ্চ এর লিস্ট দেখব ঃ

        2. git branch --list
        
 কিভাবে আমরা ব্রাঞ্চ সুইচ করবও ঃ
 
        3. git chechout branchName
 **************************++++++***************************
                        আমরা চাইলে একসাথে ৩ টা কাজ করবতে পারি । 
                        
                        git checkout branch name
 **************************++++++***************************
 
 এখন আমরা একটা ফাইল তৈরি করবও ফাইল তৈরি করার জন্য আমাদের কমান্ড ঃ
 
        touch fileName
        
   এখন আমাদের কমেন্ট দিতে হবে 
   
        4. git commit -m "Add all my files"
        
   এখন আমদের পুষ করার জন্য এই কমান্ড দিতে হবে ,
        
        5. git push --set-upstream origin branchName
       
