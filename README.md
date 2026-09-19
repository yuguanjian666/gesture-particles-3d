# Gesture Particles

A real-time interactive Three.js particle art system controlled through webcam hand gestures.

## Live Demo

[Launch the live experience](https://gesture-particles-3d.yuguanjian666.chatgpt.site)

## Features

- Open or close one hand to gather and disperse the particles.
- Move one index finger left or right to rotate the particle formation.
- Move one index finger closer to or farther from the camera to control zoom.
- Choose from seven particle formations: Heart, Flower, Saturn, Fireworks, Earth, *A Thousand Li of Rivers and Mountains*, and Epiphyllum.
- Adjust particle colors in real time.
- Use a clean, responsive interface with fullscreen support.
- Drag to rotate and use the mouse wheel to zoom when gesture control is disabled.

## Run Locally

Camera access requires HTTPS or `localhost`. The camera cannot be used when the HTML file is opened directly through `file://`.

```bash
python -m http.server 8765
```

Then open [http://127.0.0.1:8765](http://127.0.0.1:8765) in your browser.

When you click **Enable Gesture Control** for the first time, allow the browser to access your camera.

## Technology

- Three.js
- MediaPipe Tasks Vision
- WebGL and GLSL
- Vanilla HTML, CSS, and JavaScript

## Privacy

Camera frames are processed locally in your browser for real-time hand-gesture recognition. They are not uploaded to a server.

## License

[MIT](LICENSE)
