# `phpenv-config-add`

It's a [phpenv/phpenv](https://github.com/hisayan/phpenv) plugin to enable/disable configs.

## Installation

Simply clone the repository into the plugins directory:

```sh
mkdir -p "$(phpenv root)/plugins"
git clone git://github.com/sergeyklay/phpenv-config-add.git "$(phpenv root)/plugins/phpenv-config-add"
```

## Usage

```sh
phpenv config-add /path/to/config.ini
phpenv config-rm config.ini || true
```

## License

The `phpenv-config-add` is released under the [MIT License](https://github.com/sergeyklay/phpenv-config-add/blob/master/LICENSE).
