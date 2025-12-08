# .github

***
## For Repository Maintainers

### Contribution License Agreement

This organization uses a centralized reusable GitHub Actions workflow to verify whether contributors have signed the required Contribution License Agreement (CLA). The workflow lives in this **.github** repository and can be invoked by any repository that opts in.

#### Opt-In by adding the Caller Workflow to your repository


1. Create the workflow file in the repository's root directory:

``` shell
cd /path/to/repository/
touch .github/workflows/cla.yml
```

2. Paste the workflow code below inside the `cla.yml` file:

```yml
---
name: CLA Workflow

permissions:
  contents: write
  checks: write
  actions: write
  pull-requests: write

on:
  pull_request:
    types: [opened, reopened, synchronize]
  branches:
    - main
    - master

jobs:
  cla:
    uses: clima/.github/.github/workflows/cla_template.yml@main
      secrets: inherit
```
