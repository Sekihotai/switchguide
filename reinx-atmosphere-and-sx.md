---
description: 'How are they the same, and how are they different?'
---

# ReiNX, Atmosphere, and SX

ReiNX, Atmosphere, and SX all have advantages and disadvantages.

## [Atmosphere](https://github.com/Atmosphere-NX/Atmosphere/releases)

Benefits ✨ 

* Free and open source
* Frequently updated
* Supported by almost every single homebrew app
* Supports emuMMC
* Has built in prodinfo blanking

Detriments 📛 

* Doesn't have sigpatches built in
* Still work in progress, has many bugs
* Actively tries to stop installation of NSP's, including homebrew ones

## [ReiNX](https://github.com/Reisyukaku/ReiNX/releases)

Benefits ✨ 

* Has sigpatches built in
* Has own toolbox that can do nand backups
* Free and open source
* Access to Icon View in Tinfoil

Detriments 📛 

* Doesn't support emuMMC
* Not frequently updated 
* Doesn't have built in prodinfo blanking

## [SX OS](https://sx.xecuter.com/)

Benefits ✨ 

* Has sigpatches built in
* Custom menu
* Has ldn mitm built in
* Has protection \(in the form of stealth mode, not recommended for long term use\) built in
* [Has many exclusive features in Tinfoil](tinfoil/exclusive-features.md)
* Can mount XCI's from external drive

Detriments 📛 

* Not free, you need to pay
* Not open source
* Sometimes breaks other homebrew 
* Based on Atmosphere, which is already free
* Not frequently updated

## What about those CFW packs that have everything already there?

Don't use those. Ever since AtlasNX \(and by extension Kosmos\) died, CFW packs have been popping up all over GitHub. **Don't use these.** While it maybe seem like its great to have many homebrews bundled together, it makes troubleshooting much harder, and also permanently breaks emuMMC's, preventing them from switching to Vanilla Atmosphere without redoing the entire emuMMC. They also use FSS0, which is great for booting CFW on sysnand, but it's not great for anything else, including installing any NSP's. Always use regular Atmosphere with sigpatches. Use [hbappstore](https://github.com/vgmoose/hb-appstore/releases) if you're too lazy to get the homebrews from GitHub.

