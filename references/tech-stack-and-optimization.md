# Tech Stack Decision & Optimization Reference

## Priority Guidance

After understanding the exact desired outcome:
1. Strongly prioritize React + TypeScript + React Three Fiber + Three.js + WebGL + Remotion when the outcome benefits from cutting-edge 3D, cinematic motion, complex parallax, particle systems, product configurators, immersive storytelling, or high-fidelity interactive visuals.
2. Otherwise select the stack that best achieves the exact outcome with maximum performance and scalability (Next.js, vanilla HTML5 + Web Components + Three.js, other frameworks, C++/WASM modules, etc.).
3. Always justify with research-backed reasons and log the decision into the knowledge base.

## Justification Template
- Desired outcome mapping
- Research sources supporting the choice
- Rejected alternatives and why
- Performance characteristics at 1 M concurrent users

## Performance Optimization Techniques (Zero Design Degradation)

### General
- Route- and component-level code splitting
- Dynamic import + React.lazy + Suspense
- Asset preloading / prefetch with priority hints
- HTTP/3 + Brotli + long-cache immutable assets
- Critical CSS inlining; defer non-critical
- Image: AVIF/WebP with responsive srcset + sizes; quality matching design intent

### React / R3F Specific
- memo / useMemo / useCallback only where measured benefit
- R3F instancedMesh / Instances for repeated geometry
- Adaptive quality that never drops below design-specified visual floor
- Texture compression (KTX2 / Basis) matching design quality
- Geometry LOD + frustum culling + occlusion culling
- Frame-loop management (demand vs always)
- WebGL context management

### Motion / Parallax / Remotion / Shading
- CSS transform / opacity for compositor-friendly animations
- prefers-reduced-motion: equivalent non-motion path that preserves information and emotional intent
- Remotion: pre-render critical sequences; progressive enhance for interactive
- Physically-based shading and lighting techniques that remain performant

### Scalability for 1 M Concurrent
- Fully static or edge-rendered shell
- Client-side 3D only after interaction or viewport entry
- Stateless API layer
- CDN for all assets; origin shielded
- Rate limiting / bot protection at edge
- Observability: Real User Monitoring for LCP/INP/CLS + custom 3D frame-time metrics
