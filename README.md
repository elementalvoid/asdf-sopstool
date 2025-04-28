# asdf-sopstool

[![GitHub license](https://img.shields.io/github/license/elementalvoid/asdf-sopstool?style=plastic)](https://github.com/elementalvoid/asdf-sopstool/blob/master/LICENSE)

## sopstool EOL

Please note, this project is no longer maintained. `sopstool`
[was EOL'd](https://github.com/Ibotta/sopstool/pull/81) so the `asdf`
plugin is now as well.

The [sops](https://getsops.io/) program itself has added a number of features
that make this project redundant, and usage of the tool has largely
migrated to using AWS Secrets Manager or AWS Parameter Store. This
project is archived, and will not be updated.

Installations via the plugin will continue to work, but no new
changes will be made.

The last release of sopstool was [1.2.1](https://github.com/Ibotta/sopstool/releases/tag/v1.2.1).

[sopstool](https://github.com/ibotta/sopstool) plugin for
[asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add sopstool https://github.com/elementalvoid/asdf-sopstool.git
```

## Use

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions
on how to install and manage versions of sopstool.
