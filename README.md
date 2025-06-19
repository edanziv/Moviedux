# Moviedux

Moviedux is a simple React application that allows users to browse a list of movies and manage a personal watchlist. Users can add or remove movies from their watchlist, and navigate between the main movie grid and their saved watchlist using React Router.

## Features

- Browse a list of movies loaded from a JSON file
- Add or remove movies from your watchlist
- View your watchlist on a separate page
- Simple and clean UI with navigation
- Built with React functional components and hooks

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/moviedux.git
   cd moviedux
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Add your `movies.json` file:**
   Place a `movies.json` file in the `public` directory. This file should contain an array of movie objects, for example:
   ```json
   [
     {
       "id": 1,
       "title": "Inception",
       "year": 2010,
       "poster": "inception.jpg"
     },
     ...
   ]
   ```

4. **Start the development server:**
   ```
   npm start
   ```

5. **Open your browser:**
   Visit [http://localhost:3000](http://localhost:3000) to view the app.

## Project Structure

```
moviedux/
├── public/
│   └── movies.json
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── MoviesGrid.js
│   │   └── WatchList.js
│   ├── App.js
│   ├── App.css
│   └── styles.css
├── package.json
└── README.md
```

## Technologies Used

- React
- React Router
- JavaScript (ES6+)
- CSS

---

*Happy movie watching!*
