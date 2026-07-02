# Simple AI Chatbot

A basic rule-based chatbot built using Python that responds to user input using keyword matching.

## About This Project

This project is a beginner-level chatbot that simulates conversation using predefined responses. It matches user input with keywords and returns random responses.

It demonstrates:

* Conditional logic
* String handling
* Dictionaries in Python
* Simple chatbot behavior

## Features

* Keyword-based response system
* Predefined conversation patterns
* Randomized replies for variety
* Continuous chat loop
* Exit command support ("bye")

## Technologies Used

* Python
* Random module

## How It Works

1. User types a message
2. Input is converted to lowercase
3. Program checks for matching keywords
4. Random response is selected
5. Bot replies to user

## Project Structure

```text id="chat002"
ai-chatbot/
│
├── main.py      # Source Code
└── README.md    # Documentation
└── Output
```

## How to Run

```bash id="chat003"
python main.py
```

## Example Conversation

```text id="chat004"
You: hello
Bot: Hi there!

You: how are you
Bot: I am good, thank you!

You: bye
Bot: Goodbye!
```

## Supported Inputs

* hello / hi
* how are you
* name
* help
* bye

## Limitations

* No real NLP processing
* No machine learning
* No intent classification model
* No memory or context tracking
* Only keyword-based responses

## Future Improvements

* Add NLP using NLTK or spaCy
* Add intent classification model
* Add memory/context system
* Connect to AI APIs
* Improve conversation flow

## Author

Mahrukh

Robotics & Intelligent Systems Student passionate about Artificial Intelligence, Machine Learning, and conversational systems.
