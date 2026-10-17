# CodeAlpha Task 4 - Basic Chatbot

print("🤖 Welcome to Basic Chatbot!")
print("Type 'bye' to exit.")

while True:
    user_input = input("You: ").lower()

    if user_input == "hi" or user_input == "hello":
        print("Bot: Hello! 👋 How can I help you?")

    elif user_input == "how are you":
        print("Bot: I am fine! 😊 How are you?")

    elif user_input == "what is your name":
        print("Bot: My name is CodeAlpha Bot 🤖")

    elif user_input == "what is python":
        print("Bot: Python is a popular programming language. 🐍")

    elif user_input == "bye":
        print("Bot: Goodbye! 👋 Have a nice day!")
        break

    else:
        print("Bot: Sorry, I don't understand that.")
