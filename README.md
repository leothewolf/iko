<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/leothewolf/iko/main/logo_for_git.png" alt="Iko Discord Bot">
  <br>
</div>

# <p align="center">Iko Bot</p> 

# Overview
Iko is a multipurpose discord bot. Our aim is to provide all in one bot so you don't need to have multiple bots!

**Some of it's features:**
- <a href="#Ticket System">Ticket System</a>
- <a href="#Verification System">Ticket System</a>

# Ticket System

test

# Verification System

# Verification System

### Private Chat Based Verification System's Commands
* -vend
> vend command when used in private clears all the previous verification requests done by user
    Example: If a user tried to verify himself from a server A but wants to instead get verified for server B then he should type -vend in private to the bot for it to remove the trace of verification requests for the user from server A and then click 'Verify me' in server B to get verified.
   
 * -vnew
 > vnew command when used in private fetches new captcha
P.S. Users only have three(3) trials to get verified and requesting a new captcha uses one of those trials

### Server Based Verification System's Commands

* -vstart
> vstart command when used in server is use to start Verification System for that server
⠀
How to exactly use this command?
Before setting up Verification System you need to make two roles : 		'verified' and 'unverified' and you can also make two channels 'rules' [which user will see on joining server] and 'get-verified' for the verification. **Assign both roles to the bot**. Next make the categories private which you wanna just allow verified people to view by making it private and adding role 'verified' to it. Keep 'rules' channel open to everyone and make 'get-verified' channel private and add role 'unverified' to it.
⠀
Next, navigate to get-verified channel to setup the bot.
⠀
If you want to setup Verification System which has embed without image just type:
 ```-vstart verified_role```
 ⠀
If you want to setup Verification System which has embed with image just type:
 ```-vstart verified_role -i image_link```

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
> vrole command is used to change the current role assigned when the user is verified
 ⠀
[P.S. **This is not recommended and even if you change it don't forget to assign the same role to bot**]
 ⠀
How to use -vrole command?
 ⠀
Just type the following command to change current role assigned:
 ```-vrole new_verified_role```

 ⠀
* -vimg
> vimg command is used to change the image of Verification System embed
	How to use -vimg command?
 ⠀
 To just assign new image type:
  ```-vimg new_image_link ```
 ⠀
To remove image without assigning any new type:
  ```-vimg remove```
