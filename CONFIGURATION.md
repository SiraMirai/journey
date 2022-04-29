<a href="https://raw.githubusercontent.com/SiraMirai/journey/main/images/Jourmby.png"><img src="/images/Journey169v3.webp" target="_blank"></a>

---

<p align="center">
<a href="https://www.nexusmods.com/skyrimspecialedition/mods/65229"?>Nexus Page</a> | <a href="https://github.com/SiraMirai/journey/blob/main/README.md"?>Readme</a> | <a href= "https://github.com/SiraMirai/journey/blob/main/GAMEPLAY.md"?>Gameplay</a> | <a href= "https://github.com/SiraMirai/journey/blob/main/CONFIGURATION.md"?>Configuration</a> | <a href="https://github.com/SiraMirai/journey/blob/main/CHANGELOG.md"?>Changelog</a> | <a href="https://github.com/SiraMirai/journey/blob/main/SUPPORT.md"?>Support</a> | <a href="https://www.wabbajack.org/">Wabbajack</a>
</p>

---
# Configuration

- [Mod Organizer 2 Profiles](#mod-organizer-2-profiles)
- [Anniversary Edition](#anniversary-edition)
- [ENB Organizer](#enb-organizer)
- [Graphics Options](#graphics-options)
- [Optionals](#optionals)

## Mod Organizer 2 Profiles

Journey comes with two profiles in MO2. Journey and Journey - Anniversary Edition. If you don't own Anniversary Edition and all of the creation club content that comes with it, play the default Journey profile. It contains the full Journey experience outside of creation club integration.

Select the profile you want here:

![Profiles](https://raw.githubusercontent.com/SiraMirai/journey/main/images/config-profiles.png)

## Anniversary Edition

The Anniversary Edition profile requires a copy of all of the creation club mod files in order to use it.

- Launch Skyrim through Steam and allow it to download all creation club content.
- In Mod Organizer 2, activate the Anniversary Edition profile.
- Right click on `[NoDelete] Creation Club - Paid` and select `Open in Explorer`.
- Copy all files from your `Skyrim Special Edition\data`folder that begin with "cc" into the opened folder.
- Make sure all creation club content is enabled under the `Plugins` tab on the right pane in Mod Organizer 2.
- If it is not, shift-click on `[NoDelete] Creation Club - Paid`, right click and select `Enable Selected`, and finally right click and select `Send to > Top`.

When Creation Club content has been set up correctly, your Journey MO2 will look like this:

![Anniversary Edition](https://raw.githubusercontent.com/SiraMirai/journey/main/images/config%20-%20ae%20enabled.png)

## ENB Organizer
Journey includes the tool ENB Organizer for trying out different ENB and ReShade presets.

To change ENB or ReShade presets:
- Run ENB Organizer from the left side bar in Mod Organizer 2 or from the exe list on the top right.

![Executables](https://raw.githubusercontent.com/SiraMirai/journey/main/images/config-exemenu.png)

- If ENB Organizer gives a warning about being unable to check for updates, click okay and ignore it.
- In the left side menu, go to `Presets`.
- Disable the currently enabled preset and then enable the one you wish to use.

![ENB Organizer](https://raw.githubusercontent.com/SiraMirai/journey/main/images/config-enborganizer.png)

> Do not enable more than one preset at a time. If you want to enable the included Rudy ENB, you must enable `Rudy ENB - Required Files` under `Optionals` in MO2 and move the `Obsidian Weathers - Patch - Rudy ENB.esb` below `Obsidian Weathers.esp` in the plugins list.

## Graphics Options

>For Improved performance, try turning off any ENB preset and enable one of the included reshade presets.

Journey's default graphics settings are set to its `Medium` preset. For better performance or visuals, you can select one of the other included graphics configs included in the `Journey/Graphics Presets` folder into the `Profiles/[Journey]/[Journey - Anniversary Edition]` profile folder that you are using.

![Graphics Options](https://raw.githubusercontent.com/SiraMirai/journey/main/images/graphics-options.png)
![Graphics Options](https://raw.githubusercontent.com/SiraMirai/journey/main/images/graphics-options2.png)

Double click on `SSE Display Tweaks - Journey Settings` and under `Patches & Fixes` and set the resolution to match your monitor resolution and remove the # at the start of the line.

## Optionals

Journey includes a small amount of optional content for you to play with, if you want.

### Additional Followers and Companions

Included, but disabled by default, are a number of optional companions for your travels in Skyrim and can be found under `New Followers` in Mod Organizer 2.

- Enable the companion under `New Followers` that you want to enable.
- Move all enabled plugins above `RealisticWaterTwo.esp`
- If you're using the default `Journey` profile, any plugins with missing masters may be safely left disabled as they are included for the `Journey - Anniversary Edition` profile.

### Optional Tweaks

Also included are a number of optional tweaks under `Optionals` in the Mod List. 

Most optionals do not add any plugins and require no additional work to enable. For `Fast Travel For Survival Mode`, load the esp before `RealisticWaterTwo.esp`.

