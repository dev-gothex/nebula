##  FASTEST NUKE BOT

##  Requirements
- Python 3.10+
- Requirements.txt

##  Features

- Nuke : Delete all server's channels and roles
- Create Channels : Create text/voice channels with custom name
- Spam Channels: Flood channels using the bot with a custom message or embed.
- Webhook Spam : Flood channels with webhooks with a custom message or embed (fastest)
- Kick All : Kick everyone in the server except whitelist ID
- Ban All : Ban everyone in the server except whitelist ID
- Create Roles : Create roles with a custom name
- Get Admin : Give an admin role to an user or all the server
- Change Server : Change server with a custom or configured icon, name and description
- Dm All : Send a private message to all server members
- Auto Raid : Fast Raid with configured options
- Custom Bot Presence : Set your presence options in the config file


##  How To Use
1. Install Python (3.10+) and add it to PATH.
2. Download and extract latest Nebula version.
3. Install requirements → open the cmd and go in Nebula folder then run `pip install -r requirements.txt`.
4. Config the `config.py` if you want.
5. Run `main.py` in the cmd → `python main.py`.
6. Enter Bot token and server id.
   ### Get Bot Token
   - Open the [Discord Developer Portal](https://discord.com/developers/) and go to the [Applications Tab](https://discord.com/developers/applications).
   - Create a new application.
   - Upload the Discord bot to your server
      - You can either invite the Discord bot in the developer portal under OAuth2 > URL Generator > **Bot and applications.commands** > **Administrator**.
      - Or by inserting the ID found at General Information into the following link : `https://discord.com/oauth2/authorize?client_id=HERE&permissions=8&scope=bot%20applications.commands`.
   - Open the bot tab and enable **All Privileged Gateway Intents** *(PRESENCE INTENT, SERVER MEMBERS INTENT and MESSAGE CONTENT INTENT)*.
   - Copy the token of the application (Reset it before).
     
   ### Get Server Or User ID
   - Open your discord user settings.
   - App Settings → Advanced.
   - Active the Developer Mode.
   - Now you can copy the server or user ID by right clicking on their profile and selecting "Copy Server/User ID".
