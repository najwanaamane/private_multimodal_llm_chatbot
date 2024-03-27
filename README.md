# Multimodal local llm

---

# Streamlit LLM Chatbot

## Introduction

The Streamlit LLM Chatbot is a local, private chatbot application designed to facilitate interactive conversations with a multimodal interface. This project integrates several cutting-edge technologies including large language models (LLMs), ChromaDB for vector storage, Whisper AI Small for conversational capabilities, and cTransformers for text processing.

## Features

### Multimodal Interface
The chatbot supports various input modalities including text, audio, PDF, and images, providing users with a seamless conversational experience.

### LLM Integration
Powered by a large language model, the chatbot can generate responses, retrieve relevant information, and engage in natural language conversations.

### ChromaDB Integration
ChromaDB is utilized as a vector database, enabling efficient storage and retrieval of multimedia data.

### Whisper AI Small
Whisper AI Small enhances the conversational abilities of the chatbot, enabling it to understand context, generate coherent responses, and maintain engaging dialogues.

### cTransformers
cTransformers is leveraged for text processing tasks, allowing for efficient handling of text inputs and facilitating natural language understanding.

## Local and Private Nature of the Application

The Streamlit LLM Chatbot operates entirely on your local machine, ensuring that all interactions and data processing occur within your personal environment. This local setup means that no data is transmitted to external company servers during the course of your conversations.

#### Data Privacy

Your conversations with the chatbot remain confidential and secure as they are not shared with any external parties. Unlike many online chatbots that rely on cloud-based services, our application prioritizes data privacy by keeping all interactions strictly within your local environment.

#### No External Server Communication

The chatbot does not communicate with external servers maintained by third-party companies. This eliminates any concerns regarding data exposure or unauthorized access to your personal information.

#### Complete Control Over Data

By keeping the application local, you maintain complete control over your data. There are no dependencies on external services, ensuring that your conversations and any associated multimedia content remain under your jurisdiction at all times.

#### Enhanced Security

The local and private nature of the application enhances security by reducing the risk of data breaches or unauthorized access. With all processing conducted locally, you can trust that your sensitive information stays protected within your own computing environment.

### Session Management with Memory

The chatbot incorporates session management with memory, allowing it to retain context from previous interactions. This enables more personalized and coherent conversations over time, as the chatbot can recall past discussions and tailor its responses accordingly.

### Models Used

- **LLM Model (Mistral)**: The Mistral LLM model is primarily used for textual chat interactions. It generates responses, retrieves information, and engages in natural language conversations.
  
- **Whisper Model**: Whisper AI Small is employed for handling audio inputs, enabling the chatbot to process and respond to spoken queries.

- **LLAVA Model**: LLAVA is utilized for image handling and visual question answering tasks, allowing the chatbot to understand and respond to image-based queries.

- **RetrievalQA**: This model is specialized in handling PDF documents, enabling the chatbot to retrieve relevant information from PDF files and respond to queries based on their contents.

## Setup and Configuration

To set up the Streamlit LLM Chatbot, follow the instructions provided in the README.md file. Configure the application settings according to your preferences and requirements, ensuring proper paths to models, embeddings, and databases.

## Usage

Once configured, run the application using Streamlit by executing the appropriate command. Access the chatbot through your web browser and interact with it using the supported modalities.

## Disclaimer

This project is intended for personal and private use only. Exercise caution when dealing with sensitive information and ensure data privacy and security at all times.

## Contributions

Contributions to the project are welcome. If you encounter any issues, have suggestions for improvements, or wish to contribute code, please follow the guidelines outlined in the CONTRIBUTING.md file.

## License

The Streamlit LLM Chatbot is released under the [License Name] license. See the LICENSE.md file for more details.

## Contact

For inquiries, feedback, or support, please contact [Your Name] at [Your Email].

---

*Note: This README provides an overview of the Streamlit LLM Chatbot project. For detailed setup instructions, configuration options, and usage guidelines, refer to the accompanying documentation and codebase.*
