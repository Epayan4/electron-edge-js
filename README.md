# .NET and Node.js in-process on Electron

This is a fork of [electron-edge-js](https://github.com/JesseRedfield/electron-edge-js) adapted to support [Electron v.17.2.0](https://github.com/electron/electron/).

For other details, refer the parent repo.

------------------------------------------------------
Steps to build `electron-edge-js` for other electron versions:

- Install `node-gyp` package.
- open `./tools/build.bat` file.
- Add the required electron version after 68th line.
- set required nodejs version in TARGET variable.
- Run `.\build.bat release <target version>`