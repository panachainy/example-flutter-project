# workspace

## Prerequisites

- fvm
- melos

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
melos exec -- "flutter pub upgrade --major-versions"
```
