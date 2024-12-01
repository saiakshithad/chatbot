# chatbot

<img src="./images/chatbot.png"/>

![GitHub repo size](https://img.shields.io/github/repo-size/sannketnikam/chatbot)

This project aims to develop a chatbot that can interpret and respond to user input based on identified intents. It leverages Natural Language Processing (NLP) techniques along with Logistic Regression to extract intents and entities from user messages. The chatbot is built using the Streamlit framework, which facilitates the creation of interactive web applications. Key libraries used include NLTK for NLP tasks, scikit-learn for machine learning, and Streamlit for the user interface. 
# Project Overview
The project is divided into two parts:
1. NLP techniques and Logistic Regression algorithm is used to train the chatbot on labeled intents and entities.
2. For building the Chatbot interface, Streamlit web framework is used to build a web-based chatbot interface. The interface allows users to input text and receive responses from the chatbot.

## Technologies Used
- **Python**
- **NLTK**
- **Scikit-learn**
- **Streamlit**
- **JSON** for intents data


# Dataset
The dataset used in this project is a collection of labelled intents and entities. The data is stored in a list.
- Intents: The intent of the user input (e.g. "greeting", "budget", "about")
- Entities: The entities extracted from user input (e.g. "Hi", "How do I create a budget?", "What is your purpose?")
- Text: The user input text.

# Interface
Streamlit is used for building the chatbot's interface. The interface consists of a chat window that shows the chatbot's responses and a text input box where users can enter text. The interface responds to user input by using the trained model.

# Conclusion
A chatbot that can comprehend and react to user input based on intentions is created in this project. NLP and logistic regression were used to train the chatbot, and Streamlit was used to create the user interface. More data, advanced NLP methods, and deep learning algorithms might all be used to expand this research.
