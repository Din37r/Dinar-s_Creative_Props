---
name: Bug Report
about: Describe this issue template's purpose here.
title: ''
labels: bug
assignees: ''

---

name: Bug Report
description: Report a bug or issue with the resource pack.
title: "[BUG] Describe the issue"
labels: ["bug", "triage"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for helping us improve the resource pack!
  - type: textarea
    id: bug-description
    attributes:
      label: Bug Description
      description: A clear description of what the bug is.
      placeholder: For example, "Big Pile of Blue Bricks is not showing up when renaming Blue Bricks on an anvil."
    validations:
      required: true
  - type: textarea
    id: steps-to-reproduce
    attributes:
      label: Steps to Reproduce
      description: Please describe the steps to reproduce the bug, step by step.
      placeholder: |
        1. Take item X.
        2. Rename it to Y.
        3. Result: (describe what went wrong)
    validations:
      required: true
  - type: input
    id: game-version
    attributes:
      label: Minecraft Version
      description: What version of the game are you experiencing the issue on (e.g., 1.20.1)?
      placeholder: 1.20.1
    validations:
      required: true
