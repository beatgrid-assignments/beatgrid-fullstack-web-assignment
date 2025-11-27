# The movie database search

Welcome to the Beatgrid fullstack assignment.

## 🎯 Objective

You are building a movie search. Your app allows users to search through a movie dataset using an autocomplete search input.

### ✅ Requirements

- As the user types in the search input, display a dropdown with autocomplete suggestions.
- When the user selects a movie from the dropdown, display a card with detailed information about the selected title.
- When the search input is focused and empty, a dropdown should show the 10 most recently selected movies, ordered from the most recent viewed to the least recent.
- The backend persists each selection, no duplicates and survives a backend restart.
- Ensure the app can efficiently handle network requests and larger datasets.
- Bonus: match against the movie's name, actors, and directors.

## 🧩 Components

### Database

A movie database is provided for you.

To run the database:

- make sure you have [Docker](https://docs.docker.com/) installed
- navigate to the `database` folder
- run `docker compose up -d`
- import data by running `cat init.sql | mysql -h localhost -u root --port 53306 --protocol TCP`

The database is now accessible on port `53306`.

The backend application is already set up to connect to the database.

### Backend

The backend exists in two flavors: Java and Kotlin. Choose your preferred language.

To run the app:

- make sure you have Java 17+ installed
- navigate to the `backend-java` or `backend-kotlin` folder
- run `./gradlew bootRun`

You now have access on `localhost:8080`.

### Frontend

The frontend is bootstrapped with [Vite](https://vitejs.dev/) (using the React + Typescript variant) for your convenience.

To run the app, run `npm install` and then `npm run dev`. The app will be available at `http://localhost:5173/`

## 🧪 Notes

- Focus on functionality, correctness and maintainability. You are not expected to build a production-ready product.
- The UI design is up to you.
- You may modify the database schema as you see fit.
- You may use libraries and tools, including AI assistants - you'll walk us through your solution in a follow-up conversation.
- Feel free to reach out if you have any questions.

## 📦 What to Submit

Please provide:
- The GitHub repository link

## 🙌 Good luck!

We’re looking forward to reviewing your solution.
