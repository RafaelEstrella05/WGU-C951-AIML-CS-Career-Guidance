# UDC AIML Chatbot

This project is a rule-based AIML (Artificial Intelligence Markup Language) chatbot designed to run on the [Pandorabots](https://www.pandorabots.com/) platform. It uses a structured directory with categorized AIML files to simulate intelligent conversation.

## 🧠 Project Structure

```
└── Files/udc.aiml            # Main AIML file (entry point)
```

## 🚀 Getting Started on Pandorabots

To test and run this bot on Pandorabots:

### 1. Create a Pandorabots Account

Go to [Pandorabots.com](https://www.pandorabots.com/signup/) and sign up for a free account.

### 2. Create a New Bot

- Once logged in, go to your [dashboard](https://www.pandorabots.com/botmaster/en/home).
- Click **"Create a New Bot"**.
- Enter a name (e.g., `UDC-Bot`) and select the default `English (AIML 2.1)` option.

### 3. Upload Your Files

- Navigate to your bot's **Files** section.
- Upload the contents of the `Files/` directory, preserving the folder structure:
  - Upload everything inside `Substitutions/` and `System/`.
  - Upload `udc.aiml` at the root level.

> You may upload files individually or zip the directory and use the Pandorabots uploader to import the archive.

### 4. Set `udc.aiml` as Your Startup File

- In the bot's **Settings**, change the **Startup File** to `udc.aiml`.
- Save your changes.

### 5. Test Your Bot

- Click **"Talk to your bot"** or use the [Pandorabots Playground](https://playground.pandorabots.com/en/) to begin chatting.

## ✅ Example Features

- Text normalization (e.g., substitutions of slang, abbreviations)
- Rule-based responses for system queries
- Easily extensible for adding categories, topics, and random responses


