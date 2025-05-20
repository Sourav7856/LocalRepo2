📌 New Project GitHub pe kaise push kare — Full Step by Step
🎯 1️⃣ Local me apna naya project ka folder bana lo
bash
Copy
Edit
mkdir myNewProject
cd myNewProject
🎯 2️⃣ Us folder ko git repo banao
bash
Copy
Edit
git init
🎯 3️⃣ Ab apne project ke files banao ya copy kar lo
Example:

bash
Copy
Edit
echo "Hello World" > index.html
🎯 4️⃣ Sab file staging me daalo
bash
Copy
Edit
git add .
🎯 5️⃣ Commit karo
bash
Copy
Edit
git commit -m "First commit"
🎯 6️⃣ GitHub pe nayi repo banao
GitHub pe jaake "New Repository" pe click karo

Repo ka naam do (jo chaaho)

Create kar do (kuch check karne ki zarurat nahi)

🎯 7️⃣ Ab GitHub wali repo ka URL copy karo
Jaisa:

arduino
Copy
Edit
https://github.com/username/myNewProject.git
🎯 8️⃣ Ab us remote URL ko local repo me add karo
bash
Copy
Edit
git remote add origin https://github.com/username/myNewProject.git
Check karne ke liye:

bash
Copy
Edit
git remote -v
🎯 9️⃣ Ab push kar do GitHub pe
bash
Copy
Edit
git push -u origin main
Agar main branch nahi hai to pehle bana lo:

bash
Copy
Edit
git branch -M main
git push -u origin main
