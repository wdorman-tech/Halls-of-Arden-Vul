---
{"dg-publish":true,"permalink":"/all-characters/","dg-note-properties":{"aliases":["Characters","Character Index","Party Roster"],"categories":["[[organization]]","[[wiki]]"],"created":"05-05-2026 12:00"}}
---


## All Characters

Every player character in the campaign — alive, dead, or retired. See [[Character\|Character]] for the concept and [[Templates/Player Template\|Player Template]] for the character sheet template.

> [!tip] Adding a new character
> Duplicate [[Templates/Player Template\|Player Template]] into the vault root, rename it to your character's name, and set the `owner:` frontmatter to the [[All Players\|player]] who controls them. The character will appear in the table below automatically.

### Roster


```base
filters:
  and:
    - "categories.contains(\"[[character]]\")"
views:
  - type: table
    name: Characters
    order:
      - file.basename
      - owner
      - class
      - ancestry
      - level
    columnSize:
      note.categories: 401

```


## Related

- [[All Players\|All Players]] — the real-world players behind these characters
- [[Character\|Character]] — concept
- [[Templates/Player Template\|Player Template]] — character sheet template
- [[Slot-Based Inventory\|Slot-Based Inventory]] — inventory rules (flat list on the wiki, slot grid on paper)
- [[index\|Vault Home]]
- [[By Category\|By Category]] — every category, all on one page
