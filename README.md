# 🍿 usePopcorn
An interactive React application that allows users to search for movies, view details, rate them, and manage their watchlist. Built to enhance proficiency in React.js and API integration.

## 📌 Live Demo
🔗 [usePopcorn Live](https://bharathraj1614.github.io/usePopcorn/)

## 📖 Table of Contents
- [Project Overview](#-project-overview)  
- [Features](#-features)  
- [Technologies Used](#%EF%B8%8F-technologies-used)  
- [Getting Started](#-getting-started)  
- [Available Scripts](#-available-scripts)  
- [Project Structure](#-project-structure)  
- [Contributing](#-contributing) 

## 🚀 Project Overview
usePopcorn is a React.js-based application that enables users to explore movies, rate them, and manage their watched movies list. By leveraging the **OMDb API** (Open Movie Database), the app provides access to an extensive movie database, allowing users to find detailed movie information, including genre, cast, director, ratings, and more. This project was built as part of my journey to learning React.js and improving my frontend development skills.

## ✨ Features
✔️ **Movie Search** – Allows users to search for movies by title.  
✔️ **Movie Details** – Displays detailed information about selected movies.  
✔️ **Rate and Add to Watched** – Users can rate movies and add them to their watched list.  
✔️ **Remove from Watched** – Users can remove movies from their watched list.  
✔️ **Watched Movies Statistics** – Displays statistics about watched movies.  
✔️ **Keyboard Shortcuts** – Use **Enter** key to start searching and **Esc** key to close movie details.  
✔️ **Local Storage** – Watched movies are stored in the browser's local storage for persistence.  

## 🛠️ Technologies Used
- **React.js** – Frontend framework for building the UI.  
- **Create React App** – Boilerplate for setting up the project.  
- **CSS Modules** – Ensures scoped styling.  
- **JavaScript (ES6+)** – Implements modern JavaScript features.  
- **OMDb API** – Fetches movie data.  
- **GitHub Pages** – Deployed the project using GitHub Pages.  

## ⚡ Getting Started

### Prerequisites  
- **Node.js**: Download and install from [Node.js](https://nodejs.org/)  
- **npm**: Comes with Node.js (Check with `npm -v`)  

### Installation Steps  
```sh
# Clone the Repository
git clone https://github.com/bharathraj1614/usePopcorn.git
cd usePopcorn

# Install Dependencies
npm install

# Start the Development Server
npm start

#Open http://localhost:3000 in the browser.
```

## 📜 Available Scripts
``` sh
npm start      # Runs the app in development mode  
npm test       # Launches the test runner  
npm run build  # Builds the app for production  
npm run eject  # Ejects the app configuration (use with caution)
```
## 📂 Project Structure
```csharp
usePopcorn/
├── public/           # Static assets
│   ├── index.html
│   └── ...
├── src/              # Source code
│   ├── components/   # Reusable components
│   ├── assets/       # Images & other assets
│   ├── App.js        # Main app component
│   ├── index.js      # Entry point
│   └── ...
├── .gitignore
├── package.json
├── README.md
└── LICENSE
```
## 🤝 Contributing
- Fork the repository.
- Create a new branch (feature/YourFeature).
- Commit your changes (git commit -m "Added new feature").
- Push to your branch (git push origin feature/YourFeature).
- Open a Pull Request.
