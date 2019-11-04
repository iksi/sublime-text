# Sublime Text setup

Enable macOS command Line tool:

```shell
ln -sv "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sublime

```

Install package control: https://packagecontrol.io/installation

## Linter setup

Install the following packages from package control:

- SublimeLinter
- SublimeLinter-eslint

Make sure you have eslint installed globally to prevent SublimeLinter from complaining:

```shell
npm i -g eslint
```

In projects that don’t use eslint add an empty `.eslintrc` to the project’s root.

For using [standard](https://standardjs.com/) with eslint see the manual installation instructions https://github.com/standard/eslint-config-standard

