# Profile Module
A command group designed by the TheRoboticon.

> This module combines the default Tags Module included in Dyno with the power of Custom Commands to create a simple profile system for users.  
> Users will be able to set a 150-character description and view other profiles, while moderators are able to remove profiles deemed disruptive or unwanted.  
> This module group features a master switch disabling the system's profiles while still allowing moderators to remove profiles.

## Guide Markdown
We assume you are using the default command prefix, `?`. 

## Requirements
* The default tag system in Dyno needs to be enabled. Use `?module tags` to enable the tag system.  

## Commands
* `?setinfo [information]` - Sets the text displayed on your profile.  
* `?profile [user]` - Views a user's profile.
* `?delprofile [user]` - Deletes a user's profile. Requires Server Moderator.  
* `?profiles [enable/disable]` - Enables/disables the profile module. The ``?delprofile`` command will not be disabled. Requires Server Moderator.

*To see the correct usage format of the commands, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*
