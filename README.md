This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started
### Add fonts
Create file `react-native.config.js`
```
module.exports = {
    assets: ['./src/assets/fonts/']
}
```
Run `npx react-native-asset` to create link assets to your project android and ios

Now use it normal in your project 

### Build apk
Create keystore file, follow this tutorial `https://reactnative.dev/docs/signed-apk-android`

### 