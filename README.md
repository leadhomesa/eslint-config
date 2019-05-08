# This has not been released on NPM yet.

# eslint-config-leadhome
> ESLint [shareable config](https://github.com/leadhomesa/eslint-config)

A shareable configuration package for [eslint](http://eslint.org).

## Installation

To use this config, install [@leadhome/eslint-config](https://github.com/leadhomesa/eslint-config) as a development dependecy of your project:

```sh
npm install @leadhome/eslint-config --save-dev
```

Next, add this configuration to your `package.json`:

```json
{
    "eslintConfig": {
        "extends": "@leadhome/eslint-config"
    }
}
```

Or add a .eslintrc file to your project root containing: 
```json
{
    "extends": "@leadhome/eslint-config"
}
```