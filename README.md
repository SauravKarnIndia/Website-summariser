# AI-driven Website-summariser
A small web application where a user can enter any public URL. The app fetches the page content, sends it to an AI model, and shows a short summary.

## Description
This web application allows users to enter a public URL and receive a concise AI-generated summary of the webpage content.

## Tech Stack
- Frontend: React(JavaScript)
- Backend: Node.js, Express
- AI: OpenAI GPT API

## How AI Was Used
The application sends extracted webpage text to OpenAI's language model, which generates a short, human-readable summary in few sentences.

## Setup Instructions
1. Clone the repository
2. Run `npm install`
3. Create a `.env` file and add:
OPENAI_API_KEY=your_api_key_here

Copy code
4. Run `node index.js`

## Run code
Run `node index.js`
 You should see something like "Server running on http://localhost:5000"
 Keep this terminal open—the backend needs to be running for the frontend to work.
Open a new terminal (keep the backend one running) and navigate to the frontend folder.
 Start the development server:
   
   npm run dev
   
   This will open your browser to something like "http://localhost:5173/" where you can use the app!

## Notes
- Only public URLs are supported
- Large pages are truncated before being sent to the AI
