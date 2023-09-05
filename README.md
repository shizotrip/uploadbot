
# Discord Uploader Bot

This is a Discord bot that allows users to upload files to file hosting service directly from Discord. The bot is written in Python and uses the Discord.py and aiohttp libraries.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/shizotrip/uploadbot
   ```

2. Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

3. Run the bot:

   ```
   python main.py
   ```

## Usage

The bot is triggered by `/upload` slash command command and a file attachment. 

![image](https://i.imgur.com/GpQz0lU.png)

The bot will respond with a message indicating that it is processing the file and will then upload it to Anonfiles. Once the upload is complete, the bot will post a message with the file's URL and other information.
