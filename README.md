# DontEatMyContent
Prevent the notch/Dynamic Island from munching on 2:1 video content in YouTube

## Update (Oct. 31, 2022)
YouTube's new 8x zoom feature (I'm still looking for **who**) completely broke the tweak on my device. I still haven't identified a fix for it yet.

## How It Works
The rendering view is constrained to the safe area layout guide of its container, meaning it will always be below the notch and, presumably, Dynamic Island. These constraints are only activated when viewing videos with 2:1 aspect ratio (or wider; untested) to prevent unintended side effects on videos with smaller aspect ratios. 

## Compatibility
Supports iPhone 12 mini, iPhone 13 series and newer **except** iPhone SE 3rd generation, iPhone 13 Pro Max and iPhone 14 Plus.

## Grab It
* Tweaked YouTube app: https://therealfoxster.github.io/altsource/app.html?id=youtube
* .deb file: https://github.com/therealFoxster/DontEatMyContent/releases/latest

## Screenshots (iPhone 13 mini)

### Original Implementation
![original](../assets/screenshots/IMG_2096.PNG)

### Tweaked Implementation
![tweaked](../assets/screenshots/IMG_2097.PNG)

### Zoomed to Fill
![zoom to fill](../assets/screenshots/IMG_2098.PNG)
