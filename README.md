Original plugin developed by DarkunderdoG

Developer: http://tshock.co/xf/index.php?members/darkunderdog.5/

Original source: http://tshock.co/xf/index.php?threads/1-15-afk-warp-kick-plugin.2594/

Originally developed by DarkunderdoG (https://tshock.co/xf/index.php?threads/1-15-afk-warp-kick-plugin.2594/)

When a player is idle/afk for a defined time, the server will warp the player to the "afk" warp or when the player types "/afk".
This update fixes the spamming errors when the "afk" warp/region is not defined. /back was changed to /return due to command conflict with Essentials+.

Commands:
/afktime - provides the player details about their afk status
/afk - warps the user to afk
/return - warps the player back to original position (Talking or leaving the afk region also does this)
/afkwarptime <seconds> - Changes the duration of when a player is warped to afk
/afkkicktime <seconds> - Changes the duration of when a player is kicked from being afk
/afkreload - reloads the AFK config file

Config File: (AFKconfig.json)

afk.comm - Gives players access to /afktime, /afk, and /return

afk.cfg - Gives users access to /afkwarptime, /afkkicktime, and /afkreload

afk.nokick - Prevents users from being kicked or receiving kick messages 

https://tshock.co/xf/index.php?resources/afk-warp-kick.104/
