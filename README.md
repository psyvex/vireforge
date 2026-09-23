# VireForge

VireForge is a privacy-first, local-first 3D creative studio for turning photographs into digital humans and then using those humans as creative assets for scenes, animation, image/video rendering, motion capture, and export.

The product is intentionally broader than “photo to GLB”. The 3D avatar is the foundation of an editable creative workspace.

## Core principles

1. Local-first: photos and project data remain on-device by default.
2. Production-grade: correctness, profiling, memory, testing, and capability detection are first-class.
3. Progressive reconstruction: one photo is useful; additional views improve observed geometry, texture, and confidence.
4. Observed vs inferred: the system must distinguish captured evidence from estimated content.
5. Capability-aware: WebGPU, WASM SIMD/threads, codecs, and ML model support vary by browser/device.
6. Modular engine: inference, reconstruction, geometry, physics, rendering, animation, and export are independent subsystems.
7. Creative studio: avatar creation is the foundation; scenes, cameras, lighting, animation, image/video export, mocap, and future tools sit above it.

## Documentation

Architecture and planning documents live in `docs/`.

- `docs/01-product-vision.md` — product scope and long-term capability map
- `docs/02-architecture.md` — system architecture and subsystem boundaries
- `docs/03-reconstruction-pipeline.md` — single- and multi-view reconstruction pipeline
- `docs/04-runtime-and-performance.md` — WebGPU, WASM, workers, memory and performance
- `docs/05-project-format-and-export.md` — project model and export pipeline
- `docs/06-roadmap-and-acceptance.md` — implementation phases and quality gates
- `docs/07-architecture-decisions.md` — recorded architecture decisions

Implementation should begin only after the architecture is reviewed and the major decisions are accepted.
