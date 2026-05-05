---
{"dg-publish":true,"permalink":"/categories/","dg-note-properties":{"aliases":["Categories Index"],"categories":["[[organization\|organization]]","[[wiki\|wiki]]"],"created":"05-05-2026 12:00"}}
---


## Categories used in this vault

Every page in this vault has at least one category. Categories are singular and lowercase, except proper nouns. Use the [[Category Bases/categories\|categories base]] for an auto-aggregated view of every note grouped by its category links.

### Meta

- [[wiki\|wiki]]
- [[organization\|organization]]
- [[reference\|reference]]

### System & setting

- [[OSRIC\|osric]]
- [[arden-vul\|arden-vul]]
- [[concept\|concept]]
- [[houserule\|houserule]]

### Character

- [[Ancestry\|ancestry]]
- [[Culture\|culture]]
- [[Class\|class]]
- [[ability-score\|ability-score]]
- [[Alignment\|alignment]]
- [[Language\|language]]
- [[skill\|skill]]
- [[trait\|trait]]

### Magic

- [[spell\|spell]]
- [[school-of-magic\|school-of-magic]]
- [[college\|college]]
- [[deity\|deity]]

### Gear

- [[weapon\|weapon]]
- [[armour\|armour]]
- [[Equipment\|equipment]]
- [[container\|container]]

### Play

- [[mechanic\|mechanic]]
- [[condition\|condition]]
- [[Downtime\|downtime]]
- [[creature-type\|creature-type]]


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

