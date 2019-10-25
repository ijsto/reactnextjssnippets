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

## Release Notes

## [1.1.0] - 2019 October 24th

- Work resumed.
- Multiple changes, please check the snippets.

## [1.0.2] - 2019 June 11th

### Added

#### Snippet:

- NextJS Link
- `nlnkas→` | Next Link tag with <a>, `asPath` and `query`;

## [1.0.2] - 2019 June 11th

### Added

#### Categories:

- NextJS-specific Base Snippets
- ReactJS-specific Base Snippets
- ReactJS-specific Imports
- NextJS-specific Imports
- NextJS Tags
- NextJS Router
- NextJS Link

#### Snippets:

- `ncc→` | NextJS Class Component with State
- `nc→` | NextJS Functional Component

- `uctx→` | const context = useContext(contextName);
- `ust→` | const [value, setValue] = useState(null);

- `imuctx→` | import { useContext } from 'react';
- `imust→` | import { useState } from 'react';

- `imhd→` | import Head from 'next/head';
- `imlnk→` | import Link from 'next/link';
- `imrtr→` | import Router from 'next/head';
- `imrtrwr→` | import Router, { withRouter } from 'next/head';

- `nhd→` | Next Head tags;

- `nlnk→` | Next Link tag with <a>;
- `nlnkpath→` | Next Link tag with <a> and pathname;

- `nrtr→` | const { router } = Router;
- `nqry→` | const { query } = Router.router;
- `npathn→` | const { pathname } = Router.router;

## [1.0.1] - 2019 June 10th

### Added

- Snippet list to README
- TypeScript, TypeScript React and Javascript support

### (Minor) Bug Fixes

- Relative path of the icon in `package.json`

## [1.0.0] - 2019 June 10th

- Initial React Snippets by Scott Agirs Release

**Enjoy!**
/ S
