# hello-action-test

Composite action that prints the latest commit message.

## Usage

```yaml
steps:
  - uses: actions/checkout@v4
  - uses: HonzaV/hello-action-test@v1
```

The repository must be checked out first, since the action reads the commit message with `git log`.
