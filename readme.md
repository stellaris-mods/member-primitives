# Steam description

[//]: # (start)
Steam description transliterated from `steam.bbcode` by [our release script](https://raw.githubusercontent.com/stellaris-mods/scripts/master/stlrel).

## **Member Primitives? adds situation log projects for primitive civilizations, so that we don't forget about them\!**

I had a really hard time remembering to build Observation stations, so I had to come up with a solution\.

**This is 50% of that solution\!**

* Adds entries in the Situation Log when you survey a planet that has primitives on it
* The entries provide a tiny 14 day research project, where you can choose to get a reward or not


This was only done so that I don't forget about them, the reward is just to make it less of a chore removing them from the Situation Log after the station is built\. Because I can't do that automatically in a consistent manner\.

That's it, for now\! :\-)

## Random rewards
When the projects are researched, a window pops up where you can, either:

1. Get a reward
1. Ignore and NOT get the reward


The 14\-day research projects will randomly grant you one of the following rewards for 6 months, if you want:

* \-5% ship upkeep cost
* \+5% damage to drones, amoebas, and crystal entities
* \+2% science output from planet tiles


Existing pops only:

* 5% pop happiness
* \-5% ethics divergence
* \-5% food consumption
* \+5% growth speed


Existing ships only:

* Science ships: \+5% movement speed and \+5% survey speed
* Science ships: \-5% anomaly fail risk
* Military ships: \+2% evasion


I really want to tune the rewards based on empire age or size, and probably galaxy age\.
Also the rewards might be a bit dramatic, but I really don't want it to feel like a chore to "remove them" from the situation log\. And I think they need to stay relevant for the entire duration of the game\.

I'm not sure about the research time for the projects, perhaps it should be longer\.

The AI empires do not get these rewards, because they never get access to the projects in the first place\.

## Future plans
I will try to make some new icons for the situation log entries\.

I will try to make it so that when you inherit surveyed planets from integration or wars, or whatever, any primitive civilizations in that territory without an Observation Station get added to the log\.

Please test and let me know what you think\.

If you have suggestions for rewards or other adjustments, please leave a comment :\-)

## Compatibility
This mod does not overwrite any vanilla game files\.
But it DOES delete ONE translation string\. If you look at the screenshots above, at the end of each button title there is a comma\. The core game adds ", Available" behind every entry\.
And I can't for the life of me see how that text is useful\.
So in my own localization file, I set SPECIAL\_PROJECT\_STATUS\_AVAILABLE:0 ""\.

I have no idea what, if anything, that can or will break\.

## Please check out my other addons\!
[![](http://i\.imgur\.com/XLkY9rP\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=786514324) [![](http://i\.imgur\.com/HB3mzUd\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=790840932)
[![](http://i\.imgur\.com/QbwKam7\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=787280885) [![](http://i\.imgur\.com/Qowgmu2\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=785719197)
[![](http://i\.imgur\.com/557d0qz\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=776095610) [![](http://i\.imgur\.com/c85HK9A\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=785582857)
[![](http://i\.imgur\.com/hGJdX51\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=779729987) [![](http://i\.imgur\.com/HmbP3Gd\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=796214744)
[![](http://i\.imgur\.com/IVM6B6g\.png)](http://steamcommunity\.com/sharedfiles/filedetails/?id=799159083)
[And many others :\-)](http://steamcommunity\.com/workshop/filedetails/?id=779739023)

[//]: # (stop)
