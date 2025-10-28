---
name: Feature Suggestion
about: Describe this issue template's purpose here.
title: ''
labels: enhancement
assignees: ''

---

name: Feature Request
description: Suggest new content or an improvement for the resource pack.
title: "[FEAT] Suggest: [Brief idea]"
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        Describe what you would like to see added.
  - type: textarea
    id: feature-idea
    attributes:
      label: Your Idea
      description: Describe the new content/model/feature you would like to see.
      placeholder: For example, "Add a decal model via renaming iron sheet."
    validations:
      required: true
  - type: textarea
    id: why-needed
    attributes:
      label: Why is this needed?
      description: How will this improve building options or the overall experience?
    validations:
      required: false
