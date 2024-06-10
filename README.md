# Discord AI Chatbot 🤖

## Introduction

The Discord AI Chatbot is a powerful, interactive bot designed to enhance your Discord server experience with advanced AI capabilities. This bot leverages the latest in language model technology to provide a wide range of features, from command handling and image generation to secure credential management and web access. It aims to streamline interactions, provide useful functionalities, and create a more engaging environment for Discord users.

![Project Image Overview](https://github.com/zima-0201/Project-Images/blob/main/Discord-AI-ChatBot.jpg)

### Core Features

- **Hybrid Command System**: Supports both slash and normal commands for versatile interaction.
- **Image Generation**: Create images based on text prompts for free.
- **Free Language Model**: Access a robust language model without any cost.
- **Mention Recognition**: The bot responds to mentions and name calls, ensuring it’s always attentive.
- **Message Handling**: Intelligent message handling to avoid confusion in conversations.
- **Channel-Specific Responses**: Use the `/toggleactive` command to control bot activity in specific channels.
- **Open-source Models**: Utilize the power of open-source models for various tasks.
- **Secure Credential Management**: Keep credentials secure using environment variables.
- **Web Access**: Unlock additional functionalities with web access capabilities.

## System Architecture

This project is designed with a modular architecture, integrating various components to provide a seamless user experience:

- **Discord Bot API**: Interfaces with Discord to offer an interactive chatbot experience.
- **OpenAI API**: Powers the language model for intelligent responses and interactions.
- **Secure Environment Management**: Uses environment variables to manage sensitive information securely.
- **Python Backend**: The entire backend logic is implemented in Python, leveraging its extensive library ecosystem for HTTP requests, database connections, and more.

## Installation and Setup

### Step 1: Clone the Repository
```
git clone https://github.com/zima-0201/Discord-AI-ChatBot
```

### Step 2: Navigate to the Directory
```
cd Discord-AI-Chatbot
```

### Step 3: Install Requirements
```
python3.10 -m pip install -r requirements.txt
```

### Step 4: Configure Discord Bot Token and API Keys
1. Obtain your Discord bot token from the [Discord Developer Portal](https://discord.com/developers/applications).
2. Get your API key from [Groq](https://console.groq.com/keys).

### Step 5: Set Up Environment Variables
Rename `example.env` to `.env` and add your credentials:
```
DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
API_KEY=YOUR_GROQ_API_KEY
```

### Step 6: Run the Bot
```
python main.py
```
For Windows users, you may need to run as an administrator.

### Step 7: Invite the Bot to Your Server
Use the link provided in the console to invite the bot to your Discord server.

## Usage and Commands

After setup, interact with the bot using various commands and interactive buttons. Use the `/help` command to see a full list of available commands.

## Future Enhancements

The roadmap includes:
- Integrating more functionalities and improving existing ones.
- Enhancing AI capabilities for better interaction.
- Improving user data security with advanced encryption techniques.

## Contributing to the Project

We welcome contributions from the community to make the Discord AI Chatbot more robust and feature-rich. Please refer to the Contributing section for guidelines on making contributions.

## Support and Feedback

For support, feature requests, or to report bugs, please open an issue in the project repository or contact the maintainers directly.
