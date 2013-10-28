# npm-install step

Executes the `npm install` command with leveraging the wercker cache mechanism to improve installation time.

## Options

### options
- type: string
- optional: true
- description: Passed through to npm install
- example: `options: -g bower`

## Example

    - npm-install
    
# What's new

- Fix wrong directory cache created


# License

The MIT License (MIT)

# Changelog

## 0.9.3

- Fix wrong directory cache created

## 0.9.2

- Initial release
