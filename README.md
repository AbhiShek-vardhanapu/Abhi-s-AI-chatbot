# Abhi-s-AI-chatbot



This Streamlit application allows you to interact with Google's generative AI model, Gemini-Pro, in a chat-like interface. You can ask questions and receive responses, with the ability to save past conversations.

Features:

Chat with Gemini-Pro using text prompts.
View conversation history across multiple sessions.
Save and load past chat sessions for future reference.
Streamlined response display for a more natural conversation flow.
Requirements:

Python 3.6 or later
Streamlit library (pip install streamlit)
Google Cloud project with Generative AI service enabled (https://ai.google/discover/generativeai/)
API key for Generative AI service (stored in a .env file)
joblib library (pip install joblib)
Setup:

Create a Google Cloud project and enable the Generative AI service.
Create an API key for the service and store it in a file named .env at the root of your project directory. The .env file should contain a single line:
GOOGLE_API_KEY=YOUR_API_KEY
Install the required libraries:
Bash
pip install streamlit joblib
Use code with caution.

Running the application:

Open a terminal in your project directory.
Run the following command:
Bash
streamlit run app.py
Use code with caution.

Using the application:

The application will launch in your web browser.
You can start a new conversation or select a past chat from the sidebar.
Enter your question or prompt in the chat input field.
Click "Enter" or the send button to send your message to Gemini-Pro.
The application will display Gemini-Pro's response in a chat bubble format.
You can continue the conversation by asking follow-up questions.
Saving chat sessions:

The application automatically saves the chat history for the current session.
When you select a past chat from the sidebar, you'll be able to view the conversation history for that session.
Additional notes:

The code utilizes joblib to save and load chat history between sessions.
The code includes placeholders for potentially naming chat sessions, which is currently not implemented.
The response display is streamed to simulate a more natural conversation flow.
I hope this README provides a clear understanding of the application's functionality and usage!







