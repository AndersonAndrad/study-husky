<h1 align="center">Welcome to Study-husky 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-0.0.1-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: mit" src="https://img.shields.io/badge/License-mit-yellow.svg" />
  </a>
</p>




## Summary

- [Why this project](#why-this-project)
- [Why I used these technologies](#why-i-used-these-technologies)
- [How to use](#how-to-use)
- [👤 Authors](#👤-Authors)

---------------------------------------

## Why this project

I created this project to understand how it works and the implementation of technologies, husky, commitlint end commitizen.

## Why I used these technologies

I used these technologies to make it easier to work with commits within projects.

## How to use

this project is just for example, but if you want you can clone it to test it on your machine.

### install

```sh
yarn install
```

### usage

```sh
git commit
```

## How to configure in other projects

install the following dependencies

```bash
yarn add husky @commitlint/config-conventional @commitlint/cli commitizen
```

run this command on your terminal

```bash
echo "module.exports = {extends: ['@commitlint/config-conventional']}" > commitlint.config.js
```

run this command on your terminal

```bash
commitizen init cz-conventional-changelog --yarn --dev --exact
```

copy and paste into your package.json

```
 "husky": {
    "hooks": {
      "commit-msg": "commitlint -E HUSKY_GIT_PARAMS",
      "prepare-commit-msg": "exec < /dev/tty && git cz --hook || true"
    }
  }
```

## All  links used to generate the documentation

[Husky](https://github.com/typicode/husky)

[commitlint](https://github.com/conventional-changelog/commitlint)

[commitizen](https://github.com/commitizen/cz-cli)

-----------------------

## 👤 Authors

|                                                              |
| :----------------------------------------------------------- |
| Github: [@AndersonAndrad](https://github.com/AndersonAndrad) |
| LinkedIn: [@AndersonAndrad](https://linkedin.com/in/AndersonAndrad) |
| <img src="https://avatars0.githubusercontent.com/u/31743641?s=400&u=b6d9e1c428279846440325b0fae90f4b9c4d1d98&v=4" width="110"> |

--------------

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/AndersonAndrad/nest-socketio/issues). 

------------------------------

## Show your support

Give a ⭐️ if this project helped you!