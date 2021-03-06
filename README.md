# eslint-config-leadhome

A shareable configuration package for [eslint](http://eslint.org).

## Installation

To use this config, install [@leadhome/eslint-config](https://github.com/leadhomesa/eslint-config) as a development dependency of your project:
```sh
npm install @leadhome/eslint-config --save-dev
```

Next, add this configuration to your `package.json`:
```json
{
    "eslintConfig": {
        "extends": "@leadhome/eslint-config"
    },
    "prettier": "@leadhome/eslint-config/.prettierrc.json"
}
```

Or add a .eslintrc file to your project root containing: 
```json
{
    "extends": "@leadhome/eslint-config"
}
```

Then, add the following to your `package.json`:
```json
{
  "prettier": "@leadhome/eslint-config/.prettierrc.json"
}
```

License
-------

@leadhome/eslint-config is © 2020 Leadhome Pty Ltd.
It is free software, and may be redistributed under the terms specified in the [LICENSE](LICENSE) file.

Maintained by
----------------

[![logo](https://i.imgur.com/QH4yUje.png)](https://leadhome.co.za?utm_source=github)

@leadhome/eslint-config was created and is maintained by Leadhome Pty Ltd.<br />
The names and logos for Leadhome are trademarks of Leadhome Pty Ltd.

PS - If you're looking for a great company to work for, we're hiring! Head over to our [careers page]() to find out more and apply.
