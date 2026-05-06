---
{"dg-publish":true,"permalink":"/all-players/","dg-note-properties":{"aliases":["Players","Player Index","The Table"],"categories":["[[organization]]","[[wiki]]"],"created":"05-05-2026 12:00"}}
---


## All Players

Every real-world player at the table. See [[Player\|Player]] for the concept and [[Templates/Player Profile Template\|Player Profile Template]] for the player profile template.

> [!tip] 🎭 Adding a new player
> Duplicate [[Templates/Player Profile Template\|Player Profile Template]] into the vault root, rename it to the player's display name, and fill out their profile. As they create characters, link each one in the **Characters** section of their profile and set the character's `owner:` frontmatter back to this player.

### Players


```base
filters:
  and:
    - "categories.contains(\"[[player]]\")"
views:
  - type: table
    name: Players
    order:
      - file.basename
      - player_name
      - status
    columnSize:
      note.categories: 401

```


## Related

- ⚔️ [[All Characters\|All Characters]] — every character, with owner column
- 🎭 [[Player\|Player]] — concept
- 📝 [[Templates/Player Profile Template\|Player Profile Template]] — player profile template
- [[index\|Vault Home]]
- [[By Category\|By Category]] — every category, all on one page
