---
{"dg-publish":true,"permalink":"/index/","tags":["gardenEntry"],"dg-note-properties":{"aliases":["Home","Vault Home","Arden Vul Index"],"categories":["[[organization]]","[[wiki]]"],"created":"05-05-2026 12:00"}}
---


## Halls of Arden Vul — Player Wiki

This is a player-side reference for the [[Halls of Arden Vul\|Halls of Arden Vul]] campaign run on [[OSRIC\|OSRIC]] 3.0 with houserules from [[The Halls of Arden Vul Player Doc\|The Halls of Arden Vul Player Doc]]. See [[Full Vault Wiki and Formatting\|Full Vault Wiki and Formatting]] for the vault's structure and conventions.

## Quick links

- [[Houserules Index\|Houserules Index]] — every modification the GM has made to the base rules
- [[Categories\|Categories]] — every category in the vault, with auto-generated bases
- [[Pantheon\|Pantheon]] — [[The Ten\|The Ten]] and [[The Seventeen\|The Seventeen]]
- [[Seven Collegia\|Seven Collegia]] — the seven magic-user colleges
- [[Spellcasting\|Spellcasting]] — general rules for casting

## Character Creation walkthrough

1. **Generate ability scores** — see [[Modified Character Creation\|Modified Character Creation]]. 3d6 in order, then swap any two.
2. **Select an [[Ancestry\|Ancestry]]** — [[Human\|Human]] (with [[Culture\|Culture]]), [[Dwarf\|Dwarf]], [[Elf\|Elf]], [[Half-Elf\|Half-Elf]], [[Halfling\|Halfling]], [[Half-Orc\|Half-Orc]], or [[Imperial Goblin\|Imperial Goblin]] (replaces [[Gnome\|Gnome]] in this setting).
3. **Pick a [[Class\|Class]]** — [[Assassin\|Assassin]], [[Cleric\|Cleric]], [[Druid\|Druid]], [[Fighter\|Fighter]], [[Illusionist\|Illusionist]], [[Magic-User\|Magic-User]], [[Monk\|Monk]], [[Paladin\|Paladin]], [[Ranger\|Ranger]], or [[Thief\|Thief]]. ([[Multi-Classing\|Multi-Classing]] and [[Dual-Classing\|Dual-Classing]] not used at start.)
4. **Select [[Alignment\|Alignment]]** — nine alignments. (Restrictions per class are lifted except [[Cleric\|Cleric]] must match their deity.)
5. **Roll starting funds** and buy [[Equipment\|Equipment]]. Track via [[Slot-Based Encumbrance\|Slot-Based Encumbrance]].
6. **Magic-Users:** pick one of the [[Seven Collegia\|Seven Collegia]]; you start with [[Read Magic\|Read Magic]] + 2 random + 2 chosen spells.
7. **Clerics:** pick a deity from [[The Ten\|The Ten]] or [[The Seventeen\|The Seventeen]].
8. **Starting rumours:** roll 1d3 [[Adventuring Rumour\|Adventuring Rumour]] + 1d2 [[Historical Rumour\|Historical Rumour]].

## Categories

- Character: [[Ancestry\|ancestry]], [[Culture\|culture]], [[Class\|class]], [[ability-score\|ability-score]], [[Alignment\|alignment]], [[Language\|language]], [[skill\|skill]], [[trait\|trait]]
- Magic: [[spell\|spell]], [[school-of-magic\|school-of-magic]], [[college\|college]], [[deity\|deity]]
- Gear: [[weapon\|weapon]], [[armour\|armour]], [[Equipment\|equipment]], [[container\|container]]
- Play: [[mechanic\|mechanic]], [[condition\|condition]], [[Downtime\|downtime]]
- Setting: [[OSRIC\|osric]], [[arden-vul\|arden-vul]], [[concept\|concept]], [[houserule\|houserule]]

## Source documents

- [[References/OSRIC 3.0 Player Guide\|References/OSRIC 3.0 Player Guide]]
- [[References/The Halls of Arden Vul Player Doc\|References/The Halls of Arden Vul Player Doc]]


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - "!categories.isEmpty()"
    order:
      - categories
      - file.basename
    columnSize:
      note.categories: 401

```

