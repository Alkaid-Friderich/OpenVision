# OpenVision

> See again what you once saw. See what others could see.
>
> 重新看见自己曾经看见的，也能在获得授权的前提下，看见他人所见。

OpenVision is an open-source initiative exploring how human-visible experience can be captured, represented, reconstructed, and displayed across devices.

OpenVision 是一个探索人类视觉经验数字化的开源项目。我们希望建立从视觉采集、开放表征、空间重建到跨设备显示的端到端技术体系。

## Why OpenVision?

Today's cameras record images. OpenVision explores how to preserve the observer's viewpoint: imagery, stereo vision, motion, depth, gaze, optics, time, and provenance.

The project does not claim to reproduce consciousness or read visual memory. Its goal is to build measurable, inspectable technology that progressively approaches a faithful reconstruction of what was visible to an observer.

## Initial scope

The first milestone is a narrow end-to-end pipeline:

1. Capture first-person video, device pose, and calibration metadata.
2. Package them in an open, inspectable OVX recording.
3. Replay the recording with the original orientation and field of view in a browser or WebXR device.

Later phases may add stereo capture, eye tracking, depth, six-degree-of-freedom reconstruction, HDR appearance, and perception-aware display.

## Project areas

- **Capture** — reference mobile and wearable capture implementations.
- **OVX** — an extensible format for visual recordings and their provenance.
- **Processing** — synchronization, calibration, stabilization, and spatial reconstruction.
- **Player** — cross-device playback for browsers, XR headsets, and future displays.
- **Evaluation** — reproducible tests for geometric, temporal, optical, and perceptual fidelity.

## Status

OpenVision is in its founding stage. The current material defines the direction and a draft structure; it is not yet a stable specification or production implementation.

See the [project vision](docs/vision.md), [roadmap](docs/roadmap.md), and [OVX draft](specs/ovx/README.md).

## Principles

- Preserve original sensor data and store processing as traceable derivatives.
- Make time synchronization, calibration, and device descriptions first-class data.
- Clearly label captured, reconstructed, inferred, and generated content.
- Design for incomplete recordings and progressive enhancement.
- Treat consent, privacy, ownership, and revocation as architectural requirements.

## Contributing

Early contributions are welcome in specification design, capture, reconstruction, playback, perception research, privacy, and documentation. Read [CONTRIBUTING.md](CONTRIBUTING.md), [ETHICS.md](ETHICS.md), and [GOVERNANCE.md](GOVERNANCE.md) before opening a proposal.

## License

Code and project documentation are currently released under the [Apache License 2.0](LICENSE), unless a file states otherwise. Sample recordings and model weights may use separate, explicitly documented terms.
