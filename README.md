# ct-gha-common-workflows
Repository for GitHub Actions workflows commonly used at Cloudticity

## Available Workflows
This is the list of currently available reusable workflows and their inputs.

### bump_version
This workflow uses the `paulhatch/semantic-version@v4.0.2` GitHub action to carry out semantic versioning tracking.

#### Inputs
| Input                | Type    | Description                                                                                  |
|----------------------|---------|----------------------------------------------------------------------------------------------|
| bump_on_every_commit | boolean | This flag controls whether or not the action will track a new version on every commit or not |
