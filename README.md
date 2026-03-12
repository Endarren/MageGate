This addon puts some elements from the TV series StarGate onto your mage and will soon have some features for those who do not play a mage. While it does not change any of the interface, it does do some dialogue work and adds sound effects.

## Commands

Type "/mgate" to get the in game display of the commands. Add the command name at the end of that, with a space after mgate.

As of MageGate v6, there is only one command you will need to know. That is **"/mgate show"**. This will display the configuration window for Mage Gate. With that, you can do everything that was done with command line.

### Command list

*   **play**: Play one of the sound effects used by the addon.
*   **show**: Displays the MageGate main configuration frame.

## Functions

### Chat

*   Signals the start of casting a portal spell by saying "Dialing _x_".
*   Announces the completion of a portal with "Chevron _y_ locked". _y_ can be set between 7 and 9.
*   Announces failure of portal spell with "Dialing sequence aborted".
*   An optional chevron count in chat.
*   Chat messages are automatically displayed in the group you are in.

### Sound Effects

*   Optional sound effects.
*   SG-1, SG-A, or SG-U ring turning sound effect turning while casting a portal.
*   SG-1, SG-A,or SG-U gate abort sound for canceling a portal.
*   SG wormhole opening sound effect for finishing a portal.
*   Exit wormhole sound effect for when you reach the destination of ANY portal that requires a click to use.
*   A wormhole close sound effect for when a portal within 60 yards closes.
*   Option for having sound effects to play even when sound effects in game are muted.
*   Ring Teleportor, Asguard Teleporter, Star Trek TOS Transportor, and Command & Conquer Red Alert Chronoshift are available for teleport sound effects.
*   All teleport sound effects are also available for being teleported to and from an instance or when summoned.
*   You can now set all teleport spells and portal spells to the same sounds.

#### Portal Sound Effects

For portal spells, you can select a sound effect for casting the portal and for aborting or failing to cast one. For both events, you can choose from the StarGate sound effects from SG-1, SG-A, and SG-U. Each portal spell can use a different casting and abort sound effect. If you do not want that much customization, you can change it so that all portals use the same sounds.

![Portal Settings Window](http://www.curseforge.com/media/images/44/240/MG_Portal_Settings.png)

#### Teleport SFX

A list of teleporting spells and items has been added. You can use this list to select a teleport and customize the sound effect played for it.

Your teleport sound choices are:

1.  StarGate Ring Teleport
2.  StarGate Asguard Teleport
3.  Star Trek TOS Transporter
4.  Chronoshift from Command & Conquer Red Alert _(I had it so I thought I might as well add it)_

![Teleport Settings Window](http://www.curseforge.com/media/images/44/241/MG_Tele_Settings.png)

In addition, you can set if a teleport spell casted by someone else will trigger the sound effect (It is off by default because I found it annoying, but someone might want it.) You can also set the sound effect played for summoning or being teleported to and from an instance. The sound effect for each teleport spell can be different. If you do not want that much customization, you can change it so that all teleport spells use the same sounds.

#### Wormhole Close Sound Effects

Version 7 of MageGate adds a new sound effect feature for when a nearby portal expires. If a portal on the Portal Tracker closes within 60 yards of you, MageGate will play a wormhole close sound effect. The sound can be turned off and the level of sound effect can be changed. I am planning on adding an event horizon sound effect that will play while you are near a player created portal. For that, you might have three different variations to chose from, or it could be set randomly.

### Supported Languages

*   English
*   French

_If you are fluent in a language and would be interested in doing proper translation of this addon for that language, please contact me._

### Other Features

*   Optional auto accept for summonings.
*   A functional settings frame to change your MageGate settings with instead of typing them out.
*   A play command that will allow you to play any of the sound effects for Mage Gate. Sounds played by this will always be heard.
*   The option to have some sound effects triggered by others making portals.
*   Optional markers of portal locations on minimap.
*   More coming soon...

##### Portal Tracker

This feature allows you to see where a portal has been made by someone in your group on the map. Each portal is shown using the icon for that spell, i.e. the Stormwind portal marker on the minimap uses the Stormwind portal spell icon. They are not the best quality of images, since I took all of the extra stuff from them, making them circles. I am hoping to add a chevron arrow to point to portals off the minimap, but I am not good at art. If anyone has a small, like 16 x 16, chevron I could use, that would be nice.

In the feature settings window, you can disable the tracker or change their alpha value, making them more transparent if you want. Disabling the tracker will not remove the icons already on the minimap because I had some trouble getting them to come back once removed.

![Portal Tracking on minimap](http://media-curse.cursecdn.com/attachments/69/293/5800636a4259340fb84c0654b687ee32.png)

Moving your mouse over the icon of the portal on the minimap will display a tooltip with the destination of the portal. You can also click on it to see who casted it and how much longer it will last.

Anyway, the other reason for the portal tracking is to eventually allow you to have to additional sound effects; the wormhole sounds and its closing sounds for portals that are near you.

##### Auto Summon

This feature does not need much explanation. I do want to improve it into a "smart" auto summon. By that, I mean it would not automatically accept a summon when like the summoner is in the same map.

##### Traveller

This was a feature that was inspired by a friend who used to play WoW. When you accept a summon, it will broadcast in group "Incoming traveller". It is basically a way to automatically let your teammate know you got and accepted a summoning.

##### Play

This feature lets you play sound effects used by the addon. To play a sound file, you need to know the name it is stored under. Just typing "/mgate play" will show all of the names. Just type in one of them after play and it will play a sound effect. You will always hear sound effects that are played with this command, unless your computer's speakers are turned off.

## Known bugs

The only bug that I am aware of involves the ring turning sound effect. If the addon crashes, the ring turning sound effect will not stop. You can fix this by doing "/reload". I will add in code to prevent this endless sound effect from happening in future releases.

The portal exit effect can sometimes trigger when your mouse is over something with the word "portal" in the tooltip name. The only places I have seen this happen are on the gunship in Dragon Soul and in Eye of Eternity in Dragon Soul. It may happen in other places. I am working on finding a way to avoid that error.

## Reporting Bugs

If you find a bug in the addon, please let me know. You can post it in the comments or send me a private message. Please make sure to include the circumstances surrounding the bug, i.e. location, spells, etc.

## Credits

Special thanks to Ricardo58 for giving me all of the StarGate sound fx with great quality. Because of that, I have added sound effects to the addon. If you would like to have those sound effects, you can download them at [Uploading.com](http://uploading.com/files/PHXKMGM3/Stragate_Sound_Effects.zip.html) .

Thank you to the Audacity for being able to edit and convert the sound files to a format that WoW can play.

Thanks also to Diamanu for the French translations and the chevron count.

And thank you to everyone who has used this addon.
