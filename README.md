# EER (Experiencing, Experimenting, Reflecting) Chatbot
## Project Description
This project implements a chatbot utilizing retrieval mechanisms (RAG) to serve as a question-answering assistant. It leverages excerpts from transcripts of Zoom meetings pertaining to the [EER](https://www.eer.info/) project.


## Setup

To set up the environment for the EER Chatbot, follow these steps:

1. Run `bash setup_env.sh` to install the necessary dependencies listed in _requirements.txt_.

## Dependecies
Make sure to add data in the data folder.

## Code Overview

### `app.py`

This module provides the user interface for interacting with the EER Chatbot. It utilizes Streamlit to create a chat-like interface where users can input questions and receive responses generated by the chatbot.

### `main.py`

This module contains the core functionality of the EER Chatbot. It loads transcripts from meetings, processes text data, sets up retrievers and language models, and defines the logic for generating responses to user queries.
<<<<<<< HEAD

## Running the Streamlit App

To run the Streamlit application:
   ```
   streamlit run src/app.py
   ```

## Repo structure

```plaintext
Project Root
│
├── .venv
├── .env
├── .devcontainer
│   └── devcontainer.json
│
├── data
│   └── .folders
│
├── src
│   ├── app.py
│   ├── main.py
│   └── reformatting_data.py
│
├── .gitignore
├── README.md
├── requirements.txt
└── setup_env.sh
```
