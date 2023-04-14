# react-chrome-starter
a starter template for creating chrome extension with react

## Setup
1. Install dependencies with yarn and build
```sh
cd app
# install dependencies
yarn 
# build and export files to exntension directory
yarn build # on macOS
```
2. Open chrome and go to ```chrome://extensions/```
3. Toggle on developer mode on the top-right corner.
4. Click "Load unpacked", select extension folder in this directory in this folder and click confirm.
5. Now you can find the extension in the toolbar of chrome. Click on it and you can see the default page of react(with vite)
6. Have fun developing!