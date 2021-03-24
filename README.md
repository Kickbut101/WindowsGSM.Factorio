# WindowsGSM.Factorio
🧩 WindowsGSM plugin for supporting Factorio

## Requirements
[WindowsGSM](https://github.com/WindowsGSM/WindowsGSM) >= 1.21.0

You must also own the game factorio! And you will need to use the "Set Account" feature in Windows GSM.

## Installation
1. Move **Factorio.cs** folder to **plugins** folder
1. Click **[RELOAD PLUGINS]** button or restart WindowsGSM
1. You will still need to [make the map file manually](https://wiki.factorio.com/Multiplayer#Dedicated.2FHeadless_server) and place it in your serverfiles\bin\x64\ folder. Name the zip file as \<YourMapName\>_save.zip
1. Be sure to setup your server settings in the "server-settings.json" file in \servers\1\serverfiles\data directory

## Known issues
Factorio as a whole (not just with windowsGSM) doesn't seem to handoff the process ID. So when starting the server it will perpetually be in "Starting" status, instead of "Started". This also means server commands don't work correctly unless you DON'T check the embedconsole option, and you pipe in your commands to the window that pops up.


## Additional Command Line options
[Here](https://wiki.factorio.com/Command_line_parameters)

<table class="wikitable"><caption>Server options</caption>

<tbody>

<tr>

<td>--port N</td>

<td>network port to use</td>

</tr>

<tr>

<td>--bind ADDRESS[:PORT]</td>

<td>IP address (and optionally port) to bind to</td>

</tr>

<tr>

<td>--rcon-port N</td>

<td>Port to use for RCON</td>

</tr>

<tr>

<td>--rcon-bind ADDRESS:PORT</td>

<td>IP address and port to use for RCON</td>

</tr>

<tr>

<td>--rcon-password PASSWORD</td>

<td>Password for RCON</td>

</tr>

<tr>

<td>--server-settings FILE</td>

<td>Path to file with server settings. See data/server-settings.example.json</td>

</tr>

<tr>

<td>--use-server-whitelist BOOL</td>

<td>If the whitelist should be used.</td>

</tr>

<tr>

<td>--server-whitelist FILE</td>

<td>Path to file with server whitelist.</td>

</tr>

<tr>

<td>--server-banlist FILE</td>

<td>Path to file with server banlist.</td>

</tr>

<tr>

<td>--server-adminlist FILE</td>

<td>Path to file with server adminlist.</td>

</tr>

<tr>

<td>--console-log FILE</td>

<td>Path to file where a copy of the server's log will be stored</td>

</tr>

<tr>

<td>--server-id FILE</td>

<td>Path where server ID will be stored or read from</td>

</tr>

</tbody>

</table>

### License
This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/BattlefieldDuck/WindowsGSM.ARMA3/blob/master/LICENSE) file for details

