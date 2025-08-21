<img height="204" src="https://cloud.githubusercontent.com/assets/464822/20228152/d3f36dc2-a804-11e6-80ff-51ada2d13ea7.png">

# @roamjs/blueprint3

A Node 22 compatible fork of [Blueprint](https://blueprintjs.com/), a React UI toolkit for the web.

## 🚀 What's Different

This fork makes Blueprint compatible with Node.js 22+ by:

- **Modern Sass**: Replaced `node-sass` with modern `sass` (Dart Sass)
- **Updated Build Scripts**: Fixed compilation scripts for modern tooling
- **Import Path Fixes**: Resolved module resolution issues
- **Icon System Workarounds**: Temporary fixes for icon compilation
- **TypeScript Compatibility**: Updated type definitions

## 📦 Packages

- **@roamjs/blueprint3-core**: Core styles & components
- **@roamjs/blueprint3-select**: Select components
- **@roamjs/blueprint3-datetime**: Date/time components

## 🛠️ Installation

```bash
npm install @roamjs/blueprint3-core @roamjs/blueprint3-select @roamjs/blueprint3-datetime
```

## 🔧 Usage

```tsx
import { Button, Intent } from '@roamjs/blueprint3-core';
import '@roamjs/blueprint3-core/lib/css/blueprint.css';

function App() {
  return (
    <Button intent={Intent.PRIMARY}>
      Hello from Blueprint3!
    </Button>
  );
}
```

## 📋 Requirements

- Node.js >= 12 (tested with Node 22)
- React >= 15.3.0

## 🤝 Contributing

This is a fork of the original Blueprint project. For the original project, see [Palantir's Blueprint](https://github.com/palantir/blueprint).

## 📄 License

Apache-2.0 - Same as the original Blueprint project.
