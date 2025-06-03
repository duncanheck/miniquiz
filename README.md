🧠 Mini Trivia Quiz App
A simple React + Vite app that pulls multiple-choice trivia questions from the Open Trivia Database API and lets users test their knowledge in a fun, interactive way.

🛠 Features
✅ React + Vite setup

✅ User form to collect name, category, and difficulty

✅ Fetches live multiple choice questions via API

✅ Displays results with correct/incorrect feedback

✅ Clean UI styled with CSS

📦 Tech Stack
React

Vite

Open Trivia DB API

CSS for styling

📂 Folder Structure
css
Copy
Edit
src/
├── App.jsx
├── main.jsx
├── assets/
│   └── style.css
├── components/
│   ├── HomePage.jsx
│   ├── QuestionForm.jsx
│   └── Results.jsx
⚙️ How to Run Locally
Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/mini-trivia-quiz.git
cd mini-trivia-quiz
Install dependencies

bash
Copy
Edit
npm install
Start the dev server

bash
Copy
Edit
npm run dev
Visit http://localhost:5173

✏️ Customize
You can add:

More questions per session

Leaderboards with Firebase or Supabase

User avatars or score tracking

Dark mode toggle

🐛 Known Issues
Sometimes API returns no question if too specific (e.g. Hard + Sports)

📄 License
MIT — Free to use for educational and commercial purposes.
