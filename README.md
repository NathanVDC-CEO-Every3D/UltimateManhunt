# **UltimateManhunt**
This plugin is made to contribute to the Minecraft server community and add new fun minigames to servers that players would enjoy.
Me and my team also own a server called KingSMP, be sure to take a look at it.
KingSMP Discord: https://discord.gg/2hmEU2MWxB

## **License**
This plugin is licensed under **CC BY-NC-ND**, this means this plugin is **not** open source, you can not make changes to this plugin
or/and sell it commercially after. If you do want to contribute to making changes to this plugin please join my discord server and 
create a support ticket, I will respond as soon as possible.

## **How to use?**
Download the plugin [here](https://kingsmp.eu/plugin).
Upload the plugin into your plugins folder of your **Spigot** server.
Restart the server and edit the config file to your wishes.

You also need these other plugins for this plugin to work:  
[KTools](https://www.spigotmc.org/resources/ktools.108301/) and [WarningManager](https://dev.bukkit.org/projects/warningmanager/files)  
Please use version 2.4 for WarningManager.

### **Commands**
/manhunt <-- Gives you all the possible commands for manhunt.  
/manhunt join <-- Joins the game waiting que.  
/manhunt leave <-- Leaves the manhunt game but also punishes you by taking 5 points away from you or warning you if you have 0 points.  
/manhunt points <-- Views your current amount of points.  
/manhunt spectate Name_Of_Hunter <-- Spectates the hunter you entered, you can't spectate runners as that could be used for cheating.  
/manhunt spectate_random <-- Spectates random hunter of a random ongoing manhunt game.  
/manhunt reset Name_Of_Player <-- Resets all the points of the entered player (this message comes with errors, don't mind these errors the function works fine.)  
/manhunt reset_all <-- Resets the points of all players.
/manhunt create_top <-- Creates a leaderboard where you are standing, this leaderboard is focused towards the amount of points the player has.  
/manhunt delete_top <-- Deletes the leaderboard that is closest to you.

### **Permissions**
Setting up permissions isn't necessary for this plugin to work which makes it very
easy it use, it's upload and play but there are still permissions you can use to make the game better, for example
you can set a custom time for people who have a that permission, if the time group in the config is called vip 
the permission will look like this: manhunt.vip.

## **Placeholders**
This plugin has placeholders that you can use in your own leaderboards
or to display the top players somewhere. These placehoders are:  
%manhunt_player_name%  
%manhunt_topName_place%  
%manhunt_topPoints_place%

