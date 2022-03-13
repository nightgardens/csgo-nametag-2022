# CSGO Name Tag Tool 2022 (SSG 08 Crosshair Guide)
## Credits

Credits to @BeepIsla and their tool for making this possible.

## Usage

1. Download [NodeJS](https://nodejs.org/en/) and install/update it
2. Download [Git](https://git-scm.com/) and install it
3. Open a command prompt and enter `git clone https://github.com/BeepIsla/csgo-nametag-tool.git --recursive`
4. Enter the just downloaded folder using cd csgo-nametag-tool
5. Download the required dependencies using npm ci
6. Run the program using node index.js
7. Follow the on-screen instructions

## Details

Always test with a Storage Unit first, you can rename them for free infinitely! I am not responsible for any lost name tags or reduced item value.

When you start the program you can choose two options:

- `Default Item`: Default stock items such as a default AK-47 (Requires a name tag)
- `Normal Item`: Any item you can see in your [Steam Inventory](https://steamcommunity.com/my/inventory/) (Requires a name tag unless its a Storage Unit)
When entering the Steam inventory link for the item you want to rename go to your Steam inventory, find the item you want to rename, then right click -> Copy link address. You should now have a link similar to this: `/inventory/#730_2_4287161377`

The CSGO backend might still restrict some input, for example newline characters get turned into space characters automatically and there is a hard limit for the amount of characters you can use: Always test with a Storage Unit first.

If you wish to rename your items with special characters I recommend you use the raw hex system. Simply convert [any text you want](https://www.rapidtables.com/convert/number/ascii-to-hex.html) into hexadecimal and prefix it with `0x`.

## Pasteable Names
To get the crosshair code on the SSG 08 at the center of your screen you have to bump up the names of other items. I wil list the specs/details of my game that got this to work for me. I am not sure if monitor/res/external factors affect placement.

- BENQ 24.5" 240hz monitor
- Ingame res: 1280x1024
- hud_scaling 0.825 (TYPE IN CONSOLE)
- [HUD Edge Positions](https://imgur.com/a/6OoMf03)

BitCoin Deagle:

0xE280A9E280A9E280A9E280A9E280A9E280A9E280A9E282BF20E29B8FE280A9E280A9E280A9E280A9E280A9E280A9E280A9

`THIS CODE WORKS SPECIFICALLY FOR 1280x1024 WITH THE ABOVE SETTINGS!! IF YOU PLAY ON A DIFFERENT RES YOU MIGHT NEED TO ADD MORE E280A9 TO THE END OF THE ABOVE CODE. E280A9 IS AN EXTRA PIECE OF HEXADECIMAL CODE THAT IM NOT SURE WHAT IT FULLY MEANS`

SSG 08:

✛‮‱‱⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻

This can be pasted directly into CS:GO and you do not need to use the above cmd lines to make it work.

`ONCE AGAIN YOU MAY NEED TO ADD MORE ⸻ TO THE ABOVE PASTE TO FIT DIFFERENT RESOLUTIONS. THIS PASTE WORKS FOR 1280x1024.`
