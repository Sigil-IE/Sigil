# [WIP] Sigil: a shared directory of mods for Infinity Engine games
### [Background information](https://github.com/Sigil-IE/Sigil/wiki#background-information) - [Plans](https://github.com/Sigil-IE/Sigil/wiki#plans) - [Methodology](https://github.com/Sigil-IE/Sigil/wiki#methodology) - [F.A.Q.](https://github.com/Sigil-IE/Sigil/wiki#faq)


# Read me

## Player
[A New Player’s Guide to Installing and Playing Mods](https://www.gibberlings3.net/forums/topic/33164-a-new-player%E2%80%99s-guide-to-installing-and-playing-mods/)

Steam or GOG users that want to install a WeiDU mod on anything that includes Siege of Dragonspear must first run [DLC Merger](https://forums.beamdog.com/discussion/71305/mod-dlc-merger-merge-steam-gog-sod-dlc-or-custom-dlcs-with-the-main-game).

The categories are not meant to be used as install orders (see the wiki for a possible future scope expansion materials), just to organise the mods, hence some mods appear in multiple categories.

The descriptions are broad overviews, always read the mod's page and/or readme for the details. Some mods change too many things or give too many options to fully list in a few sentences. Many mods are broken up into components, some of which may be skipped, but here they are presented collectively.

<details><summary>

## Contributor</summary>
Check [projects](https://github.com/Sigil-IE/Sigil/projects) for current status and any issues that are marked as help wanted. Collaborators welcome.


**Adding a new mod**

Check that the mod link is alive and match the template below, omitting alternative download locations or forums or sites as needed. Underscores are purely for ease of selection, Title Case is prescriptive. Write a one to two sentence description yourself if the one provided by the mod author is too long. The description should be light on adjectives and heavy on quantifiers. Place the mod in an appropriate game and category (may add to multiple, but try for as few as possible). The category may be carried over from BWS if in doubt.
 
```markdown
* [Mod_Name](main_download_location_link) [(Short_Name_For_Alternative_Download_Location)](alternative_download_location_link) by **Author_Name** *Description_of_the_mod* [Forum](link_to_the_discussion_of_the_mod_if_distinct_from_download_location) [Site](link_to_the_page_for_the_mod_if_distinct_from_download_location) `technical_information_such_as_minimal_EET_compatible_version_number`
```
</details>

# Enhanced Editions

### Tools
* [DLC Merger](https://github.com/Argent77/A7-DlcMerger/releases) *Required for Steam or GOG versions of BG EE and SoD to use mods.* [Forum](https://forums.beamdog.com/discussion/71305/mod-dlc-merger-merge-steam-gog-sod-dlc-or-custom-dlcs-with-the-main-game)
* [EEex](https://forums.beamdog.com/discussion/71798/mod-eeex-v0-9-7-alpha) *Executable extender allowing to mod hardcoded mechanics. The game must be started using InfinityLoader.exe/EEex.exe after installation rather than the regular executable. May be put before EET_end if there are mods that require it also before EET_end.* `v0.2.0-alpha or above (can be installed even after setup-EET_end)`
* [EE Keeper](https://forums.beamdog.com/discussion/16497/ee-keeper-updated-to-v1-0-4) *Save game, creature, and character editor.*
* [Alweth's Easy Portrait Grabber Tool](https://github.com/abrahamwl/portrait-grabber/releases/) by **Alweth** *Grabs any image and formats it into a portrait.* [Forum](https://forums.beamdog.com/discussion/17596/alweths-easy-portrait-grabber-tool)

<!-- <details><summary> -->

## Enhanced Edition Trilogy (BG I EE + SoD + BG II EE)</summary>
[EET](https://github.com/Gibberlings3/EET/releases) *Merges enhanced editions of Baldur's Gate I, Baldur's Gate II, and the Beamdog expansion Siege of Dragonspear into a single experience.* [Forum.](https://www.gibberlings3.net/forums/forum/195-enhanced-edition-trilogy/)

The following is mostly a downstream version of the [Mod Compatibility List for EET](https://k4thos.github.io/EET-Compatibility-List/EET-Compatibility-List.html) with added categories and short descriptions and removed techical details (make sure to read the original for those). Some mods that have been tested to work on EET, but have not yet been added to the compatibility list are present. Compatibility with EET does not imply compatibility with all other mods that are compatible with EET, read the individual mod's readme.

### **Mods installed on BG:EE previous to installing EET on BG2:EE**

### Big Mods
* [Dark Horizons BG:EE](https://forums.beamdog.com/discussion/18833/bg-ee-dark-horizons-released/p1) *Centers around an organisation hunting down the player character throughout the game. Adds quests, encounters, items, shops, two joinable NPCs.* `v2.12 or above`
* [Drizzt Saga](https://forums.beamdog.com/discussion/29969/drizzt-saga-v3-released-now-bgee-compatible/p1) *Adds Drizzt and his companions as joinable NPCs along with new quests, locations, items, and creatures.* `v3 or above (select default option during installation - despite the name it's compatible with both EET Worldmap and BP-BGT Worldmap)`
* [The Stone of Askavar](https://forums.beamdog.com/discussion/42168/mod-the-stone-of-askavar-for-totsc-tutu-bgt-and-bg-ee/p1) *Adds quests, items, spells, creatures.* `v1.9 or above (select default option during installation - despite the name it's compatible with both EET Worldmap and BP-BGT Worldmap)`
### NPCs
* [Drake NPC](https://github.com/ArtemiusI/Drake/releases) *Neutral Good Human Priest of Tyr that may be taken through BG I and SoD. Has crossmod content.* `v0.1 BETA`
* [Margarita NPC](https://forums.beamdog.com/discussion/15867/mod-npc-margarita-zelleod/p1) *Lawful Neutral Halfling Stalker.* `v1.0 or above`
* [Saradas Magic](https://forums.beamdog.com/discussion/23861/bg-ee-mod-saradas-magic-released/p1) *Archmage joinable NPC and 7 new arcane spells.* `v1.1 or above`
* [Sharteel NPC mod for SoD](http://www.shsforums.net/files/file/1164-sharteel-npc-mod-for-sod/) *Allows to take Shar-Teel through SoD* `Pre-Release 1.1 or above`
* [Sirene NPC](https://forums.beamdog.com/discussion/42721/npc-mod-sirene-npc-for-bg-ee-v1-0/p1) *Lawful Good Tiefling Martyr (Paladin) that may be taken through BG I and SoD. Has crossmod content.* `v1.0 or above`
* [Tenya Thermidor](https://forums.beamdog.com/discussion/33291/tenya-thermidor-v1-3/p1) *Chaotic Neutral Cleric.* `v1.5 or above`
* [Verr'Sza NPC](https://downloads.weaselmods.net/download/verrsza-bg1ee/) *Evil Rakshasa Hunter that may be taken through BG I and SoD.* `v2.4 or above`
* [White NPC](https://downloads.weaselmods.net/download/white-npc/) *Chaotic Neutral Human Barbarian* `v2.2 or above`
### NPC extensions
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`
* [Garrick: Tales of a troubadour](http://mirandir.baldursgateworld.fr/garrick-tt/) *Expands Garrick, building on previous expansion in BG1 NPC Project. Requires BG1 NPC Project. Conflicts with Garrick's Infatuation and Tenya NPC.* `v1.24 or above`
* [Sharteel NPC mod for SoD](http://www.shsforums.net/files/file/1164-sharteel-npc-mod-for-sod/) *Allows to take Shar-Teel through SoD* `Pre-Release 1.1 or above`
### Quests
* [Aerie for BG:EE](https://forums.beamdog.com/discussion/38824/aerie-in-bg-ee-v1-1/p1) by **Coutelier** *Adds Aerie as a non-companion NPC with a couple of small quests.* `v1.1 or above`
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`
* [T'was a Slow Boat from Kara-Tur](https://forums.beamdog.com/discussion/15959/mod-twas-a-slow-boat-from-kara-tur-queststorenew-items-release-90/p1) *Adds a quest and 30+ items.* `v.90 or above`
### Items
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`
* [T'was a Slow Boat from Kara-Tur](https://forums.beamdog.com/discussion/15959/mod-twas-a-slow-boat-from-kara-tur-queststorenew-items-release-90/p1) *Adds a quest and 30+ items.* `v.90 or above`
### Spells
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`
* [Saradas Magic](https://forums.beamdog.com/discussion/23861/bg-ee-mod-saradas-magic-released/p1) *Archmage joinable NPC and 7 new arcane spells* `v1.1 or above`
### Crossmods
* [Drake NPC](https://github.com/ArtemiusI/Drake/releases) *Adds a Neutral Good Human Priest of Tyr that may be taken through BG I and SoD. Has crossmod content.* `v0.1 BETA`
* [Garrick: Tales of a troubadour](http://mirandir.baldursgateworld.fr/garrick-tt/) *Expands Garrick, building on previous expansion in BG1 NPC Project. Requires BG1 NPC Project. Conflicts with Garrick's Infatuation and Tenya NPC.* `v1.24 or above`
* [Sirene NPC](https://forums.beamdog.com/discussion/42721/npc-mod-sirene-npc-for-bg-ee-v1-0/p1) *Lawful Good Tiefling Martyr (Paladin) that may be taken through BG I and SoD. Has crossmod content.* `v1.0 or above`
### Corrections
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`
### Tweaks
* [Rough World](https://forums.beamdog.com/discussion/59889/rough-world-beta/p1) *Makes the reputation system less forgiving, adds higher-level spawns, makes Chapter 7 more restrictive.* `vBeta or above`
### Sound
* [BG1 Unfinished Business](https://github.com/Pocket-Plane-Group/bg1ub/releases) *Restores cut content, including quests, characters, lines, items, spells, and sounds. Fixes vanilla bugs and inconsistencies.* `v14 [BETA] or above`

### **Mods installed after EET main component on BG2:EE**

### Big Mods
### NPCs
* [Adrian NPC](https://github.com/SpellholdStudios/Adrian_NPC/releases) *Lawful Evil Half-elf Sorcerer.* `V4.0 or above`
* [Afaaq, the Djinni Companion](https://github.com/Argent77/DjinniCompanion/releases) *Chaotic Good Djinni Fighter/Mage.* `v2.2 or above`
* [Amber](https://www.gibberlings3.net/mods/npcs/amber/) *Chaotic Good Tiefling Fighter/Thief.* `v5 or above`
* [Angelo NPC](https://www.gibberlings3.net/mods/npcs/angelo/) *Chaotic Neutral Human Fighter/Mage.* `v6`
* [Anishai One Day NPC](https://www.gibberlings3.net/files/file/687-anishai-one-day-npc/) *Makes the Lawful Evil Human Monk from Mae'Var's guildhouse a joinable companion.* `v2 or above`
* [Arath](http://www.shsforums.net/files/file/1001-arath/) *Human Druid* `v4 or above`
* [Ascalon's Breagar](https://github.com/Gitjas/Ascalons_Breagar/releases/latest) by **Ascalon, WhiteAgnus, Jastey** *Dwarven Smith companion that may be taken through the entire trilogy* [Forum](https://www.baldurs-gate.de/index.php?threads/ascalons-breagar.44520/) `v7.0 or above`
* [Aura NPC](https://forums.beamdog.com/discussion/65891/v3-2-aura-a-gnome-artificer-npc-for-bg-ee-sod/p1) by **ArtemiusI** *Lawful Good Gnome Artificer that may be taken through BGEE and SoD* `v3.2 or above`
* [Auren Aseph NPC](https://www.gibberlings3.net/mods/npcs/auren/) *Neutral Good Human Fighter* `v10`
### NPC extensions
* [Ajantis BG1 Expansion](https://www.baldurs-gate.de/index.php?resources/jasteys-ajantis-bg1-expansion.2/) by **Jastey** *Either adds or expands (if BG1NPC project is also installed) Ajantis' friendship and romance tracks.* [Forum](https://www.gibberlings3.net/forums/forum/199-ajantis/) [Site](https://www.gibberlings3.net/mods/npcs/ajantis/) `v10 or above`
* [Ascension](https://github.com/InfinityMods/Ascension) *Expands and changes the later parts of ToB, including adding new abilities, enemies, epilogues, rewriting dialogues, and making encounters more tactical. Original project leader was David Gaider.* `v1.5 BETA or above`
### Quests
* [Adalon's Blood](https://www.baldurs-gate.de/index.php?resources/adalons-blood-silberdrachenblutmod.5/) *Adds an alternative way to receive Adalon's blood.* `v1.4 or above`
* [Adventures in Papperland](http://www.shsforums.net/files/file/139-adventures-in-papperland/) *A joke encounter with The Beatles* `v6.0 or above`
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
* [Alternatives](https://www.gibberlings3.net/mods/quests/alternatives/) *Adds alternative routes to siding with the Shadow Thieves or with Valen's Mistress.* `v12 or above`
* [Anniversary (G3 mini mod)](https://www.gibberlings3.net/mods/quests/g3a/) *A joke quest celebrating the anniversary of Gibberlings 3.* `v9.1`
* [Ascalon's Questpack](https://github.com/Gitjas/Ascalons_Questpack/releases) by **Ascalon, WhiteAgnus, Jastey)** *Multiple quests of various genres. Compatible with Glam's NPC Pack as long as the relevant option is chosen during install.* [Forum](https://www.baldurs-gate.de/index.php?threads/ascalons-questpack-version-2-01-tester-gew%C3%BCnscht.44450/) [Site](https://baldurs-gate.de/index.php?resources/ascalons-questpack.4/) `v2.02 or above`
* [Assassinations](https://github.com/Pocket-Plane-Group/Assassinations/releases) *A series of quests centred around being an assassin. Accessible to a non-heroic non-paladin protagonist.* `v13 or above`
* [Athkatlan Grounds: Ooze's Lounge](https://downloads.weaselmods.net/download/oozes-lounge/) *Adds a few areas to Athkatlan sewers, along with quests, items, and graphics.* `v2.3 or above`
* [Athkatlan Grounds: Southern Edge](https://downloads.weaselmods.net/download/southern-edge/) *Adds a new district to Athkatla containing early game quests and encounters.* `v1.0 or above`
* [Athkatlan Grounds: Tangled Oak Isle](https://downloads.weaselmods.net/download/tangled-oak-isle/) *Adds a new area and quests to Athkatla.* `(since v0.91)`
### Kits
### Items
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
* [Athkatlan Grounds: Ooze's Lounge](https://downloads.weaselmods.net/download/oozes-lounge/) *Adds a few areas to Athkatlan sewers, along with quests, items, and graphics.* `v2.3 or above`
### Spells
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
### Tactical
* [Ascension](https://github.com/InfinityMods/Ascension) *Expands and changes the later parts of ToB, including adding new abilities, enemies, epilogues, rewriting dialogues, and making encounters more tactical. Original project leader was David Gaider.* `v1.5 BETA or above`
### Crossmods
* [Ajantis BG1 Expansion](https://www.baldurs-gate.de/index.php?resources/jasteys-ajantis-bg1-expansion.2/) by **Jastey** *Either adds or expands (if BG1NPC project is also installed) Ajantis' friendship and romance tracks.* [Forum](https://www.gibberlings3.net/forums/forum/199-ajantis/) [Site](https://www.gibberlings3.net/mods/npcs/ajantis/) `v10 or above`
* [Ajoc's minimod for EE and EET](http://www.shsforums.net/topic/59054-ajocmod-for-ee-and-eet/) *An addition to The Darkest Day, includes new quests, monsters, items, and areas* `v1.0 or above (this update requires resources from [original ajocmod](http://www.shsforums.net/files/file/119-ajocs-minimod/)`
### Corrections
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Achievements!](https://github.com/Argent77/A7-Achievements/releases) by **Argent77** *Adds Steam achievements as journal entries with in-game rewards to any version of the games. Allows to earn some SoD achievements not normally registered by Steam.* [Forum](https://www.gibberlings3.net/forums/topic/33035-achievements-for-everyone/) [Site](https://github.com/Argent77/A7-Achievements) `v1.0 or above`
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
### Tweaks
* [3.5e Weapon Style Rebalance](http://www.shsforums.net/files/download/1205-35-edition-weapon-style-rebalance/) by **Reddbane** *Multiple ways to change the behavior of "Weapon Style" proficiencies with the aim to improve balance and bring them closer to D&D 3.5 edition and Pathfinder.*
* [5E-Style Spellcasting](https://github.com/UnearthedArcana/5E_spellcasting/releases) *Makes prepared spells take up slots per level rather than per specific spell. Compatible with Tome & Blood. Doesn't affect spellcasters from Shadow Magic.* `v1.1 or above`
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Achievements!](https://github.com/Argent77/A7-Achievements/releases) by **Argent77** *Adds Steam achievements as journal entries with in-game rewards to any version of the games. Allows to earn some SoD achievements not normally registered by Steam.* [Forum](https://www.gibberlings3.net/forums/topic/33035-achievements-for-everyone/) [Site](https://github.com/Argent77/A7-Achievements) `v1.0 or above`
* [Adalon's Blood](https://www.baldurs-gate.de/index.php?resources/adalons-blood-silberdrachenblutmod.5/) *Adds an alternative way to receive Adalon's blood.* `v1.4 or above`
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
* [Alternatives](https://www.gibberlings3.net/mods/quests/alternatives/) *Adds alternative routes to siding with the Shadow Thieves or with Valen's Mistress.* `v12 or above`
* [Animal Companions](https://github.com/thisisulb/AnimalCompanions) by **Ulb** *Gives rangers and optionally druids the ability to befriend a permanent animal companion.* [Forum](http://www.shsforums.net/topic/56242-animal-companions/) `v1.3 or above`
* [Ascension](https://github.com/InfinityMods/Ascension) *Expands and changes the later parts of ToB, including adding new abilities, enemies, epilogues, rewriting dialogues, and making encounters more tactical. Original project leader was David Gaider.* `v1.5 BETA or above`
* [aTweaks](http://www.shsforums.net/topic/38261-atweaks-v451-released/) [(GH)](https://github.com/FredrikLindgren/aTweaks/tags) by **aVENGER & Wisp** *Tweaks and changes focused on emulating the Pen and Paper experience and increasing gameplay consistency. Includes convenience Thief, Bard, and Cleric/Paladin scripts to make them perform class actions when idle. Some components are compatible with similar ones in the G3 BG2 Fixpack.* [Forum](http://www.shsforums.net/forum/598-atweaks/) `v4.50 or above`
### Graphics
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
* [Artaport](https://forums.beamdog.com/discussion/51904/mod-artaport-4-0/p1) by **Artrastrophe, Etamin** *Adds over 100 portraits for the player (have to be installed manually), optionally replaces companion portraits and adds portraits to non-joinable NPCs* [Site](https://github.com/Eltamin/artaport) `(EE native version of [PaintBG](http://www.shsforums.net/files/file/1033-paintbg/)) v2 or above`
* [Athkatlan Grounds: Ooze's Lounge](https://downloads.weaselmods.net/download/oozes-lounge/) *Adds a few areas to Athkatlan sewers, along with quests, items, and graphics.* `v2.3 or above`
* [aTweaks](http://www.shsforums.net/topic/38261-atweaks-v451-released/) [(GH)](https://github.com/FredrikLindgren/aTweaks/tags) by **aVENGER & Wisp** *Tweaks and changes focused on emulating the Pen and Paper experience and increasing gameplay consistency. Includes convenience Thief, Bard, and Cleric/Paladin scripts to make them perform class actions when idle. Some components are compatible with similar ones in the G3 BG2 Fixpack.* [Forum](http://www.shsforums.net/forum/598-atweaks/) `v4.50 or above`
### Portraits
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Ace's Enchanters Portrait Pack](https://www.gibberlings3.net/files/file/1007-aces-enchanters-portrait-pack/) by **theacefes** *A collection of 8 portraits from the character art of the Enchanters book series.* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Amaurea's BG Portraits](https://www.gibberlings3.net/files/file/684-amaureas-bg-portraits/) by **Amaurea (portraits), Berelinde (code)** *Alternative portraits for every BG companion (may be used by the player).* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Amaurea's BG2 Portraits](https://www.gibberlings3.net/files/file/683-amaureas-bg2-portraits/) by **Amaurea** *Alternative portraits for every BGII companion (may be used by the player).* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Artaport](https://forums.beamdog.com/discussion/51904/mod-artaport-4-0/p1) by **Artrastrophe, Etamin** *Adds over 100 portraits for the player (have to be installed manually), optionally replaces companion portraits and adds portraits to non-joinable NPCs* [Site](https://github.com/Eltamin/artaport) `(EE native version of [PaintBG](http://www.shsforums.net/files/file/1033-paintbg/)) v2 or above`
### Sound
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Almateria's Restoration Project](http://www.shsforums.net/files/file/1053-almaterias-restoration-project/) *Restores cut sounds, characters, lines, locations, items, Wish options, encounters, icons, XP rewards. Expands Cernd's quest and Slayer content. Compatible with Quest Pack, which should be installed after component G.* `v8.2.7 or above`
* [aTweaks](http://www.shsforums.net/topic/38261-atweaks-v451-released/) [(GH)](https://github.com/FredrikLindgren/aTweaks/tags) by **aVENGER & Wisp** *Tweaks and changes focused on emulating the Pen and Paper experience and increasing gameplay consistency. Includes convenience Thief, Bard, and Cleric/Paladin scripts to make them perform class actions when idle. Some components are compatible with similar ones in the G3 BG2 Fixpack.* [Forum](http://www.shsforums.net/forum/598-atweaks/) `v4.50 or above`
### UI
* [Bubb's Spell Menu Extended](https://www.gibberlings3.net/forums/topic/35838-ui-bubbs-spell-menu-v45/) *Displays all available spells at once, allows to search for spells via typing, adds an Arcane/Divine spells filter. Requires EEex. Compatible (if installed after) with EET GUI, Dragonspear UI++ (read the thread for a link to the specific version needed), Lefreut's enhanced UI.* `v2.2 or above (must be installed after setup-EET_gui, can be installed even after setup-EET_end)`
* [Dragonspear UI++](https://forums.beamdog.com/discussion/50357/mod-dragonspear-ui-v2-42-now-compatible-with-bg2-ee) *Overhaul adding a shared inventory screen, making many components fill the screen, removing empty backgrounds and more.*
### AI scripts
* [aTweaks](http://www.shsforums.net/topic/38261-atweaks-v451-released/) [(GH)](https://github.com/FredrikLindgren/aTweaks/tags) by **aVENGER & Wisp** *Tweaks and changes focused on emulating the Pen and Paper experience and increasing gameplay consistency. Includes convenience Thief, Bard, and Cleric/Paladin scripts to make them perform class actions when idle. Some components are compatible with similar ones in the G3 BG2 Fixpack.* [Forum](http://www.shsforums.net/forum/598-atweaks/) `v4.50 or above`

<!-- </details> -->

<details><summary>

## Baldur's Gate I Enhanced Edition and Siege of Dragonspear</summary>
### Big Mods
### NPCs
* [Ascalon's Breagar](https://github.com/Gitjas/Ascalons_Breagar/releases/latest) by **Ascalon, WhiteAgnus, Jastey** *Dwarven Smith companion that may be taken through the entire trilogy* [Forum](https://www.baldurs-gate.de/index.php?threads/ascalons-breagar.44520/) `v7.0 or above`
* [Aura NPC](https://forums.beamdog.com/discussion/65891/v3-2-aura-a-gnome-artificer-npc-for-bg-ee-sod/p1) by **ArtemiusI** *Lawful Good Gnome Artificer that may be taken through BGEE and SoD* `v3.2 or above`
### NPC extensions
* [Ajantis BG1 Expansion](https://www.baldurs-gate.de/index.php?resources/jasteys-ajantis-bg1-expansion.2/) by **Jastey** *Either adds or expands (if BG1NPC project is also installed) Ajantis' friendship and romance tracks.* [Forum](https://www.gibberlings3.net/forums/forum/199-ajantis/) [Site](https://www.gibberlings3.net/mods/npcs/ajantis/) `v10 or above`
### Quests
* [Aerie for BG:EE](https://forums.beamdog.com/discussion/38824/aerie-in-bg-ee-v1-1/p1) by **Coutelier** *Adds Aerie as a non-companion NPC with a couple of small quests.* `v1.1 or above`
* [Ascalon's Questpack](https://github.com/Gitjas/Ascalons_Questpack/releases) by **Ascalon, WhiteAgnus, Jastey)** *Multiple quests of various genres. Compatible with Glam's NPC Pack as long as the relevant option is chosen during install.* [Forum](https://www.baldurs-gate.de/index.php?threads/ascalons-questpack-version-2-01-tester-gew%C3%BCnscht.44450/) [Site](https://baldurs-gate.de/index.php?resources/ascalons-questpack.4/) `v2.02 or above`
### Kits
* [The Artisan's Kitpack](https://lynxlynx.info/ie/modhub.php?ArtemiusI/The-Artisan-s-Kitpack&master) by **Artemius_I** *Fighter (Arcane Archer, Kensai, Vanguard (option for Khalid)), Ranger (Dark, Hunter, Rashemi Berserker (Minsc only)), Paladin (Divine champion (option for Ajantis, Keldorn, Sirene), Mystic Fire), Druid (Hivemaster, Thief (Assassin (option for Hexxat), Magekiller, Rogue Archer (option for Imoen)), Shaman (Warhorn Shaman), Sorcerer (Dragon Disciple, Pale Master))* [Forum](http://www.shsforums.net/topic/60112-the-artisans-kitpack-for-bgee-bg2ee-and-iwdee/) [Site](https://artisans-corner.com/the-artisans-kitpack/) `EET`
### Items
### Spells
### Tactical 
### Crossmods
* [Ajantis BG1 Expansion](https://www.baldurs-gate.de/index.php?resources/jasteys-ajantis-bg1-expansion.2/) by **Jastey** *Either adds or expands (if BG1NPC project is also installed) Ajantis' friendship and romance tracks.* [Forum](https://www.gibberlings3.net/forums/forum/199-ajantis/) [Site](https://www.gibberlings3.net/mods/npcs/ajantis/) `v10 or above`
### Corrections
### Tweaks
* [3.5e Pathfinder Thac0 Progression](http://www.shsforums.net/files/download/1172-35epathfinder-thac0-progression/) by **Reddbane** *Alters the attack progression to be smoother and closer to 3.5 balance.* [Forum](http://www.shsforums.net/topic/59169-35-edition-pathfinder-style-tweaks-collection-thac0-constitution/) 
* [3.5e Pathfinder Universal (All Classes) Constitution Bonus](http://www.shsforums.net/files/download/1174-35epathfinder-universal-all-classes-constitution-bonus/) by **Reddbane** *All classes now receive the same bonuses for 17+ CON.* [Forum](http://www.shsforums.net/topic/59169-35-edition-pathfinder-style-tweaks-collection-thac0-constitution-hit-dice) 
* [3.5e Weapon Style Rebalance](http://www.shsforums.net/files/download/1205-35-edition-weapon-style-rebalance/) by **Reddbane** *Multiple ways to change the behavior of "Weapon Style" proficiencies with the aim to improve balance and bring them closer to D&D 3.5 edition and Pathfinder.* `EET`
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Achievements!](https://github.com/Argent77/A7-Achievements/releases) by **Argent77** *Adds Steam achievements as journal entries with in-game rewards to any version of the games. Allows to earn some SoD achievements not normally registered by Steam.* [Forum](https://www.gibberlings3.net/forums/topic/33035-achievements-for-everyone/) [Site](https://github.com/Argent77/A7-Achievements) `v1.0 or above`
* [Animal Companions](https://github.com/thisisulb/AnimalCompanions) by **Ulb** *Gives rangers and optionally druids the ability to befriend a permanent animal companion.* [Forum](http://www.shsforums.net/topic/56242-animal-companions/) `v1.3 or above`
* [House Rules Tweaks](https://lynxlynx.info/ie/modhub.php?ArtemiusI/House-Rule-Tweaks&master) by **Artemius_I** *Tweaks for dialogue, rules, stats, graphics, animations* [Forum](https://forums.beamdog.com/discussion/56035/v1-6-artemius-is-house-rule-tweaks-most-recent-moved-all-kit-components) [Site](https://artisans-corner.com/house-rules/) `EET`
* [aTweaks](http://www.shsforums.net/topic/38261-atweaks-v451-released/) [(GH)](https://github.com/FredrikLindgren/aTweaks/tags) by **aVENGER & Wisp** *Tweaks and changes focused on emulating the Pen and Paper experience and increasing gameplay consistency. Includes convenience Thief, Bard, and Cleric/Paladin scripts to make them perform class actions when idle. Some components are compatible with similar ones in the G3 BG2 Fixpack.* [Forum](http://www.shsforums.net/forum/598-atweaks/) `v4.50 or above`
### Graphics
### Portraits
* [Ace's Enchanters Portrait Pack](https://www.gibberlings3.net/files/file/1007-aces-enchanters-portrait-pack/) by **theacefes** *A collection of 8 portraits from the character art of the Enchanters book series.* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Amaurea's BG Portraits](https://www.gibberlings3.net/files/file/684-amaureas-bg-portraits/) by **Amaurea (portraits), Berelinde (code)** *Alternative portraits for every BG companion (may be used by the player).* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Amaurea's BG2 Portraits](https://www.gibberlings3.net/files/file/683-amaureas-bg2-portraits/) by **Amaurea** *Alternative portraits for every BGII companion (may be used by the player).* [Forum](https://www.gibberlings3.net/forums/forum/28-miscellaneous-released-mods/) [Site](https://www.gibberlings3.net/mods/other/portraitpacks/) `EET`
* [Artaport](https://forums.beamdog.com/discussion/51904/mod-artaport-4-0/p1) by **Artrastrophe, Etamin** *Adds over 100 portraits for the player (have to be installed manually), optionally replaces companion portraits and adds portraits to non-joinable NPCs* [Site](https://github.com/Eltamin/artaport) `(EE native version of [PaintBG](http://www.shsforums.net/files/file/1033-paintbg/)) v2 or above`
### Sound
* [AC's Miscellaneous Tweaks](http://www.shsforums.net/topic/61094-acs-miscellaneous-tweaks/) by **Andrea Colombo** *Various small tweaks and fixes, including changing appearance of items, portraits, and bringing in sound sets across the games.* `RC1 or above`
* [Awesome Soundsets Vol.1](http://www.shsforums.net/files/download/1102-awesome-soundsets-vol-1/) by **Smeagolheart** *BG NPC voices customised to fit the player* [Forum](http://www.shsforums.net/topic/57786-awesome-soundsets-vol-1/?hl=awesome+soundsets) [Site](http://www.shsforums.net/files/file/1102-awesome-soundsets-vol-1/) `Doesn't work on BGEE 2.6 or SoD, has to be installed on BG2EE before also installing EET to be used in BGEE+SoD`
* [Awesome Soundsets Vol.2](http://www.shsforums.net/files/download/1106-awesome-soundsets-vol-2/) by **Smeagolheart** *IWD2 soundsets* [Forum](http://www.shsforums.net/topic/57812-awesome-soundsets-vol-2/?hl=awesome+soundsets) [Site](http://www.shsforums.net/files/file/1106-awesome-soundsets-vol-2/) `Doesn't work on BGEE 2.6 or SoD, has to be installed on BG2EE before also installing EET to be used in BGEE+SoD` 
* [Awesome Soundsets Vol.3](http://www.shsforums.net/files/download/1107-awesome-soundsets-vol-3/) by **Smeagolheart** *PST soundsets customised to fit the player* [Forum](http://www.shsforums.net/topic/57845-awesome-soundsets-vol-3/?hl=awesome+soundsets) [Site](http://www.shsforums.net/files/file/1107-awesome-soundsets-vol-3/) `Doesn't work on BGEE 2.6 or SoD, has to be installed on BG2EE before also installing EET to be used in BGEE+SoD`
* [Awesome Soundsets Vol.4](http://www.shsforums.net/files/download/1108-awesome-soundsets-vol-4/) by **Smeagolheart** *Soundsets from The Monkey Island series customised to fit the player* [Forum](http://www.shsforums.net/topic/57846-awesome-soundsets-vol-4/?hl=awesome+soundsets)  [Site](http://www.shsforums.net/files/file/1108-awesome-soundsets-vol-4/) `Doesn't work on BGEE 2.6 or SoD, has to be installed on BG2EE before also installing EET to be used in BGEE+SoD`
### UI
### AI scripts
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
* [Polish list by Cahir](https://baldur.cob-bg.pl/bg1ee-mody)
</details>

<details><summary>

## Baldur's Gate II Enhanced Edition</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
* [Polish list by Cahir](http://baldur.cob-bg.pl/bg2ee-mody)
</details>

<details><summary>

## Icewind Dale Enhanced Edition</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

<details><summary>

## Planescape: Torment Enhanced Edition</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

# Originals

<details><summary>

## Baldur's Gate I</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

<details><summary>

## Baldur's Gate II</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

<details><summary>

## Icewind Dale</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

<details><summary>

## Icewind Dale II</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>

<details><summary>

## Planescape: Torment</summary>
### Localisation
* [French list by Jazira](https://github.com/Jazira33/CCTradFR)
</details>
