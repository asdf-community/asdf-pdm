# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test pdm https://github.com/1oglop1/asdf-pdm.git "pdm --version"
```

Tests are automatically run in GitHub Actions on push and PR.
