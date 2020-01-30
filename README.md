FairyBot is a library of code I created while I was playing Lords&Knights mobile strategy. There are several bots I wrote to make me and my friend’s gaming experience more fun and easy. If you never played this game following won’t tell you much and you can only trust me if I say everyone who ever used it was excited.

Bridgy uses one gaming account to tripwire every habitat of every player from a list of alliances with 5 troops(~3 times a day it was updating dead/sent back troops or over numbered troops left after building fortress/city). Every several minutes Bridgy checks whether there was a fight with those tripwires, whether there were significant losses to think this attack is real, posts this report, groups it with others, and sends as in-game message as well as message in Telegram messenger.

AutoAllianceHelper has a Tkinter GUI and can use up to 10 accounts to click the free alliance help button every 20 minutes. Unlike the idea of simulating an android device and simulating screen clicks, this method allows recovering from server errors, logins into that account, etc.

AttackPlanner helps planning attacks. With it, you can upload alliances, players, habitats by links, or have all habitats of player/alliance; you can parse links from a text; you can take players/alliances from rating; you can take habitats around certain point on a map. After you can sort or filter them by points, type(castle/fortress/city), distance from a point on a map, if shield or vacation mode is used. Also, you can group them by everything mentioned before, including clustering(5 castles or 5 fortresses for building). After you can split real and fake targets among your players mentioning how many real targets they can attack(fakes can also be divided relatively if the total amount is fixed). Target messages are automatically created with time, date, targets, player names on them.

Spammer uses multiple accounts and multithreading to share a message with players of top-50 alliances on the server as fast as possible. I only used it twice to share my point of view on what happened. This method is abusive, and I highly recommend not to use it on the main accounts.

Burner is a Bridgy but with the opposite function. Instead of protecting its own players with 5 troops, it attacks enemies with 1. Of course, 1 attack does not make any severe difference, but when every habitat is under attack, it brings morale a bit down, clutters everything for people playing multiple accounts and is harmful to bots with defense functionality which can be triggered by these attacks or prevent them from using habitats with one attack for helping against actual real attacks.
