## Testing out RN with nem-sdk

Trying to get nem-sdk worked in ReactNative but not working...

### What did I do

- Replace `rn-nodeify` to the one on Github (mvayngrib/rn-nodeify)
- Run `node_modules/.bin/rn-nodeify --install`
- `$ watchman watch-del-all`
- `$ rm -rf node_modules`
- `$ npm install`
- `$ rm -rf $TMPDIR/react-*`
- `$ node_modules/.bin/rn-nodeify --hack`
- `$ react-native link`
- `$ react-native run-ios`

### ReactNative

- Started with Expo => didn't work
- Restarted with `create-react-native-app`
- Needed to `yarn eject` to run `react-native link`

### Ref
- https://github.com/QuantumMechanics/NEM-sdk
- https://github.com/parshap/node-libs-react-native
- https://github.com/philikon/ReactNativify
- https://github.com/tradle/rn-nodeify
- https://github.com/browserify/browserify
- https://expo.io/
- https://github.com/react-community/create-react-native-app/blob/master/EJECTING.md
