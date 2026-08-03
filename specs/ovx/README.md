# OVX recording format — early draft

OVX is a proposed open package for synchronized visual data, device calibration, spatial representations, provenance, and consent metadata.

This document is exploratory and not a stable specification.

## Design goals

- Human-inspectable during early development.
- Extensible without invalidating simpler recordings.
- Explicit time bases and coordinate systems.
- Original inputs preserved separately from derived outputs.
- Provenance for every reconstruction, inference, and generation step.
- Privacy and consent metadata that can be enforced by tools.

## Candidate package layout

```text
recording.ovx/
├── manifest.json
├── video/
│   ├── left.mp4
│   └── right.mp4
├── telemetry/
│   ├── pose.jsonl
│   ├── gaze.jsonl
│   └── exposure.jsonl
├── calibration/
│   ├── camera.json
│   └── display.json
├── spatial/
│   ├── depth.mp4
│   └── scene.glb
├── provenance.json
└── consent.json
```

All elements except `manifest.json` are expected to be optional and declared by the manifest. A future revision will define schemas, identifiers, clock relationships, coordinate conventions, integrity checks, and access-control behavior.

## Content origin labels

OVX tools should preserve one of these origins for each stream or asset:

- `captured`: directly recorded by a sensor;
- `reconstructed`: computed from recorded geometric or multi-view evidence;
- `inferred`: estimated by a model where direct evidence is incomplete;
- `generated`: synthesized content not present in the source observation.
