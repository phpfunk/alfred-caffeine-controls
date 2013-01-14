Caffeine Controls for Alfred
============

An AppleScript so you can easily control Caffeine from [Alfred App](http://alfredapp.com/). You will need Alfred and the Powerpack to use this.

## [Version 2 is ready for Alfred 2](https://github.com/phpfunk/alfred-caffeine-controls/tree/v2)

* [Go here to read more.](https://github.com/phpfunk/alfred-caffeine-controls/tree/v2)

Installation
----------------

To install Caffeine Controls in Alfred double click on the extension file.

How to use
----------------

Once installed with Alfred you can run the following commands

    caff        ::  Toggle caffeine on and off
    caff on     ::  Turn caffeine on indefinitely
    caff 5      ::  Turn caffeine on for 5 minutes (the # can be changed to any number)
    caff off    ::  Turn caffeine off
    caff quit   ::  Quit caffeine (can also use 'caff end' or 'caff exit')
    caff start  ::  Start caffeine (can also use 'caff init')


Notes
----------------
If caffeine is not active and you turn it on with either 'caff on' or 'caff #' or 'caff', it will automatically start the Caffeine application for you. You do not have to call 'caff start' first.

Big thanks to [pfburno](https://github.com/pfbruno) for his contributions and ideas for this extension (initial growl integration, toggle and easy-to-use turn on for 'x' minutes approach).


Growl vs. No Growl
----------------
Two versions of the extension are available, one with Growl and one without. If you wish to use the one without Growl please install the 'Caffeine Controls No Growl.alfredextension' file.

Download
----------------
[Caffeine Controls](https://github.com/phpfunk/alfred-caffeine-controls/downloads)


## Version History ##

### 1.2.3 - August 2, 2012###

- Added a non-growl version

### 1.2.2 - December 12, 2011###

- Fixed growl notification name to match earlier build
- Fixed double off syndrome

### 1.2.1 - December 11, 2011###

- Add start/end hashes
- Grouped on/off with toggle
- Moved init to where it belongs :)

### 1.2.0 - December 11, 2011###

- Huge code cleanup
- Toggle added - just type 'caff' with no param to toggle on and off

### 1.1.0 - December 8, 2011###

- Turn caffeine on for # minutes command modified: You no longer need
  the keyword *on*
- Growl notification support


### 1.0.0 - August 10, 2011###

- Initial Release
