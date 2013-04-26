Netbeans OS X Launcher
======================

Introduction
------------
I use zip packages from [Netbeans](http://www.netbeans.org) for all practical purposes. This gives me freedom to put netbeans anywhere. Also, I don't need admin rights.

This application (or workflow) creates a launchable icon for netbeans. 

How to use this?
----------------
You just need to put netbeans.app, next to `netbeans` script under `bin` directory.

Just git clone/export this project into a bin directory. For example,
```bash
cd $NETBEANS_HOME/bin
git clone git@github.com:yogendra/netbeans-osx-launcher.git netbeans.app
```
*NOTE:* `.app` extension is important as Mac OS X uses this to identify launchable application.

Here, _$NETBEANS_HOME_ need to be changed to where ever you have extracted netbeans archive.
Now, you can simply click on *netbeans* icon in Finder and launch application
You can also drag *netbeans* icon to Dockbar for quick access.


Why do I see two netbeans icons on lauch?
-----------------------------------------
Thats cause the netbeanse script uses a separate JVM process to lauch main application.
I don't have any idea how to make it apear as one icon. If you have any idea, please file via issue.


