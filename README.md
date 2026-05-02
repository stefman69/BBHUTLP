# BBHUTLP
A plugin file for BepInEx that allows for removing the crosshair, cursor, and shotgun from Big Buck Hunter Ultimate Trophy on steam. This should be compatible with any lightgun that can emulate the mouse cursor movement and mouse buttons. If you run into issues let me know and I can try to troubleshoot.


# Install
In order to install this plugin you will need the latest release of BepInEx for Unity IL2CPP x64. Currently that can be found at this link:

https://builds.bepinex.dev/projects/bepinex_be/755/BepInEx-Unity.IL2CPP-win-x64-6.0.0-be.755%2B3fab71a.zip

You will also need to have Big Buck Hunter Ultimate Trophy installed through steam. 

Once you have that installed extract the files from the BepInEx-Unity.IL2CPP-win-x64-6.0.0-be.755+3fab71a.zip to the folder for the game. That can usually be found at this adress on your main drive: "C:\Program Files (x86)\Steam\steamapps\common\BigBuckHunter_UltimateTrophy"

Then you will want to run the game once to have BepInEx install all of it's assets into the game folder.

Once those are copied over and you have run the game once you will need to download BBHUT Lightgun Patch.dll file from my github page and place it in the plugins folder of BepInEx, which should be found here: "C:\Program Files (x86)\Steam\steamapps\common\BigBuckHunter_UltimateTrophy\BepInEx\plugins"

You can find the latest release of my patch here: https://github.com/stefman69/BBHUTLP/releases/tag/v1

Once that is done you should be able to run the game with no cursor or crosshair and it will feel like a real lightgun experience. One final optional step here wou;d be to duplicate or zip the files for the game, as steam will update them and there is no gaurantee that this will continue working after future updates.

# Wii Shotgun Info

I can't recommend enough getting a wii mote/nunchck and the big buck hunter peripheral for the wii that feels pretty close to the real guns. With the software lichtknarre and a decent 4 IR harness you can have a pretty solid arcade experience at home for around $100 (if you can find a good deal on the shotgun attachment). As of right now you will need to reach out to them for a test build that allows for use of the nunchuck and use my remap exe (BuckHunt.exe) that maps the proper keys for nunchuck controls. You can check out Lichtkinarre at their website here: https://geekonarium.de/en/lichtknarre-lightgun/

You can find the latest release for my controller remapper here: https://github.com/stefman69/BBHUTLP/releases/tag/v1.0

In order to make it work you will need to install auto hotkey. You cant toggle thr hotkey off with the macro ctrl+shift+s and if the application is still open it can be reenabled by pressing ctrl+shift+e. I have no idea how well this will work on other computers, but I assume if you have the application installed and use my exe it will work. You can find auto hotkey here: https://www.autohotkey.com/docs/v2/

Once again you will need to ask in the comments on the geekonarium site for a link to the latest test build if you want to get this working.
