# AGENTS.md

Read [CLAUDE.md](./CLAUDE.md) and [README.md](./README.md) first.

## Scope

Do not add source, build output, screenshots, keys, or docs. Do not edit `index.html` here. Change the policy in the app repository, then copy `store/privacy-policy.html` over `index.html`.

When a change makes a sentence in CLAUDE.md, AGENTS.md, or a Cursor rule false, delete or rewrite that sentence in the same change.

## Refinement ladder

Before ending substantial work, read `~/.cursor/skills/retro/SKILL.md` and run its harvest. Do not wait to be asked. A retro that changes no file did not happen.

A lesson climbs. Leave it on the lowest rung that will hold it, and move it up when that rung fails.

1. **Stage.** A first sighting is one dated line in `~/.cursor/retro/staged.md`, with its artefact. That file is not loaded into a session.
2. **Rule.** A second sighting, or a miss that nearly shipped or cost more than about half an hour. The same claim goes in `CLAUDE.md` and one `.cursor/rules/*.mdc` (one concern, under 50 lines). The entry is the rule, not the incident: no dates, PR numbers, or `file:line`.
3. **Firing.** If a rule already said it and the miss happened anyway, add no line. Fix the firing: the wrong file, a vague sentence, or a rule that is wrong and must be retracted in every copy.
4. **Guard.** If a test or a script can catch it, write the guard and delete the prose. The change that removes a line names the guard.

**Mistakes not to repeat** is capped. Adding an entry means superseding or retiring another.

Do not invent a lesson. No artefact, no landing.
