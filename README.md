# AWeber FlexBox Grid
AWeber FlexBox Grid is born from AWeber's need to have a responsive and modern grid system to use on its website and web application. This is why we used FlexBox grid as the base for this project but using SCSS as a preprocessor language to provide maintainability and ease of development.

## Installation
### npm
TBD…

### Bower
TBD…

### Production CSS | CDN
TBD…

## Development
* Fork and clone the **AWeber FlexBox Grid** repository
* Install project’s dependencies
* Create a branch for your changes using [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)
* Make your changes and document them properly using [SASSDoc](http://sassdoc.com/) guidelines
* Lint your changes and create a PR for your changes pointing to `develop` branch

### Install dependencies
We use [Yarn](https://yarnpkg.com/) as a package manager, please install it before start working on the project.
```bash
yarn
```

### Build documentation
We use SASSDoc to build the project’s documentation although this is not a required step prior to publish a PR.
```bash
yarn docs
```

### Lint code changes
Is very important to lint your code changes before creating the PR so the continuous integration service allows to merge the PR.
```bash
yarn lint
```

### Build distribution files
If you need or want to check the production output files you can use this command:
```bash
yarn dist
```
