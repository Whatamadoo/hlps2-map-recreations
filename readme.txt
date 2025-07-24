These are Half-Life PS2 decay and deathmatch map recreations I made for GMOD. By 'recreation' I mean cleaning up Goldsrc decompiles to a decently acceptable state.
https://steamcommunity.com/workshop/filedetails/?id=3217033872 (decay maps)
https://steamcommunity.com/sharedfiles/filedetails/?id=3377424537 (deathmatch maps)

These use the halflife prop pack from the workshop (https://steamcommunity.com/workshop/filedetails/?id=665025902 ) but only for the health/suit chargers, eye scanners, and pool props used in ht05dorms. There are also some textures from the PC port of decay from before I decided getting them from the map themself. The rest I port myself.
The folders contain an "assets" folder which contain the assets I ported or modified myself.

I MADE THESE WITH PORTING THEM TO SOURCE IN MIND.
This means that some entities have been changed on principle to work better in source, like replacing trigger_auto/relay and multimanagers to their source counterparts with appropriate input/outputs as well as changing the textures and the entities they're applied to etc etc. Other than major player activated scripted events, the I/O hasn't been ported over. There's usually a visgroup called 'old' in the maps that contain unchanged stuff from the decompile like off grid geometry and unneeded (for me) entities.

Decay maps :
ht01accident : completed but old and bad. A lot of changes from the base map like making sliding door glass func_breakable and increasing renderamt value instead of using unlitgeneric. A lot of nodraw faces were given textures along with extra functionality and buttons added to OOB areas.
ht01accident2 : only combined and de-disastered into accident1.
ht02hazard : completed.
ht03uplink : completed.
ht04dampen : completed. Has some changes I dont remember.
ht05dorms : completed. I don't remember all the changes but I dont believe they're too bad. Though alot of nodraw surfaces have been given textures. 
ht07signal : complete.
ht10focus : complete.
ht11lasers : complete.
ht12fubar : complete. Scripting was redone near completely.
ht91alien : complete. Has some fake lights to better recreate original lighting.

I also did these, same principles from above apply (changing ents, textures to work in source). These just have one 'assets' folder since I made them as part of the same addon.
PS2 Deathmatch maps :
basement : complete
datacore2 : have not started (and no plan to)
debris : complete
office : complete
signal : complete (made seperately from ht07signal)
skirmish : complete
snark_pit2 : have not started (and no plan to)
stalkyard2 : have not started (and no plan to)
water_canal : complete
waypoint : complete
