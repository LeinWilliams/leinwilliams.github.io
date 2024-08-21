# ReadMe

[![Insight logo](insight.svg)](https://leinwilliams.github.io/insight/)

## About
Insight is an application I made to show my controller inputs. The goal was to create an input viewer that has a streamlined aesthetic, but also offers flexible customization options that make it easy to use with applications such as OBS. I've tailored it to suit my particular needs, but perhaps others can find value in it as well. You can [watch a demonstration on YouTube](https://www.youtube.com/watch?v=uW3oDu6yxyY) if you want to see it in action.

## Features
Many of the features are self-explanatory within the application itself, so I'll just highlight a few of them here. I've also intentionally kept the entire application on one file, so saving a local copy is just as simple as right-clicking on the page and selecting "Save as..." All the assets (scripts, images, etc.) are already embedded.

### Coloring
There are some simple color customization options, which can be used for setting something like chroma-keying.

### Button Mapping
Button mapping is supported. If the buttons on your controller don't correlate with the correct buttons visually (and they won't in some cases), you can change them easily from the access bar at the bottom of the page. Some controllers are made so that the d-pad is seen as a control stick instead of four buttons, so you'd need to correct something like that here in order for the inputs to display properly.

### Configurations
Configurations can be saved, downloaded, and loaded back at any time. This is especially useful if you want to use different configurations for various controllers, games, or video/stream overlays.

### Multi-Windows
Insight uses popup windows to display inputs, and this is done for a few reasons. For one, this allows for a window's dimensions to be set to a specific size so that it always appears as the exact size you want it to be in OBS. Another reason is that it can give the window a player-specific title, which can be used by OBS to determine exactly which window is for player 1 and which is for player 2.

## Disclaimer
This was meant to just be a personal project that I initially wasn't going to release to the public. I make no guarantees as to whether it will work on your particular browser of choice. It should at least work in browsers based on Chromium version 127, but it will probably work in most modern browsers anyway.
