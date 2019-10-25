# React Snippets for NextJS by iJS

Thanks for giving this a go. Hope this helps and makes your coding more efficient and fun.

## Hello.

Animations coming soon.

> Pull requests for animations or any other contributions are most welcome!

## Installation

- Launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions (or navigate from the sidebar to Extensions tab).
- In search box type in "Scott Agirs" and choose the React Snippets by Scott Agirs
- Install the extension (you may need to relaunch VS Code)
- Get a coffee, a cookie and celebrate by writing some NextJS code more effeciently than ever!

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

## Must have React Snippets

|     Trigger | Content                            |
| ----------: | ---------------------------------- |
|      `imr→` | Explicitely import React           |
|     `imrc→` | Import React { Component }         |
|     `imst→` | (16.8+) useState import            |
|      `ust→` | Use (16.8+) useState hook          |
|    `imeff→` | (16.8+) useEffect import           |
|    `imctx→` | (16.8+) useContext import          |
|     `uctx→` | Use React useContext hook          |
|    `immem→` | (16.8+) useMemo import             |
|    `imref→` | (16.8+) useRef import              |
| `imimphan→` | (16.8+) useImperativeHandle import |
| `imlayeff→` | (16.8+) useLayoutEffect import     |
| `imdebval→` | (16.8+) useDebugValue import       |
|      `imt→` | Import PropTypes                   |
|        `cc` | Class Component                    |
|      `ccc→` | Class Component With Constructor   |
|       `fc→` | Functional Component               |

## NextJS-specific Snippets

| Trigger | Content     |
| ------: | ----------- |
| `imhd→` | import Head |
|  `nhd→` | Use Head    |

## NextJS Link

|     Trigger | Content                           |
| ----------: | --------------------------------- |
|    `imlnk→` | import Link                       |
|     `nlnk→` | Use Link                          |
| `nlnkpath→` | Next Link tag with pathname;      |
|  `nlnkdyn→` | Next Link tag with dynamic route; |

## NextJS Router

|    Trigger | Content                          |
| ---------: | -------------------------------- |
|   `imrtr→` | import Router                    |
| `imrtrwr→` | import Router and withRouter HOC |
| `imusrtr→` | import Router hook               |

- More snippets to come, stay tuned!

## Expanded Snippets

### imr - Import React - if you must (NextJS imports React implicitly)

```javascript
import React from 'react';
```

### imrc - Import React, Component

```javascript
import { Component } from 'react';
```

### imst - Import { useState }

```javascript
import { useState } from 'react';
```

### ust - React useState

```javascript
  const [value, setValue] = useState(${1:INITIAL_VALUE});
```

### imeff - Import { useEffect }

```javascript
import { useEffect } from 'react';
```

### imctx - Import { useContext }

```javascript
import { useContext } from 'react';
```

### uctx - React useContext

```javascript
const $0 = useContext(${1:CONTEXT_OBJECT});';
```

### immem - Import { useMemo }

```javascript
import { useMemo } from 'react';
```

### imref - Import { useRef }

```javascript
import { useRef } from 'react';
```

### imimphan - imImport { useImperativeHandle }

```javascript
import { useImperativeHandle } from 'react';
```

### imlayeff - imImport { useLayoutEffect }

```javascript
import { useLayoutEffect } from 'react';
```

### imdebval - imImport { useDebugValue }

```javascript
import { useDebugValue } from 'react';
```

### imt - imImport PropTypes

```javascript
import PropTypes from 'prop-types';
```

### impt - Import PropTypes

```javascript
import PropTypes from 'prop-types';
```

### impc - Import PureComponent

```javascript
import React, { PureComponent } from 'react';
```

### cc - Class Component

```javascript
class | extends Component {
  state = { | }

  render() {
    return ( | );
  }
}

export default |;
```

### ccc - Class Component With Constructor

```javascript
class | extends React.Component {
    constructor(props) {
      super(props);
      this.state = { | }
    }
    render() {
        return ( | );
    }
}

export default |;
```

### sfc - Stateless Function Component

```javascript
const | = props => {
  return ( | );
};

export default |;
```

### imhd - import NextJS Head

```javascript
import Head from 'next/head';
```

### nhd - Use NextJS Head

```javascript
<Head> | </Head>
```

### imlnk - import NextJS Link

```javascript
import Link from 'next/link';
```

### nlnk - Use NextJS Link

```javascript
<Link href="|">
  <a>|</a>
</Link>
```

### nlnkpath - Use NextJS Link With Pathname

    "body": [
      "<Link href={{ pathname: \"${1}\", query: { queryName: queryValue } }}>",
      "\t<a>",
      "\t\t$0",
      "\t</a>",
      "</Link>"

### nlnkdyn - Use NextJS LinkTagWithDynmicRoute

```javascript
<Link href="/|" as={`/|`}>
  <a>|</a>
</Link>
```

### imrtr - importNextRouter

```javascript
import Router from 'next/router';
```

### imrtrwr - importNextRouterWithRouter

```javascript
import Router, { withRouter } from 'next/router';
```

### imusrtr - importNextUseRouter

```javascript
import { useRouter } from 'next/router';
```

## Release Notes

## [1.0.1] - 2019 October 25th 11th

### Added

#### Snippets:

- `ncc→` | NextJS Class Component with State
- `nc→` | NextJS Functional Component

#### Other:

- Updated README with expanded Snippets

## [1.0.0] - 2019 October 24th

- Initial React Snippets by Scott Agirs Release

**Enjoy!**
/ S
