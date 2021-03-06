# Conway's Game Of Life in 3D
> A JavaScript implementation of Conway's game of life in 3D.

This demo generates a representation of 3D world with WebGL and processes the
"living world" in a separate thread with HTML5 Web Workers.

## Example
You can find an example at a local tilde.club server:

http://palvelin.club/~jehna/game-of-life-3d/

Here's a screenshot of an example game:

![example image](http://i.imgur.com/QTbhNDX.gif)

## Additional info

Here are a few details:
- Uses [Three.js](http://threejs.org/) to render world in WebGL
- The "living world" is processed in a separate thread via [Multithread.js](keithwhor.github.io/multithread.js/)
- The script is mobile-friendly and runs well with iPhone
- Medium world runs decently in iPhone 5 / iOS8

## Contributions
Contributions are warmly welcome via pull requests.

Please open an issue beforehand and use feature branches.

### Thank you
A special thank you for forcing me to actually code this to [lehtu](https://github.com/lehtu)

## License
The work is licensed under MIT license