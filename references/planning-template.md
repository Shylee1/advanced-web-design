# Exhaustive Scope Planning Template

Use this exact structure for Stage 1 output. Fill every section. Leave no ambiguity. Include all design aspects.

## 1. Project Vision & Finish Line
- One-sentence end-state description (exact user outcome)
- Success criteria (measurable)
- Explicit user constraints (copy verbatim)
- Opportunities to exceed expectations (beneficial details the user may not have specified or been aware of)
- Trajectory awareness note (current stage vs finish line)

## 2. Narrative / Storyline / User Journey
- Primary user persona(s)
- Emotional arc and story beats
- Page/section sequence that tells a coherent story
- Purpose statement for every major area (must serve a distinct purpose; content must belong only there)

## 3. Information Architecture, Functions & Workflows
- Site map / page hierarchy
- Section inventory with purpose justification
- Content ownership rules (what belongs where, what is forbidden in each area)
- Redundancy elimination plan
- Functions, user workflows, state machines, edge cases

## 4. Full Visual System
- Layout grid system (desktop / tablet / mobile)
- Spacing scale
- Typography scale + font pairings (with sources)
- Color system (primary, secondary, accent, neutral, semantic) + contrast ratios
- Textures, materials, shading, lighting
- Depth / elevation / 3D treatment rules
- Motion / parallax / micro-interaction principles / animation timelines / cinematic sequences
- Anti-patterns to avoid (industry-specific and general)

## 5. Interaction Model
- Primary interaction patterns
- Micro-interactions inventory
- Gesture / scroll / hover / focus behaviors
- Reduced-motion fallback strategy (must preserve full information and emotional intent)

## 6. Component Inventory
- Atomic to organism list
- Reusable vs one-off
- State matrix for each interactive component

## 7. Tech Stack Decision
- Chosen stack with full justification (research-backed)
- Why React + R3F + Three.js + WebGL + Remotion was or was not selected
- Alternative stacks considered and rejected (with reasons)
- Required libraries / versions / build tooling

## 8. Performance Budget & Optimization Strategy
- Target metrics (LCP, INP, CLS, TTI, bundle size, GPU memory, frame time)
- Per-feature optimization technique (never by removal or simplification)
- Code-splitting / lazy-loading / asset strategy
- WebGL / 3D specific optimizations (instancing, LOD, frustum culling, texture compression, etc.)
- Caching / CDN / edge plan

## 9. Responsiveness Strategy
- Breakpoints
- How complex elements (3D, parallax, motion, shading) adapt without visual degradation
- Touch vs pointer differences
- Testing matrix (device classes)

## 10. Scalability Plan (1 M Concurrent Users)
- Architecture diagram (high-level)
- Stateless design points
- Edge / CDN / serverless recommendations
- Database / API scaling notes if applicable
- Failure modes and mitigations

## 11. Accessibility, SEO, AEO, GEO, AI-Agent Compatibility, Security, Analytics
- WCAG 2.2 AA checklist items specific to this design
- Semantic HTML / ARIA strategy
- SEO meta / structured data plan
- AEO (Answer Engine Optimization) plan
- GEO (Generative Engine Optimization) plan
- AI-agent compatibility: agents must be able to interact with, view, and read everything (content, controls, state, structure)
- Security headers / CSP / auth notes
- Analytics events

## 12. Exact Ordered Build Sequence
- Numbered steps, fewest possible
- Dependencies between steps
- Checkpoint / adherence-check points
- Sub-agent delegation opportunities

## 13. Pre-Approval Checklist
- [ ] Every user requirement extracted and mapped
- [ ] Every section has a purpose statement
- [ ] No redundancy; flows and workflows complete
- [ ] Narrative flows
- [ ] Visual system complete (textures, shading, 3D, motion, etc.)
- [ ] Performance strategy preserves full design
- [ ] Tech stack justified with sources
- [ ] 1 M-user readiness addressed
- [ ] SEO, AEO, GEO, and AI-agent compatibility addressed
- [ ] Opportunities to exceed expectations noted
- [ ] Ready for user approval
