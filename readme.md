📚 StudyNest

A place where students finally stop asking “Sir, notes send?”

🚀 Overview

StudyNest is my attempt at ending the legendary WhatsApp note-requesting marathon in college.
Instead of chasing lecturers or spamming class groups, students can now access all study resources in one place.

Lecturers upload.
Students download.
Admins… well, they enjoy power.

Basically — a clean, organized study material hub that just works.

🎯 Why I Made This

Because chaos is not a learning system.
And because if I had to hear “Bro PDF share cheyyara” one more time… 🧨

This project solves:

✅ Scattered notes everywhere
✅ Students begging lecturers for PDFs
✅ Staff forwarding the same file 50 times
✅ My sanity slowly fading

So yes, digital peace achieved.

🧠 Key Features
Feature	Description
👤 User Roles	Admin, Lecturer, Student
🔐 Role-Based Login	Because random people shouldn't upload memes as study notes
📂 Subject-Wise File Uploads	PDFs go to their subjects, not to random folders
⚙️ Auto-Generated Subject Pages	Add a subject → boom, a page magically appears
🗑️ Delete Files/Subjects	Cleanliness = Godliness
🎒 Student Dashboard	Browse and download notes like a civilized student


🛠️ Tech Stack

Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Node.js, Express.js
Database	MongoDB (with Mongoose)
Uploads	Multer 
Auth	bcrypt.js

⚙️ How It Works
👨‍🏫 Lecturer

Adds subjects

Uploads PDFs

Deletes old files when syllabus suddenly changes 🙃

Backend generates subject HTML pages automatically

🎓 Student

Opens subjects

Downloads notes

Pretends they will actually read them

🧙 Admin

Creates users

Controls access


🧾 Installation

Clone the project:

git clone https://github.com/Mahesh-Kiran/StudyNest.git
cd StudyNest
npm install
node index.js


MongoDB should be running too.

🧩 Problems Solved
Problem	How StudyNest Fixes It
Notes everywhere	Central hub for files
Time wasted asking teachers	Upload once → available forever
Poor organization	Subject-wise separation
Security issues	Hashed passwords + role permissions
Manual sharing chaos	Automated pages + file management

And yes, finally one platform > 50 WhatsApp groups 🙏

💡 Lessons Learned

File systems + MongoDB = tricky but doable

Multer hates mistakes, so don't make them

Frontend + backend teamwork is like group projects… except it actually worked 🤪

🎯 Future Improvements

Cloud storage (because PDFs get heavy)

Better UI (we all start somewhere)

Email/SMS notifications for new notes