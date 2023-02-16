# Mela front-end Contributing Guide

We're really excited that you are interested in contributing to Mela. Please take a moment to read through our [Code of Conduct](CODE_OF_CONDUCT.md) first. All contributions (participation in discussions, issues, pull requests, ...) are welcome. Unfortunately, we cannot make commitments that issues will be resolved or pull requests will be merged swiftly, especially for new features.

## Development requirements

```sh
curl -fsSL https://deb.nodesource.com/setup_18.x | bash - &&\
apt-get install -y nodejs
sudo npm install -g npm@latest
sudo npm instlal -g yarn
```

## Development setup

```sh
# install dependencies
$ yarn install

# serve with hot reload
$ yarn dev
```

## This project has been initialized with

```sh
npx nuxi init mela_frontend
cd mela_frontend
yarn install
yarn add @nuxt/devtools -D
yarn add sass node-sass -D
yarn add bootstrap bootstrap-vue-next @popperjs/core -D
yarn add nuxt-icon -D
yarn add eslint eslint-plugin-vue @vue/eslint-config-typescript typescript @vue/eslint-config-prettier @rushstack/eslint-patch prettier -D
yarn add stylelint stylelint-config-standard-scss -D
```
