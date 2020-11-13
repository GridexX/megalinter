<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- Generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/nvuillam/mega-linter/tree/master/megalinter/descriptors/env.yml -->
# ENV

## Linted files

- File extensions:
  - `.env`

## Mega-linter configuration

| Variable | Description | Default value |
| ----------------- | -------------- | -------------- |
| ENV_FILTER_REGEX_INCLUDE | Custom regex including filter |  |
| ENV_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |  |

## Linters

| Linter | Configuration key |
| ------ | ----------------- |
| [dotenv-linter](env_dotenv_linter.md) | [ENV](env_dotenv_linter.md) |