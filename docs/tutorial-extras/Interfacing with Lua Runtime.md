---
sidebar_position: 1
---

# Interfacing with Lua Runtime

If you're a mod developer, and you want to add features to Lua Runtime, then here's how to do it.

## Adding the Gradle dependency

Add this dependency to your `build.gradle` file:

```groovy title="build.gradle"
modImplementation
```

This adds Lua Runtime as a dependency for the mod.

## Adding features

Then, to add features to it, call `LuaRuntimeClient.Instance.LuaInstance.AddToTable` with a `LuaValue` as an arg.