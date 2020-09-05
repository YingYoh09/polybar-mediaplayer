# polybar-mediaplayer

A minimal script to get current media title and artist for [Polybar](https://github.com/jaagr/polybar) which playerctl support (spotify, google-chrome, firefox,...)

![screenshot](image.jpg)  
[test link](https://youtu.be/F5tS5m86bOI)

## Dependencies
* [python3](https://www.python.org)
* [Nerd Font](https://nerdfonts.com/)
* [playerctl](https://github.com/altdesktop/playerctl)

## Usage
Polybar config
```  
[module/mediaplayer]  
type = custom/script
interval = 2
exec = /path/to/mediaplayer_get.py
````
