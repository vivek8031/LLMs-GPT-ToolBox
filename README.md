# 🤖 GPT For Y'all: A Streamlit-based Language Model Application 

This repository contains code for a Streamlit application that leverages language models for various tasks 📚. The application includes functionalities for basic language generation 💬, creative writing ✍, text summarization 📝, few-shot learning 🎯, and Python code generation 🐍.

## 🌟 Features

The Streamlit application provides an interface for the following tasks:

1. **Base Generation** 💬: This feature is for standard language generation tasks. Users can provide a prompt, and the application will generate a response based on the input.

2. **Creative Writing** ✍: This feature allows users to generate creative content, such as stories or poems. Like base generation, it requires a user-provided prompt.

3. **Text Summarization** 📝: This feature enables users to summarize long blocks of text. It requires a large text input from the user and generates a summarized version of the input.

4. **Few-Shot Learning** 🎯: This feature is useful for performing few-shot learning. Users can provide a set of examples and a prompt, and the application will generate a response based on the given examples and the prompt.

5. **Python Code Generation** 🐍: This feature leverages a Python agent for generating Python code based on user prompts.

## 📖 Usage

To use the application, you need to provide your OpenAI API Key and a path to the weights for your GPT model.

For each feature, you can input your prompt or text into the input box and hit 'Enter' 🖱. The application will generate and display the response.

## 🛠 Installation and Setup

The application requires Python and Streamlit. Other dependencies are included in the `requirements.txt` file.

To set up and run the application, follow these steps:

1. Clone this repository to your local machine 🖥.

2. Install the necessary dependencies by running `pip install -r requirements.txt` 📦.

3. Set up your OpenAI API Key and the path to the GPT model weights 🔑.

4. Run the application using Streamlit with `streamlit run app-comparison.py` 🚀.

## 📚 Dependencies

The main dependencies for this project are:

- [Streamlit](https://streamlit.io/): Used to build the web application interface.
- [Langchain](https://github.com/hwchase17/langchain.git): Used for language generation tasks.

## 🔗 Other References

- [GPT4AllReference](https://github.com/nomic-ai/gpt4all/tree/main): Mainly used to determine how to install the GPT4All library and references. The documentation was changing frequently, and at the time of coding this was the most up-to-date example of getting it running.
