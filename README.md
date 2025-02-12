# NetflixGPT
Movies recomandation with AI.

Setup
Install react app using create-react-app (CRA)
npx create-react-app netflix-gpt
Create .env file and put configure
REACT_APP_BASE_URL = YOUR_APPLICATION_BASE_URL; // http://localhost:300
REACT_APP_OPENAI_KEY = YOUR_API_KEY_WILL_HERE;
REACT_APP_TMDB_KEY = YOUR_API_KEY_WILL_HERE;
REACT_APP_FIREBASE_KEY = YOUR_FIREBASE_KEY
REACT_APP_FIREBASE_APP_ID = YOUR_FIREBASE_APP_ID
Install and init tailwind css
npm install -D tailwindcss
npx tailwindcss init
Configure tailwind css in your project

npx tailwindcss init command will create a file tailwind.config.js in your project's root directory. Open tailwind.config.js and replace all content with below code.

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
Add the @tailwind directives for each of Tailwind’s layers to your ./src/index.css file.
@tailwind base;
@tailwind components;
@tailwind utilities;
Now you created a react app with tailwind css successfully. Now run the below command on your terminal to start your local development server.
npm start
Features
Home Page (is user !authorised)

Signin/Signup Page
SignInForm / SignUpForm
Browse Page

Navbar
Showcase
Trendings
MoviesSuggestion
MoviesList * N
NetflixGPT

Search
MoviesSuggestion
Screen Shot
Live Demo : (Live Demo)

Screen Shot
Landing Page

Landing Page

Signin Page

Signin Page

Signup Page

Signup Page

Browse Page

Browse Page

Movie List

Movie List

Shimmer Loading

Shimmer Loading

Search Page

Search Page

Watch Now Page

Watch Now Page

💖 Support This Project
Thank you for taking the time to explore NetflixGPT! This project represents an in-depth implementation of features extracted from the inspiring course "Namaste-React" by Akshay Saini. It's been a rewarding journey, and I'm genuinely grateful for the opportunity to create and share this with the community.

I want to express my heartfelt thanks to everyone who has shown interest and provided feedback. Your support and involvement mean a lot to me.

If you have any questions, suggestions, or just want to connect, feel free to reach out.

<Happy coding />

🙏 Thank You 🙏
Feel free to modify it to suit the tone and style of your project. The goal is to encourage participation, collaboration and learning.

Made with ❤️ and React.
