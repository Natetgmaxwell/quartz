---
{"publish":true,"created":"2025-09-08T18:03:11.000+10:00","modified":"2025-09-13T11:21:43.000+10:00","published":"2025-09-13T11:21:43.000+10:00","cssclasses":"","aliases":null,"tags":null,"dg-publish":true,"---\n# Blood Loss\n\n> [!ontology]\n> up":"[[Cards/Blood]]"}
---

# Blood Loss

> [!ontology]
> up:: [[Blood]]
> jump:: 
> down:: 

> [!Definition] Definition

# Reference

- 

## Mentions

```base
views:
  - type: table
    name: Default view
    order:
      - file.link
    sort:
      - column: file.name
        direction: asc
    filters:
      and:
        - file.hasLink([[Blood Loss]])
        - not:
            - file.hasTag("source")
        - not:
            - file.hasLink("Blood Loss")
        - not:
            - file.inFolder("Extras")
display:
  file.link: Incoming Links

```

```base
properties:
  file.link:
    displayName: Outgoing Links
views:
  - type: table
    name: Default view
    filters:
      and:
        - file.hasLink("")
        - not:
            - file.hasTag("source")
        - file.name != this.file.name
    order:
      - file.link
    sort: []

```

| Sources |
| ------- |


## Flashcards