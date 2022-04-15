# Verification System
<br>

> **Note :** Please check [here](https://github.com/leothewolf/iko#%EF%B8%8F-how-secure-is-our-bot) for the permissions needed for executing the commands. 
<br>

### Some confusing words
+ Verified role : This will be the role alloted when user is verified by the bot
+ Unverified role : This will be the role alloted when the user joins the server and removed after verification

### Private Chat Based Verification System's Commands
* -vend
> vend command is used in private chat and it clears all the previous verification requests done by user<br><br>Example: If a user tried to verify himself from a server A but wants to instead get verified for server B then he should type -vend in private to the bot for it to remove the trace of verification requests for the user from server A and then click 'Verify me' in server B to get verified.
 <br>  
 * -vnew
 > vnew command is used in private chat and it fetches new captcha<br><br>P.S. Users only have three(3) trials to get verified and requesting a new captcha uses one of those trials

### Server Based Verification System's Commands

* -vstart
> vstart command is used in server to start Verification System for that server<br><br>How to exactly use this command?<br>Before setting up Verification System you need to make two roles one verified and other unverified and you can also make two channels 'rules' (which user will see on joining server) and 'get-verified' for the verification. **Assign both roles to the bot**. Next make the categories private which you wanna just allow verified people to view by making it private and adding verified role to it. Keep 'rules' channel open to everyone and make 'get-verified' channel private and add unverified role to it.<br><br>Next, navigate to get-verified channel to setup the bot.<br><br> **Note** : You need to mention the role id and not the role itself!<br><br>If you want to setup Verification System which has embed without image just type:<br><br>```-vstart -r role_id```<br><br>If you want to setup Verification System which has embed with image just type:<br><br>```-vstart -r role_id -i image_link```

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
> vrole command is used to change the current role assigned when the user is verified<br><br>**Note: This is not recommended and even if you change it don't forget to assign the same role to bot and yea don't tag the role you just need to type the role id**<br><br>How to use -vrole command?<br><br>Just type the following command to change current role assigned:<br><br>```-vrole -r new_verified_role_id```

* -vurole
> vrole command is used to change the current unverified role assigned when the user joins server<br><br>**Note: This is not recommended and even if you change it don't forget to assign the same role to bot and yea don't tag the role you just need to type the role id**<br><br>How to use -vurole command?<br><br>Just type the following command to change current role assigned:<br><br>```-vurole -r new_unverified_role_id```

 ⠀
* -vimg
> vimg command is used to change the image of Verification System embed<br><br>How to use -vimg command?<br><br>To just assign new image type:<br><br>```-vimg new_image_link ```<br><br>To remove image without assigning any new type:<br><br>```-vimg remove```
