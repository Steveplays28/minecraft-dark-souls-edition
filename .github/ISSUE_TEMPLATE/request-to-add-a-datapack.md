---
name: Request to add a datapack
about: Request to add a new datapack to the modpack.
title: 'Add '
labels: datapack, enhancement
assignees: ''

body:
  - type: input
    id: datapack-link
    attributes:
      label: Datapack link
      description: Datapack link, preferably from Modrinth, but CurseForge is allowed if there's no Modrinth version.
      placeholder: https://modrinth.com/datapack/tectonic
    validations:
      required: true

---
