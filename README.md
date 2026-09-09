# ARURA GitHub templates

Shared issue and pull request templates for ARURA-AB repositories.

## Templates

| File | Purpose |
| --- | --- |
| [Task form](.github/ISSUE_TEMPLATE/task.yml) | Separate required fields for summary, scope, acceptance criteria, test plan, and risk assessment, with starter lists and a risk-level prompt. |
| [Bug report form](.github/ISSUE_TEMPLATE/bug.yml) | Collects the problem, reproduction steps, and expected behavior. |
| [Issue configuration](.github/ISSUE_TEMPLATE/config.yml) | Disables blank issues in the issue chooser. |
| [Pull request template](.github/pull_request_template.md) | Prompts for a summary, related issue, changes, validation, risks, deployment details, and review checks. |

## Using the defaults

GitHub applies these defaults to ARURA-AB repositories that do not define their own templates of the corresponding type. This `.github` repository must be public for organization defaults to apply. A repository with its own valid issue templates or issue template configuration overrides the entire default issue-template folder.

The issue forms use the `task` and `bug` labels. Create these labels in this repository and in repositories using the forms.

See GitHub's [default community health file documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) for inheritance details.

Task issues default to the [ARURA project](https://github.com/orgs/ARURA-AB/projects/1). GitHub requires the person opening the issue to have write access to that project for automatic assignment through the template. See [issue form syntax](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms).

The prefilled `Risk level:` text is not synchronized with sidebar or project fields. All task fields remain required, but starter text does not enforce a substantive answer.

## Updating templates

Edit issue forms in `.github/ISSUE_TEMPLATE/` and the pull request template in `.github/pull_request_template.md`. Manage classification through GitHub’s issue sidebar instead of adding fields to the task form. Labels and issue types use repository and organization settings; custom issue fields such as risk level must be configured at the organization level. Issue templates cannot define or set custom sidebar fields. See [GitHub’s issue field documentation](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/adding-and-managing-issue-fields). Changes on the default branch apply to newly created issues and pull requests that use these templates.
