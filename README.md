# renovate-config-zce

[![NPM Downloads][downloads-img]][downloads-url]
[![NPM Version][version-img]][version-url]
[![License][license-img]][license-url]
[![Dependency Status][dependency-img]][dependency-url]
[![devDependency Status][devdependency-img]][devdependency-url]
[![Code Style][style-img]][style-url]

> My personal [renovate](https://renovate.whitesourcesoftware.com/) config preset.

## Usage

`package.json` within a `renovate` section:

```json
{
  "renovate": {
    "extends": [
      "zce"
    ]
  }
}
```

Or in the project root directory `renovate.json`:

```json
{
  "extends": [
    "zce"
  ]
}
```

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [汪磊](https://zce.me)



[downloads-img]: https://img.shields.io/npm/dm/renovate-config-zce.svg
[downloads-url]: https://npmjs.org/package/renovate-config-zce
[version-img]: https://img.shields.io/npm/v/renovate-config-zce.svg
[version-url]: https://npmjs.org/package/renovate-config-zce
[license-img]: https://img.shields.io/github/license/zce/renovate-config-zce.svg
[license-url]: https://github.com/zce/renovate-config-zce/blob/master/LICENSE
[dependency-img]: https://img.shields.io/david/zce/renovate-config-zce.svg
[dependency-url]: https://david-dm.org/zce/renovate-config-zce
[devdependency-img]: https://img.shields.io/david/dev/zce/renovate-config-zce.svg
[devdependency-url]: https://david-dm.org/zce/renovate-config-zce?type=dev
[style-img]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[style-url]: https://standardjs.com
