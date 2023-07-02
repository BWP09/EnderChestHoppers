# Ender Chest Hoppers
An _**extremely**_ simple SpigotMC plugin that allows hoppers to interface with Ender Chests!
IDK why but I couldn't find just a simple plugin that does this.
I made this for 1.20.1, it will probably work for other versions too (untested).

## Note
This is my first Spigot plugin (:smiley:), so it is probably quite buggy! So if you have any issues/suggestions open an issue.
I am also new relatively new to Java so just ignore how bad the code is 🤪.
If you want to contribute then open a PR.

## Installation
Just drag n' drop! No setup, config, commands, or perms (might come in future updates).
This also means that the plugin is always active.
BTW don't mess with the `storage.json` files they are, well, used for storing Ender Chest/Hopper info between server restarts.

## Use
(Has to be done in this order)

1. Place down the Ender Chest.
   - The hoppers will use the Ender Chest inventory of the player that placed it.
2. Place down I/O hoppers.
   - I/O hoppers have to be named `ENDER ALL` in an anvil.
     <!-- In future updates you will be able to pick which slots they interface with, in the form of `ENDER [ROW]:[COLUMN]` (omitting brackets). -->
3. Test it! hopefully it will work! If it doesn't, open an issue (screenshots always help!).


It works kinda weird, but it works. I just wanted to get this working, so more/better features will come later.

## Possible Updates?
- [ ] Add support for addressing individual Ender Chest slots.
- [ ] Add support for perms (and a config).
