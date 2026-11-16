# Varyk's Kryszard and Roofoo S14 Fusion

A Project Diablo 2 Season 14 loot filter. It is [Kryszard's PD2 Loot Filter](https://github.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter) (design, styling and filter levels), updated for Season 14, with the Holy Grail tracking from [Roofoo's filter](https://github.com/RoofooEvazan/Roofoo-s-PD2-Loot-Filter) added and the strict levels reworked for endgame.

All credit for the original filters goes to Kryszard and Roofoo.

## Filter levels
0 Show All, 1 Hide Just Trash, 2 More Notify, 3 More Notify w/o Potions, 4 Recommended, 5 Recommended w/o Potions, 6 Strict, 7 Strict w/o Large Charms, 8 Max-Strictness

## Holy Grail alerts
- Unidentified uniques and set items you have not discovered yet get a purple `[GRAIL]` tag, a large minimap border, a star pattern and Roofoo's grail sound.
- Rings, amulets and other bases that can roll several uniques keep saying GRAIL until you have found every possible one.
- Kryszard's GG and Uber items keep their own big display and get the `[GRAIL]` tag added.
- Items you have already found go back to Kryszard's normal display and sounds.

## Strict and Max-Strictness
These rules only apply at character level 70 and up. Below that, every level works as in Kryszard's filter, so leveling characters still see useful rares. Items in your inventory, stash or cube are never hidden.

**Recommended (4) and up**
- Magic class items only show for your own class: claws, pelts, barb helms, paladin shields, necro wands and heads, sorc orbs, and Amazon weapons and quivers.

**Strict (6 and 7)**
- Level 6 hides health and mana potions (full and 35% rejuvenation potions still show) and flawless gems and flawless skulls.
- Level 7 also hides magic Large Charms.
- All rare armor, helms, gloves, boots, belts, rings, amulets, circlets and jewels show, except ethereal ones.
- Regular rare shields: only Monarch, Aegis and Ward (the bases that can roll 4 sockets).
- Magic weapons, armor, quivers, rings, amulets and circlets are hidden, including crafting bases. Magic jewels and charms still show as in Kryszard's filter.
- Ethereal rares that are not weapons are hidden.
- Arrows and quivers only show for Amazons.
- Rare class items show at item level 70 and up. Your own class gets a minimap pin. Other classes still see rare pelts, barb helms and War Fist claws, without a pin; all other off-class items are hidden.
- Claws: only the War Fist look (Hatchet Hands, Fascia, War Fist).
- Rare staves: sorceress only.
- Rare weapons: only these lines (all difficulties, since bases can be upgraded). Ethereal ones get a minimap pin.
  - One-handers: Crystal Sword, War Axe, Flail and War Hammer lines
  - Bows: Long Bow, Long Battle Bow and Long War Bow lines, plus Reflex, Ceremonial and Grand Matron Bows (Amazon)
  - Crossbows: Heavy Crossbow and Repeating Crossbow lines
  - Two-handed swords: Giant Sword, Bastard Sword, Flamberge and Great Sword lines
  - Mauls: Maul and Great Maul lines
  - Polearms and spears: Pike line only
  - Two-handed axes: Battle Axe, Great Axe and Giant Axe lines
  - Javelins: Throwing Spear and Glaive lines
  - Daggers, throwing knives and throwing axes are hidden for every class.

**Max-Strictness (8)**
- Same as Strict, except:
  - Physical rare weapons only show if ethereal. Ethereal War Fist claws show for every class.
  - Sorceress orbs and staves are caster weapons, so they show as on Strict.
  - Other classes' rare pelts, barb helms and War Fists are hidden.

## Other additions
- **Season 14:** new maps (The Poisoned Well, The Fortress of Aranoch, The Descent from Mount Arreat), new town areas, new uniques (Spectral Plate, Warriv's Warder) and new runewords (Madness, Finesse, Deception, Jealousy).
- **Map tooltips:** monster immunities checked against the PD2 wiki for all tier 1 to 3 maps, including Kyovashad's new fire, lightning and magic immunes.
- **Boots:** identified boots show their total resist (for example "95R") and a Dual, Tri or Quad Res line, from Roofoo's filter.
- **Sounds:** Uber Ancients sigils use the greater mummy sound.
