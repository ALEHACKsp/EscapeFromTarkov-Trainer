
# EscapeFromTarkov-Trainer

-**important note**- before publishing this repository, I gave all the details to EFT developers, so that they can fix their 
game (so this trainer should not be usable anymore). Indeed I don't care for offline game trainers, but I don't want a multiplayer or online game to be ruined by cheaters. I was just interested by the reverse-engineering part. In the same vein I will not explain how I was able to circumvent BattlEye to inject the managed code in the game AppDomain.

This is an attempt -for educational purposes only- to alter a Unity game at runtime without patching the binaries (so without using [Cecil](https://github.com/jbevain/cecil) nor [Reflexil](https://github.com/sailro/reflexil)).
EFT is using BattlEye, so we **cannot** use [SharpMonoInjector](https://github.com/warbler/SharpMonoInjector).

This trainer gives:
- HUD (ammo left)
- Door unlocker
- Wallhack
- Exfiltration points outline
- Autohealth (offline raid only)
- No bullet hits (offline raid only)