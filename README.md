# RGP Lua Utility Scripts
These utilities are implemented in the [Lua Programming Language](http://www.lua.org/). They are designed to run in the [RGP Lua](https://robertgpatterson.com/-fininfo/-rgplua/rgplua.html) plugin environment within the [Finale application](https://www.finalemusic.com/) for music notation.

These utilities have zero dependencies, except as noted. Simply configure and run them. A simple way to get started with them is to download the repository to any folder on your computer and point RGP Lua to the `rgpluaclassbrowser.lua` and/or `rgpluaconsole.lua` scripts. After restarting Finale they appear in your RGP Lua menu.


### RGP Lua Class Browser
Class browser for the RGP Lua Finale plugin.

As a modeless dialog, the minimum version of RGP Lua required is v0.56. Beyond this, any version of the script should work with any version of RGP Lua. However, the script is also dependent on `jwluatagfile.xml` for method and property type information as well as links to the [PDK Framework documentation](https://pdk.finalelua.com/index.html). This xml file *is* tied to its release of RGP Lua. The `jwluatagfile.xml` file is auto-generated by [Doxygen](https://www.doxygen.nl) with changes tracked in this repository.

The current release of both  `rpgluaclassbrowser.lua` and `jwluatagfile.xml` are available at the [download site](https://robertgpatterson.com/-fininfo/-rgplua/rgplua.html) for RGP Lua.

The `jwluatagfile.xml` file should be placed inside the same folder as `rgpluaclassbrowser.lua`.

### RGP Lua Console
Console editor for quick-starting Lua scripts in Finale.

RGP Lua Console mimics the Development tab of [JW Lua](http://jwmusic.nu/jwplugins/wiki/doku.php?id=jw_lua). It has a pane for line numbers, for editing, and for print output. It is dependent on the `FCCtrlTextEditor` control, introduced into the PDK Framework with RGP Lua version 0.68. Therefore, it requires 0.68 as a minimum version.

The current release of `rgpluaconsole.lua` is available at the [download site](https://robertgpatterson.com/-fininfo/-rgplua/rgplua.html) for RGP Lua.
