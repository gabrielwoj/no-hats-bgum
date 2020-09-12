<p align="center"> 
  <a href="https://gamebanana.com/skins/169236" rel="nofollow">
    <img
        alt="No-Hats-mod"
        src="https://screenshots.gamebanana.com/img/ss/srends/5e5be378f1b6c.jpg"
        width="850"
      />
    </a>
</p>

This is a pack of mods whose purpose is to remove some visual aspects from Team Fortress 2 (cosmetics, skins, unusuals and some christmas lights).

These versions don't have release numbers at the end, I'll simply replace them whenever they receive an update so the .vpk files names won't change. This should mean you could add them to your personal tf2 repo to receive any updates as soon as they're out.

**If you modified the mod**, I added a new `updates` directory containing vpk files that only remove cosmetics from specific updates, starting with the one from summer 2020. Like that you won't need to scrap your modified mod to have the latest hats disappear. You could merge them together to avoid having too many files in your `custom` folder. If you figured out how to modify the mod, you should have no problems doing this. ;)

# Navigation

* [Installation](#installation)
  * [Modify mod](#some-links)
   * [Changelog](./.github/CHANGELOG.md)
* [Buglist](./.github/BUGLIST.md)
  * [Modify](#modify)
  * [Specific Updates](./updates)
* [Questions & Answers](./.github/Q%26A.md)
* [Credits](./.github/CREDITS.md)


## Primary mod

- no\_hats\_bgum.vpk
  - This is the main mod of the pack, it prevents the game from loading cosmetics. It also makes the default headgear reappear, should it be removed by the cosmetic the player is wearing. (E.g. no more soldiers jumping around without helmet, safety first amarite?)
  
  ![](https://screenshots.gamebanana.com/img/ss/skins/5dd1de610007f.jpg)
  
  ![](https://screenshots.gamebanana.com/img/ss/skins/5dd31a2441ea7.jpg)
  
## Secondary mods

- no\_bugged\_misc.vpk
  - Rarely, some pyro masks still appear in the main mod. This is due to a bug, the mod is unable to replace them with the default pyro head so they're simply not showing up. For visibility reasons (snipers) I let them appear by default but you can use this mod if you want to remove them completely (they will sometimes still appear due to the same bug). This mod is intended to be installed with the main mod.
- no\_hats\_creatorstf.vpk
  - This mod is for people playing in the creators.tf servers. It removes the custom cosmetics the servers add. I can't guarantee that this mod will stay up to date since I don't know how often new cosmetics will be released. This mod is intended to be installed with the main mod.
- no\_unusuals.vpk
  - This file removes unusual particles but doesn't work on Valve servers (because of their sv_pure whitelist). I'm not the person maintaining this mod thus I will not update it if some unusuals are still appearing.
- no\_christmas\_lights.vpk
  - Removes christmas lights from festivized weapons. Not to confuse with the limited **festive** weapons, not affected by this mod.
- no\_skins.vpk
  - This file removes the majority of the weapon skins, with some exceptions. This mod doesn't work on Valve servers and you need to move all of your skinned items at the end of your inventory, otherwise your weapons will load indefinitely.
- no\_botkiller.vpk
  - Removes robot heads from weapons.

## Installation

* On Windows, place any .vpk file into: 
   `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\custom`

* On Linux, place any .vpk file into: 
`~/.local/share/Steam/steamapps/common/Team Fortress 2/tf/custom`

If your game isn't in the default location, you can always go on the game's page in your Steam library. `click the settings icon > Manage > Browse local files`

## Bug report

* If you ever come across a bug (e.g. a cosmetic not being replaced or a player not having the default headgear appearing) you can send me an e-mail at `comments3294071264 AT net-c DoT com`. PLEASE read [Buglist](./.github/BUGLIST.md) and [Q&A](./.github/Q%26A.md) if you want to contact me. (You can also post a new issue on this repo but I prefer e-mails.)

## Modify

![](https://screenshots.gamebanana.com/img/ss/skins/5db363d11849f.webp)

#### Here are 2 videos "trying" to show how you can modify the mod to let some cosmetics appear.

* [Windows](https://streamable.com/uav0li)

* [Linux](https://streamable.com/vxchci)

<p align="center"> 
  <img
        alt="No-Hats-mod"
        src="https://isaydesu.xyz/images/nhm_commercial.png"
        width="850"
      />
</p>
