# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore

- Latest build status with azerothcore:

Based on an original Mod by StygianTheBest
Reworked by Nelnamara 7/2024

### Description

This module performs several actions on new players. It has the option to give new players BOA starting gear,
additional weapon skills, and special abilities such as custom spells. It can also set the reputation of the player
to exalted with all capital cities for their faction granting them the Ambassador title. This is typically done in
the core's config file, but it's bugged (as of 2017.08.23) in AzerothCore. It can also announce when players login
or logoff the server.

### Features ###
------------------------------------------------------------------------------------------------------------------
- Player ([ Faction ] - Name - Logon/Logoff message) notification can be announced to the world
- New characters can receive items, bags, and class-specific heirlooms
- New characters can receive additional weapon skills
- New characters can receive special abilities
- New characters can receive exalted rep with capital cities (Title: Ambassador) on first login

### Installation
1- Place the module in the AzerothCore modules folder
2- Compile and install AzerothCore
3- Place Patch-9.MPQ in your clients data folder
4- Adjust settings in mod_customlogin.conf

Upon login your characters should get a variety of items:
- Bags
- Class Based supply bag with starter Heirlooms
- Special "Convention Goody Bag"
- A Handy Engineering item (WIP)

### Credits

- StygianTheBest for the original Mod
- [Nelnamara](https://github.com/Nelnamara) 2024 rework, and new additions
