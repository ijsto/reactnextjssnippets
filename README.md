<p align="center"><img width="368px" src="https://raw.githubusercontent.com/ijsto/reactnextjssnippets/master/images/logo02.png"></p>
<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=iJS.reactnextjssnippets"><img src="https://vsmarketplacebadge.apphb.com/installs-short/iJS.reactnextjssnippets.svg?style=for-the-badge&colorA=85bf00&colorB=679400&label=DOWNLOADS"/></a> <a href="https://code.visualstudio.com/updates/v1_25"><img src="https://vsmarketplacebadge.apphb.com/rating-star/iJS.reactnextjssnippets.svg?style=for-the-badge&colorA=38B8F0&colorB=3726A6"/></a> 
<a href="https://ijs.to"><img src="https://img.shields.io/badge/Learn%20JavaScript-iJS.to%E2%86%92-gray.svg?colorA=B838F0&colorB=8721C3&style=for-the-badge"/></a>
</p>

# React Snippets for Next.js by iJS

Thanks for giving this a go. Hope this helps and makes your coding more efficient and fun.

## Hello.

Animations coming soon.

> Pull requests for animations or any other contributions are most welcome!

## Installation

- Launch the Command Pallete (Ctrl + Shift + P or ⌘Cmd + Shift + P) and type "Install Extensions" (or navigate from the sidebar to Extensions tab).
- In search box type in "iJS" and choose the React Next.js Snippets by iJS
- Install the extension (you may need to relaunch VS Code)
- Get a coffee, a cookie and celebrate by writing some Next.js code more effeciently than ever!

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

## Must have React Snippets

|     Trigger | Content                                  |
| ----------: | ---------------------------------------- |
|      `imr→` | Explicitely import React                 |
|     `imrc→` | Import React { Component }               |
|     `imst→` | (16.8+) useState import                  |
|      `ust→` | Use (16.8+) useState hook                |
|    `imeff→` | (16.8+) useEffect import                 |
|    `imctx→` | (16.8+) useContext import                |
|     `uctx→` | Use React useContext hook                |
|    `immem→` | (16.8+) useMemo import                   |
|    `imref→` | (16.8+) useRef import                    |
| `imimphan→` | (16.8+) useImperativeHandle import       |
| `imlayeff→` | (16.8+) useLayoutEffect import           |
| `imdebval→` | (16.8+) useDebugValue import             |
|      `imt→` | Import PropTypes                         |
|        `cc` | Class Component                          |
|      `ccc→` | Class Component With Constructor         |
|       `fc→` | Functional Component                     |
|      `fce→` | Functional Component as named export     |
|     `fcde→` | Functional Component with default export |

## Next.js-specific Snippets

| Trigger | Content     |
| ------: | ----------- |
| `imhd→` | import Head |
|  `nhd→` | Use Head    |

## Next.js getInitialProps()

|  Trigger | Content                                             |
| -------: | --------------------------------------------------- |
|   `gip→` | getInitialProps() outside component                 |
| `ccgip→` | static getInitialProps() inside class component     |
| `gipaq→` | Next.js getInitialProps() withApollo() expose query |

## Next.js getStaticProps()

| Trigger | Content                  |
| ------: | ------------------------ |
|  `gsp→` | exports getStaticProps() |

## Next.js getServerSideProps()

| Trigger | Content                      |
| ------: | ---------------------------- |
| `gssp→` | exports getServerSideProps() |

## Next.js getStaticPaths()

|    Trigger | Content                  |
| ---------: | ------------------------ |
| `gspaths→` | exports getStaticPaths() |

## Next.js Link

|     Trigger | Content                           |
| ----------: | --------------------------------- |
|    `imlnk→` | import Link                       |
|     `nlnk→` | Use Link                          |
| `nlnkpath→` | Next Link tag with pathname;      |
|  `nlnkdyn→` | Next Link tag with dynamic route; |

## Next.js Router

|    Trigger | Content                                                    |
| ---------: | ---------------------------------------------------------- |
|   `imrtr→` | import Router                                              |
|    `nrtr→` | Declare Next.js Router from useRouter                      |
|  `nqprtr→` | Destructure Next.js query param from Router from useRouter |
| `imrtrwr→` | import Router and withRouter HOC                           |
| `imusrtr→` | import Router hook                                         |
|  `nqprtr→` | Destructure Next.js query param from Router from useRouter |

