# electron-screenshot

Faça capturas de tela em uma janela Electron

# Install

npm install electron-screenshot

# Usage

Use in an already existing atom-shell window

for a standalone implementation see [electron-screenshot-service](https://github.com/FWeinb/electron-screenshot-service)

``` js
var screenshot = require('electron-screenshot')
screenshot(options, [cb])
```

#### options

### filename
png filename

### delay (in ms)
default `0`
