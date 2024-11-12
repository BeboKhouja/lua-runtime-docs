---
sidebar_position: 4
---

# Allowing ... in config

By default, Lua Runtime blocks access to running commands, accessing local IPs, and chatting on behalf of the player for privacy and security. If scripts require it, you may want to allow it here.

## Getting into the config folder

For client, it is located in `[Minecraft folder]/config/lua_runtime_config.json`.
For server, it is located in `[Minecraft folder]/config/lua_runtime_config_server.json`.

## What each one means

| Property          | Description                                                        | Default value |
|-------------------|--------------------------------------------------------------------|---------------|
| `allowCommands`   | Whether commands are allowed to run on behalf of the player.       | `false`       |
| `allowChat`       | Whether scripts can chat on behalf of the player.                  | `false`       |
| `urls`            | A list of URLs to be allowed, or blocked.                          |               |
| `allowOpenLinks`  | Whether scripts can open links or not.                             | `true`        |
| `allowListenChat` | If disabled, the `Minecraft.AddChatListener` event won't be fired. | `false`       |
| `allowCopy`       | Whether scripts can copy to the clipboard or not.                  | `true`        |
| `allowPaste`      | Whether scripts can paste from the clipboard.                      | `false`       |

## Allowing access to local IPs

Remove the JSON object with the `url` property as `$local`.