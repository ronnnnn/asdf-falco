# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test falco https://github.com/ronnnnn/asdf-falco.git "falco -V"
```

Tests are automatically run in GitHub Actions on push and PR.
