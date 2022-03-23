<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/leothewolf/iko/main/logo_for_git.png" alt="Iko Discord Bot">
  <br>
</div>

# <p align="center">Iko Bot</p> 

# Overview
Iko is a multipurpose discord bot. Our aim is to provide all in one bot so you don't need to have multiple bots!

**Some of it's features:**
- <a href="#ticket-system">Ticket System</a>
- <a href="#verification-system">Verification System</a>

# Ticket System

* -tstart
> tstart command is used to start Ticket System for that server<br><br>How to use -tstart command?<br>Choose a channel in your server from where tickets will be created and from where the ticket system can be managed, let the name of channel be 'create-tickets' [can be any]. Next for setting up Ticket System<br><br>If you want to setup Ticket System which has embed without image just type:<br><br>```-tstart support_role```<br><br>If you want to setup Verification System which has embed with image just type:<br><br>```-tstart support_role -i image_link```

<br>

* -tclose
> tclose command is used when you want to close the ticket

<br>

* -tstop
> tstop command is used to stop Ticket System and delete it from the server. Deletes the created tickets too

<br>

* -tstatus
> tstatus command is used to get the current status of Ticket System

<br>

* -trole
> trole command is used to change the currently assigned support role<br><br>To use this command first navigate to the ticket channel or the main channel from where ticket system was set up [If you don't remember that just type -tstatus to get it]<br><br>To change the role run the following command<br><br>```-trole current_support_role new_support_role```<br><br>[The role assigned and the role removed should only be one word. Ex: 'supporter' and not 'supporter blah blah']

<br>

* -tnotify
> tnotify is used to change notification settings for notification on ticket close and ticket open<br><br>For ticket open the users are tagged in the ticket thus formed but for closing the users are notified via PMs<br><br>How to use tnotify command?<br>So basically we have three arguments we can enter here that are none, author and all<br><br>So for example if you wanna notify everyone of opening but just the author[the one who opened ticket] about closing [this are default settings] the command will be:<br>```-tnotify all author```<br><br>For notifying everyone about ticket opening and closing command will be:<br><br>```-tnotify all all```<br><br>And same goes for notifying noone: <br><br> ```-tnotify none none```

<br>

* -tdel
> tdel command can be used in Ticket System channel to delete all the tickets which are open

<br>

* -tchannel
> tchannel command can be used in any channel to reset Ticket System channel<br><br>Just type following command to change Ticket System channel<br><br>```-tchannel new_channe_id```

<br>

* -timg
> timg command is used to change the image of Ticket System embed<br><br>How to use -timg command?<br><br>To just assign new image type:<br><br>```-timg new_image_link ```<br><br>To remove image without assigning any new image type:<br><br>```-timg remove```

<br>

# Verification System

### Private Chat Based Verification System's Commands
* -vend
> vend command is used in private chat and it clears all the previous verification requests done by user<br><br>Example: If a user tried to verify himself from a server A but wants to instead get verified for server B then he should type -vend in private to the bot for it to remove the trace of verification requests for the user from server A and then click 'Verify me' in server B to get verified.
 <br>  
 * -vnew
 > vnew command is used in private chat and it fetches new captcha<br><br>P.S. Users only have three(3) trials to get verified and requesting a new captcha uses one of those trials

### Server Based Verification System's Commands

* -vstart
> vstart command is used in server to start Verification System for that server<br><br>How to exactly use this command?<br>Before setting up Verification System you need to make two roles : 'verified' and 'unverified' and you can also make two channels 'rules' [which user will see on joining server] and 'get-verified' for the verification. **Assign both roles to the bot**. Next make the categories private which you wanna just allow verified people to view by making it private and adding role 'verified' to it. Keep 'rules' channel open to everyone and make 'get-verified' channel private and add role 'unverified' to it.<br><br>Next, navigate to get-verified channel to setup the bot.<br><br>If you want to setup Verification System which has embed without image just type:<br><br>```-vstart verified_role```<br><br>If you want to setup Verification System which has embed with image just type:<br><br>```-vstart verified_role -i image_link```

 ⠀
* -vget : this command when used in server, fetches back the Verification System embed
> -vget command when used in server, fetches back the Verification System embed

 ⠀
* -vstop
> vstop command when used in server, stops and deletes Verification System embed

 ⠀
* -vstatus
> vstatus command when used in server, fetches current status embed of the Verification System embed

 ⠀
* -vrole
> vrole command is used to change the current role assigned when the user is verified<br><br>P.S. **This is not recommended and even if you change it don't forget to assign the same role to bot**<br><br>How to use -vrole command?<br><br>Just type the following command to change current role assigned:<br><br>```-vrole new_verified_role```

 ⠀
* -vimg
> vimg command is used to change the image of Verification System embed<br><br>How to use -vimg command?<br><br>To just assign new image type:<br><br>```-vimg new_image_link ```<br><br>To remove image without assigning any new type:<br><br>```-vimg remove```
