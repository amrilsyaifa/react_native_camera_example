# Installation

### Version

```json
{
  "name": "react_native_camera_example",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "start": "node node_modules/react-native/local-cli/cli.js start",
    "test": "jest"
  },
  "dependencies": {
    "react": "16.8.3",
    "react-native": "0.59.9",
    "react-native-camera": "^2.11.0"
  },
  "devDependencies": {
    "@babel/core": "7.4.5",
    "@babel/runtime": "7.4.5",
    "babel-jest": "24.8.0",
    "jest": "24.8.0",
    "metro-react-native-babel-preset": "0.54.1",
    "react-test-renderer": "16.8.3"
  },
  "jest": {
    "preset": "react-native"
  }
}

```

Install the library from npm:

```sh
npm install react-native-camera --save
```

donk use 
```sh
react-native link react-native-camera
```

you install manualy, follow step in documentation in [HERE](https://github.com/react-native-community/react-native-camera/blob/master/docs/installation.md#requirements).