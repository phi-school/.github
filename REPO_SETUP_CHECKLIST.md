# Repository Settings Checklist

## 1. General

- [ ] Repository name is clear, concise, and follows the naming conventions.
- [ ] Description is filled out, giving a quick overview of the project.
- [ ] README is present, properly formatted, and informative.
- [ ] The default branch is set to `main`.
- [ ] An image is provided for Social Preview (optional).
- [ ] Issue templates are set up.
  - [ ] Bug issue template.
  - [ ] Feature request issue template.
- [ ] Allow squash merging is enabled.
  - [ ] Default message is set to pull request title.
  - [ ] Allow merge commits is disabled.
  - [ ] Allow rebase merging is disabled.
- [ ] Automatically delete head branches.

## 2. Branch protection rules

- [ ] Branch protection is enabled for `main`.
- [ ] Require a pull request before merging.
- [ ] Require status checks to pass before merging is enabled.
  - [ ] Require branches to be up to date before merging.
  - [ ] Specify the status checks that are required to pass.
- [ ] Require linear history.

## 3. Code security and analysis

- [ ] Private vulnerability reporting is enabled.
- [ ] Dependabot alerts are enabled.
- [ ] Dependabot security updates are enabled.
- [ ] Code scanning with CodeQL analysis is enabled.

## 4. Collaborators and Teams

- [ ] Correct teams have been granted the right access levels.

## 5. Secrets and Variables

- [ ] Relevant repository or organization level secrets are set up, like `NPM_TOKEN`.

## 6. GitHub Actions

- [ ] Workflows for CI/CD are set up and running correctly.
- [ ] Workflow permissions are properly configured.
  - [ ] Read and write permissions.
  - [ ] Allow GitHub Actions to create and approve pull requests.

## 7. GitHub Apps

- [ ] Relevant GitHub Apps are installed and properly configured.

## 8. Community

- [ ] Code of Conduct is present.
- [ ] Contributing guide is present.
- [ ] Pull request template is set up.

## 8. Sponsorship (Optional)

- [ ] Sponsorship options are set up if the project is open source.
