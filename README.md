# Anime News Telegram Bot

This Telegram bot fetches anime news from multiple sources like MyAnimeList, Crunchyroll, and TheAnimeDaily, and posts them in your chosen Telegram channel or group. You can use this bot to create an anime news channel that automatically updates with the latest news.

## Features
- Fetches **Anime News** from the following RSS feeds:
  - [MyAnimeList](http://myanimelist.net/rss.php?type=news)
  - [Crunchyroll](https://feeds.feedburner.com/crunchyroll/rss)
  - [TheAnimeDaily](https://www.theanimedaily.com/feed/)
- Allows you to **connect a news channel** where the bot will post updates.
- Provides **admin-only control** over which channel receives the news.

## Requirements

- **Python 3.x**
- **Telegram API Keys**: You can get your API keys from [Telegram](https://my.telegram.org/apps).
- **Bot Token**: Obtain your bot token from [BotFather](https://t.me/botfather).
- **MongoDB**: Set up your MongoDB database. You can use MongoDB Cloud at [MongoDB Atlas](https://cloud.mongodb.com/).

## Available Commands

- `/start`: Starts the bot and provides basic info.
- `/news <channel_id_or_username>`: Connects a channel (with @username) where the bot will post the anime news.

## Owner/Sudo Commands

- `/news <channel_id_or_username>`: Admins use this command to connect the bot to a Telegram channel or group for posting news.

## How to Host the Bot

You can easily deploy this bot to **Render** with just a few clicks. Use the button below to deploy it instantly:

<p align="center">
  <a href="https://render.com/deploy?template=https://github.com/Bots-Nation/AnimeNews-Bot">
    <img src="https://img.shields.io/badge/Deploy%20To%20Render-blue?style=for-the-badge&logo=render" width="220" height="38.45"/>
  </a>
</p>

For manual hosting, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/Bots-Nation/AnimeNews-Bot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AnimeNews-Bot
    ```
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up the configuration in the `config.py` file with your **Telegram bot token**, **API keys**, **MongoDB URL**, and the following RSS feed links:
    ```python
    class Config:
        ...
        RSS_FEEDS = {
            "MyAnimeList": "http://myanimelist.net/rss.php?type=news",
            "Crunchyroll": "https://feeds.feedburner.com/crunchyroll/rss",
            "TheAnimeDaily": "https://www.theanimedaily.com/feed/"
        }
    ```
5. Run the bot:
    ```bash
    python bot.py
    ```

## Credits

- **AniList API**: [GitHub Repo](https://github.com/AniList/ApiV2-GraphQL-Docs)
- Special thanks to [@BOTSKINGDOMS](https://t.me/BOTSKINGDOMS) for their contributions.

## Note
This is **Version 2** of the bot, so don't expect much functionality yet. More features and improvements will be added soon. Contributions are welcome! If you would like to help, please feel free to open a pull request or contact me.

For support or questions, reach out to me at:
- [@BOTSKINGDOMS](https://t.me/BOTSKINGDOMS)
- [@BOTSKINGDOMSGROUP](https://t.me/BOTSKINGDOMSGROUP)

## Example Images
Here are some anime-related images that you can use in your bot interface:

![Anime Image](https://images8.alphacoders.com/138/1384114.png)
![Isagi Yoichi](https://motionbgs.com/media/5511/isagi-yoichi-devil-eyes.jpg)
