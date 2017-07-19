# Problem statement
validates an opspec package

# Example usage

> note: in examples, VERSION represents a version of the opspec.pkg.validate pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/opspec.pkg.validate#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/opspec.pkg.validate#VERSION
```

## compose

```yaml
op:
  pkg: { ref: github.com/opspec-pkgs/opspec.pkg.validate#VERSION }
  inputs:
    pkg:
```


# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/opspec.pkg.validate/issues)
