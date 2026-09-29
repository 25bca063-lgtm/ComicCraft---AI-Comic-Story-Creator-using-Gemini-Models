# ComicCraft – AI Comic Story Creator using Gemini Models

A simple BCA college-project web application that turns a user's story idea into a structured comic using Gemini.

## Features
- Story idea input
- Genre, audience and panel selection
- Gemini-generated title and logline
- Character generation
- Panel-by-panel scenes
- Dialogue and visual prompts
- Responsive web UI
- API key kept on the server

## Technology
- HTML, CSS, JavaScript
- Node.js + Express
- Google GenAI JavaScript SDK
- Gemini model

## Run
1. Install Node.js.
2. Open a terminal in this project folder.
3. Run `npm install`.
4. Copy `.env.example` to `.env`.
5. Put your Gemini API key in `.env`:
   GEMINI_API_KEY=YOUR_GEMINI_API_KEY
6. Run `npm start`.
7. Open http://localhost:3000

Do not put your Gemini API key inside public/app.js or index.html.
