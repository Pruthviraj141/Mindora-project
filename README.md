# Personal Therapy Chatbot with Emotion Detection and Support

This repository contains the code for a personalized therapy chatbot, "Dr. James," which utilizes various technologies to provide mental health support. The chatbot can detect the user's emotions, provide relevant responses, and send emails with helpline details if the user expresses distress.

## Features

- **Emotion Detection**: Uses a pre-trained model to detect emotions (e.g., sadness, anger, joy) from the user's input.
- **Therapeutic Responses**: Generates empathetic and professional responses to the user's queries using a language model.
- **Helpline Assistance**: Sends an email with helpline numbers based on the user's location if sadness is detected.
- **User Data Storage**: Stores user information and chat history securely in a Firebase database.
- **Vector Database**: Uses a Chroma vector database for document retrieval to improve response accuracy.
- **Personalized Support**: Offers personalized therapy-like sessions based on the user's input.

## Tech Stack

- **Python**: The main programming language used to write the code.
- **Firebase**: Used to store user and chat history data.
- **LangChain**: Framework used for document processing, embeddings, and creating the QA chain.
- **HuggingFace**: Provides models for embeddings and emotion detection.
- **Groq**: Utilized for generating responses using an advanced large language model (LLM).
- **PyTorch**: Used for running models for emotion detection.
- **SMTP/Email**: Sends email notifications with helpline numbers when needed.


