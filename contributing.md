# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test betterleaks https://github.com/panz3r/asdf-betterleaks.git "betterleaks --help"
```

Tests are automatically run in GitHub Actions on push and PR.
