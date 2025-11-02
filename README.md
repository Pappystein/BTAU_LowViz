# BTAU_LowViz
LowVisiblity is integrated with Battletech Advanced Universe.

The Warnings and Basics:  
0)  Everything in this document is important to know.  However if you want to read the GUTS of the changes and how it will affect your game on your computer skip to IN GAME before reading the rest of this.  NOTE If you install my mod you are agreeing you have read everything here!
1) Installing LowVisiblity Mid career can cause issues to happen with mechs in your mechbay.  Store and rebuild to resolve issues/errorsx
2)  ****MOST IMPORTANT**** If you add These folders for LowVisiblity and then LATER REMOVE them... you ***WILL*** BREAK YOUR SAVE!!!!
3)  This is based on the LowVisiblity mod as included in RogueTech developed by FrostRaptor.  I did seek and recieve permission to post/repost even though FrostRaptor as an Open licensing.
4)  Installing BTAU_LowVis into your Battletech Advanced Universe build.  DOES VOID your support warranty with the BTAU Team.  Do not post errors/Ticket to the BTAU Team.  Do not blame the failing of me or this Sub-Mod on the BTAU team.  Installing this Submod means you AGREE that the BTAU Team is NOT AT FAULT for any issues you may have with the game.
5)  In so far as updates to BTAU is concerned.  The Basic settings contained here in have only been adjusted ONCE in 3 years of updates.   And that was because the BTAU Dev team did the same thing I was previously doing in this submod (a simple chassis flag.)  So I had to remove my duplicate settings.   This mod is pretty BTAU version Agnostic.   Still playing on V17.1   You can use this.   Playing on 18.3  Yes you can use this.  And as of initial Release... you can use it with V19.5.   HOWEVER BTAU Versions prior to V19.5 will loose certain features that are specific to the Sanctuary Alliance.  Don't Expect your SA tech to be all powerful if you are running this mod on a Build of BTAU before 19.5

So what is LowVisiblity and what does it do:
In its simplest LowVisibility tries to make Sensors in HairBrainedScheme's Battletech worke closer to Table Top (TT hence forth) and Real life.  There are plenty of limitations still in the game with LowVisiblity that makes this "Better but not great."   What LowVisiblity does is "adjust" the power of sensors so they work like any ElectroMagnetic sensors (RADAR/LIDAR/SONAR/Mk1Mod1 Eyeball are all ElectroMagnetic at their core) behave like ElectroMagnetic Sensors do in Real life.   That is to say the Larger the signature the further away it can be detected the smaller the signature the closer things are before they are detected.   Now without getting into the Weeds here and now... BTAU is not really setup for this in its current implimentation, and The BTAU_LowViz submod does not currently address this key issue.    BUT BTAU_LowVis is the first of 3 building blocks to do so with future expansions growth.   Only time and interest in these changes will see if I invest the emmense time and effort into going further.

HOW Does LowVisiblity do this.    Seriously it is by adding more math to sensor equations.   The Sensor Equations in HBS BT are almost Boolean.   Is target less than xxx meters away from active unit.   If TRUE then detected with full information.  If False NOT DETECTED.    Now LowVisiblity gets into Exponetial and Logrithmic math which is actually the same math that is used by Real World Sensors....  It isn't the SAME exact math but close enough for the point of comparision.   Why isn't it the same?  For that we would have to ask Frost Raptor but in short I think it is because LowVisiblity is still combining all the various sensors into ONE SINGLE formula.   

IN GAME (The Mini faq):
* Will this make the game run slower on my Po-Ta-To PC (very slow computer with limited memeory) vs Standard BTAU.    yes.   SLIGHTLY.
* Will this make the AI tougher to fight against:   BOTH   The AI can detect you less and has less information to prioritize targeting... Which is almost equally canceled out by you haveing the same limitations.
* How are sensors changed?   Well sensors are now generational in a sence.   Industrial Sensors don't see as well as say Periphery sensors... But Periphery Sensors do not offer the protection that Industrial sensors grant for example.   Have an industrial mech?  Got some clan Sensors out of salvage?   You can upgrade the Industrial mech with those clan sensors.   Wow did your gunnery improve!
* Why is my Screen all green-Monochrome?   You are on a night mission and the unit in question is equipped with the ADVANCED NIGHT Vision feature.  The Visual change to green can be jaring for some peoples eyes so it can actually be turned off in the LowVisiblity settings when you are out of the game.
* How come I can not tell much information about the enemy mech I am about to shoot?   Your sensors do not have enough power to get past the enemy's counter-measures (Not ECM like we know from BTAU)  Get better sensors... or have multiple units in close (less than about 300m) from the enemy unit before moving your main shooter into range.


INSTALLING BTAU_LowViz
Drop the included folders into the Mods Folder.     DONE   No configuring of files to work on your PC is required other than that.   It is Suggested that you run a new career after installing but as stated previously you CAN dump this in and rebuild all your units... a tedious process.

Found a Bug?  Found an Error?   How to get support?
Direct Message Pappystein on Discord from the BTAU server.

Have a question about this mod.   There is a Pafftek Industries Low Visiblity BTAU Integration sub-channel under the #Modding-forum on the BTAU discord Server.  Feel free to read and the post your question.   The author, Pappystein may ask you to remove your post at a later date once they have integrated your question into the IN GAME (The Mini Faq) Above... this is done to reduce un-needed reading on the Forum thread for new members.
