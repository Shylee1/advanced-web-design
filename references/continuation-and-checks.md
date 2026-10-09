# Continuation Protocol & Periodic Checks

## Output Limit Handling
1. Complete the current logical unit (sentence, function, component, or checklist item) if possible.
2. Append exactly this sentence on its own line:
   Reached output limit. Reply 'continue' to resume precisely where left off.
3. On the subsequent user message containing "continue" (or equivalent), resume at the exact character/code point of interruption.
   - No summary of prior work
   - No re-statement of the plan
   - No "as I was saying"
   - Pure continuation

## Periodic Adherence Checks (Mandatory)
Insert a short adherence block after:
- Completion of Stage 1 scope
- Each major section or component in Stage 3
- Any user-requested iteration
- Final Stage 4

Adherence block format:
### Adherence Check
- Plan item X: [matched / deviation]
- User instruction Y: [matched / only the requested change applied]
- Design fidelity: [no simplification]
- Exceed-expectations additions: [list if any]
- Trajectory: [N% complete - remaining: list]
- Sources / knowledge-base entries used this step: [notes]
- Sub-agents used (if any): [list]
- SEO / AEO / GEO / AI-agent compatibility: [status]

## Iteration Rules
- User states exact change -> apply only that change.
- All other files, styles, components, narrative, and performance strategies remain untouched.
- Re-run research only for the changed portion.
- Re-issue adherence check after the change.

## Trajectory Awareness Statement
At the start of every major output after Stage 1:
Current stage: [name]
Progress toward finish line: [description]
Remaining critical path: [short list]

## Sub-Agent Delegation (when supported)
Spawn sub-agents for:
- Parallel trend / technique research
- Independent component or section implementation
- Optimization and performance validation
- Accessibility / SEO / AEO / GEO / AI-agent compatibility testing
Coordinate results back into the main trajectory.
