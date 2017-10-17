# RetroGaming



## Status Light  
#6 - GND  
#8 - TXD

Edit your /boot/config.txt file and add the following line:
enable_uart=1

## Button  
### Clone Repo for button: https://github.com/mattsage/Shutdown-Button  
#9 - GND  
#11 - GPIO 17  


## Theme:  
SNES mini: https://github.com/ruckage/es-theme-snes-mini  
Retrorama:https://github.com/lipebello/es-theme-Retrorama  

## Spashscreen  
https://github.com/RetroPie/RetroPie-Setup/wiki/Splashscreen  

/home/pi/RetroPie/splashscreens  
  
## Loading Screens  
https://github.com/retropie/retropie-setup/wiki/runcommand#adding-custom-launching-images  

"The images must be placed at /opt/retropie/configs/SYSTEM_NAME/ and named as launching.png (or .jpg).  

Example: /opt/retropie/configs/nes/launching.jpg."  

A more general launching image (not related to a specific system) can be named as /opt/retropie/configs/all/launching.jpg.  

## Bezels:  
opt\retropie\emulators\retroarch\overlays\borders  

If you permission denied: sudo chown -R pi /opt/retropie/  

Once you have the bezels installed open on retroarch and assign each one to each system (Select + Y)  

Download:  
http://retropie.mrhariasbuilds.com  
https://github.com/lipebello/retrorama-overlay-pack  

## Overlay:  
CRT-PI-CURVATURE
retroarch  (Select + Y)  

## System Icons:  
/home/pi/RetroPie/retropiemenu/icons  
