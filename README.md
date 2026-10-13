# Basic Rule-Based Chatbot Using Python

## Project Overview

This project is a simple rule-based chatbot developed using Python. It interacts with users through the console and provides predefined responses to specific messages such as "hello", "how are you", and "bye".

## Features

- Greets the user with a welcome message.
- Responds to predefined user inputs.
- Supports continuous conversation using a loop.
- Converts input to lowercase for easier matching.
- Exits the conversation when the user types `bye`.
- Displays a default response for unrecognized messages.

## Technologies Used

- Python
- Functions
- `if-elif-else` statements
- `while` loop
- Input and output

## Project Structure

```text
CodeAlpha_Task4_Chatbot/
└── chatbot.py
```

## Installation and Execution

1. Install Python on your computer.
2. Clone or download this repository.
3. Open the project folder in VS Code or another Python editor.
4. Open a terminal in the project folder.
5. Run the following command:

```bash
python chatbot.py
```

## Example Conversation

```text
Chatbot: Hello! Welcome to the chatbot.
Chatbot: Type 'bye' to exit.

You: hello
Chatbot: Hi!

You: how are you
Chatbot: I'm fine, thanks!

You: bye
Chatbot: Goodbye!
```

## How It Works

1. The `chatbot()` function contains the chatbot's logic.
2. The `while` loop keeps the conversation running.
3. The `input()` function receives messages from the user.
4. The `if-elif-else` statements match inputs with predefined replies.
5. The `break` statement ends the conversation when the user types `bye`.

## Learning Outcomes

- Understanding Python functions and loops.
- Using conditional statements to make decisions.
- Handling user input and displaying output.
- Building a simple interactive console application.
- Understanding the basic logic behind rule-based chatbots.

## Internship Information

**Organization:** CodeAlpha  
**Internship:** Python Programming Internship  
**Task:** Task 4 — Basic Chatbot

## Project Purpose

The purpose of this project is to practice Python programming fundamentals by developing a simple chatbot that responds to user messages using predefined rules.
