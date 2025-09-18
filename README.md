Simple Chatbot using Google Gemini AI

This repository contains a lightweight chatbot powered by Google’s Gemini model. It demonstrates how to build conversational applications with Generative AI using a clean and minimal Python implementation.

Features

AI-powered chatbot using Gemini API

Interactive chat loop from terminal

Easy to extend and customize

Well-structured and beginner-friendly codebase

Requirements

Python 3.8+

google-generativeai (Gemini API SDK)

A valid Google API Key for Gemini

Install dependencies:

pip install google-generativeai

Setup

Get your Gemini API key from Google AI Studio
.

Save it as an environment variable:

export GOOGLE_API_KEY="your_api_key_here"


(On Windows use set instead of export)

Usage

Run the chatbot script:

python chatbot.py


Sample interaction:

You: Hello, chatbot!
Bot: Hi there! How can I help you today?

Project Structure
simple-gemini-chatbot/
 ├── chatbot.py        # Main chatbot code
 ├── requirements.txt  # Dependencies
 └── README.md         # Project documentation

Future Improvements

Add memory to retain conversation context

Build a web interface (Streamlit/Flask)

Support multi-turn chats with history

License

This project is licensed under the MIT License – feel free to use and modify.
