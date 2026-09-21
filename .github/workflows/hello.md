---
on:
  workflow_dispatch:
permissions:
  contents: read
engine: copilot
safe-outputs:
  create-issue:
    title-prefix: "[hello] "
    max: 1
---

# Hello World

Write a friendly one-paragraph greeting to this repository's contributors.
Create an issue containing the greeting.