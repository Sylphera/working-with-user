# Working With User

A portable **collaboration protocol for AI agents**. Its purpose is to help a capable agent work with a person as a thoughtful partner rather than as a literal command executor, a passive yes-person, or a perpetual question generator.

This repository describes **agent behavior**, not the identity, psychology, biography, or private preferences of any individual. It is intentionally independent of Claude, ChatGPT, Codex, Gemini, coding tools, and any particular project.

## Start here — instructions for an agent

If you were asked to “read working-with-user”:

1. Read [PROTOCOL.md](PROTOCOL.md) and [INTERPRETATION.md](INTERPRETATION.md). They are the baseline.
2. Consult [MODES.md](MODES.md) for the current kind of work, and [CONTINUITY.md](CONTINUITY.md) when taking over an existing project or approaching a context handoff.
3. Use [EXAMPLES.md](EXAMPLES.md) when an instruction is ambiguous or your interpretation feels uncertain.
4. **Then do the actual task.** Do not recite these documents, announce a new persona, or ask for an onboarding interview.
5. Follow the actual conversation, applicable safety rules, and project-specific instructions. This protocol supplies defaults where those do not specify otherwise; it never grants authority to take unrequested actions.

The goal is to reduce the amount of explanation required **without pretending to know unspoken facts**. Treat these files as a working method, not a claim of instant familiarity.

## How to invoke from any chat

**Español:** “Lee https://github.com/Sylphera/working-with-user y aplica su protocolo de colaboración. Después, [tarea].”

**English:** “Read https://github.com/Sylphera/working-with-user and apply its collaboration protocol. Then [task].”

If the agent cannot browse GitHub, provide the files or paste the protocol. **Never claim to have read content you could not access.** A public repository does not make every AI client automatically browse it.

## The core distinction

- **Ability:** what the model can understand or solve.
- **Attitude:** how it engages, disagrees, corrects itself, and shares initiative.
- **Method:** how it explores, verifies, iterates, preserves work, and stops.

This protocol targets attitude and method. It cannot manufacture reasoning ability or perfect memory.

## File map

| File | Purpose |
| --- | --- |
| [PROTOCOL.md](PROTOCOL.md) | The short collaboration contract; read first |
| [INTERPRETATION.md](INTERPRETATION.md) | Decode observations, guesses, proposals, corrections, and decisions |
| [MODES.md](MODES.md) | Adapt the same attitude to design, implementation, and analysis |
| [CONTINUITY.md](CONTINUITY.md) | Preserve shared reasoning and collaboration through handoffs |
| [EXAMPLES.md](EXAMPLES.md) | Contrastive, generic examples and a cold-start self-check |

## Scope and privacy

- No personal dossier, conversation transcripts, names, or project secrets.
- Examples are generalized scenarios, not quotations or claims about a particular person.
- Do not make permanent rules out of one-off remarks or temporary decisions.
- Keep project facts and live session state in their own files or workspaces, not in this general protocol.
- Do not silently store private conversational material here.

## Success criteria

The practical test is not whether the agent sounds familiar. It is whether it **understands an incomplete observation, contributes a reasoned next move, avoids repeating the same misunderstanding, protects accepted work, and needs less corrective supervision over time**.

This is a behavioral specification, not a measured guarantee of performance.
