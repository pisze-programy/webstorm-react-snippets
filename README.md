# React snippets for Webstorm
Live templates (snippets) for JetBrains product like Webstorm IDE.

## Introduction

This repository contains LiveTemplates for [React](https://github.com/facebook/react) and to be used with [JetBrains](http://www.jetbrains.com/) products such as [WebStorm](http://www.jetbrains.com/webstorm/).

Live Templates are a set of abbreviations that expand in to 'code snippets' for common tasks such as creating variables and functions.
These abbreviations significantly speed up development and reduce coding errors.

## Installation

### Webstorm
Depending on the operating system you are using, the <group_name>.xml files are stored at the following locations:

* [Windows] - `<your_user_home_directory>\.WebStorm<version_number>\config\templates`
* [Linux] - `~WebStorm<version>/config/templates`
* [OS X] - `~/Library/Preferences/WebStorm<version>/templates`

## List of snippets

* [Components](https://github.com/Krbz/webstorm-react-snippets#react-components)
* [PropTypes](https://github.com/Krbz/webstorm-react-snippets#react-propTypes)
* [Redux Actions](https://github.com/Krbz/webstorm-react-snippets#react-redux-actions)
* [React Lifecycles Hooks](https://github.com/Krbz/webstorm-react-snippets#React-component-lifecycle-hook)


## How to use the Live Templates
The following show the available abbreviations and their default implementations.

## React Components

<!--DOC_START-->
### `rc`
React ES6 Component

```js
import React, { Component, PropTypes } from 'react';

export default class $VAR$ extends Component {
  render() {
    return (${2:<div>MyComponent</div>});
  }
}

$VAR$.propTypes = {
  $END$
};
```

### `rcc`
React ES6 Component with Constructor

```js
import React, { Component, PropTypes } from 'react';

export default class $COMPONENT$ extends Component {
  constructor(props) {
    super(props);
  }

  render() {
    return (
      <div></div>
    );
  }
}

$COMPONENT$.propTypes = {
  $END$
};
```

### `rfunc`
React ES6 Functional Component

```js
import React, { PropTypes } from 'react';

export default function $COMPONENT$ (props) {
  return (
    <div>

    </div>
  );
}

$COMPONENT$.propTypes = {
  $END$
};
```

### `rconst`
React ES6 Constructor

```js
constructor(props) {
  super(props);
  $END$
}
```

### `rbm`
React ES6 bind method to this

```js
this.$VAR$ = this.$VAR$.bind(this);
$END$
```

## React PropTypes

### `rpa`
React PropType array

```js
$VAR$: PropTypes.array,
$END$
```

### `rpar`
React PropType array required

```js
$VAR$: PropTypes.array.isRequired,
$END$
```

### `rpb`
React PropType boolean

```js
$VAR$: PropTypes.bool,
$END$
```

### `rpbr`
React PropType boolean required

```js
$VAR$: PropTypes.bool.isRequired,
$END$
```

### `rpd`
React ES6 props definition

```js
$VAR$.propTypes = {
  $END$
};
```

### `rpe`
React PropType element

```js
$VAR$: PropTypes.element,
$END$
```

### `rper`
React PropType element required

```js
$VAR$: PropTypes.element.isRequired,
$END$
```

### `rpf`
React PropType function

```js
$VAR$: PropTypes.func,
$END$
```

### `rpfr`
React PropType function required

```js
$VAR$: PropTypes.func.isRequired,
$END$
```

### `rpn`
React PropType number

```js
$VAR$: PropTypes.number,
$END$
```

### `rpnr`
React PropType number required

```js
$VAR$: PropTypes.number.isRequired,
$END$
```

### `rpo`
React PropType object

```js
$VAR$: PropTypes.object,
$END$
```

### `rpor`
React PropType object required

```js
$VAR$: PropTypes.object.isRequired,
$END$
```

### `rps`
React PropType shape

```js
$VAR$: PropTypes.shape({
  $END$
}),
```

### `rpsr`
React PropType shape required

```js
$VAR$: PropTypes.shape({
  $END$
}).isRequired,
```

### `rpstr`
React PropType string

```js
$VAR$: PropTypes.string,
$END$
```

### `rpstrr`
React PropType string required

```js
$VAR$: PropTypes.string.isRequired,
$END$
```

## React Redux Actions


### `rat`
React Action Type

```js
export const $VAR$ = '$VAR$';
$END$
```

### `ra`
React Action function

```js
export function $VAR$(payload) {
  return { type: types.$VAR2$, payload };
}
$END$
```

## React Component Lifecycle hook


### `rcwm`
[ComponentWillMount](https://facebook.github.io/react/docs/react-component.html#componentwillmount)

```js
componentWillMount() {
  $END$
}
```

### `rcr`
[Component Render](https://facebook.github.io/react/docs/react-component.html#render)

```js
render() {
  $END$
}
```

### `rcdm`
[ComponentDidMount](https://facebook.github.io/react/docs/react-component.html#componentdidmount)

```js
componentDidMount() {
  $END$
}
```

### `rcwum`
[ComponentWillUnmount](https://facebook.github.io/react/docs/react-component.html#componentwillunmount)

```js
componentWillUnmount() {
  $END$
}
```

### `rcwu`
[ComponentWillUpdate](https://facebook.github.io/react/docs/react-component.html#componentwillupdate)

```js
componentWillUpdate() {
  $END$
}
```

### `rcdu`
[ComponentDidUpdate](https://facebook.github.io/react/docs/react-component.html#componentdidupdate)

```js
componentWillMount() {
  $END$
}
```

### `rcscu`
[ShouldComponentUpdate](https://facebook.github.io/react/docs/react-component.html#componentwillupdate)

```js
componentWillMount() {
  $END$
}
```






## Credits
* [Netguru](https://github.com/netguru/atom-react-es6-snippets) for inspiration

## License
MIT © [Krystian Błaszczyk](https://github.com/Krbz)
«