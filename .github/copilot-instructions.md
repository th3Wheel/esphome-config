# GitHub Copilot Instructions

## Commit Messages

- Follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification for commit messages.
- Use the following format: `<type>[optional scope]: <description>`.
- Include a reference to the issue number in the commit message (e.g., `#123`), if applicable.
- Use the following types:
  - `feat`: A new feature.
  - `fix`: A bug fix.
  - `docs`: Documentation only changes.
  - `style`: Changes that do not affect the meaning of the code (e.g., white-space, formatting, missing semi-colons, etc.).
  - `refactor`: A code change that neither fixes a bug nor adds a feature.
  - `perf`: A code change that improves performance.
  - `test`: Adding missing tests or correcting existing tests.
  - `chore`: Changes to the build process or auxiliary tools and libraries such as documentation generation.
  - `ci`: Changes to the CI configuration files and scripts.
  - `build`: Changes that affect the build system or external dependencies.
  - `revert`: Reverts a previous commit.
  - `wip`: Work in progress.
- Use the following scopes:
  - `core`: Core functionality.
  - `config`: Configuration files.
  - `docs`: Documentation.
  - `test`: Tests.
  - `ci`: Continuous integration.
  - `build`: Build system.
  - `deps`: Dependencies.
  - `refactor`: Refactoring.
  - `style`: Code style.
  - `perf`: Performance.
  - `fix`: Bug fixes.
  - `feat`: New features.
  - `chore`: Chores.
  - `revert`: Reverts.
  - `wip`: Work in progress.  
- Examples:
  - `feat(core): add new feature`
  - `fix(core): fix issue with feature`
  - `docs(core): update documentation`
  - `style(core): format code`
  - `refactor(core): refactor code`
  - `perf(core): improve performance`
  - `test(core): add tests`
  - `chore(core): update build process`
  - `ci(core): update CI configuration`
  - `build(core): update build system`
  - `revert(core): revert previous commit`
  - `wip(core): work in progress` 
- include a list of files affected by the commit in the body of the commit message.

## Code Style

- Use underscores for field names (e.g., `field_name`).

## Formatting

- Ensure code is formatted according to the project's `.editorconfig` and `.prettierrc` settings.
- Enable `formatOnSave` and `formatOnPaste` in the editor settings.

## Python

- Use the specified Python interpreter path: `path/to/your/python`.
- Include pylint arguments: `--load-plugins pylint_homeassistant`.

## YAML

- Associate `*.yaml` files with `home-assistant`.
- Use the specified YAML schemas for validation:
  - Ansible Playbook: `https://json.schemastore.org/ansible-playbook.json`
  - GitHub Workflow: `https://json.schemastore.org/github-workflow.json`
  - GitHub Action: `https://json.schemastore.org/github-action.json`

## Extensions

- Recommended extensions:
  - `esbenp.prettier-vscode`
  - `ms-python.python`
  - `redhat.vscode-yaml`
  - `keesschollaart.vscode-home-assistant`
  - `esphome.esphome-vscode`
  - `vscode-icons-team.vscode-icons`
  - `EditorConfig.EditorConfig`
  - `GitHub.vscode-pull-request-github`
  - `ellacrity.recoil`
  - `wholroyd.jinja`

## Additional Notes

- Follow any additional instructions provided in the `.copilot-instructions.md` file.
- Use instruction files for code generation when specified.
