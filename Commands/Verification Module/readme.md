# Verification Module (Images)
A commmand group designed by Nex
> This command group implements an advanced verification system using image verification and codes.
> By using this, you can easily prevent raids from occuring by creating a system difficult for bots to navigate. 

## Guide Markdown
We assume you are using the default command prefix, `?`.  
Commands with inputs are denoted as `?command [input]`.  
Commands with choice inputs are denoted as `?command [input1/input2]`.

## Requirements
* One channel, ``#welcome``, which contains any rules and information joining users should read.
* Inside ``#welcome``, make sure to tell the user to use ``?dmimage`` to get their code.
* One role, ``Newcomer``, which has been denied Read Message permissions in all channels except welcome.
* This role should be given when joining. You will use the Autoroles module for this. \*

## Command Syntax and Usage
* ``?dmimage`` - Sends a DM to the user with a random image.
* ``?[password]`` - Verifies the user.   
* Note that ``?[password]`` is just a placeholder for any of the [10 codes](https://github.com/Strand-Custom-Commands/Strand-Custom-Commands/blob/master/Commands/Verification%20Module/codes.txt) available. You should not add ``?password`` as an actual command.
* ``?verify [user]`` - Verifies another user.
* ``?unverify [user]`` - Unverifies (?) another user.

\* If you need help setting up Dyno modules, you can head to their [support server](https://discord.gg/MRaPFTH).

*Guide Version 1.1*
