# Features

This mod aims to improve on the existing features, as well as add additional features that may futher be helpful in tracking and managing one's statistics.

Note that any optional features that this mod adds to the game, such as the "/statistics" command and the "Stat announcement system", may be disabled in the config or though the in-game mod settings menu.
The /statistics command

Alt command: /stats
This is an optional feature that adds a command that allows people (with sufficient permission levels, such as OP) to manage and view player statistics through commands. This feature may also be useful for writing datapacks that may wanna read as well as manage player statistics.

### Note: Can be disabled in the config.

## The command syntax is the following:

    /statistics clear <targets>
    /statistics edit <targets> <stat_type> <stat> (set|increase) <value>
    [ex. general stat]: /statistics edit @s minecraft:custom minecraft:jump set 123
    [ex. item stat]: /statistics edit @s minecraft:used minecraft:wooden_shovel set 123
    [ex. mob stat]: /statistics edit @s minecraft:killed minecraft:zombie set 123

## The "General" statistics tab

This tab does not add nor show anything special regarding general statistics other than the redesigned UI layout. The filters menu features a way for you to hide all general statistics that are currently set to '0', as well as a search bar that will help you look for a specific statistic.
The "Items" statistics tab

The items tab displays items in a visual grid of items, similar to how an inventory screen does it. The items are categorized in item groups, just like they would be in the creative inventory menu. All items you interacted with are shown in this tab. This will hopefully help you find the items you are looking for easier. The search field in the filters menu can be used to look for specific items. To see a statistic for an item, place your cursor over the said item, or use "Tab" to navigate to it using your keyboard, and a tooltip text will display the statistics. The "Show item names" checkbox defines whether or not the tooltip will also show the item name.

## The "Mobs" statistics tab

Similar to the "Items" tab, the "Mobs" tab will also show mobs in a grid. The mobs are visually rendered on the GUI screen, so it is easier for you to find the mob you are looking for, and because it looks nicer. Just like with the items tab, to see the statistics for a given mob, place your cursor over the said mob, or use "Tab" to navigate to it using your keyboard. A tooltip text will show you the statistics.

Note that due to technical limitations in my programming, some mobs may fail to render properly, and some mobs may even appear as "plain text" instead of their 3D model due to errors in my rendering method.

## The "Food & drinks" statistics tab (formerly "A balanced diet")

This tab aims to help you achieve the "A balanced died" advancement. It does that by displaying all food items in grouped grids, similarly to how the "Items" tab does it. This tab will show you all food items, even the ones you haven't interacted with, and will also highlight the foods you already ate before, helping you identify which foods you need to eat next to earn the advancement.

Note that this tab may not precisely tell you exactly which foods you do and do not need, as that kind of criteria is controlled "server-side", and may be modified by other mods and data-packs. As such, all foods are shown instead.

## The "Hostile creatures" statistics tab (formerly "Monsters Hunted")

This tab aims to help you achieve the "Monsters hunted" advancement. It shows you a grid of mobs similarly to the "Mobs" tab, except the mobs shown on this tab are hostile creatures you have either killed or are yet to kill. Similarly to the "Food & drinks" tab, any mobs you have killed will be highlighted in this tab, helping you easily see which mobs you need to kill next in order to earn the advancement.

Note that just like with "Food & drinks", the criteria for getting the advancement is controlled server-side, and may be modified by other mods and data-packs. As such, all hostile creatures are always shown.

## In-game config menu

A menu that lets you configure the mod in-game. Nothing more or less.

## MCBS files

This is an additional feature that aims to let people save a "snapshot" of their current statistics, into a file, which can then be opened later or shared with other players.

Note that opening an MCBS file does not "override" you current stats, as it only shows you what your stats looked like at the time you saved the MCBS file.

## The statistics hud

This is another additional feature that allows you to "pin" any stat to the "in-game-hud", where you can then look at any statistic of your choosing as you play the game. To pin a stat, simply right-click it with your mouse (hold down shift as well if you have REI installed).

Note that due to technical limitations, pinned statistics update occasionally by default, and will not update "live" unless this mod is installed on the server-side as well and the "live stat updates" is enabled on the client-side.

