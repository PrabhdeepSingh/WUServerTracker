# Introduction
**Wurm Unlimited Server Tracker** - is a live game server tracker.

# Demo
This is the horizontal version: ![alt text](http://wua.xplosivegames.com/servers/tracker/horizontal.png "Horizontal Server Tracker")
This is the vertical version: ![alt text](http://wua.xplosivegames.com/servers/tracker/vertical.png "Vertical Server Tracker")

# Requirements / Dependencies
The following programs and modules are required to run WUServerTracker

- LAMP/WAMP, Nginx, or UniServerZero XI running PHP 5.5.0 or higher.
- Wurm Unlimited Server with RMI enabled
- [WUAHelper](https://github.com/PrabhdeepSingh/WUAHelper) - Used for RMI

# Installation
#### Download
- Download or clone from GitHub

#### Application configuration
This is a basic configuration / setup guide on getting this software up and running on your host.
- Place files from this repo into your `www` folder
- Open the `config.php` file`
  - In the `$rmiConfig` array change the `ip, port, and password` to your RMI details
  - Save and close
If everything goes smoothly you should be able to navigate via your brower to your WUST folder and test out the game tracker

#### Wurm Unlimited configuration
To interact with your WU server you need to enable RMI on it, and to do that you need to edit `wurm.ini` file
- Go to your `wurm.ini` file
  - Add the following line at the end of the file: `USE_INCOMING_RMI=true`
  - Save the file and start the server
If everything goes smoothly you should see `RMI Registry listening on ........`

# Usage

- To view the horizontal version in your browser navigate to to your //webhost/WUServerTracker/horizontal.png
- To view the vertical version in your browser navigate to to your //webhost/WUServerTracker/vertical.png