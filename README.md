# Auto_like_comment_instagram_bot

Instagram Bot
This Python script automates interactions on Instagram, allowing you to like photos associated with specific hashtags. This can help increase engagement and visibility on the platform. The bot uses the Selenium library to navigate the Instagram website and perform actions.

Prerequisites:
1. Before running the Instagram bot, you need to have the following dependencies installed:

   Python (3.x recommended) <br/>
   Selenium (pip install selenium) <br/>
   Chrome WebDriver (download and configure it for your system)

Getting Started
1. Clone the repository to your local machine:
    git clone https://github.com/yourusername/instagram-bot.git

2. Install the required Python packages:
    pip install selenium

3. Download the Chrome WebDriver from here. Make sure the WebDriver version matches your Chrome browser version.

4. Edit the main.py file and replace the placeholders with your Instagram username and password:
    username = "***USERNAME***"
    password = "***PASSWORD***"

   
Usage:
1. Run the bot script:
  python main.py
  
The bot will log in to your Instagram account and start liking photos associated with random hashtags from the predefined list.

The bot will periodically sleep and continue the process, helping you interact with Instagram content.
