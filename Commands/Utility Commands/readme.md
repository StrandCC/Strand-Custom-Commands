# Utility Commands
Commands designed by the Strand Team.
> Useful commands for communication and general server improvement.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Commands
* `?advdm [user] [message]` - Sends a dm to the speficied user and then announces a success message. 
* `?dashboard` - Links to the server's dashboard.
* `?link [link] [message]` - Creates an embed containing a link, along with a message.
* `?lookup [user]` - Shows information about the specified user (Updated by TheSilentPro#9920).
* `?mention [user] [message]` - Mentions the user, shows their status and then says the message you provide. Useful for anonymous pings.
* `?owner [message]` - Sends a message to the server owner via DMs.
* `?panel (module)` - Links to a specific module on the dashboard. List of modules: `autoroles`, `customcommands`, `moderation`, `music`, `autoresponder`, `tags`, `actionlog`, `announcements`, `automessage` & `automod`.
* `?reddit [subreddit]` - Searches the provided subreddit and then outputs the result in an embedded message. 
* `?pindmods [message]` - Pings the moderators with a message. Requires two roles: `Trusted` & `Moderator` and one channel: `#mod-pings`.
* `?status [user]` - Checks the status of the specified user.  
* `?superclean` -  Removes all Dyno command triggers and responses from the channel.

Currently Bugged:
* `?pomodoro` - Sets a [Pomodoro Timer](https://francescocirillo.com/pages/pomodoro-technique) for the user.

*To see the commands in action, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*

### Note
The `?remindme` command is currently bugged, which may affect the `?pomodoro` command.
