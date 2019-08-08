pre-commit-prototool
====================

[uber/prototool](https://github.com/uber/prototool) hooks for https://pre-commit.com

Usage
-----

Choose one of `prototool-lint`,`prototool-format` or `prototool-format-fix` and add it to your`.pre-commit-config.yaml` as follows.

```yaml
- repo: git@github.com:nametake/pre-commit-prototool.git
  rev: master
  hooks:
    - id: prototool-format-fix
```

Available hooks
---------------

-	`prototool-lint` - Runs `prototool lint`
-	`prototool-format` - Runs `prototool format`
-	`prototool-format-fix` - Runs `prototool format` with `--fix` option
