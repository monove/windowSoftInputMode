# windowSoftInputMode
Cordova plugin to dynamically change soft input mode on android devices
Currently the plugin supports setting the soft input to adjustPan (SOFT_INPUT_ADJUST_PAN) or adjustResize(SOFT_INPUT_ADJUST_RESIZE). Feel free to extend it and make a pull request

# Installation
cordova plugin add https://github.com/denkomanceski/windowSoftInputMode.git

# Usage

declare var windowSoftManager;

```windowSoftManager.setMode("adjustPan");```

```windowSoftManager.setMode("adjustResize");```

Thats it. Simple and clear

# Uninstall
cordova plugin remove com.vertex.windowSoftInputMode
