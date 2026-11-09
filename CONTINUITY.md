# Continuity across sessions and context compaction

Continuity is not just a list of tasks. A productive session develops **shared criteria for judging results**. A handoff that preserves only code locations and outstanding actions may technically resume a project while losing the ability to interpret feedback naturally.

This protocol itself is general and public. **Keep live session details, private information, and project-specific history in the relevant private/local workspace—not in this repository.**

## Two distinct kinds of memory

### Stable, cross-session method
- How to distinguish observations, theories, exploratory ideas, decisions, and authorization.
- Expected level of independent judgment and constructive disagreement.
- How to handle critique without defensiveness, pointless repetition, or automatic agreement.
- The boundary between a suggestion and permission to execute.

These rules live in [PROTOCOL.md](PROTOCOL.md) and [INTERPRETATION.md](INTERPRETATION.md).

### Session-specific shared understanding
- What is being built or decided, and why.
- Which aspects are already accepted and must not regress.
- Which proposals are tentative, rejected, or superseded—and the reason.
- The evidence that changed the group's mind.
- **Successful reasoning patterns:** a particularly useful reframing, an accepted disagreement, or a correction that unlocked progress—and *why* it worked.
- **Working rapport in task terms:** whether the work is exploratory or execution-focused; when the agent should be bold with ideas versus cautious with side effects. Do not serialize private personality judgments or intimate conversational details.
- What forms of verification matter for this particular work.
- Which actions are authorized and which remain proposals.
- The last concrete state, current blockers, next useful action, and source locations.

This is dynamic context. It should be handed off with the task, not copied into public generic instructions.

## The handoff should preserve *why*

A weak handoff:

> “The animation was changed. Next: fix responsiveness.”

A strong handoff:

> “The earlier interaction was liked for continuous momentum; a later implementation was rejected because it restarted speed at every target change. Preserve the accepted layout while diagnosing perceived discontinuity. Passing frame-rate averages are not proof of smooth interaction. Current task is responsive scaling; no redesign was authorized.”

The second version gives the next agent a basis for judging new work. It does not merely provide a list of files.

## Compact session handoff template

Use the following sections when a transfer or compacting summary is being prepared:

1. **Objective and mode** — what is currently being designed, built, or evaluated; whether the task is exploratory, authorized for implementation, or read-only.
2. **Current state** — exact completed work, tests, versions, branches, files, and what remains incomplete.
3. **Accepted invariants** — features, aesthetics, behaviors, or decisions already approved; protect them.
4. **Shared evaluation criteria** — why certain options were accepted or rejected, with the evidence that mattered. Include one or two representative *successful ways of reasoning together*, not only failures and prohibitions.
5. **Important corrections** — misconceptions previously made by the agent, and the corrected interpretations.
6. **Open hypotheses** — distinguish observed facts from suspected causes and untested ideas.
7. **Boundaries** — permissions, protected work, privacy, environment safety, and actions that require approval.
8. **Next move** — the most useful next action, grounded in the current instruction.
9. **Sources of truth** — where the actual artifacts, specifications, decisions, and original conversation can be checked.

Include enough detail to preserve judgment but not a full transcript. For long work, point to actual files or artifacts so the next agent can verify rather than invent details.

## Portability and persistence limits

This repository is a **portable starting protocol**, not a cross-platform memory system. Different agents and clients offer different memory, compaction, file access, and persistent-context facilities. Do not assume the current client can write to persistent memory or load private files automatically.

When context reduction is approaching:
1. If the client supports persistent or session-local handoff files and the work's authorization allows it, update the *private task-context* handoff before the loss occurs.
2. If it does not, produce a self-contained handoff for the next agent and state plainly that the user or host must preserve it.
3. Include the real source of truth, the active decision criteria, and one meaningful example of *why* a previous correction or disagreement improved the work.
4. Do not publish private session material into this public repository as a workaround.

If a platform supplies a compacted summary plus a few recent verbatim turns, read **both**; later turns may supersede the summary. Cross-check volatile facts against current artifacts instead of assuming the summary is up to date.

## Recovery after loss of context

1. Read the current task and any handoff.
2. Check current source-of-truth material for volatile claims or details omitted from the summary.
3. Distinguish retained facts from inferred reconstructions.
4. Continue within the last authorized scope; do not manufacture a new approval ceremony.
5. If a genuinely material detail is absent, ask one focused question. Do not ask for already documented information.
6. Correct stale handoff statements when fresh evidence disagrees.

Never pretend the summary is a complete recollection of an earlier dialogue.

A good recovery is neither a fresh formal onboarding nor an imitation of remembered jokes. It restores the **shared decision process**: what is accepted, what remains uncertain, where the agent can contribute judgment, and what evidence would change the current plan.

## Updating what is learned

A session may reveal a useful, general interaction principle. Before making it persistent:
- Verify it occurred more than once, or that the reasoning is broadly applicable.
- Store the *distinction learned*, not a personality judgment or a one-off command.
- Record a counterexample or limit so it is not overgeneralized.
- Keep personal and project-specific details out of public documents.
- Avoid automatic writes to any memory repository without authorization.

**Measure success by fewer repeated corrections, fewer lost decisions, and quicker return to productive collaboration—not by an agent claiming to remember everything.**
