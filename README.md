## react-compound-slider

Under heavy development.

# Installation

React Compound Slider is available as an [npm package](https://www.npmjs.org/package/react-compound-slider).

## npm

To install and save in your `package.json` dependencies, run:

```
npm install react-compound-slider
```

## [Tutorial](https://goo.gl/8nCBqt)

## [Live Demos](https://goo.gl/RsrByr)

The main idea of this library starts from an observation that slider components are really just a relatively positioned outer div with elements absolutely positioned inside by a percentage.
In this library the `Handles`, `Tracks`, and `Ticks` components are used as children to the `Slider` component and they let you tap into a stream of values and percentages that you can then render using your own components.

This is a [compound component](https://www.youtube.com/watch?v=hEGg-3pIHlE) approach to creating sliders that separates the logic from the actual presentation.
In practical terms this means you can create just about any kind of slider you can imagine and use whatever style approach you want.
The library also has nothing to do with markup.  You can render whatever markup you want.
The `Slider` just streams you the data and really only cares about the dimensions of the outer div where it takes its measurements from.
