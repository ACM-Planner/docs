# Planner 2.0 docs

Official documents and development recommendations

## Mockup

[![Precursor](https://precursorapp.com/document/Mockup-Planner2-17592204070496.svg?auth-token=)](https://precursorapp.com/document/Mockup-Planner2-17592204070496)

Get the `.pdf` version [here](./mockup.pdf).

## Development

### Requirements

* [Node.js 6](https://nodejs.org/en/)
* [Python 3](https://www.python.org/)

### Dependencies

```sh
pip install -U autopep8 flake8 pep8
```

```sh
npm install -g babel-eslint eslint eslint-plugin-flowtype eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react htmlhint jsonlint nodemon tern
```

### IDE

The usage of Atom as the main IDE is recommended, along with these plugging:

```sh
# Common
autoclose-html
highlight-line
highlight-selected
indent-guide-improved
trailing-spaces
sublime-style-column-selection
editorconfig
autocomplete-paths
file-icons
pigments
atom-beautify
linter

# Python
autocomplete-python
linter-flake8
linter-pep8

# Javascript
atom-ternjs
linter-eslint
linter-jsonlint
linter-csslint
language-babel
turbo-javascript
```

Install all with:

```sh
apm install autoclose-html highlight-line highlight-selected indent-guide-improved trailing-spaces sublime-style-column-selection editorconfig autocomplete-paths file-icons pigments atom-beautify linter autocomplete-python linter-flake8 linter-pep8 atom-ternjs linter-eslint linter-jsonlint linter-csslint language-babel turbo-javascript

```
