# Project vision

OpenVision asks how an observer's relationship with a visible environment can be recorded and reconstructed at another time, place, or display.

A conventional video primarily stores images. A richer visual record may also describe stereo views, depth, observer pose, gaze, optics, exposure, timing, environment, provenance, consent, and access conditions.

Conceptually, a visual record can be described as:

```text
V = {I, D, P, G, O, E, C}
```

- `I`: image or multi-view optical data
- `D`: depth and spatial structure
- `P`: observer position and head pose
- `G`: gaze, fixation, and optional pupil state
- `O`: capture and display optical models
- `E`: exposure, illumination, and environment metadata
- `C`: time, place, consent, provenance, and privacy context

Not every recording needs every component. OpenVision is designed for progressive enhancement: a valid video-and-pose recording can later be accompanied by depth, gaze, reconstruction, or improved calibration.

## Long-term outcome

OpenVision aims to make visual records preservable, portable, inspectable, and shareable with consent. It seeks perceptual fidelity through measurable engineering, while maintaining a strict distinction between sensor evidence and algorithmic synthesis.
