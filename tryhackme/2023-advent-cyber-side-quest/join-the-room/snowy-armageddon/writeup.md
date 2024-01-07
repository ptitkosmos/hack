# SQ2 - Snowy ARMageddon - Join the room

The challenge is in the mini game of the regular [advent calendar, day 6](https://tryhackme.com/room/adventofcyber2023#task-12).

I advise you to follow the learning path to understand what can be done in this game and how memory can be affected.

Play a fresh minigame.

Overflow first time the memory for many coins.

You may have notice that the shop misses some items. Get "a" item (i.e. the white yeti token) with the memory corruption.

If you talked to the shoper, he is okay to sell you the real yeti token (blue one). You just have to ask for "a" item in the shop.

In front of the house, a new character appears. Talk several times to the Glitch and he will give you some clues : 
> A cat named "Snowball" talks to the shoper "Midas" and the name switcher "Ted" with exactly "31337" coins and the "Yeti token", and make the secret 30 lives code.

Reset your memory to get normal "a" item (white yeti token). Depending your previous try you may reset your inventory before (check game instructions for that).

Rename all the stack with the previous names (think to rename several times to have the nul bit after each entry) and `space space { z` coins.

Rename your self only Snowball.

Talk to the shoper "Ted" and buy him :
* "a"
* 6 mushrooms
* 4 erable leaves
* 1 red ball
You should have the 31337 coins and all well named.

Do the Konami code (&uarr; &uarr; &darr; &darr; &larr; &rarr; &larr; &rarr; a b).

Wait till the QR code appears (down).
