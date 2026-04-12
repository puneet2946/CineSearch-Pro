# CineSearch Pro – Movie & TV Explorer

## Overview

CineSearch Pro is a responsive web application that allows users to discover, search, and explore movies and TV shows using real-time data from the TMDb (The Movie Database) API.

The application focuses on providing a clean user interface along with interactive features such as search, filtering, sorting, and personalized watchlists.

---

## Features

### Search

* Search movies and TV shows by title
* Fetch and display real-time results using API integration

### Filtering

* Filter content based on:

  * Type (Movie / TV Show)
  * Release Year
  * Rating

### Sorting

* Sort results by:

  * Popularity
  * Rating
  * Alphabetical order

### Watchlist

* Add and remove items from a watchlist
* Data stored using localStorage
* Separate watchlist section for easy access

### Theme Toggle

* Switch between dark and light mode
* User preference stored in localStorage

### Pagination

* Navigate through multiple pages of results
* Improves performance and usability

### Movie Details

* View detailed information:

  * Poster
  * Title
  * Rating
  * Overview
  * Release date

### Trending Section

* Displays trending movies and TV shows
* Keeps the content dynamic and engaging

---

## Technologies Used

* HTML5
* CSS3 / Tailwind CSS
* JavaScript (ES6+)
* TMDb API

---

## API Used

The Movie Database (TMDb) API
https://www.themoviedb.org/documentation/api

---

## Concepts Implemented

* Fetch API (fetch, async/await)
* Array Higher Order Functions:

  * map()
  * filter()
  * sort()
* DOM Manipulation
* Event Handling
* Local Storage
* Debouncing (for optimized search)

---

## Project Structure

cineSearch-pro/
│── index.html
│── style.css
│── script.js
│── pages/
│     └── watchlist.html
│── utils/
│     └── api.js

---

## How to Run the Project

1. Clone the repository:
   git clone https://github.com/your-username/cineSearch-pro.git

2. Navigate to the project folder:
   cd cineSearch-pro

3. Open index.html in your browser

---

## Future Enhancements

* Recently searched suggestions
* Trailer preview integration
* Progressive Web App (PWA) support
* User authentication system

---

## Demo Link

* https://cine-search-pro-jade.vercel.app/

---

## Best Practices Followed

* Clean and modular code structure
* Responsive design across devices
* Reusable functions (DRY principle)
* Proper error handling for API calls

---

## Conclusion

CineSearch Pro demonstrates the practical implementation of JavaScript fundamentals, API integration, and responsive UI development. The project focuses on usability, performance, and clean design to deliver a smooth user experience.

---

## Author

Puneet
BTech CSE (AI/ML) – Newton School of Technology

---
