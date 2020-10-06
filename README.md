# Status Monitor Application

Simple application to monitor CPU and memory usage using HTML/CSS and JavaScript with Electron.js framework.

![Alt text](src/assets/screenshot.png?raw=true "Screenshot: Status Monitor Application - Electron.js")

# Creating an Installer

In the project directory, you can run:

Using [Squirrel](https://github.com/Squirrel/Squirrel.Windows) method. One click installer which install immediately without any confirmation window or allow users to change the install path. 

```
$ npm run make
```

Either using [electron-builder](https://github.com/electron-userland/electron-builder) to get permissions at installing time.

```
$ npm run build-installer
```

Your app will be packaged into executable file on your current machine platform. The output will be in out/dist folder in your project. 