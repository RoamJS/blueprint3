# blueprint3

A React 18 compatible fork of [Blueprint](https://blueprintjs.com/) 3, a React UI toolkit for the web.

## 🚀 React 18 Support

This fork has been updated to support React 18 with the following improvements:

-   Updated peer dependencies to support React 16.3+, 17, and 18
-   Updated dev dependencies to use React 18.2.0
-   Updated TypeScript types to React 18
-   Maintains backward compatibility with React 16.3+

## 📦 Packages

### New Packages (Recommended)

-   **blueprint3-core**: Core styles & components
-   **blueprint3-select**: Select components
-   **blueprint3-datetime**: Date/time components

## 🛠️ Installation

### Option 1: Use new packages

```bash
npm install blueprint3-core blueprint3-select blueprint3-datetime
```

### Option 2: Use npm overrides

Add this to your `package.json`:

```json
{
    "overrides": {
        "@blueprintjs/core": "npm:blueprint3-core@^3.50.4",
        "@blueprintjs/select": "npm:blueprint3-select@^3.18.6",
        "@blueprintjs/datetime": "npm:blueprint3-datetime@^3.23.14"
    }
}
```
