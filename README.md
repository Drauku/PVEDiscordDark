![](https://i.imgur.com/mTsbUWk.png)

## PVEDiscordDark
PVEDiscordDark is a  CSS 'theme' for the Proxmox Web UI. It was made with Discord's color scheme. Although ~99.8% (Psst, totally not a random percentage) of the Web UI has been darkened. There are some graphs that are still white because their background colors are defined in javascript, there is an experimental [feature](https://github.com/Weilbyte/PVEDiscordDark/tree/master/serverside/jsmod) to change these.

You can check the 'previews' folder in the repo to check out how some stuff look (without the JS modification)

## Installation 
*Can be installed two ways*:
* Server-side
* Browser Extension

**Server-side Installation:**
1. Enter your PVE **node** shell..
2. Ensure you are connected to the internet and can access Github.
3. Run this bash command as root/sudo:
   
   ```wget https://raw.githubusercontent.com/Drauku/PVEDiscordDark/master/serverside/ddInstall.sh && chmod +x ddInstall.sh && bash ddInstall.sh```
4. <del>Run ```ddInstall.sh``` with root/sudo.</del>
5. <del>Follow instructions given. </del>
6. Done! 

**If you want the charts/gauges and other elements to be dark mode too please look [here.](https://github.com/Weilbyte/PVEDiscordDark/tree/master/serverside/jsmod)**

**Browser Extension Installation:**
1. Download a browser extension (such as Stylish) that allows you to change CSS styles 
2. Follow extension-specific instructions to add custom style. For the style content paste in the contents of this file: ```https://raw.githubusercontent.com/Weilbyte/PVEDiscordDark/master/discordDark.css```
3. Save style and enable it - and youre done.

## Uninstall
*Depending on how you installed it..*

**Server-side Uninstallation:**
1. Enter your PVE **node** (the one you installed the theme on) shell...
2. ```wget https://raw.githubusercontent.com/Weilbyte/PVEDiscordDark/master/serverside/ddRemove.sh```
3. Run ```ddRemove.sh``` with root/sudo.
4. Follow whatever instructions are given.
5. Done! Its gone!

**Browser Extension Uninstallation:**
*Just remove the style from the extension?*

### Disclaimers
**If youre using the installation script..**
*Make a backup of ```/usr/share/pve-manager/index.html.tpl```. The script makes one anyways but make another one just to be sure*

*Awoo'ing on this repo is allowed.*
