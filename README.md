# eslint-config

My [ESLint](https://eslint.org/) [shareable config](https://eslint.org/docs/developer-guide/shareable-configs) so that you can write JavaScript in the same style that I do. Check out the contents of the config file here: [eslintrc.json](./eslintrc.json)


## Installation

Install using the following `npm` command:

```shell
npm install eslint @jsejcksn/eslint-config --save-dev
```


## Usage

Add the following to your project's existing `.eslintrc.json` file:

``` json
{
  "extends": "@jsejcksn"
}
```

or, if you don't have one yet: instead of generating it using `eslint --init`, you can use

```shell
printf "{\n  \"extends\": \"@jsejcksn\"\n}\n" > .eslintrc.json
```
