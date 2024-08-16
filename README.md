# TempVoice

An upcoming implementation of a temp voice bot with user and admin commands.

### Prerequisites

- [Node.js](https://nodejs.org/) (v16.x or higher)
- [Discord Developer Portal](https://discord.com/developers/applications) account to create your bot
- [Discord.JS](https://discord.js.org/) (v14.x or higher)

### Setup
1. To setup run the following commands
```npm
npm install discord.js dotenv sqlite3
```

2. Populate the categories in the .env file (Rename env.example to .env):
```env   
DISCORD_TOKEN=""
CLIENTID = ""
OWNERID = ""
ADMINROLEID = ""
SERVERID = ""
DATABASENAME=""
```

You may need to run `node deploy-commands` and `node deploy-database`
