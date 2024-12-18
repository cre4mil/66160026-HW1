# 66160026-HW1

# git command used in this lab
- git clone https://github.com/cre4mil/66160026-HW1.git
- md css ,md js ,md images
- git checkout -b development
- git add .
- git commit -m "Initial structure"

<!-- สร้าง branch สำหรับหน้า home page  -->
- git checkout -b feature/home-page
- git add home.html 
- git commit -m "Add structure to home"
- git add home.html
- git commit -m "Add home page, add header and nav"
- git add home.html
- git commit -m "Add main highlight section html"
- git add home.html
- git commit -m "Add images"
- git add home.html
- git commit -m " Add article content for main section in home "
- git add home.html
- git commit -m " Add footer and contact details to home"

<!-- สร้าง branch สำหรับหน้า about page  -->
- git checkout development  
- git checkout -b feature/about-page
- git add about.html
- git commit -m "Add base structure for about"
- git add about.html
- git commit -m "Add header and navigation to about"
- git add about.html
- git commit -m "Add content and image for attraction"
- git add about.html
- git commit -m "Add footer to about"

<!-- สร้าง branch สำหรับหน้า contact page  -->
- git checkout development  
- git checkout -b feature/contact-page
- git add contact.html
- git commit -m "Add basic structure to contact"
- git add contact.html
- git commit -m "Add header and navigation to contact "
- git add contact.html
- git commit -m "Add personal information form to contact"
- git commit -m "Add message field and submit button to contact"
- git commit -m "Add footer to contact"

<!-- แก้ไขไฟล์ script.js -->
- git add js/script.js
- git commit -m "Add script"

<!-- แก้ไขไฟล์ style.css -->
- git add css/style.css
- git commit -m "Add global styles for body "
- git commit -m "Add header styles"
- git add css/style.css
- git commit -m "Add navigation menu styles with hover effects"
- git add css/style.css
- git commit -m "Add hamburger menu styles"
- git add css/style.css
- git commit -m "Add main content styles"
- git add css/style.css
- git commit -m "Add styles for images and fade-in animation"
- git add css/style.css
- git commit -m "Add article styles with shadow effects"
- git add css/style.css
- git commit -m "Add footer styles"
- git add css/style.css
- git commit -m "Add form styles "
- git add css/style.css
- git commit -m "Add responsive"

<!-- merge และ push  -->
- git checkout development
- git merge feature/home-page
- git merge feature/about-page
- git merge feature/contact-page
- git push origin development


