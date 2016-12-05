# echint-config-dev <a href="https://github.com/editorconfig/editorconfig"><img src="https://rawgit.com/ctate/editorconfig/master/.autocode/icon.svg" alt="EditorConfig Logo" width="90" height="90" align="right"></a>

[![NPM Version][npm-img]][npm-url]
[![Build Status][cli-img]][cli-url]
[![Licensing][lic-image]][lic-url]

[echint-config-dev] is a shareable configuration package for [editorconfig].

## Install

Add [echint] and [echint-config-dev] to your project:

```sh
npm install --save-dev echint echint-config-dev
```

Then, add this configuration to your `package.json`:

```json
{
  "echint": {
    "extends": "dev"
  }
}
```

[npm-url]: https://www.npmjs.com/package/echint-config-dev
[npm-img]: https://img.shields.io/npm/v/echint-config-dev.svg
[cli-url]: https://travis-ci.org/jonathantneal/echint-config-dev
[cli-img]: https://img.shields.io/travis/jonathantneal/echint-config-dev.svg
[lic-url]: LICENSE.md
[lic-image]: https://img.shields.io/npm/l/echint-config-dev.svg
[log-url]: CHANGELOG.md
[log-image]: https://img.shields.io/badge/changelog-md-blue.svg
[git-url]: https://gitter.im/postcss/postcss
[git-image]: https://img.shields.io/badge/chat-gitter-blue.svg

[echint]: https://github.com/ahmadnassri/echint
[echint-config-dev]: https://github.com/jonathantneal/echint-config-dev
[editorconfig]: http://editorconfig.org/
