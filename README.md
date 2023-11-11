# replit eaglercraft server
ty Byte#9476 for fixing the forwarding issue!!
extra help discord server | anotha one

smashed together by ayunami2000
THIS REPLIT USES PluginInstaller

LATEST UPDATE: NOW FORWARDS IPS!!

ALSO, IF IT DOESNT WORK, ANOTHER FIX IS TO RENAME THE REPLIT AND THEN RENAME IT BACK

# Helpful video tutorial by a generous user
motd changing is DIFFERENT than what these tutorials say!! -- check the java/bungee_command/config.yml for how to change (motd1 is first line, motd2 (you can add this) is the 2nd one)

https://www.wevideo.com/view/2581865286

YouTube Mirror: https://www.youtube.com/watch?v=As99AOL_-vM

# Helpful Google Doc by a generous user
Here in case it helps!

# Usage:
Fork it, and press "Run" at the top to run the server!

# NOTE: to control, you MUST open the website view in a new tab instead of playing in the editor.
# To change the server icon:
Replace the server-icon.png file under java/bungee_command with your desired server icon.

# To run server commands:
In the "Console" tab in the replit, you can send server commands.

# To save progress:
Notice: This is now done automatically, every 5 minutes, using a plugin! In the server console or in-game as an opped player, run /save-all to save the world.

# Too slow?
This is because you are using a free service to host a Minecraft server. Of course it is slow and the only way to fix this is to self-host at home.

# Getting admin/OP or enabling command blocks
To give yourself OP (admin), go to the server console and run op username and press enter (replacing "username" with your username in-game).

To enable command blocks, go to java/bukkit_command/server.properties and add a new line at the end: enable-command-block=true. Then, restart the server.

# Item ID List
# Plugins
Eaglercraft is Minecraft 1.5.2, so plugins you will use will have to be supported by Bukkit 1.5.2 (not Spigot). You can add plugin JAR files into the java/bukkit_command/plugins folder.

Official Plugin Collection

https://github.com/LAX1DUDE/eaglercraft-plugins

Some plugins I suggest you use:

# LoginSecurity
Adds /login and /register to your server. Make sure you turn OFF sessions in the config (run server once after adding plugin, run the server once after adding loginsecurity, go to "plugins/LoginSecurity/config.yml", and change sessions: use: from true to false), or else players may be able to "resume session" on any account!

# Essentials & Essentials Extra
"Essential" commands and features for any Minecraft server. Widely popular, even today!

# WorldEdit
Super popular world editing plugin!

# WorldGuard
Region protecting. Requires WorldEdit for selecting the regions.

# PlotMe
A once-popular plot plugin for creative OR survival plots to build on!

# SeekAndFind
A cool-looking hide-and-seek plugin, BUT I have not tested it so it might not work!

# NoSpawnChunks
Prevents loading spawn chunks on your server. Helps to optimize it greatly!

# Not working?
1. Make sure you haven't broken any essential files.
2. (try this multiple times, at least 5-10. this fixes the "End of Stream" issue among many, many others) Try clicking on the "Shell" tab (next to the "Console" tab) and running busybox reboot. Then you can try pressing the Run button again and see if it works.
3. Join the official Eaglercraft discord server and look for any answers there.
4. If all else fails, contact me directly through Discord at ayunami2000#5250
5. If you do not have access to Discord, THEN you can leave a comment on the Replit.
