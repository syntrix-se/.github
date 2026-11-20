# Syntrix

**Open tools for Space Engineers modders.**

Syntrix started as the shared base of our own mod family and is now open for everyone. It gives mods the services they would otherwise each build again: networking, block settings, terminal controls, chat commands, windows, an in-game wiki and more. One small file docks a mod at runtime, and a missing Syntrix never crashes it.

## Repositories

| Repository | What it is |
|---|---|
| [**Syntrix**](https://github.com/syntrix-se/Syntrix) | The framework mod (MIT). Source, example mod, changelog and the [manual in the wiki](https://github.com/syntrix-se/Syntrix/wiki). |
| [**Syntrix.RichHud**](https://github.com/syntrix-se/Syntrix.RichHud) | The former Rich HUD UI service of Syntrix (API 2) as a library, for mods that ship Rich HUD themselves. |
| [**iv4xr-se-plugin**](https://github.com/syntrix-se/iv4xr-se-plugin) | Fork of the iv4XR plugin with fixes for current game versions and extra tools for automated in-game tests (LGPL-3.0). |

## Get started

- **Players and server owners:** subscribe to [Syntrix on the Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3840449435). Mods that need it list it as a required item, so Steam loads it for you.
- **Modders:** copy `SyntrixApi.cs` into your mod and follow [Getting Started](https://github.com/syntrix-se/Syntrix/wiki/Getting-Started).

## Our promise

Endpoints are never removed, old dock files keep working, and new services come with a new minor version. The version scheme is explained in [Docking and Versions](https://github.com/syntrix-se/Syntrix/wiki/Docking-and-Versions).

## Contributing

Bug reports and ideas are welcome as issues in the matching repository. If you use Syntrix in your mod, please name it in your mod description.
