# Chemiverse — Chemistry, made curious

A responsive chemistry-learning web app for school, higher-secondary and college learners.

## Included in this first release
- Interactive periodic-table view with 118 element tiles and a searchable/filterable explorer
- Element detail popups and local explored-element tracking
- Five-question chemistry quiz with answer explanations, score and XP
- Chemi study companion with built-in starter explanations
- Learning dashboard, progress tracking and dark/light theme
- Responsive desktop and mobile layout

## Run locally
Clone or download this repository and open `index.html` in a modern browser. No build step or package installation is required. For a local server, run `python -m http.server 8000` and visit `http://localhost:8000`.

## Deploy with GitHub Pages
Open **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. GitHub will publish the static site after its deployment finishes.

## Current scope and next steps
This is a frontend starter release. Progress is stored in the current browser using localStorage and does not sync between devices. Chemi currently uses built-in starter explanations; live Gemini responses require a secure backend. User accounts, cloud sync, 3D molecular simulation and a virtual chemistry lab are not connected yet. Never place an AI API key in browser JavaScript or commit secrets to GitHub; keep keys in server-side environment variables.
