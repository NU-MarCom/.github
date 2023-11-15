# Northeastern University External Affairs
## Marketing Communications Team
- [https://brand.northeastern.edu/](https://brand.northeastern.edu/)

This organization contains repositories for the following projects:
- NU Start Framework (Parent and Child Themes)
- GitHub Actions reusable workflows
- GitHub Actions starter workflows

## GitHub Action Workflows
### Starter Workflows
Starter Workflows are default workflows that can be selected when creating a new repository. Utilize these when creating new sites for WP Engine so that you have a common deployment workflow for projects/repositories. These workflows are located under `workflow-templates` in the `.github` repository. There you'll find starter templates that can call reusable templates at an organization, enterprise, and public level.

### Reusable Workflows
Reusable Workflows can be found in the `github-actions-templates` repository. These are intended to be called from a Starter or Repository Workflow. This is where most of the integration or logic for deployments and builds are located. Starter Workflows can easily call a Reusable Workflow at the job level, allowing for jobs to be dependent on each other (e.g., build dependencies first, then deploy if successful).