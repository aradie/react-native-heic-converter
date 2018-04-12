
# react-native-heic-converter

## Getting started

`$ npm install react-native-heic-converter --save`

### Install with NPM
```javascript
"dependencies": {
    ...
    "react-native-heic-converter": "github:makskolesnikov/react-native-heic-converter",
    ...
}
```

`$ npm i`

### Mostly automatic installation

`$ react-native link react-native-heic-converter`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-heic-converter` and add `RNHeicConverter.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNHeicConverter.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<


## Usage
```javascript
import RNHeicConverter from 'react-native-heic-converter';

RNHeicConverter.getJpgPath({
    uri: you_string_uri,
}, (error, result) => {
    console.log(error, result); // null, { success: true, path: "path/to/jpg" }
});

```
  