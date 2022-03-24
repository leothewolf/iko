# Ticket System

<br>

> **Note :** Please check [here](https://github.com/leothewolf/iko#%EF%B8%8F-how-secure-is-our-bot) for the permissions needed for executing the commands. 
<br>

* -tstart
> tstart command is used to start Ticket System for that server<br><br>How to use -tstart command?<br>Choose a channel in your server from where tickets will be created and from where the ticket system can be managed, let the name of channel be 'create-tickets' [can be any]. Next for setting up Ticket System<br><br>If you want to setup Ticket System which has embed without image just type:<br><br>```-tstart support_role```<br><br>If you want to setup Verification System which has embed with image just type:<br><br>```-tstart support_role -i image_link```<br><br>**Note :** If the support role has more than one word examples it's name 'supporter role' then just type this command: <br><br>```-tstart supporter role -i image_link```

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
> trole command is used to change the currently assigned support role<br><br>To use this command first navigate to the ticket channel or the main channel from where ticket system was set up [If you don't remember that just type -tstatus to get it]<br><br>To change the role run the following command<br><br>```-trole new_support_role```

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
