<div align="center">

# Among-Us-Host-Tools-Suite

**a collection of small mods that work together for a better game experience**

[![Code license: GPL-3.0](https://img.shields.io/badge/code-GPL--3.0-blue.svg)](LICENSE)
[![Platform: Windows](https://img.shields.io/badge/platform-Windows-0078D4.svg)](#requirements)

</div>

#
At this point there are *several* host utility mods out there floating around to better moderate the weirdness that can be publand. They almost all share a common problem: most of them keep getting more and more and more features added until they are a giant sprawling bloated mess. Yes they work great, and have great features, but sometimes they include a lot of features you have absolutely no interest in. And on top of that, the bigger the mod is and the more parts of the code it touches, the higher the chances are that the whole mod will break any time there is an update to the game, no matter how small.

My plan to solve that was to split the tool features into different mini mods that all do different portions of the job. (I can not take full credit for this idea. Thank you Makeshift/Alternatemew).  That way, if an update comes out, there is a much higher chance that only a portion of the suite of mods will be affected, and you can temporarily remove those until those portions are fixed, and you can continue to use any other features that are still working. It also allows you to pick and choose adding features you do or do not want, without the need to bog things down with a million features you will never use.

**The core mod**

[Banlist](https://github.com/katzklaw/banlist). Just what it says on the box. Lets you maintain a friend code based blacklist/whitelist. Blacklisted people are auto-banned when they attempt to join. Auto kicks or bans people who say start words (configurable list) or disallowed words (configurable list), or who are under a certain (configurable) level. Auto kicks/bans people with invalid friend codes or people who are on your in-game block list. Auto kicks/bans people who join with names that are on a (configurable) disallowed list, regardless what their friend code is. Includes a moderator system so you can allow specific friends to help maintain peace by also kicking/banning troublemakers. You can append a reason when using the /kick or /ban chat options and that reason gets added to the ban list so you can remind yourself WHY you banned that guy.

**The add ons**

Ender.  Lets you end a meeting or a game prematurely. Troll mashes the report button 10 seconds into R1, then says nothing? /endmeeting or /em.   It's a rarer case, but sometimes you just need or want a game to end immediately for whatever reason. /endgame or /em ends the game as an "impostor disconnect".  ALSO integrates with the moderator list from Banlist and allows anyone whom you have designated as a moderator to end meetings using the same /endmeeting or /em commands. 

TaskKillTracker. Shows you what your task completion status is in number/number format appended to the end of your name. Shows what EVERYONE's task completion status and/or number of kills made on the vote screen after you are dead. Adds a "dark mode" to chat. Allows you to adjust the color of chat to any chosen hex code. Each one of these features can be individually toggled on or off. 

[GameLogger](https://github.com/katzklaw/TwixLogger). Forked from [Twix](https://github.com/whichtwix)'s Game Logger and updated for the current update. Changes from Twix's version: vote logging is on by default, can be toggled off. Votes are logged in the order they are cast, not in ID order as previously. In addition to how many kills each imp made at the end of the log, there is also a list of how many tasks each player finished.

RpcSniffer.  A rudimentary anticheat. Alerts you if someone triggers a *possibly* invalid RPC. ***TAKE THE INFO FROM THIS LOG WITH A GRAIN OF SALT.*** It will not capture everything, because some cheat actions just do not generate RPC calls, and it can potentially give a false positive.  ***BUT***... having that warning is better than nothing at all and can possibly alert you to someone doing fishy shit in your game. 


# 
**Installation:**
If you do not already have bepinex in your game folder, download the "Core Files" zip, and put all the files inside that folder into your game folder, wherever your Amongus.exe resides. Then open the bepinex folder, and then the plugins folder, and drop the dll files for the various features you want into that folder and load your game. (The first time you load your game after installing any mod it will take a very long time to load as it is building new config files and whatnot. Don't panic. Wait it out). If any mod ceases to function due to an update, or you no longer wish to use that particular mod, simply remove it from the plugin folder. 


#
<p align="center">This collection of mods is not affiliated with Among Us or Innersloth LLC, and the content contained therein is not endorsed or otherwise sponsored by Innersloth LLC. Portions of the materials contained herein are property of Innersloth LLC.</p>
<p align="center">© Innersloth LLC.</p>
