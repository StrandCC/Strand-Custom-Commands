# Custom Command Guide
So, you're here to learn how custom commands work. Well, you've come to the right place!
Before we begin, let's talk about some of the syntax I will be using in this guide.

## Syntax

This guide assumes you are using the default prefix for commands, which is the question mark (?). If you have a different prefix, you should use that instead.

Command examples will be written like this:

**?command** **\[input\]** \- *Usage and Syntax*

>Command Content

**Chat Output (If Applicable) and Explanation**

Let's get started!

## Variables

*Variables are simply placeholders that you can use inside custom commands. These placeholders will be updated with specific values when the command is called. There are a lot of variables that can be used in custom commands, but a select few tend to get used the most.*

`{user}` outputs the username of the person calling the command.

`{server}` outputs the name of the server.

`{channel}` outputs the name of the channel.

`{&role}` mentions a specific role.

`{datetime12}` displays the 12-hour time and date in EST.

`{delete}` deletes the calling command.

`{silent}` silences the default response of the bot.

`{require:role}` requires a specific role to call the command.

`{require:#channel}` requires a specific channel to call the command.

`{dm:user}`sends the response as a DM to the user.

`$1` returns the first input for a command,`$2` the second, and so forth.

`$1+` returns the first input and everything after that.`$2+` behaves the same way, and so forth.

`{choose:option1;option2;option3}` makes a list of items to randomize, while`{choice}` gets a random selection from that list.

**That's a lot of variables! So how can we use them?**

*Let's start off with a simple command which tells the user where they are.*

**?location** - outputs the location of the user in the server.

>{delete}  
>  
>{user}, you are in the {channel} channel in the server {server}.

**Chat Output**

For each variable in the command, Dyno responded with a specific output. Since I called the command, it used my name (TheRoboticon) with the {user} variable, and since the command was called in the #support channel in the Tutorial Server, those two variables were specified accordingly.  

### Role Functionality
Let's say you have a gaming server and you've got a group of people you play with. Why not make a command to notify them when you're ready to start?

**?ready**

>{delete}
>{require:Gamemaster}
>{require:#gaming}
>{&Gamers}, we're ready to go! It is currently {datetime12}.

**Chat Output**

