---
on:
  schedule: daily
  workflow_dispatch:
permissions:
  contents: read
engine: copilot
tools:
  github:
    toolsets: [repos]
safe-outputs:
  create-issue:
    title-prefix: "[hello] "
    max: 1
---

# Hello World

Look at the most recent 5 commits in this repository.
Write a short, friendly summary of what changed and create an issue with it