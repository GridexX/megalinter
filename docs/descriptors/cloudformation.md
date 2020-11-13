<!-- markdownlint-disable MD003 MD020 MD033 MD041 -->
<!-- Generated by .automation/build.py, please do not update manually -->
<!-- Instead, update descriptor file at https://github.com/nvuillam/mega-linter/tree/master/megalinter/descriptors/cloudformation.yml -->
# CLOUDFORMATION

## Linted files

- File extensions:
  - `.yml`
  - `.yaml`
  - `.json`

- Detected file content:
  - `AWSTemplateFormatVersion`
  - `(AWS|Alexa|Custom)::`

## Mega-linter configuration

| Variable | Description | Default value |
| ----------------- | -------------- | -------------- |
| CLOUDFORMATION_FILTER_REGEX_INCLUDE | Custom regex including filter |  |
| CLOUDFORMATION_FILTER_REGEX_EXCLUDE | Custom regex excluding filter |  |

## Linters

| Linter | Configuration key |
| ------ | ----------------- |
| [cfn-lint](cloudformation_cfn_lint.md) | [CLOUDFORMATION](cloudformation_cfn_lint.md) |