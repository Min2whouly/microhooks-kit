# microhooks-kit

A handful of React hooks I keep copy-pasting between projects

Started as a weekend hack, grew on me.

## What it does

- useMediaQuery SSR-safe
- useLocalStorage with JSON serialization
- useDebounce with leading/trailing options
- Tiny: no dependencies besides React

## Getting started

```bash
npm install
npm test
```

## How to use

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## License

MIT. Do whatever you want.
