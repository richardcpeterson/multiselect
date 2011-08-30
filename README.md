# jQuery UI Multiselect #

I've merged some of the pull requests from the original author's repo to make this plugin useable for me.

If you submit patches I'll try be a little more on top of maintaining them.

## History ##

### 8/30/2011 ###
* Updated so change event is fired on Remove All and Add All

### 8/9/2011 ###

* Merged code from NateEag to fix duplicate items - issues 90 & 91
* Merged code from chickenchan to fix issue with loosing sort order - issue 22
* Updated so width doesn't expand past what the target elements width is. Borders were causing this to happen.
* Add code to trigger the original select boxes change event whenever the list changes.
* Added support for specifying width and height. If not specified it will default to using the target element's dimensions which can be inconsistent if the target is a select element and it's not visisble.

## Original Author's comments ##

This repository is no longer actively maintained by the author. However, pull requests are always welcome. If there's someone interested in officially maintaining the plugin, please let me know.

In case you are looking for an AJAX version, please also consider "Yanick Rochon's":http://github.com/michael/multiselect/tree/next version.