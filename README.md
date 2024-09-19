# WhatsApp Chat Analyzer

A web application that allows users to upload WhatsApp chat exports and perform various analyses. This tool helps to generate statistics such as the number of messages, words, media files shared, and even the most active users in a group chat. It's built using **Streamlit** for the web interface and **pandas** for data analysis.

## Features

- **Upload WhatsApp Chats**: Upload `.txt` files exported from WhatsApp.
- **Chat Statistics**: View total messages, word count, media messages, and links shared.
- **User-Based Analysis**: Get insights into specific users, such as the most active participants.
- **Word Cloud**: Visualize the most common words used in the chat.
- **Emoji and Link Extraction**: Analyze the use of emojis and links shared in the chat.

## How It Works

1. **Preprocessing**: The raw chat data is parsed, separating messages, users, and timestamps.
2. **Statistical Analysis**: The tool calculates statistics such as message counts, words, media, and link sharing.
3. **Visualization**: Data is visualized using charts, word clouds, and summary statistics.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/whatsapp-chat-analyzer.git
   cd whatsapp-chat-analyzer
2. Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit application:

bash
3. Copy code
streamlit run app.py
