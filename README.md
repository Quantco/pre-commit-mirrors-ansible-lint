# ansible-lint pre-commit hook

pre-commit hook of ansible-lint with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For ansible-lint: see [here](https://github.com/ansible/ansible-lint)

## Using ansible-lint with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-ansible-lint
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: ansible-lint-conda
```
