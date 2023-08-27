# workspace

## Prerequisites

- fvm
- melos

```sh
dart pub global activate very_good_cli
```

## Getting start

```bash
fvm install
melos bs
```

## Manage fvm version on all sub-modules

`melos exec -- "fvm use 3.10.6"`
`melos exec -- "fvm install"`

## Maintain dependency

```sh
# check dependencies per package
dart pub outdated --no-dev-dependencies --up-to-date --no-dependency-overrides
# upgrade all packages
melos exec -- "flutter pub upgrade --major-versions"
```

## Create packages

[ref](https://pub.dev/packages/very_good_cli)
