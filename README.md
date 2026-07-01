# Basic-Chatbot
# 🤖 Simple Python Chatbot

A beginner-friendly chatbot built using Python. This chatbot responds to a few predefined user inputs and continues the conversation until the user types **"bye"**.

## 📌 Features

- Greets the user.
- Responds to:
  - `hello`
  - `how are you`
- Ends the chat when the user types `bye`.
- Uses a `while` loop for continuous conversation.
- Great project for Python beginners.

## 🛠️ Technologies Used

- Python 3

## 📂 Project Structure

```
simple-chatbot/
│
├── chatbot.py
└── README.md
```

## ▶️ How to Run

1. Make sure Python 3 is installed.
2. Save the code as `chatbot.py`.
3. Open a terminal in the project folder.
4. Run the program:

```bash
python chatbot.py
```

## 💬 Sample Output

```
Chatbot: Hi, Type 'bye' to exit.

You: hello
Chatbot: Hi!

You: how are you
Chatbot: I'm fine, thanks!

You: bye
Chatbot: Goodbye
```

## 📖 Code Overview

- Displays a welcome message.
- Uses an infinite `while` loop to keep chatting.
- Converts user input to lowercase using `.lower()` for case-insensitive matching.
- Uses `if-elif` statements to identify user commands.
- Stops the program using `break` when the user enters `bye`.

## 🚀 Future Improvements

- Add more conversation responses.
- Support greetings like `hi` and `hey`.
- Handle unknown inputs with a default response.
- Use dictionaries or functions instead of multiple `if-elif` statements.
- Add GUI using Tkinter.
- Add voice input and text-to-speech.

## 👩‍💻 Author

**Tanishka Yadav**

---

⭐ If you found this project useful, consider giving it a star!
