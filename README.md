# next-i18next-auto-google-translate

This package will look at your default translation file and generate
any other specified translation file requested by default only looking
up missing keys.

The end goal being you only ever need
to manage a single language translation set.

It is highly recommended to typically have any existing translation files committed
before running.

## Usage

```bash
yarn add -D next-i18next-auto-translate
```

```json
{
  "scripts": {
    "translate": "next-i18next-auto-translate"
  }
}
```
