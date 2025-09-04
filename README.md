# utilityNest

# Required technologies:

- Nodejs (windows, docker, npm) `v22.19.0` [Node.js](https://nodejs.org/en/download)
- Visual Studio 2022 `17.14.13` [Visual Studio](https://visualstudio.microsoft.com/)
- Yarn `1.22.22` [Yarn](https://classic.yarnpkg.com/en/docs/install#windows-stable)

## Folder setup

React Native Windows supports up to version 0.72.x (most stable pairing). Run:

```bash
npm install react-native@0.72
npm install react-native-windows@0.72 --save
```

## Initialisation

Make sure to add this at the beginning of "package.json" in order for the Initialisation to work.

### ❗ Important:

The project name must be alphanumeric (no spaces or special characters).

Use PascalCase or camelCase.

```json
  "name": "utilityNest",
  "version": "1.0.0",
  "private": true,
```

```bash
npx react-native-windows-init --overwrite
```

This will:

- Add a windows/ folder with solution/project files.
- Configure your React Native project for Windows.

## Run the Windows App

In order to be able to run and compile the app, you must first download the "Desktop development with C++" with the following components :

- Windows 10/11 SDK
- MSBuild (usually already installed)
- C++ CMake Tools

```bash
npx react-native run-windows
```
