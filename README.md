# React catalog view

This package contains catalog components based on the ones in PF3's patternfly-react-extensions package.

This package is currently an extension. Extension components do not undergo the same rigorous design or coding review process as core PatternFly components. If enough members of the community find them useful, we will work to move them into our core PatternFly system by starting the design process for the idea.

Development for this extension was previously being done under the [patternfly-react repo](https://github.com/patternfly/patternfly-react/tree/caf893d71966a0eabcde909a29d9a872367d9897/packages/react-catalog-view-extension).

### Installing

```
yarn add react-catalog-view-extension
```

or

```
npm install react-catalog-view-extension --save
```

### Usage

```
import { Component } from 'react-catalog-view-extension';
```

#### Styling:

Example with SCSS:

```
@import "~patternfly-react/dist/sass/patternfly-react";
@import "~react-catalog-view-extension/dist/sass/react-catalog-view-extension";
```

### Building

```
yarn build
```

Note the build scripts for this are located in the root package.json under `yarn build`.

### Testing

Testing is done at the root of this repo.

```
yarn test
```

### Publishing

```
yarn publish
```
