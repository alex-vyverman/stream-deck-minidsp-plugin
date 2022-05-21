# stream-deck-minidsp
 A plugin to control miniDSP
 The heavy lifting of the back-end is entirly based on https://github.com/mrene/minidsp-rs, and it's HTTP API daemon. Much respect to Mathieu Rene for his hard work!

1. Go to https://github.com/mrene/minidsp-rs/releases and download the appropriate release for your system.
2. start up the 'minidspd' daemon on your local system, or a remote system on your network that has your miniDSP devices connected to it on USB.
3. install the plugin and configure the action. Each button action represents a preset number you can switch to.
4. Enjoy and post issues or pull requests!

This is a very primitive first release, so lower your expectations accordingly.
I've only tested this so far on macOS Big Sur on my local machine
