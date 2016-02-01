#next-dom-detect

##description:
+ Dom event module based on next toolkit.

##usage:
+ general device type
```javascript
nx.$.os.phone
nx.$.os.tablet
```

+ specific OS
```javascript
nx.$.os.ios
nx.$.os.android
nx.$.os.webos
nx.$.os.blackberry
nx.$.os.bb10
nx.$.os.rimtabletos
```

+ specific device type
```javascript
nx.$.os.iphone
nx.$.os.ipad
nx.$.os.ipod // [v1.1]
nx.$.os.touchpad
nx.$.os.kindle
```
+ specific browser
```javascript
nx.$.browser.chrome
nx.$.browser.firefox
nx.$.browser.safari // [v1.1]
nx.$.browser.webview // (iOS) [v1.1]
nx.$.browser.silk
nx.$.browser.playbook
nx.$.browser.ie // [v1.1]
```
+ Additionally, version information is available as well.
+ Here's what's returned for an iPhone running iOS 6.1.
```javascript
!!nx.$.os.phone         // => true
!!nx.$.os.iphone        // => true
!!nx.$.os.ios           // => true
nx.$.os.version       // => "6.1"
nx.$.browser.version  // => "536.26"
```
