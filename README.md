# Chatbot Project
## Overview
This is a simple chatbot built using HTML, CSS, and JavaScript. The chatbot interacts with users by sending and receiving messages, and it utilizes the Gemini API for AI-generated responses.

## Features
- User can send messages to the chatbot.
- Bot generates responses using the Gemini API.
- Typing indicator to simulate bot thinking.
- Interactive UI with avatars for user and bot messages.

## Technologies Used
- HTML
- CSS
- JavaScript
- Gemini API (for AI responses)

## Setup Instructions
1. Open `chatBot.html`,`chatBot.css`,`chatBot.js` in your code editor  .

## API Configuration
1. Obtain an API key from Gemini.
2. Replace `API_KEY` in `chatBot.js`:
   ```js
   const API_KEY = "your-api-key-here";
   ```
3. Ensure the correct API endpoint is used:
   ```js
   const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${API_KEY}`;
   ```

## Usage
- Type a message in the input field and press send.
- The bot will generate a response after a short delay.

## Future Improvements
- Enhance UI with animations.
- Add voice-to-text functionality.
- Improve bot response accuracy.
- Make use of emogi and attachment icon.


##Designed by Agrim Saxena.

