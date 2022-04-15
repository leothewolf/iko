# Bump System

<br>

> **Note :** Please check [here](https://github.com/leothewolf/iko#%EF%B8%8F-how-secure-is-our-bot) for the permissions needed for executing the commands. 
<br>

### 🤔What the hell is bump system?
Let me take an example, let's say you have like 20 servers and you daily post a gif or some stuff which you again repost to all of your 20 servers....Ain't that too boring and too tiring? Well here come's **Iko** to the rescue with it's amazing bump system. What the bump system does is when you post a particular message in a channel it will repost that message to all of those 20 server in a particular channel which you specify, so now no need to post in all server, you just post in once and in the rest bot posts it!

<br>

### Some common terms we will use

+ Agent : Agent here refers to the person who will post the message in a particular message to be posted in other servers
+ Agent Id : This is the agent's user id
+ Bump channel : This will be the main channel from where the message will be distributed, you post a message here and the bot will post those messages in all the servers where you have your agent id configured
+ Sub chanel : This are the channels on other server where the message from bump channel will be posted

<br>

### How to use?

1) First choose a bump channel or a channel from where your post will be posted to other channels. Type in it ```-bagent```

2) Once you type ```-bagent``` the bot will give you a unique agent id copy it. Next navigate to a sub channel or the channel on other channel where you wanna post from the main bump channel

3) In sub channel type ```-bstart -a agent_id``` this will start the bump system in the channel and link the current sub channel to your main bump channel

4) You can add as many as sub channel as you want in different servers or same server.

5) Now to post anything, example a gif link type this in in your main bump channel ```-bdump gif_link``` . **Bingo!** If you have followed all steps correctly it was also posted in other sub channels!

**Note : The message you include with -bdump can be as long as you want, it can also be multiline and can also include quotes and bold/italics letters**

<br>

### Some other commands

+ ```-bstop``` : this command when used in any sub channel will stop the bump system posting for that channel

<br>

+ ```-bdetails``` : to get all the servers associated with an agent (You need to be an agent for this)

<br>

+ ```-bstatus``` : can be used by admin to see if bump system is running in a channel

<br>

+ ```-bchannel``` : to remove a sub channel of an agent (this can be only used by an agent and only to remove a sub channel associated to him/her)
> How to run -bchannel command? <br><br> Just type following command in you main bump channel : <br> ```-bchannel -c channel_id``` <br><br> (Channel id of the channel the agent wants to remove)
