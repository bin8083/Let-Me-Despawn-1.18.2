# LET ME DESPAWN

### Let Me Despawn (LMD) is a Minecraft mod designed to address entity lag issues by modifying the despawn mechanics for mobs that have picked up or equipped items.
## Key Features

    Allows mobs with equipped items to despawn naturally
    Preserves dropped items when mobs despawn
    Configurable mob exclusion list
    Server-side functionality (not required on client)

## Functionality

In vanilla Minecraft, mobs that pick up or equip items become persistent and do not despawn naturally. This behavior can significantly contribute to entity lag, especially in modded environments with increased mob variety and spawn rates.

LMD modifies the despawn check to allow these mobs to despawn naturally, like any other mob. To prevent item loss, any picked up or equipped items are dropped when the entity despawns.

    Note: Mobs named with a name tag will still be prevented from despawning naturally.

## Configuration (Version 1.2.1 and later)
Config File

    Location: config/letmedespawn.json
    Reload command: /almanac reload

## Commands
               Command 	                Description
      /letmedespawn add <mobName> 	Add mobs to the config
    /letmedespawn remove <mobName> 	Remove mobs from the config

Mobs added to the config will retain their vanilla behavior and not despawn after picking up items. All commands update the mob list in real-time, eliminating the need for game restarts or manual reloads.
