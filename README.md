# MultiResolution-cocos2dx
A base project to support max number of resolutions in the market for iOS and Android

This is a demo project to show how to work with multiple resolutions devices. The original solution was explained by wiwing in this thread http://discuss.cocos2d-x.org/t/am-i-overthinking-this-multi-resolution-support/18493

This demo uses NO_BORDER resolution policy. This means that part of the screen could not be visible depending in which device your game is running on. 

You can find in res/ folder two psd files:

- cocos2d-x-designsize.psd
- cocos2d-x-designsize-landscape.psd

Those psds contains two layers: one red with "Maybe not visible" and another with "Always visible" screen. Designers must design all important content inside the "Always visible" layer. Depending the size of the running device, a part of "Maybe not visible" layer will be cropped.

