🚀 SparkBytes Frontend

The frontend for SparkBytes, a platform designed to manage and distribute extra food from Boston University events.

📌 Features

🔍 View upcoming events with available food

📅 Event details page with descriptions and locations

📝 User authentication (login, signup)

🎨 Responsive UI using React & TailwindCSS

🔗 Integration with the backend API

🛠️ Tech Stack

Framework: React (Vite)

UI Library: TailwindCSS

State Management: React Context API

Routing: React Router

API Communication: Axios

⚙️ Setup & Installation

1⃣ Clone the repository

git clone https://github.com/yourusername/sparkbytes-frontend.git
cd sparkbytes-frontend

2⃣ Install dependencies

npm install

3⃣ Set up environment variables

Create a .env file in the root directory and configure:

VITE_API_URL=http://localhost:8000/api

4⃣ Start the development server

npm run dev

Frontend should now be running at: http://localhost:5173/

🚀 Deployment on Heroku

🔐 Login to Heroku

heroku login

🌍 Create a Heroku app

heroku create sparkbytes-frontend

⚙️ Set environment variables

heroku config:set VITE_API_URL=https://sparkbytes-backend.herokuapp.com/api

🛣️ Deploy to Heroku

git add .
git commit -m "Deploy frontend"
git push heroku main

🔥 Open the deployed app

heroku open

🌟 License

This project is licensed under the MIT License.

