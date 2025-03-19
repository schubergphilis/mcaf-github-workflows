# mcaf-github-workflows

Repository to synchronize GitHub workflows and repository files.

## Adding Repositories

To add your repository to the sync:

- Add your repository to  `REPOSITORIES` in the YAML file: `.github/workflows/workflow-synchronization.yaml`.

## Updating & Creating Workflows

To create or modify a workflow:

- Add or update a YAML file in the [`.github/workflows/`](.github/workflows/) directory.
- Update the `README.md` with details about your workflow.
- Ensure that your changes align with best practices and repository conventions.
- Push your changes to a branch and open a Pull Request (PR) once all modifications are complete.

## Workflows

### Label Synchronization

Ensures that the repository contains the required GitHub labels.

### PR Validation

Verifies that a PR has the required labels and a properly formatted title before merging.

### Release Drafter

Automatically drafts a release based on PR labels, title, and description, simplifying the release process.

### Terraform Validation

Validates Terraform code to ensure adherence to best practices and security standards.

### Changelog Update

Automatically updates `CHANGELOG.md` when a new release is published, keeping version history up to date.

## Repository Files

### `.gitignore`

Maintains consistency with our module structure and pre-commit setup.
_Note: OS-specific or IDE-specific ignores are excluded; users should configure these in their global `.gitignore` file._

### `LICENSE`

Ensures that all repositories include the Apache License Version 2.0 for open-source compliance.

### `CONTRIBUTING.md`

Provides clear guidelines on how to contribute, ensuring a structured and efficient collaboration process.

### `.pre-commit-config.yaml`

Includes a pre-commit configuration to streamline local development by catching simple issues before creating a PR.

### Pull Request Template

Standardizes PR submissions by guiding contributors to provide essential details, improving the review process.

### Issue Templates

Defines structured templates for bug reports, feature requests, and general questions to ensure clear and complete issue descriptions.
