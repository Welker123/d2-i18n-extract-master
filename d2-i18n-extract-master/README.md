Extract i18n.t translation strings from DHIS2 frontend apps

## Install

```bash
$> yarn add @dhis2/d2-i18n-extract
```

## Example

```bash
$> d2-i18n-extract -p ./src/ -o ./i18n/
```

## Usage
```
d2-i18n-extract [-h] [-v] [-p PATH] [-o OUTPUT]

Optional arguments:
  -h, --help            Show this help message and exit.
  -v, --version         Show program's version number and exit.
  -p PATH, --path PATH  directory path to recurse and extract i18n.t 
                        translation strings
  -o OUTPUT, --output OUTPUT
                        destination path for en.pot file.
```
