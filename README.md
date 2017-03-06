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


## How to use the Live Templates
The following show the available abbreviations and their default implementations.

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

## PropTypes

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





## Credits
* [Netguru](https://github.com/netguru/atom-react-es6-snippets) for inspiration

## License
MIT © [Krystian Błaszczyk](https://github.com/Krbz)
«