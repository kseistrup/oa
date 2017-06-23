# OpenAlias

OpenAlias related convenience scripts

## mkoa

Easily construct openaliases.

```
Usage: mkoa [OPTIONS] ADDRESS

positional arguments:
  ADDRESS               recipient address

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show version information and exit
  --copyright           show copying policy and exit
  -n NAME, --name NAME  name of recipient
  -d DESCRIPTION, --description DESCRIPTION
                        transaction description
  -c CURRENCY, --currency CURRENCY
                        currency (default: BTC)
  -a AMOUNT, --amount AMOUNT
                        transaction amount
  -i ID, --id ID        payment id

Caveat: None of the arguments are checked for validity.
```

### Examples

```sh
$ mkoa -n 'mkoa support' 1Mkoabrd5htXBQsUn9Fa82n8G6YsKp4RaL
oa1:btc recipient_address=1Mkoabrd5htXBQsUn9Fa82n8G6YsKp4RaL; recipient_name=mkoa support;
```

:smile:
