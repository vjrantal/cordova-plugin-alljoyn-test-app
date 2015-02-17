cordova-plugin-alljoyn-test-app
===============================

Setting up
----------

Add the AllJoyn plugin either from local folder:

```
cordova plugin add <correct-local-path>/cordova-plugin-alljoyn
cordova plugin add <correct-local-path>/cordova-plugin-alljoyn/tests
```

Or from a Git repository:

```
cordova plugin add https://github.com/AllJoyn-Cordova/cordova-plugin-alljoyn.git
cordova plugin add https://github.com/AllJoyn-Cordova/cordova-plugin-alljoyn.git#:/tests
```

Include the test framework plugin:

```
cordova plugin add https://github.com/apache/cordova-plugin-test-framework.git
```

Running
-------

Add the platform you want to run on and run:

```
cordova platform add <your-platform>
cordova run <your-platform>
```
