name: Call Reusable Workflow

on:
  push:

jobs:
  call-reusable:
    uses: ./.github/workflows/reusable.yml
