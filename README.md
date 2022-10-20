# PublisherPlus
![](https://img.shields.io/badge/Mod_Version-1.6-blue.svg)
![](https://img.shields.io/badge/Built_for_RimWorld-1.4-blue.svg)
![](https://img.shields.io/badge/Powered_by_Harmony-2.x-blue.svg)

---

Provides extended options for publishing mods to the Steam Workshop.

This 'mod' has no affect on gameplay and is only useful for mod developers uploading to the Steam platform.

---

Forked from https://github.com/RealTelefonmast/PublisherPlus - which is in turn forked from https://github.com/Jaxe-Dev/PublisherPlus which is the original repo ([Original Steam Workshop page](https://steamcommunity.com/sharedfiles/filedetails/?id=1510554297)).

---

## Notes

This fork is intended to be a stop-gap solution until the original author gets around to update their original work to 1.4 Rimworld. Inductively, this mod has a different `packageId` so it is independent from the original

This has no compatibility with the Fluffy's Mod-Manager, a feature in the original

This does not come with an prebuilt assembly to save space, so you need to build it by yourself

## Compiling

This repository should be cloned into the `Mods` folder of Rimworld, like so:
```ps
PS ...\Rimworld\Mods> git clone https://github.com/martinlyra/PublisherPlus.git
```

First, you need to grab the Harmony mod from [Steam Workshop](https://steamcommunity.com/workshop/filedetails/?id=2009463077), subscribe to it.

Then you should have the latest [.NET SDK](https://dotnet.microsoft.com/download), and to be sure, [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework) to make sure that you have all you need to build this project for `net48`. For more information about .NET SDK, [see the documentations here](https://learn.microsoft.com/en-gb/dotnet/core/sdk).

Once the .NET SDK has been installed, you should have `dotnet` CLI tools. Open a terminal and have its current directory to the `Source` folder. Then run `dotnet build`. 

```ps
PS ...\Rimworld\Mods\PublisherPlus\Source> dotnet build
```

If all is green, you should be able to use the mod immediately in Rimworld.
