# Sand Pendulum Lissajous Art Drawer

Simulates a damped Lissajous sand pendulum that draws spiraling colored patterns on a black canvas. The x and y oscillations have independently configurable integer frequency ratios, a phase offset, and an exponential decay rate that causes the amplitude to shrink over time — exactly like a real sand pendulum losing energy. The hue cycles continuously as the path is drawn, creating rainbow layered sand effects.

## Features

- X and Y frequency sliders (integers 1–8) for classic Lissajous ratios
- Phase offset slider (0–2π) to shift the figure shape
- Decay rate slider controlling how quickly the oscillation damps out
- Draw speed slider (1–10×) for fast or slow trace
- Hue start slider to begin the color cycle at any point on the wheel
- Pause/Resume animation control
- Reset & Redraw button applies current slider values and starts a fresh canvas
- Download PNG saves the current canvas artwork
- 540×540 black canvas with anti-aliased line rendering
- Pure Canvas 2D API, no external libraries
