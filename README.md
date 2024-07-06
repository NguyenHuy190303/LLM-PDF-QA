# LLM-PDF-QA Project

## Overview
This project implements a Question Answering system using Large Language Models (LLMs) on PDF documents. The system supports running via Tunnel or Ngrok.

## Files in the Repository
- `RAG_LLM(Vicuna)_Chainlit.ipynb`: The main notebook for the project.
- `app.py`: The script to run the application using Ngrok.
- `README.md`: Documentation for the project.

## Installation
To set up the environment, follow these steps:
1. **Clone the repository**:
    ```bash
    git clone https://github.com/Koii2k3/LLM-PDF-QA.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd LLM-PDF-QA
    ```

3. **Install the required packages**:
    ```bash
    pip install -r <required-library> (all libraries in the first code block in RAG_LLM(Vicuna)_Chainlit.ipynb file)
    ```

## Running the Applications
Using Google Colab and upload all the `RAG_LLM(Vicuna)_Chainlit.ipynb` and `app.py`, then:
### Using Tunnel
Run the relevant Tunnel code blocks in the `RAG_LLM(Vicuna)_Chainlit.ipynb` notebook to start the application via Tunnel.
### Using Ngrok
1. **Register/Login on [Ngrok](https://ngrok.com/) and get your TOKEN**
2. **Enter the token to `your-ngrok-token` in relevant Ngrok code blocks**

Run the relevant code blocks in the `RAG_LLM(Vicuna)_Chainlit.ipynb` notebook to start the application via Tunnel.

## Screenshots
![Wait to upload PDF](./data/1.png)
![Result](./data/2.png)
