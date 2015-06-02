# npm-install step

Executes the `npm install` command with leveraging the wercker cache mechanism to improve installation time.

If `npm install` fails, it will be retried three times before failing.

## Options

### options
- type: string
- optional: true
- description: Passed through to npm install
- example: `options: browserify`

## Example

```yaml
build:
    steps:
        - npm-install
```

# License

The MIT License (MIT)

# Changelog

## 1.0.0

- Add retry on error

## 0.9.3

- Fix wrong directory cache created

## 0.9.2

- Initial release
