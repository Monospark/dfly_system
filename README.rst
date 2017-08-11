dfly_system
===========

dfly_system is a collection of dragonfly grammars which provide the following essential features for `dragonfly_loader <https://github.com/Monospark/dragonfly_loader>`_:

| **On-the-fly grammar reloading**
| Reload your grammar files after making a change by using the reload command. If something breaks, you can fall back to the latest working version.
|
| **Basic control commands for WSR**
| If you want to use your dragonfly grammars with *Windows Speech Recognition* (WSR), you need some basic commands to control WSR. However, WSR does not provide any control commands, e.g. "stop listening". dfly_system provides you with these commands.

Command reference
-----------------

- *reload modules* - completely reloads all loaded modules and configurations
- *enable <grammar name> grammar* - enables the given grammar if it is not already enabled
- *disable <grammar name> grammar* - disables the given grammar if it is not already disabled

WSR only commands:

- *quit* - quits
- *stop listening* - disables all grammars until it's woken up again
- *wake up* - enables all the previously disabled grammars

The translated commands for other languages can be found in the *translations* directory.
