Atom Editor packages list files for batch(bulk) installed packages easily.

[Chinese Readme 中文解說](README_zh.md)

## How to use:

Use command line `apm` tool. Change the `package-list-file.txt` to general.txt/react.txt/rn.txt/sass.txt/md.txt/php.txt below.

> apm install --packages-file package-list-file.txt

## Test:

- Mac OS X ✅
- Windows(10) ✅

### HTML/CSS/JS/Git

!! Basic usage, install this first.

- general.txt

### SASS(SCSS)

- sass.txt

### React

- react.txt

### React Native

- rn.txt

### Markdown

- md.txt

### PHP Development

!! To install php in your computer first.

- php.txt

### Chinese Language Menu

- cht.txt

## Note

Your computer need over 400MB space and it cost you 15~30 mins to install all packages above.

- atom-ternjs: if it isn't worked, downgrade to 0.14.2 version.
- [sync-settings](https://atom.io/packages/sync-settings): for backup settings. You need a github account
- [nuclide](https://atom.io/packages/nuclide): contains many extensions. (!!NOTE: some features are NOT supported Windows)

## Changlog

### 161001

- add nuclide.txt
- rename web.txt to general.txt

### 160930

- remove all verion annotation, apm now will install the latest version of packages.
- add sass.txt and rn.txt.
- add some packages for web and markdown usage.
