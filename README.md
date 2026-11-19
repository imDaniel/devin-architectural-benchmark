# Devin Architectural Digital Twin Benchmark

An open-source engineering benchmark for reconstructing ten iconic architectural landmarks using Three.js, WebGPU and autonomous Devin coding agents.

## First Target: Sagrada Família

The initial milestone focuses on Gaudí-inspired procedural geometry, including hyperboloids, helicoids and branching columns.

## Devin Bots Workflow

1. Geometry Agent — TypeScript parametric mesh generators.
2. Asset Agent — Photogrammetry ingestion, glTF conversion and LOD optimization.
3. Rendering Agent — Next.js, React Three Fiber and WebGPU viewer.
4. QA Agent — Hausdorff-distance validation, Vitest and Playwright regression tests.
5. Integration Agent — CI pipelines, code review and performance benchmarks.

## Acceptance Criteria

- Reproducible procedural geometry
- Configurable adaptive tessellation
- Reference mesh distance validation
- Automated visual regression
- Documented CI and performance measurements

## Execution Model

Each milestone is assigned to an independent Devin run, delivered as a reviewable pull request with measurable acceptance criteria.

Status: Planning / Initial benchmark specification.
