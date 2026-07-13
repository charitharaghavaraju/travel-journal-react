# My Travel Journal 🌍

A simple React app that displays a personal travel journal — a list of trip entries, each with a photo, country, dates, a Google Maps link, and a short description.

## Features

- Renders a list of journal entries from static data (`data.js`)
- Each entry shows a main image, title, country, trip dates, description, and a link to view the location on Google Maps

## Tech Stack

- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)

## Getting Started

### Installation

```bash
npm install
```

### Run the dev server

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview the production build

```bash
npm run preview
```

## Project Structure

```
├── components/
│   ├── Header.jsx    # Page title and icon
│   └── Entry.jsx      # Single journal entry card
├── data.js             # Journal entry data
├── App.jsx              # Renders the list of entries
├── index.jsx              # React entry point
├── index.html
└── index.css
```
