Have you ever watched a 3D movie and wondered how software winds up with such a true-to-life image?

Unlike video games, which use complicated and math-intensive tricks for realtime graphics, movie studios render 3D films like “Frozen” or “Big Hero 6” via an elegant and intuitive algorithm called “path tracing”. Path tracing is a computer graphics Monte Carlo method of rendering images of three-dimensional scenes such that the global illumination is faithful to reality. Fundamentally, the algorithm is integrating over all the illuminance arriving to a single point on the surface of an object. Path tracers simulate actual photons of light bouncing around a scene, reacting to the objects and materials they encounter. Such programs run slowly, but render beautiful images, and they’re surprisingly easy to write and understand. In this talk, we’ll explore this fascinating algorithm with examples in JavaScript.

![example](https://pbs.twimg.com/media/DAugql3W0AAQUtm.jpg:large)
