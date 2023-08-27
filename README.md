# Launching Feather Client on MultiMC

> The JSON file may not be up to date.

> This method of launching Feather Client is not officially supported and you may come across issues!

> Do not ask Feather client staff regarding this project!

## Launching

1. Add a new instance on MultiMC and select "1.8.9", click "OK."
2. On the right, click "Edit instance" then click "Version."
3. Click "Install Forge" on the right, then click OK on the bottom.
4. Click "Add Empty" on the right and for the name, put `feather` and for the uid, put `net.digitalingot.feather`.
5. Right click on the version you created and click "Edit."
6. Replace the contents of the file with the contents of the [JSON file included](./net.digitalingot.feather.json) with this project.
7. Click "Open libraries" on the right.
8. Download and rename the files accordingly.
    - Download <https://libs.feathercdn.net/discord_game_sdk_windows.jar> and rename it to `discord-game-sdk4j-0.5.4-natives-windows.jar`.
    - Download <https://libs.feathercdn.net/fcef-0.0.5-natives-windows-2.jar> and rename it to `fcef-0.0.5-natives-windows.jar`.
    - Download <https://libs.feathercdn.net/fwebp-0.0.1-natives-windows.jar> and don't rename it.
    - Download <https://libs.feathercdn.net/favif-0.0.1-natives-windows.jar> and don't rename it.
    - Download <https://libs.feathercdn.net/jnopus-windows.jar> and rename it to `jnopus-1.0-natives-windows.jar`.
9. Place all of those files in the libraries folder you had opened.
10. Add FeatherOpt to your mods folder (create your mods folder if it does not exist): <https://libs.feathercdn.net/FeatherOpt-1.0.0-SNAPSHOT-11.jar>.
11. Click "Launch" and it will launch Feather Client.
