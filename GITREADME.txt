The following is all the information needed to load my custom keybindings into my omarchy configuration:

The git folder is going to need to be initialized in the /home/<user>/.local/share/omarchy/default. Use the following git command:


Then you can just pull the repository from there.


Additional Information:

https://www.reddit.com/r/omarchy/comments/1nq4kat/where_is_the_caps_lock_mapped_config_file/

Hello, I have been using arch for a year and has found omarchy great. I have a full keyboard but moving to arrowws and home, del buttons is inefficient, and want to map those with my Fn key and other keys. But as a left handed user, I wanna map caps lock to Fn key first, and then to other keys. But I just realised that caps lock is already mapped to emojis (which is pretty cool tbh), and I wanna know where they are mapped, such that I can make space for the regular keys I wanna map to arrows and stuff.
Thanks in advance!

EDIT: Found at ~/.local/share/omarchy/default/xcompose

From the Omarchy manual:
You can add more of your own by editing ~/.XCompose, then running omarchy-restart-xcompose in the terminal to get the changes picked up


Note: When running this command, the terminal will get all kind of glitchy. This is normal. DO NOT ctl z or ctl c out of the glitchy. Let it ride until it is done and then it should work fine.

