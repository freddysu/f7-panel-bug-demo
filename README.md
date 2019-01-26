# f7-panel bug demo
The project uses template from [timkim's phonegap-template-vue-f7-split-panel](https://github.com/phonegap/phonegap-template-vue-f7-split-panel)

## Link to the issue page
https://github.com/framework7io/framework7/issues/2966


## Run the app on Android
```
$npm install
```

```
$cordova platform add android
```

```
$npm run cordova-run-android
```

## Reproduce the bug
Scroll down the list and click on menu icon at the same time.
The app will freeze.
