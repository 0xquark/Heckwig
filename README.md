# Heckwig
This is a Discord bot that allows users to:
  - Get notified about upcoming CTF competitions with CTF-level Type ( Beginner , Intermediate , Difficult )
  - Retrieve a team's CTF ranking from CTFTime.
  - Convert various encodings (such as base64, base32, binary, rot13, and rot47) to normal strings.

### Requirements
  - A discord bot token
  - A ctftime api key ( get it from ctftime.org )

### Usage
  - Create a new Discord bot and get its token at the Discord Developer Portal. Create .env file and add the following
  ```shell
  DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN
  CTFTIME_API_KEY=YOUR_CTFTIME_API_KEY
  ```
  - Add the bot to your server
  - Run the bot
  
### Commands
- `!ctfnotify [level]`: Notifies the user about upcoming CTF competitions that match the specified level (beginner, intermediate, advanced, or all).
- `!ctfranking team`: Retrieves the specified team's CTF ranking from CTFTime.
- `!convert string [encoding]`: Converts the specified string from the specified encoding (base64, base32, binary, rot13, rot47) to a normal string
