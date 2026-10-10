# Movie Ratings

A responsive movie search website built with HTML, CSS, and JavaScript using the OMDb API.

## Features
- Search for movies and browse matching results
- Live title suggestions while typing (titles must start with the entered text)
- Movie posters and release years
- Click a result to see IMDb rating, release date, plot, director, cast, genre, runtime, language, awards, and box office when available
- Responsive dark theme for mobile and desktop

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a browser.
3. Search for a movie title.

The page uses the OMDb API key configured in `index.html`. For a public production website, avoid exposing API keys in client-side code; use a small backend proxy and rotate the key if it has been shared publicly.

## API
Movie information is provided by [OMDb API](https://www.omdbapi.com/).
