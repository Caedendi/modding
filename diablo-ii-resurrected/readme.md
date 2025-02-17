# Diablo II: Resurrected mods

- ### [10x10 Horadric Cube for D2RMM](./10x10Cube)

  Expands the Horadric Cube's grid size to 10x10.

  ![mouse.jpg](./10x10Cube/_meta/mouse.jpg)

- ### [Custom Gem Recipes](./CustomGemRecipes)

  Overrides the amount of gems required to upgrade to a higher tier.
  <details>
    <summary>Read more</summary>
    
  Optionally, adds downgrade recipes with yet another configurable amount.  
  It does not affect the amount of gems required to transmute other items.
  </details>

  ![demo.jpg](./CustomGemRecipes/_meta/demo.png)

- ### [Custom Skill Level Requirements](./CustomSkillLevelRequirements)

  Applies a multiplier to skill level requirements, decreasing or increasing requirements as desired.

  ![demo.png](./CustomSkillLevelRequirements/_meta/demo.png)

- ### [Custom Gem Recipes](./ImprovedPotionVisibility)

  Reshuffles and replaces potion textures to make them easier to tell apart.

  ![demo.png](./ImprovedPotionVisibility/_meta/demo.png)

- ### [Invisible Helmets](./InvisibleHelmets)

  Turns helmets invisble by scaling them down to 0.
  <details>
    <summary>Read more</summary>
    
  Only works on playable characters, by overriding the scale for each class to 0.
  Modifying the initial scale would make them invisible as well when dropped, so I don't think it would be possible to hide them for mercenaries too.
  </details>

  ![demo.jpg](./InvisibleHelmets/_meta/demo.jpg)

- ### [Invisible UI Frames](./InvisibleUIFrames)

  Hides the frames around UI windows. "Large Font Mode" compatible.

  ![hd_stash.jpg](./InvisibleUIFrames/_meta/hd_stash.jpg)

- ### [Selectively Disable Potion Drops](./SelectivelyDisablePotionDrops)

  Lets you disable drops of individual HP/MP/RV potions, by replacing them with gold drops.
  Does not affect fixed loot, such as sparkling chests or boses.

- ### [Smaller Grid Items](./SmallerGridItems)

  Scales down the space items take in the inventory to a maximum of two slots.
  <details>
    <summary>Read more</summary>
    
  Has separate toggles for weapons, armor and miscellanous items. Mix as you please.  
  Works by scaling down the item sprites, so it only works for vanilla item sprites, so place mods that add item sprites after this one (otherwise the items will take less grid space while still using full sprites, causing issues).  
  Affects all items bigger than two slots and, in addition, belts (to keep the gear scale more consistent).
  </details>

  <details>
    <summary>"Keep sockets" setting</summary>

  Keeps items with potential to have sockets bigger. Since they use the same sprites as other item variants that don't have sockets, they appear smaller visually while still taking extra space. It ain't pretty, but it's a good compromise if you care about sockets. See [_demonstration_](./SmallerGridItems/_meta/keep_sockets.png).

  Turning the setting off will scale down even socketed items, <span style="color:#f64f2e">**permanently reducing the max amount of sockets both for existing and new items**</span>.  
   Only items acquired after the setting is reenabled or the mod removed will again be able to get their full amount of sockets.
  </details>

  <details>
    <summary>Disabling the mod</summary>

  Before you disable the mod, make sure the items have enough room to grow back into their original size. Otherwise, overlapped items will be lost. See [_demonstration_](./SmallerGridItems/_meta/disabling.png).
  </details>

  ![demo.jpg](./SmallerGridItems/_meta/demo.jpg)

- ### [UI Fixes](./UIFixes)

  Fixes the placement of a few item grids.
  <details>
    <summary>Read more</summary>
    
  Currently fixes:

  - (Vanilla) vendor panel layout
  - (Mod) Expanded Stash (16x13)

  Make sure the mod is loaded after the mods it fixes.
  </details>

  ![demo.png](./UIFixes/_meta/demo.png)
