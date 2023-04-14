![localhost_5000_](https://user-images.githubusercontent.com/102640510/232117305-2f3679b2-b162-4fb9-8555-8b8a2d59b7de.png)

# Open AI DALL-E Image Generator
This project is a web application that allows users to generate images from textual descriptions using OpenAI's DALL-E model.

### Features
- A simple user interface to enter textual prompts and choose the desired image size
- A backend server that handles requests to OpenAI's API and generates images based on the provided input
- Display of the generated image on the user interface

### Getting Started

#### Prerequisites
- Node.js
- An API key from OpenAI

#### Installation
1. Clone the repository:
`git clone https://github.com/JohnnyCulbreth/open-ai-dalle-gen.git`

2. Install the required dependencies:
`npm install`

3. Create a .env file in the root directory with the following content:
`OPENAI_API_KEY=your_api_key_here`
Replace your_api_key_here with your OpenAI API key.

4. Start the server:
`npm run dev`

5. Visit http://localhost:5000 in your browser to use the application.

### Built With
- Node.js
- Express
- OpenAI API
- Vanilla JavaScript, HTML, and CSS
