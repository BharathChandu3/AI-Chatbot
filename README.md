# AI-Chatbot


## Overview
This project is a web-based chatbot interface that allows users to input messages, process intents, and interact with the chatbot. The chatbot provides simple responses to greetings and common questions, as well as Google search results using the Google Custom Search API.

## Features
- **User Input**: Type a message and receive responses from the chatbot based on keyword matching.
- **Intent Processing**: The chatbot recognizes intents such as greetings, goodbyes, asking for help, and more.
- **Google Search Integration**: If the chatbot doesn't recognize an intent, it searches Google using the Custom Search API.
- **Interactive UI**: Includes a dynamic chat interface with separate message styles for user input and chatbot responses.

## Technologies Used
- **HTML, CSS, JavaScript**: For the structure, design, and functionality of the chatbot interface.
- **Google Custom Search API**: Used for searching the web when the chatbot doesn't have a pre-defined response.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/BharathChandu3/AI-Chatbot.git
   cd <repository_name>
# Chatbot UI with Google Custom Search Integration

## Google Custom Search Setup:
1. **Create a project in the Google Developer Console**.
2. **Enable the Custom Search API**.
3. **Generate an API key** and create a **Custom Search Engine ID**.

## Update API Keys:
- Open the `script.js` file.
- Replace the placeholder values for the `apiKey` and `searchEngineId` with your actual Google API key and Custom Search Engine ID.

## Usage:
1. Open `index.html` in your web browser.
2. Type your message in the input box and click the **Send** button or press **Enter**.
3. The chatbot will respond with predefined responses based on recognized keywords.
4. If no match is found, it will search Google using the provided query and display the first result.

## Project Structure:
- **index.html**: The main HTML structure of the chatbot UI.
- **styles.css**: Contains all the styles for the chatbot interface.
- **script.js**: Handles the chatbot logic, including sending messages, processing intents, and making API requests.

## Key Functionalities:
### Chat Interface:
- User types a message, and the chatbot displays both the user's message and the chatbot's response in the chat window.

### Intent Recognition:
- The chatbot uses simple keyword-based recognition to match user input with pre-defined intents and provide a relevant response.

### Google Custom Search:
- If the chatbot doesn't recognize the user's message, it automatically queries the Google Custom Search API for relevant results and displays the top link in the chat.

## Styles and Design:
- The chat interface includes message boxes for both the user and the chatbot, along with a smooth scrolling effect.

## Future Enhancements:
1. **Advanced Natural Language Processing**: Improve intent recognition with more advanced NLP models.
2. **Speech-to-Text Integration**: Allow users to input queries using voice.
3. **More Complex Conversations**: Expand the chatbot's abilities with more detailed intents and responses.

## License:
This project is licensed under the MIT License. See the LICENSE file for details.




Email: tirumalasettybharathchandu@gmail.com
GitHub: https://github.com/BharathChandu3
