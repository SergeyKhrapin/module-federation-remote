# Remote Module

This is the remote module in a Webpack Module Federation setup. It exposes a `Button` component that can be consumed by other applications.

## Features

- Exposes a React Button component via Module Federation.
- Runs a development server on port 3001.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm start
   ```

3. The remote module will be available at `http://localhost:3001`.

## Exposed Modules

- `Button`: A simple React button component that shows an alert when clicked.

## Module Federation

This module uses Webpack's Module Federation plugin to expose the `Button` component. The remote entry is `remoteEntry.js`.