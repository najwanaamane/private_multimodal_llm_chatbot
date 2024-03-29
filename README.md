# All-in-One local Chatbot

---

# Multimodal local LLM Chatbot

## Introduction

The Streamlit LLM Chatbot is a local, private chatbot application designed to facilitate interactive conversations with a multimodal interface. In this project, LangChain technology serves as the backbone, integrating various Large Language Models (LLMs) including Mistral, LLAVA for image handling, while Whisper AI Small enhances conversational capabilities, and RETRIEVALQA as a pdf question answering chain. ChromaDB is utilized for vector storage purposes, s. Additionally, cTransformers is employed for text processing tasks.

## Features

### Multimodal Interface
The chatbot supports various input modalities including text, audio, PDF, and images, providing users with a seamless conversational experience.

### Models Used

- **LLM Model (Mistral)**: The quantized Mistral model __mistral-7b-instruct-v0.2-code-ft.Q5_K_M.gguf__  is primarily used for textual chat interactions. It generates responses, retrieves information, and engages in natural language conversations.
  
- **Whisper Model**: __Whisper AI Small__  is employed for handling audio inputs, enabling the chatbot to process and respond to spoken queries.

- **LLAVA Model**:  LLAVA __llava_ggml-model-q5_k.gguf__ is utilized for image handling and visual question answering tasks, allowing the chatbot to understand and respond to image-based queries.

- **RetrievalQA**: This model is specialized in handling PDF documents, enabling the chatbot to retrieve relevant information from PDF files and respond to queries based on their contents.

### cTransformers
cTransformers is leveraged for text processing tasks, allowing for efficient handling of text inputs and facilitating natural language understanding.

### ChromaDB   

ChromaDB serves as a vector database, storing vector representations of multimedia data items. These vectors are generated using techniques like embeddings or feature extraction, capturing various characteristics of the multimedia content. Stored in a high-dimensional space, each dimension corresponds to a specific feature of the multimedia content. This approach enables ChromaDB to efficiently store and retrieve multimedia data, facilitating fast and accurate retrieval based on similarity metrics in the vector space.   


### Session Management with Memory

The chatbot incorporates session management with memory, allowing it to retain context from previous interactions. This enables more personalized and coherent conversations over time, as the chatbot can recall past discussions and tailor its responses accordingly.   

## Local and Private Nature of the Application

The Streamlit LLM Chatbot operates entirely on your local machine, ensuring that all interactions and data processing occur within your personal environment. This local setup means that no data is transmitted to external company servers during the course of your conversations.

#### Data Privacy and Security

The chatbot does not communicate with external servers maintained by third-party companies. There are no dependencies on external services, ensuring that your conversations and any associated multimedia content remain under your jurisdiction at all times.  

The local and private nature of the application enhances security and eliminates any concerns regarding data exposure or unauthorized access to your personal information.   




---

### Setting Up the Environment

1. **Create a Virtual Environment:** It's recommended to use Python 3.10.12. If you haven't already, create a virtual environment by running:

    ```bash
    python3 -m venv myenv
    ```

2. **Upgrade pip:** Ensure you have the latest version of pip by running:

    ```bash
    pip install --upgrade pip
    ```

3. **Install Requirements:** Install the required dependencies by running:

    ```bash
    pip install -r requirements.txt
    ```

    *Note: Windows users may encounter installation differences.
   
### Setting Up Local Models

4. **Download Models:** Download the models you wish to use. For image chat, download the LLAVA model (ggml-model-q5_k.gguf and mmproj-model-f16.gguf), and the quantized Mistral model from TheBloke (mistral-7b-instruct-v0.1.Q5_K_M.gguf).

5. **Customize Config File:** Adjust the configuration file (config.yaml) to reflect the models you downloaded.


### Initializing Database and Running the Application

6. **Initialize Database:** Initialize the SQLite database for chat sessions by running:

    ```bash
    python3 database_operations.py
    ```

7. **Run the Application:** Finally, launch the Streamlit LLM Chatbot by executing:

    ```bash
    streamlit run app.py
    ```

---



