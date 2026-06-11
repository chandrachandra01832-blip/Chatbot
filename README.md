Simple Rule-Based Chatbot:


This is a basic Python chatbot that uses simple keyword matching to respond to user input.
It demonstrates how to build a conversational loop with predefined responses.

Features:


Responds to greetings (hello, hi)
Handles common phrases (how are you, thanks, bye)
Provides a default response when input is not recognized
Runs in a continuous loop until the user types bye

How It Works:


User input is converted to lowercase and stripped of extra spaces.
The chatbot checks if the input contains any predefined keywords.
If a match is found, the chatbot returns the corresponding response.
If no match is found, it returns a default message:
"Sorry! I don't understand that"

Example Usage:


$ python chatbot.py
Chatbot: Hello! Type 'bye' to exit.
You: hello
Chatbot: Hi there! How can I help you today?
You: how are you
Chatbot: I’m just code, but I’m doing great! How about you?
You: thanks
Chatbot: You’re welcome!
You: bye
Chatbot: Goodbye!
