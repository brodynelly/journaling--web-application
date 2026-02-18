# Journaling Web App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![CI](https://github.com/brodynelly/journaling--web-application/actions/workflows/ci.yml/badge.svg)](https://github.com/brodynelly/journaling--web-application/actions/workflows/ci.yml) ![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript)

A mockup for a daily journaling web app with drawable entries. Concept prototype for a guided journaling experience — handwritten input via Apple Pencil on iPad, with entries stored and displayed on the home feed.

**Live demo:** https://marvelous-kelpie-866eb4.netlify.app/

## Screenshots

![Home feed](https://github.com/user-attachments/assets/aacea867-a493-4fbd-b876-1e81d7732b3f)
![Entry view](https://github.com/user-attachments/assets/aadcc4e3-45ca-4edc-9f45-f5e7e824e797)

## Tech Stack

- **TypeScript / React** — UI and component logic
- **Tailwind CSS** — styling
- **Netlify** — deployment
- **REST API** — basic POST routes for journal entries

## Getting Started

```bash
git clone https://github.com/brodynelly/journaling--web-application
cd journaling--web-application
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

## Usage

- The home page displays a feed of existing journal entries
- Click **New Entry** to create a drawable canvas entry
- Entries are posted to the API and reflected in the feed

## Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Route-level views
├── api/            # API call helpers
└── main.tsx        # App entry point
```

## License

MIT
