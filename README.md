🎲🗓️ React Chatbot (Embedded via Script Tag)
A lightweight chatbot built with React, fully embedded inside a simple HTML file using a <script> tag. This project demonstrates how to run React with JSX (via Babel) without a build system.
The chatbot can respond to three types of requests:
Roll a die → returns a number 1–6
Flip a coin → returns Heads or Tails
Tell the date → returns today’s date
Perfect for learning React or experimenting with simple NLP logic inside a minimal setup.
✨ Features
🎲 Die roll command — “roll a die”, “roll”, “dice”, etc.
🪙 Coin flip command — “flip a coin”, “coin”, “heads or tails”, etc.
📅 Date command — “what’s the date”, “today’s date”, etc.
⚛️ Uses React and ReactDOM directly from CDN
💡 JSX powered by Babel Standalone
🚀 No bundlers, Node, or installs required
📂 Project Structure
project/
│── index.html      // Contains your React chatbot
└── styles.css      // Optional styling
🛠️ Technologies Used
HTML5
React 18 (CDN)
ReactDOM 18 (CDN)
Babel Standalone for JSX
CSS (optional)
🚀 Getting Started
Download or clone the project.
Open index.html in your browser.
Start chatting with the bot!
No terminal, no dependencies — everything runs in the browser.
🧠 How the Chatbot Works
The chatbot listens for keywords in the user’s message:
Die Rolling
If the user types anything like:
“roll a die”
“roll”
“dice”
The bot responds with a number 1–6.
Coin Flip
If the user types:
“flip a coin”
“coin”
“heads or tails”
The bot returns Heads or Tails.
Date
If the user asks:
“what’s the date”
“today’s date”
“date?”
The bot responds with today’s formatted date.
If the input doesn't match any command, the bot politely explains what it can do.
