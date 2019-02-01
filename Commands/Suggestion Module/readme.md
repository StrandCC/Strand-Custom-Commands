# Suggestion Module
This module makes making, approving, denying suggestion very easy and organised!

## Guide Markdown
We assume you are using the default command prefix, `?`.   
Commands with inputs are denoted as `?command [input]`.   
Commands with choice inputs are denoted as `?command [input1/input2]`.   

## Requirements
* One role - `Suggestion Manager`.
* Two channels - `#suggestions` & `#suggestion-log`.
* Add a welcome message to `#suggestions` channel explaining how to use the command.
* Set up the `#suggestion-log` channel to be only accessible to the `Suggestion Manager` role.

## Commands
* `?suggest [suggestion]` - Makes a suggestion in the `#suggestions` channel.
* `?approve [user] [suggestion-id]` - Approves a suggestion. Requires the `Suggestion Manager` role.
* `?deny [user] [suggestion-id] [reason]` - Denies a suggestion. Requires the `Suggestion Manager` role.
* `?implement [user] [suggestion-id]` - Implements a suggestion. Requires the `Suggestion Manager` role.
