# Ia_openai_gen

This is a simple image generator built with Node.js and Express that uses OpenAI's Dall-E models to generate images.

Usage
Rename the example.env file to .env.

Generate an API KEY at OpenAI and add it to the .env file.

Install the dependencies : 

npm init -y
npm i express openai dotenv
npm i -D nodemon

Run server

npm run dev
Visit http://localhost:5000 in your browser.

The endpoint is at POST http://localhost:5000/openai/generateimage.
