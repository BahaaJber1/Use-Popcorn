# usePopcorn

A React app for searching movies, viewing details, and tracking your watched list. Built as part of a React learning project.

<img width="1916" height="907" alt="image" src="https://github.com/user-attachments/assets/d8f4ce3b-a220-45f9-b0f8-9a05594e81be" />

<img width="1916" height="905" alt="image" src="https://github.com/user-attachments/assets/99b3f695-70c0-4f95-928f-4cdce2eaeb8f" />

<img width="1916" height="908" alt="image" src="https://github.com/user-attachments/assets/14c36af1-4c9c-487d-9839-cf0c91e59d5a" />




## Features

- Search for movies using the OMDb API.
- View movie details, including poster, plot, actors, director, and ratings.
- Rate movies with a star rating component.
- Add movies to your watched list and track your own ratings.
- See summary statistics for watched movies (average ratings, runtime).
- Remove movies from your watched list.
- Responsive and interactive UI.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone this repository or download the source code.
2. Navigate to the project directory:

   ```bash
   cd 07 usepopcorn
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

### Running the App

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Project Structure

- `src/App.js` – Main React application file.
- `src/StarRating.js` – Star rating component.
- `src/useMovies.js` – Custom hook for fetching movies.
- `src/useLocalStorageState.js` – Custom hook for persisting watched list.
- `src/useKey.js` – Custom hook for keyboard shortcuts.
- `src/index.js` – Entry point for React.
- `src/index.css` – App styles.

## Customization

- You can change the OMDb API key by editing the `KEY` constant in `src/App.js`.
- Extend the watched list logic or UI by editing the relevant components.

## License

This project is for educational purposes only.
