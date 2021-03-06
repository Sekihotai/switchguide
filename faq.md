---
description: Facts and Questions
---

# FAQ

## What are sigpatches?

Sigpatches are files that allow you to play pirated games on your Nintendo Switch. ReiNX and SX OS both have sigpatches built in, while Atmosphere does not. There are two types of sigpatches. The first are FileSystem patches, also known as FS patches. These allow you to install unsigned games, such as leaks and converts. ES patches are used for installing NSP's \(piracy\).

## What are tickets?

Tickets are used on the Nintendo Switch to find whether or not the person owning the console actually owns the game they're trying to play. If the console doesn't find the necessary ticket, the game doesn't start. Tickets can only be found on games that are downloaded from the CDN, and installing games that are directly from the CDN without paying will result in a ban without the proper protection.

## Should I use Incognito, 90DNS, or Atmosphere blanking?

Incognito is by far the safest of the three, but the least convenient. To reverse the effects of Incognito, you need to restore a prodinfo backup, and if you don't have one, then you're essentially banned. 90DNS needs to manually add new domains, so if they're too late, you could be banned. Atmosphere blanking is safer, but if you accidentally delete the exosphere.ini file, your blanking goes away. In short, Incognito is the safest option.

## What is FSS0 and why is it bad?

FSS0 is a boot method that uses fusee secondary to boot instead of fusee primary. While this method is great for using custom firmware on your sysnand, it isn't great for much else, including installing pirated or homebrew NSP's since it doesn't load the sigpatches correctly. It causes many problems that require moving to regular fusee primary and reinstalling the game, which is why its better to use fusee primary.

## What are sysmodules?

Sysmodules are applications that run in the background on your Switch. They can do almost anything, from [running an FTP server in the background for seamless file transferring](https://github.com/cathery/sys-ftpd-light) to [playing music while you're using the Nintendo Switch.](https://github.com/HookedBehemoth/sys-tune) They can even [allow you to play multiplayer without the need to pay for Nintendo Switch Online.](https://github.com/spacemeowx2/ldn_mitm)

