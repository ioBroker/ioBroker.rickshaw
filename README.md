![Logo](admin/rickshaw.png)
ioBroker.rickshaw
=================

draw charts with rickshaw

## Changelog
### 0.1.4 (2015-01-08)
* (bluefox) set name of socket connection

### 0.1.3 (2015-01-07)
* (bluefox) set onlyWWW flag

### 0.1.2 (2015-01-03)
* (bluefox) fix selectId dialog

### 0.1.1 (2015-01-02)
* (bluefox) add history to dependencies

### 0.1.0 (2015-01-02)
* (bluefox) enable npm install

### 0.0.7 (2014-12-12)
* (bluefox) remove common files like jquery and so on

### 0.0.6 (2014-12-12)
* (bluefox) update select ID dialog and remove jqGrid

### 0.0.5 (2014-12-10)
* (bluefox) build in select ID dialog

### 0.0.4 (2014-12-05)
* (bluefox) use "linear" interpolation by default

### 0.0.3 (2014-11-26)
* (bluefox) fix IDs without units

### 0.0.2 (2014-11-24)
* (bluefox) usable adapter


### How to use
- install "socketio"-adapter and create one instance
- install "web"-adapter and create one instance.
- Select in settings of "web"-adapter the instance of installed "socket.io"-instance.
- install "rickshaw"-adapter and call
- Go to http://ip:8082/rickshaw/edit.html