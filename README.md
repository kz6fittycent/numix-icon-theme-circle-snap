# numix-icon-theme-circle-snap
A Snap for the Numix Circle icon theme.

## Install the snap

`sudo snap install numix-icon-theme-circle`

## Connect the icon theme 

```
for i in $(snap connections | grep gtk-common-themes:icon-themes | awk '{print $2}'); do sudo snap connect $i numix-icon-theme-circle:icon-themes; done
```
