# TempVoice

An open source upcoming implementation of a temp voice bot with user and admin commands. Should work on multiple servers.

### Acknowledgements
- Jacon500 - Some code optimizations and assistance with some features
- ZMaster - Some function setup and assistance

### Prerequisites

- [Node.js](https://nodejs.org/) (v16.x or higher)
- [Discord Developer Portal](https://discord.com/developers/applications) account to create your bot
- [Discord.JS](https://discord.js.org/) (v14.x or higher)

### Setup
1. To setup run the following commands
```npm
npm install discord.js dotenv
```

2. Populate the categories in the .env file (Rename env.example to .env):
```env   
DISCORD_TOKEN=""
CLIENTID = ""
ADMINROLEID = ""
#SERVER ID IS REQUIRED FOR A SERVER TO DEPLOY GUILD COMMANDS TO.
SERVERID = "" 
```

You will need to run `node deploy-commands`.
