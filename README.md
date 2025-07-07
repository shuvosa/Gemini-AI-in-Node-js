# Gemini-AI-in-Node-js

This project demonstrates how to use the [@google/generative-ai](https://www.npmjs.com/package/@google/generative-ai) Node.js package to interact with Google's Gemini AI models.

## Features

- Connects to Gemini AI using an API key
- Sends a prompt and prints the AI-generated response
- Uses environment variables for secure API key management

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- A Google Generative AI API key

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/shuvosa/Gemini-AI-in-Node-js.git
   cd Gemini-AI-in-Node-js
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up your API key:**
   - Create a `.env` file in the project root:
     ```
     API_KEY=your-google-generative-ai-api-key
     ```
   - **Note:** Remove `export` and quotes if present.

4. **Run the example:**
   ```sh
   node index.js
   ```

## File Structure

- [`index.js`](index.js): Main script to interact with Gemini AI
- [`package.json`](package.json): Project dependencies
- [`.env`](.env): Environment variables (not committed to version control)

## Example Output

```
Once upon a time, there was an AI who discovered the secrets of magic...
```



