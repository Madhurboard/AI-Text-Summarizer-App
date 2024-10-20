
# AI Text Summarizer

## Overview

The **AI Text Summarizer** is a web application built using HTML, CSS, and JavaScript, which provides concise summaries of long text inputs using the Hugging Face API. The app was developed and tested using tools like Postman API Console and Replit for easy integration and collaboration.

## Features

- **User-friendly Interface**: Simple and clean UI for easy interaction.
- **AI-powered Summarization**: Uses Hugging Face's pre-trained models to generate accurate text summaries.
- **Cross-platform Compatibility**: Accessible on all modern web browsers.
- **API-based**: Integrates Hugging Face’s Summarization API for backend functionality.

## Technologies Used

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
- **API**: 
  - Hugging Face Summarization API
- **Tools**: 
  - Postman API Console for testing API requests
  - Replit for development and hosting

## Getting Started

### Prerequisites

1. **Hugging Face API Key**: 
   - Sign up at [Hugging Face](https://huggingface.co/) and generate an API key.
   
2. **Development Environment**: 
   - You can use Replit or any local IDE (e.g., VS Code).

### Setup Instructions

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/ai-text-summarizer.git
   cd ai-text-summarizer
   \`\`\`

2. Create a `.env` file for your Hugging Face API key (for deployment):
   \`\`\`bash
   API_KEY=your-huggingface-api-key
   \`\`\`

3. Update `script.js` to include your API key in the API request.

4. Run the project locally by opening `index.html` in a browser or deploying it on Replit.

### Running the App

1. Open the `index.html` file in your browser or deploy on Replit.
2. Paste or type in the text you want to summarize in the input field.
3. Click the **Summarize** button to generate a summary via the Hugging Face API.

## Testing API with Postman

To manually test the API:

1. Open Postman and create a **POST** request to Hugging Face’s Summarization API.
2. In the **Headers**, add:
   - `Authorization: Bearer YOUR_API_KEY`
3. In the **Body**, provide the input text:
   \`\`\`json
   {
     "inputs": "Your long text to summarize..."
   }
   \`\`\`

4. Send the request and check the response for the summary.

## File Structure

\`\`\`
.
├── index.html           # Main HTML page for the app
├── styles.css           # CSS styles for the UI
├── script.js            # JavaScript for API calls and functionality
└── README.md            # Project documentation
\`\`\`

## Deployment

You can deploy the project on:

- **Replit**: Create a new project, upload your files, and ensure the Hugging Face API key is securely added.
- **GitHub Pages**: For static hosting, push the repository to GitHub and enable GitHub Pages in the repository settings.

## License

This project is licensed under the MIT License.

---

Feel free to contribute, suggest improvements, or report bugs!
