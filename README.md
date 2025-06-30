# Anime News Telegram Bot

This Telegram bot fetches anime news from multiple sources like MyAnimeList, Crunchyroll, and TheAnimeDaily, and posts them in your chosen Telegram channel or group. You can use this bot to create an anime news channel that automatically updates with the latest news.

### Features
- Fetches **Anime News** from:
  - [MyAnimeList](https://myanimelist.net)
  - [Crunchyroll](https:Crunchyroll.com)
  - [TheAnimeDaily](https://www.theanimedaily.com/)
  - [AnimeNewsNetwork](https://www.animenewsnetwork.com/)
- Allows you to **connect a news channel** where the bot will post updates.
- Provides **admin-only control** over which channel receives the news.

---

### RSS
- Here are some RSS:
  - [MyAnimeList](https://myanimelist.net/rss/news.xml)
  - [Crunchyroll](https://feeds.feedburner.com/crunchyroll/rss)
  - [TheAnimeDaily](https://www.theanimedaily.com/feed/)
  - [AnimeNewsNetwork](https://www.animenewsnetwork.com/newsfeed/rss.xml?ann-edition=us)

---

### Requirements

- **Python 3.x**
- **Telegram API Keys**: You can get your API keys from [Telegram](https://my.telegram.org/apps).
- **Bot Token**: Obtain your bot token from [BotFather](https://t.me/botfather).
- **MongoDB**: Setup your MongoDB database. You can use MongoDB Cloud at [MongoDB Atlas](https://cloud.mongodb.com/).
- **Youtube Cookie**: You can get YT Cookies by using get cookies.txt. Here's the link [Chrome](https://chromewebstore.google.com/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc).
- **FFMPEG**: Install FFMPEG before using the bot.

---

### Available Commands

- `/start`: Starts the bot and provides basic info.
- `/news <channel_id_or_username>`: Connects a channel (with @username) where the bot will post the anime news.
- `/sendnews <rss> <position>`: Send news [Force].

---

### Owner/Sudo Commands

- `/news <channel_id_or_username>`: Admins use this command to connect the bot to a Telegram channel or group for posting news.
- `/sendnews <rss> <position>`: Send news [Force].

---

### How to extract Cookies and setup them.

- **Read this Article**: You will find full Guide Here [Click Here](https://github.com/yt-dlp/yt-dlp/wiki/Extractors#exporting-youtube-cookies)
- **How to setup**: Save the cookies as cookies.txt in the root Directory.

---

### How to Host the Bot

You can easily deploy this bot to **Heroku** with just a few clicks. Use the button below to deploy it instantly:

<p align="center">
  <a href="https://heroku.com/deploy?template=https://github.com/Bots-Nation/AnimeNews-Bot">
    <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blue?style=for-the-badge&logo=heroku" width="220" height="38.45"/>
  </a>
</p>

You can easily deploy this bot to **Render** with just a few clicks. Use the button below to deploy it instantly:

<p align="center">
  <a href="https://render.com/deploy?template=[[https://github.com/Bots-Nation/AnimeNews-Bot](https://github.com/animeheacen/Auto-Anime-News)](https://github.com/animeheacen/Auto-Anime-News)">
    <img src="https://img.shields.io/badge/Deploy%20To%20Render-blue?style=for-the-badge&logo=render" width="220" height="38.45"/>
  </a>
</p>

For manual hosting, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/DARKXSIDE78/AnimeNewsBot.git
    ```
2. Navigate to the project directory:
    ```bash
    cd AnimeNewsBot
    ```
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Set up the configuration in the `config.py` file with your **Telegram bot token**, **API keys**, and **MongoDB URL**.
5. Run the bot:
    ```bash
    python bot.py
    ```

---

### Credits

- **AniList API**: [GitHub Repo](https://github.com/AniList/ApiV2-GraphQL-Docs)
- Special thanks to [@BOTSKINGDOMS](https://t.me/BOTSKINGDOMS) for their contributions.

---

### Note:
This is **Version 3** of the bot, so don't expect much functionality yet. More features and improvements will be added soon. Contributions are welcome! If you would like to help, please feel free to open a pull request or contact me.

For support or questions, reach out to me at:
- [@BOTSKINGDOMS](https://t.me/BOTSKINGDOMS)
- [@BOTSKINGDOMSGROUP](https://t.me/BOTSKINGDOMSGROUP)

---

### Example Images
Here are some anime-related images that you can use in your bot interface:

![1](https://i.ibb.co/fzn5pVR9/1.png)
![2](https://i.ibb.co/2Y85Znbk/2.png)
