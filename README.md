#### WTF?

Get some info when the status of a tracked UPS packet updates. Polls
webinterface.

#### How to

Fire up with <code>./track_ups TRACKINGNUMBER &</code> to have it run in background

Scans for changes in status every 60s. If found, say something and opens
status page in browser.

#### TODO:

* parse file instead of relying on diff
* support DHL, Hermes, ...
* APIs???
* Daemonize
* Multiple packets?
