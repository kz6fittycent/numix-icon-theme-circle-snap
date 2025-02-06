[![🧪 Snap Builds](https://github.com/kz6fittycent/numix-icon-theme-circle-snap/actions/workflows/test-snap-can-build.yml/badge.svg)](https://github.com/kz6fittycent/numix-icon-theme-circle-snap/actions/workflows/test-snap-can-build.yml)

# numix-icon-theme-circle-snap
A Snap for the [Numix Circle icon theme](https://github.com/numixproject/numix-icon-theme-circle/).

## Install the snap

`sudo snap install numix-icon-theme-circle`

## Connect the icon theme 

```
for i in $(snap connections | grep gtk-common-themes:icon-themes | awk '{print $2}'); do sudo snap connect $i numix-icon-theme-circle:icon-themes; done
```
