# ChatBOT
Beginner ChatBOT (pun intended)


This is a simple Python chatbot that can learn new answers to questions based on user input. It's one of my beginner projects that I created to understand how chatbots work and how data is stored in JSON files.
Features

- The bot starts with a few pre-defined questions and answers.
- If the bot doesn’t know the answer to a question, you can teach it!
- It remembers new answers by saving them to a JSON file.

Why I Built This

I’ve been programming for less than 6 months, and this chatbot project was a great way for me to practice:

- Working with files in Python (reading from and writing to JSON).
- Using string matching to find the closest answer to a user’s question.
- Building a simple interaction loop that can run until you type "quit."
    
How to Use the Chatbot

    Clone the repository: 
    git clone https://github.com/YourUsername/ChatBot.git

Navigate to the project directory:

    cd ChatBot

Make sure you have Python installed. You can check with:

    python --version

Run the chatbot.py file:

    python chatbot.py

Start chatting with the bot! You can ask it questions, and if it doesn't know the answer, you can teach it. Type quit to exit the chatbot.

Example Conversation:

You: What is AI?
Bot: I don't know the answer. Can you teach me?
Type the answer or "skip" to skip: Artificial Intelligence is a branch of computer science.
Bot: Thank you! I learned a new response!

You: What is AI?
Bot: Artificial Intelligence is a branch of computer science.

Files in This Repository

- chatbot.py: The main Python script that runs the chatbot.
- knowledge_base.json: A JSON file where the bot stores its questions and answers.

What I Learned

This project helped me understand:

- How to read and write JSON files.
- How to use difflib for string matching.
- How to build a basic chatbot interaction loop.

As someone still early in my programming journey, this was a fun and rewarding project that improved my skills.
Contributing

Since I'm new to programming, I'm not looking for contributions just yet, but feel free to fork this project or use it as a learning tool like I did!
