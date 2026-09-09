# ARURA GitHub templates

Shared issue and pull request templates for ARURA-AB repositories.

## Templates

| File | Purpose |
| --- | --- |
| [Task form](.github/ISSUE_TEMPLATE/task.yml) | One Markdown text area for summary, scope, acceptance criteria, test plan, and risk assessment, followed by work type and risk level dropdowns and component checkboxes. |
| [Bug report form](.github/ISSUE_TEMPLATE/bug.yml) | Collects the problem, reproduction steps, and expected behavior. |
| [Issue configuration](.github/ISSUE_TEMPLATE/config.yml) | Disables blank issues in the issue chooser. |
| [Pull request template](.github/pull_request_template.md) | Prompts for a summary, related issue, changes, validation, risks, deployment details, and review checks. |

## Using the defaults

GitHub applies these defaults to ARURA-AB repositories that do not define their own templates of the corresponding type. This `.github` repository must be public for organization defaults to apply. A repository with its own valid issue templates or issue template configuration overrides the entire default issue-template folder.

The issue forms use the `task` and `bug` labels. Create these labels in this repository and in repositories using the forms.

See GitHub's [default community health file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for inheritance details.

## Updating templates

Edit issue forms in `.github/ISSUE_TEMPLATE/` and the pull request template in `.github/pull_request_template.md`. Keep task classification controls outside the task's Markdown text area. Changes on the default branch apply to newly created issues and pull requests that use these templates.
