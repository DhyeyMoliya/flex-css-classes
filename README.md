# Flex CSS Classes

This library provides basic CSS classes for using Flexbox features like Flex row, Flex Column, properties like grow, alignments and more.

## Installation

Run following command to install library using NPM:

``npm install flex-css-classes``

## Usage

This library is available in two CSS variants :
* CSS
* SCSS

Import / Link the library file by referring to the node_modules folder

**Note :** *If this library's css class names are conflicting with yourexisting css frameworks like bootstrap(.row) or angular material(.row), then you can use prefixed(flex-prefixed.scss/css) files which use (.flex-\*) like **.flex-row**, **.flex-column**, **.flex-item** classes.*

### For **CSS** library :

```
@import "node_modules/flex-css-classes/css/flex.css";

or

<link rel="stylesheet" href="node_modules/flex-css-classes/css/flex.css" />
```

or

```
@import "node_modules/flex-css-classes/css/flex-prefixed.css";

or

<link rel="stylesheet" href="node_modules/flex-css-classes/css/flex-prefixed.css" />
```


### For **SCSS** Library :

```
@import "node_modules/flex-css-classes/scss/flex.scss";
```

or

```
@import "node_modules/flex-css-classes/css/flex-prefixed.scss";
```

## Demo and Library Description

Run ``demo.html`` file from ``node_modules/flex-css-classes`` folder in your local browser to see a demo having examples and description of the library.

## License

This project is licensed under the ISC License.