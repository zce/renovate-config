# @zce/renovate-config

> My personal [renovate](https://renovate.whitesourcesoftware.com/) config preset.

## Usage

`package.json` within a `renovate` section:

```json
{
  "renovate": {
    "extends": [
      "github>zce/renovate-config"
    ]
  }
}
```

Or in the project root directory or `.github` directory `renovate.json`:

```json
{
  "extends": [
    "github>zce/renovate-config"
  ]
}
```

## Renovate

- [Renovate Docs](https://docs.renovatebot.com/)

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](license) &copy; [汪磊](https://zce.me)
