# Nightfall mods

Auto-update files for our NightfallCraft Minecraft server. The Nightfall Updater mod checks the latest release here
when the game starts: it downloads newer builds of our own mods (itself included) and applies the changes when you
close the game. Each release has our mod jars and a `manifest.json` (build ids, sizes and SHA-256 checksums). Other
authors' mods are not hosted here: any the manifest lists point at their official Modrinth or CurseForge downloads.

To turn auto-update off, set `autoUpdate=false` in `config/otherworldupdater.properties`.
