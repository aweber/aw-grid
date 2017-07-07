# AWeber FlexBox Grid
AWeber FlexBox Grid is a responsive modern grid system for creating structured layouts in both websites and web applications. Based on flexbox properties, it is a customized version of the infamous [Flexbox Grid](http://flexboxgrid.com/) and uses SCSS as a preprocessor language to facilitate development and maintenance.

## Installation
### npm
TBD…

### Bower
TBD…

### Production CSS | CDN
TBD…

## Development
* Fork and clone the **AWeber FlexBox Grid** repository.
* Install the project's dependencies.
* Create a branch for your changes using [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/).
* Make your changes and document them using the [SASSDoc](http://sassdoc.com/) guidelines.
* Lint your changes before opening a PR.
* Open a PR comparing your branch with the `develop` branch as the base.

### Install dependencies
Install [Yarn](https://yarnpkg.com/) package manager before working on the project.
```bash
yarn
```

### Build documentation
Use [SASSDoc](http://sassdoc.com/) to build the project’s documentation. _Not required to open a PR_.
```bash
yarn docs
```

### Lint code changes
Lint your changes before opening a PR. If you don't, the Continuous Integration (CI) service won't allow your PR to be merged.
```bash
yarn lint
```

### Build distribution files
Check the production output files, if needed.
```bash
yarn dist
```
