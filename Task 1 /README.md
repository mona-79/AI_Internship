A Simple Rule-Based Chatbot

## Project Overview

Chatting_ai is a simple rule-based chatbot designed to interact with users using predefined responses. It can greet users, share jokes, provide basic advice, perform simple calculations, and help with information search. This project is an excellent starting point for understanding basic chatbot logic and text processing in Python.

## Features

- **Greeting**: Responds with a friendly greeting.
- **Name Inquiry**: Provides a response when asked about its name.
- **Jokes**: Shares a random joke when prompted.
- **Calculations**: Performs basic arithmetic calculations.
- **Search Assistance**: Offers to help search for information.
- **Help**: Lists available commands and how to interact with the chatbot.
- **Advice**: Provides simple advice when requested.
- **Unknown Input**: Handles unrecognized inputs with an appropriate response. 

## How It Works

- The chatbot uses predefined responses stored in arrays.
- It matches user input against specific keywords using simple logic and regular expressions.
- Depending on the match, the bot selects an appropriate response from the corresponding category.
- For calculations, it extracts mathematical expressions using regular expressions and evaluates them.

## Code Structure

- **responses**: A dictionary containing predefined responses for different categories.
- **calculate_expression()**: A function to evaluate simple mathematical expressions.
- **generate_response()**: The core function that determines the chatbot's response based on user input.
- **Main Loop**: The chatbot runs in a loop, continuously accepting user input until the user types 'bye'.

## Dependencies

- Python 3.x

No external libraries are required for this project.

## Customization

- You can easily extend or modify the predefined responses by updating the `responses` dictionary.
- For more complex functionality, consider integrating machine learning models or external APIs.

## License

This project is open-source and available under the [MIT License](LICENSE).

