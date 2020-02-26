# template-extension
Web extension template

## what this?

this repo is just a web extension template
power by parcel

## installation

```sh
# clone this repo
git clone git@github.com:ddo/template-extension.git
cd template-extension

# remove git
rm -r .git

# install dependencies
yarn
```

Then update the ``package.json`` and ``src/manifest.json`` file

## dev

```sh
yarn watch
```

Then load unpacked the folder ``dist/`` in ``chrome://extensions/``

## build

```sh
yarn build
```

Then deploy the ``dist/``
