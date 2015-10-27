Command to build:

```
electron-packager . mattermostmac  --platform=darwin --arch=x64 --version=0.34.1 --asar --overwrite --icon=appl.icns   --app-version=0.0.2
```

If you want to change to a host other than localhost:8065, edit this line in main.js:

```
  mainWindow.loadUrl('https://localhost:8065/teamname');
```

