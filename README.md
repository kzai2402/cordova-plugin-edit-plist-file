# cordova-plugin-edit-plist-file
A Cordova plugin to edit the iOS *-Info.plist file without manually modifying it. 

Forked and Modified by @kzai2402

Original version by Haythem OUEDERNI - @haythemOUE

# Platforms
iOS only

# 1 - Description
A Cordova plugin to edit the iOS *-Info.plist file without manually modifying it.

# 2 - How to use
This plugins will default update the NSAllowArbitraryLoad to false on iOS.

If you don't need to add other apps you can add it directly to your project by running <br/><br/>

```
cordova plugin add cordova-plugin-edit-plist-file
```

or

```
cordova plugin add https://github.com/kzai2402/cordova-plugin-edit-plist-file.git
```

If you want to custumize the plugin you can :
- download the plugin in a local repo
- edit the plugin.xml file of the plugin
- add the local plugin to your project by running :

```
cordova plugin add /your-repo/cordova-plugin-edit-plist-file
```
