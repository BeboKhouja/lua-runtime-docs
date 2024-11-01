---
sidebar_position: 4
---

# Allowing ... in config

By default, Lua Runtime blocks access to running commands, accessing local IPs, and chatting on behalf of the player for privacy and security. If scripts require it, you may want to allow it here.

## Getting into the config folder

It is located in `[Minecraft folder]/config/lua_runtime_config.json`.

## What each one means

| Property        | Description                                                  |
|-----------------|--------------------------------------------------------------|
| `allowCommands` | Whether commands are allowed to run on behalf of the player. |
| `allowChat`     | Whether scripts can chat on behalf of the player.            |
| `urls`          | A list of URLs to be allowed, or blocked.                    |

## Allowing access to local IPs

Remove the JSON object with the `url` property as `$local`.