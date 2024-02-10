# Personal AI Chat App

## Overview

The AI Chat App is a chatbot implementation that pioneers a 30% responsiveness boost with zero-cost implementation and an interactive interface. It seamlessly integrates audio, image, and PDF AI models, leveraging the open-source Mistral LLM and Ollama.

## Features

- **Multi-Modal Integration:** The chatbot supports audio, image, and PDF inputs, providing a comprehensive conversational experience.

- **Responsive AI Models:** Achieves a 30% responsiveness boost through the integration of Mistral LLM and Ollama.

- **Zero-Cost Implementation:** The implementation is designed to be cost-effective, allowing users to harness advanced AI capabilities without incurring additional expenses.

- **Interactive Interface:** The Streamlit-based user interface provides a user-friendly experience, making it easy to interact with the chatbot.

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/ai-chat-app.git
    cd ai-chat-app
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app:**

    ```bash
    streamlit run app.py
    ```

4. **Open your browser and navigate to [http://localhost:8501](http://localhost:8501) to access the AI Chat App.**


## Rersults Demo

1. LLM uses Duckduckgo agent for retrieving latest information if it doesn't know the answer.

<img width="1208" alt="image" src="https://github.com/Deepakv1210/Personal-AI-Chatbot/assets/154148155/23ecc2bc-6513-4a3f-b185-46db2897b70a">

2. It is capable of interacting with multiple files.

<img width="1138" alt="image" src="https://github.com/Deepakv1210/Personal-AI-Chatbot/assets/154148155/ca507482-9c6a-4006-bdc7-1a11b2488243">

3. Image captioning model, generating textual descriptions of the visual content within an image.

<img width="1105" alt="image" src="https://github.com/Deepakv1210/Personal-AI-Chatbot/assets/154148155/f7c1efa2-d39f-4cb2-aec7-c3be039d1fd4">

4. Speech or audio processing model, enabling tasks such as transcription, speech recognition, or generating textual summaries based on the content of the audio data.




## Configuration

The app can be configured by modifying the `config.yaml` file. Adjust the parameters according to your preferences.

## Usage Instructions

1. Launch the app using the provided instructions.

2. Select or create a chat session from the sidebar.

3. Type your message in the "Type your message here" input field and click the "Send" button.

4. Optionally, check the "check internet?" checkbox to enable internet searches if LLM does't provide answers.

5. Upload audio, image, or PDF files using the respective file uploaders on the sidebar.

6. Explore the chat history and enjoy the interactive AI chat experience.

## Additional Notes

- The app utilizes Mistral LLM and Ollama for advanced natural language processing capabilities.

- For internet searches, ensure the "check internet?" checkbox is selected.

- Save your chat history using the "Save Chat History" button.

