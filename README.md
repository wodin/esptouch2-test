# esptouch2-test

`react-native-esptouch2` has not been updated in a couple of years, so
to use it in an Expo SDK 43 app it needs to be "jetified". You can do
that by installing `patch-package` and using the patch in the `patches`
directory in this repository.

## Installing `react-native-esptouch2` in an Expo SDK 43 managed workflow app

Copy the patch from this repository into a
[`patches`](https://github.com/wodin/esptouch2-test/tree/main/patches)
directory in the root of your app.

Install
[`patch-package`](https://github.com/ds300/patch-package/blob/master/README.md)
and the `postinstall` hook.

Install `react-native-esptouch2`:

```
yarn add react-native-esptouch2
```

or

```
npm install react-native-esptouch2
```

For a development workflow similar to Expo Go, install
[`expo-dev-client`](https://docs.expo.dev/clients/introduction/).

Then buils with [EAS Build](https://docs.expo.dev/build/introduction/).
