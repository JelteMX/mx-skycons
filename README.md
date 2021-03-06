# Skycons for Mendix

Skycons for Mendix implements 10 animated weather icons from the Skycons library for use in your Mendix Application
The original Skycons repository can be found [here](https://github.com/darkskyapp/skycons)

## Contributing

For more information on contributing to this repository visit [Contributing to a GitHub repository](https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)!

## Typical usage scenario

For weather information on, for example dashboards

## Description

The Mendix implementation of the Skycons library allows the user to show of one ten available, animated, weather icons in your application.

## Configuration & Properties

The widget does not need an entity as it's context, but will work nonetheless
Place the widget at the desired location on your page. The widget properties are pretty straightforward:

* Icon - What type of icon to display
* Width - The width of the canvas element
* Height - The height of the canvas element
* Colors - Whether to use one color or 'real-life' coloring (ie. the sun is yellow, and raindrops are blue) or a single color for the entire icon
* Color - If at the 'Colors' property 'One Color' is selected, what color should the icon be?
* Animate - Whether to animate the icon or not.


## Known issues and bugs

We ran into a 'Constructor not found' issue when navigating to / from the page the widget was on. However, recently the widget has been working fine, both in a sandbox environment as locally. If you do run in to this issue, and know how to solve is, let us know. Or better yet, issue a Pull Request on Github!
