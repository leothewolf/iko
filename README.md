<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/leothewolf/iko/main/logo_for_git.png" alt="Iko Discord Bot">
  <br>
</div>

## 🔎 Overview
**Iko** is a multipurpose discord bot. Our aim is to provide all in one bot so you don't need to have multiple bots!

**Some Notable Feature**
+ 🎫 <a href="https://github.com/leothewolf/iko/blob/main/ticket_system.md">Ticket System</a>
  + Auto delete on of tickets on 24 hours inactivity
  + Create as many as tickets as you want
  + Perfectly built notification system with all capabilities to manage it any way you want
  + Capability to attach images with tickets embed
  + One ticket per user
  + Support role tagged on opening of ticket (Unless turned off from notification settings)
  + Git inspired status system

<br>

+ 🛡️ <a href="https://github.com/leothewolf/iko/blob/main/verification_system.md">Verification System</a>
  + Auto generation of captcha by the bot
  + Three trials allowed per 10 mins to prevent missuse
  + User can fetch new captcha if current one is not visible
  + Unverified role assigned on server joining automatically by the bot
  + Verified role assigned on getting verified
  + Git inspired status system

<br>

+ 🖼️ <a href="https://github.com/leothewolf/iko/blob/main/gif_system.md">Gif System</a>
  + Start/stop gif system
  + SFW gif commands
  + NSFW gif commands
  + Git inspired status system

+ Pickup lines
  + Just type '-pick' to fetch a pickup line for yourself
  + If you want to say it for someone else just type '-pick @mention'<br>**(You can mention as many as people you want! No need to add commas or spaces)**

## 🛡️ How secure is our bot?
Umm let's breakdown this question in terms of the systems our bot has...
- Ticket System
  - All the commands except '-tclose' require administrator permission by the user to get executed and '-tclose' can also be used by the user or the supporter role to close the ticket and not in any other channels of the server, this has been done so to close the ticket manually

- Verification System
  - The private commands to clear personal logs and to ask for new captcha are allowed for user to execute without any permissions in private chat with the bot
  - All the server based commands require user to have administrator privileges to execute the commands

<br>

🤔 **Why have we only allowed user with administrator privileges to execute most of the commands rather breaking down the stuff and allowing staff to execute them?**
> "Ninety-nine percent of all failures come from irresponsible use of the permissions granted."
We as a bot developer asked you to grant permissions to our bot over your prestigious server, in that case we don't want any misuse of the permissions granted so to prevent that and for better security we have kept most of the commands for user with administrator privileges.

<br>

## ❓ How and where are the provided permissions used?

- Send Messages Permission : To send messages for the purpose of opening/closing of tickets and also to send ticket/verification system embeds
- Manage Messages Permission : This permission is used to remove the bots embed which are not of any use. Ex: After starting of verification system the yes/no embed prompted is of no use so it's deleted by the bot.
- Manage Threads Permission : There is an upcoming feature for the permission mentioned
- Embed Links Permission : For our gif system (under development)
- Attach Files Permission : For our gif system (under development)
- Read message history Permission : This is needed to delete the tickets after 24 hours inactivity
- Read Messages/View Channels Permission : This permission is needed for bot to view the channels and messages so the bot can detect it's commands
- Manage roles Permission : To add 'verified' and 'unverified' roles for Verification System
- Manage Channels : To create ticket's channel

<br>

## 🔗 Links

Privacy Policy : https://github.com/leothewolf/iko/blob/main/privacy_policy.md

Support Server : https://discord.gg/X7bZffdsQt

Bot Invite Link : https://discord.com/api/oauth2/authorize?client_id=951127063149039637&permissions=17448430608&scope=bot
