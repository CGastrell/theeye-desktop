# TheEye Desktop client
An electron wrapper for theeye.io app

## Instructions
Clone the repo and install it's dependencies
```bash
git clone https://github.com/cgastrell/theeye-desktop
cd theeye-desktop
npm install
```

### Build
Build the package for your preferred platform with the included scripts.

**Note:** All builds are 64bit architecture. If you need 32bit versiones, edit `package.json` and look for the `--arch` arguments on the scripts
```bash
npm run package-mac
npm run package-win
npm run package-linux
```

Builds will be stored on `./release-builds` directory
