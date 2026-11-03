# Image Search (Pixabay)

A React app that searches the Pixabay API for pictures of cats or dogs and shows the first four results.

## How it works

- Open `/Pixxa?s=cats` or `/Pixxa?s=dogs`, or type a search term in the input
- Any other term shows a validation message
- Unknown routes show a 404 page

## Tech stack

React, React Router 6, the Pixabay API.

## Getting started

```bash
npm install
npm start
```

The app opens at http://localhost:3000.

## Configuration

Create a `.env` file (see `.env.example`) with your own free key from https://pixabay.com/api/docs/:

```
REACT_APP_PIXABAY_KEY=your-pixabay-key
```
