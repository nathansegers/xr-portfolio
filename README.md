# XR Archipelago

A spatial portfolio built with three.js: floating islands per project that you scroll between on desktop, step into with WebXR on a headset, or place on a table in AR.

- **Desktop / mobile:** scroll or swipe between islands; **Portal** mode uses the front camera (MediaPipe face tracking) for head-coupled perspective — lean in to zoom.
- **Hand cam (mobile back camera, or a laptop webcam):** pinch the ball to lift and throw it, swipe an open hand through it to kick. An invisible depth-only hand lets your real hand pass in front of the ball and islands.
- **VR (Quest, Android XR):** poke buttons, pinch to grab, throw the ball, palm-up menu.
- **AR (Android Chrome, Quest):** tap to place, swipe to throw, depth occlusion, optional back-camera hand tracking.

Everything lives in a single `index.html` (three.js and MediaPipe load from jsDelivr).

URL switches: `?portal=mouse`, `?hands=mesh|spheres|none`, `?layers=0`.
