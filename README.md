# AWeber FlexBox Grid
AWeber FlexBox Grid is a responsive modern grid system for creating structured layouts in both websites and web applications. Based on flexbox properties, it is a customized version of the infamous [Flexbox Grid](http://flexboxgrid.com/) and uses SCSS as a preprocessor language to facilitate development and maintenance.

## Installation
### npm
```bash
npm install @aweber/aw-grid --save-dev
```

### Bower
```bash
bower install aw-grid
```

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
_[npm 5^](http://blog.npmjs.org/post/161081169345/v500) is preferred_.
```bash
npm install
```

### Build documentation
Use [SASSDoc](http://sassdoc.com/) to build the project’s documentation. _Not required to open a PR_.
```bash
npm run docs
```

### Lint code changes
Lint your changes before opening a PR. If you don't, the Continuous Integration (CI) service won't allow your PR to be merged.
```bash
npm run lint
```

### Build distribution files
Check the production output files, if needed.
```bash
npm run dist
```
