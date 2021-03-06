# iocage-my-plugins
Plugin manifest files for [iocage](https://github.com/iocage/iocage).  These files provide a convenient way to create a jail, preconfigured with some software.

## Prerequisites
A \*BSD system with the [iocage](https://github.com/iocage/iocage) jailmanager.

## Installing Plugins
Download a plugin manifest file to your local file system.
```
fetch https://raw.githubusercontent.com/jsegaert/iocage-my-plugins/master/mineos.json
```
Install the plugin.  Adjust the network settings as needed.
```
iocage fetch -P mineos.json -n mineos
```

## Plugin manifest files
### mineos.json
This will install [MineOS](https://minecraft.codeemo.com/mineoswiki/index.php?title=MineOS-node_(pkg_add)), an easy way to create, host and manage Minecraft servers via a Web-based User Interface.
### node-red.json
This will install [Node-RED](https://nodered.org/).
### tetris.json
This will install [Bastet](http://fph.altervista.org/prog/bastet.html) (short for Bastard Tetris).
### xmage-server.json
This will install the server components of [XMage](http://xmage.de/) 
### jdownloader.json
This will install [JDownloader](http://jdownloader.org/)
### deluge-pip.json
This will install [Deluge](https://www.deluge-torrent.org/)
### heimdall-dashboard.json
This will install [Heimdall Application Dashboard](https://heimdall.site/)
