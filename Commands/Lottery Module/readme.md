# Verification Module
A commmand group designed by the Roboticon.

> This command group implements a lottery system with a thousand combinations, as a well as master switch for the module.  
> This module can help you run giveaways within your server.

## Guide Markdown  
We assume you are using the default command prefix, `?`. Commands with inputs are denoted as ``?command [input]``. Commands with choice inputs are denoted as ``?command [input1/input2]``. Commands with optional inputs are denoted as ``?command (input)``.

## Requirements
* One channel: ``#lottery-tickets``, which has send message permissions denied for ``@everyone``.
* One role: ``Lottery Winner``, which will be given to the winning user.

## Commands
* ?numbers [num] [num] [num] - Posts the user's lottery number in the chat.
* ?draw - Selects the winning combination and filters for it.
* ?winner [user] - Awards the winning user.

*To see the commands in action, visit the [Wiki](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/wiki).*
