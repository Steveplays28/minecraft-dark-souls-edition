---
name: Request to add a mod
about: Request to add a new mod to the modpack.
title: Add
labels: enhancement, mod
assignees: ''

body:
  - type: input
  id: mod-link
  attributes:
    label: Mod link
    description: Mod link, preferably from Modrinth, but CurseForge is allowed if there's no Modrinth version.
    placeholder: https://modrinth.com/mod/sodium
  validations:
    required: true

---