- More snippets to come, stay tuned!

## Expanded Snippets

### imr - Import React - if you must (Next.js imports React implicitly)

```javascript
import React from "react";
```

### imrc - Import React, Component

```javascript
import { Component } from "react";
```

### imst - Import { useState }

```javascript
import { useState } from "react";
```

### ust - React useState

```javascript
  const [value, setValue] = useState(${1:INITIAL_VALUE});
```

### imeff - Import { useEffect }

```javascript
import { useEffect } from "react";
```

### imctx - Import { useContext }

```javascript
import { useContext } from "react";
```

### uctx - React useContext

```javascript
const | = useContext(|);';
```

### immem - Import { useMemo }

```javascript
import { useMemo } from "react";
```

### imref - Import { useRef }

```javascript
import { useRef } from "react";
```

### imimphan - imImport { useImperativeHandle }

```javascript
import { useImperativeHandle } from "react";
```

### imlayeff - imImport { useLayoutEffect }

```javascript
import { useLayoutEffect } from "react";
```

### imdebval - imImport { useDebugValue }

```javascript
import { useDebugValue } from "react";
```

### imt - imImport PropTypes

```javascript
import PropTypes from "prop-types";
```

### impt - Import PropTypes

```javascript
import PropTypes from "prop-types";
```

### impc - Import PureComponent

```javascript
import React, { PureComponent } from "react";
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

### fc - Functional Component without a state

```javascript
const | = props => {
  return ( | );
};

export default |;
```

### fcst - Functional Component with a useState hook

```javascript
import { useState } from 'react';

const | = props => {
  const [value, setValue] = useState(${1:INITIAL_VALUE});

  return ( | );
};

export default |;
```

### imhd - import Next.js Head

```javascript
import Head from "next/head";
```

### nhd - Use Next.js Head

```javascript
<Head> | </Head>
```

### gip - getInitialProps() outside component

```javascript
|.getInitialProps = ({ req }) => {
  return |
}
```

### ccgip - getInitialProps() outside component

```javascript
static async getInitialProps() { return { | }; }
```

### gipaq - static getInitialProps() inside class component

```javascript
static async getInitialProps({ Component, ctx }) {",
  let pageProps = {};
  if (Component.getInitialProps) {
    pageProps = await Component.getInitialProps(ctx);
  }

  pageProps.query = ctx.query;
  pageProps.asPath = ctx.asPath;

  return { pageProps };
}
```

### gsp - exports getStaticProps()

```javascript
export async function getStaticProps(context) {
  return {
    props: { | }, // will be passed to the page component as props
  }
}
```

### gspaths - exports getStaticPaths()

```javascript
export async function getStaticPaths() {
  return {
    paths: [
      { params: { | } } // See https://nextjs.org/docs/basic-features/data-fetching#the-paths-key-required
    ],
    fallback: | // See https://nextjs.org/docs/basic-features/data-fetching#fallback-true
  };
}
```

### gssp - exports getServerSideProps()

```javascript
export async function getServerSideProps(context) {
  return {
    props: {}, // will be passed to the page component as props
  };
}
```

### imlnk - import Next.js Link

```javascript
import Link from "next/link";
```

### nlnk - Use Next.js Link

```javascript
<Link href="|">
  <a>|</a>
</Link>
```

### nlnkpath - Use Next.js Link With Pathname

```javascript
<Link href={{ pathname: |, query: { queryName: | } }}>
  <a>|</a>
</Link>
```

### nlnkdyn - Use Next.js LinkTagWithDynmicRoute

```javascript
<Link href="/|" as={`/|`}>
  <a>|</a>
</Link>
```

### imrtr - importNextRouter

```javascript
import Router from "next/router";
```

### nrtr - Next.js Router from useRouter

```javascript
const router = useRouter();
```

### nqprtr - Next.js query param from useRouter

```javascript
const { $1 } = router.query;
```

### imrtrwr - importNextRouterWithRouter

```javascript
import Router, { withRouter } from "next/router";
```

### imusrtr - importNextUseRouter

```javascript
import { useRouter } from "next/router";
```
