# steam-desktop-icon-fix
Fix for Steam games with no desktop shotcut icon

- Exit out of Steam
- Go to your "steamapps" folder and delete all the "appmanifest_****.acf" files. Leave any ".gcf" or ".vdf" files and especially the sub-folders of "steamapps" alone.
- Start Steam.
- Go to your Library and you will see that all of the games that were in that library now appear to be uninstalled.
- Now select these games (you can select many at a time) and attempt to install them in the location where they were installed before. Be sure to specify if you want (or do not want) Steam to create "desktop" or Windows "start menu" shortcuts. Steam will appear to go through the process of installing the selected games one-at-a-time. However, because the game files are already there, instead Steam will verify the files and minimize downloading. In rare instances when for example the game has not been updated, Steam may discard the now defunct game files and download the game from scratch, but this is rare. You should periodically check on the progress because some games will require accepting game specific EULAs.
- Repeat from step 1 above for your Steam libraries that are in other drives; that is, go to the drive and delete the ".acf" files in the "steamapps" folder of the drive and then install the games that appear to be uninstalled. Generally it is a good idea to use the procedure one drive at-a-time so as not to accidentally install a game to the wrong drive which would lead to downloading of the game from scratch because the erroneously selected location would have no game files.

Source: https://steamcommunity.com/discussions/forum/1/4031348273658006638/?tscn=1702378531
