# Gemini AI Agent with Tool Calling 

This project is a command-line AI agent built using the Google Gemini API.  
The agent intelligently decides when to use predefined tools to answer user queries.

---

## Features

- Add two numbers
- Check whether a number is prime
- Fetch live cryptocurrency prices using CoinGecko API
- Answer general questions using Gemini AI
- Demonstrates AI tool/function calling

---

## Tech Stack

- Node.js
- JavaScript (ES Modules)
- Google Gemini API (@google/genai)
- CoinGecko Public API
- readline-sync

---

## Project Structure

AI-AGENT
├── index.js  
├── package.json  
├── package-lock.json  
├── .gitignore  
└── Day4.svg  

---

## Example Usage

Ask me anything--> 5 aur 5 ka sum  
10  

Ask me anything--> Is 17 a prime number?  
Yes, 17 is a prime number.  

Ask me anything--> Bitcoin price  

---

## How It Works

- User input is sent to Gemini
- Gemini decides whether a tool is needed
- The corresponding tool is executed
- Tool output is sent back to Gemini
- Gemini generates the final response

---

## Security

- API keys are stored using environment variables
- `.env` is excluded using `.gitignore`
- No sensitive information is committed

---

## Future Improvements

- Add more tools
- Improve error handling
- Convert CLI to web application
- Persist conversation history

---

## Author

Pandurang More
