# mcaf-github-workflows

Repository for centralized reusable Github workflows.

## Create workflows

Create or modify a yaml file in [.github/workflows/](.github/workflows/). Also update README.md with details about your workflow and remember that this is a public repository.

Push your changes to a branch. Once you are done with all your changes, open a PR.

## Workflows

### PR Validation

Verifies the PR has the required labels and proper title set.

### Release Drafter

Creates a drafted release based on the labels, title and description of the PR.

### Terraform Validation

Verifies the terraform code adheres to best practises and has secure defaults set.

### Update changelog

Updates the CHANGELOG.md when a release gets published.
