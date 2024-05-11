---
title: 1.0 Game Update
parent: For Users
---

# RE: 1.0 - Updated 5/9
Previous versions of mods and BepInEx do not work with the 1.0 game update. There will be an announcement in discord and versions published to Thunderstore when they are ready. 

### Mod Development Community
The remainder of this page is provided for developers and anyone willing to accept any risks in testing pre-released mods, don't expect support or full functionality. The purpose of this page is to help gather feedback, please report issues and bugs.

#### Current Work In Progress
- [BepInEx 1.688.1](<https://github.com/Odjit/BepInEx/releases/tag/vrising-release>)
- [Bloodstone 0.2.0](<https://github.com/decaprime/Bloodstone/releases/tag/v0.2.0>) (known: will break client load!)
- [VampireCommandFramework 0.8.4](<https://github.com/decaprime/VampireCommandFramework/releases/tag/v0.8.4>)
- [Killfeed 0.1.1](https://github.com/decaprime/Killfeed/releases/tag/v0.1.1) (not tested, @deca in discord with feedback from multiplayer testing please)
  
#### Developer Resources
- Published nuget [VRising.Unhollowed.Client 1.0.0.792660001](<https://www.nuget.org/packages/VRising.Unhollowed.Client/1.0.0.792660001>)
- Published template [VRising.ModTemplate 0.1.7](<https://www.nuget.org/packages/VRising.ModTemplate/0.1.7>) tested `dotnet new vrisingmod --use-vcf --use-bloodstone` works with versions from above

#### Known Issues
- Bloodstone will crash on client launch
- Bloodstone Keybindings do not work (are disabled)
- CustomNetworkEvents Broken (@deca:wip)