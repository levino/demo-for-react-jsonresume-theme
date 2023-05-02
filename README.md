# How to use `jsonresume-theme-stackoverflow-react`

Before you start please use `yarn` to install the dependencies:

```
$ yarn
```

## Default (using English theme)

You can just use the default English version of the theme like so:

```
yarn resume serve -t jsonresume-theme-stackoverflow-react -r resume.en.json
```

## i18n (German and English)

As you can see in this repo, `jsonresume-theme-stackoverflow-react` also exports a German template and you can see in the `scripts` section of the [`package.json`](./package.json) how it can be used:

```json
{
  "scripts": {
    "build:de": "yarn resume export -r resume.de.json -t ./node_modules/jsonresume-theme-stackoverflow-react/dist/de CV.pdf",
    "dev:de": "yarn resume serve -r resume.de.json -t ./node_modules/jsonresume-theme-stackoverflow-react/dist/de",
    "build:en": "yarn resume export -r resume.en.json -t ./node_modules/jsonresume-theme-stackoverflow-react/dist/en CV.pdf",
    "dev:en": "yarn resume serve -r resume.en.json -t ./node_modules/jsonresume-theme-stackoverflow-react/dist/en"
  }
}
```

### Remarks

I made [`jsonresume-theme-stackoverflow-react`](https://www.npmjs.com/package/jsonresume-theme-stackoverflow-react) since I need to output a German CV in some cases. My package is a fork of [`jsonresume-theme-stackoverflow`](https://www.npmjs.com/package/jsonresume-theme-stackoverflow) which has a nice design. Maybe the people from this package will merge my changes in and then I will discontinue my fork. Please double check.

The CVs of Samantha Jones were made up / translated for me by ChatGPT.
