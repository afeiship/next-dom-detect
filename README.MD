#next-ui-template

##description:
+ Dom event module based on next toolkit.

##usage:
+ general device type
```javascript
$.os.phone
$.os.tablet
```

+ specific OS
```javascript
$.os.ios
$.os.android
$.os.webos
$.os.blackberry
$.os.bb10
$.os.rimtabletos
```

+ specific device type
```javascript
$.os.iphone
$.os.ipad
$.os.ipod // [v1.1]
$.os.touchpad
$.os.kindle
```
+ specific browser
```javascript
$.browser.chrome
$.browser.firefox
$.browser.safari // [v1.1]
$.browser.webview // (iOS) [v1.1]
$.browser.silk
$.browser.playbook
$.browser.ie // [v1.1]
```
+ Additionally, version information is available as well.
+ Here's what's returned for an iPhone running iOS 6.1.
```javascript
!!$.os.phone         // => true
!!$.os.iphone        // => true
!!$.os.ios           // => true
$.os.version       // => "6.1"
$.browser.version  // => "536.26"
```
