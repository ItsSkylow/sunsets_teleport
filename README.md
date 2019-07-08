sunsets_teleport
================

[FiveM GTA] Simple teleportation script with configuration file


Installation
============


1. add sunsets_teleport to your resources directory.
1. Add `start sunsets_teleport` to your server.cfg.

Configuration
=============
To change the action key change selectedKey (default value: "E")<br />
To add a teleportation, add this line in Config.Positions:<br />
`{{x, y, z, 0}, {x, y, z, 0},  "[" .. SelectedKey .. "] " .. "Text to show when player is inside the area."},`
