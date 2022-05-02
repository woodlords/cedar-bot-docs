# cedar-bot-docs


# Adding Bot to Server

## Invite the bot
Follow this link to invite Cedar Bot
https://discord.com/api/oauth2/authorize?client_id=964044914335821874&permissions=2416045136&scope=bot%20applications.commands


## Create Verification Channel
First we want to make sure we create a new channel for the verification.
Let's pretend we call it #verification-bot


## Change Channel Permissions

Make sure we change the permissions on that channel. Right click Channel > permissions > Add Role > Cedar Bot. 
Give it the following permissions 
* Read Messages 
* Manage Messages 
* Read History 
* Use Application Commands


## Allow & Block Roles
If you want specific users to use the bot, you can manage the commands permissions in the server settings.
Server Settings > Integrations > Cedar Bot 
Then click on the command you want and assign it to specific roles or channels.
