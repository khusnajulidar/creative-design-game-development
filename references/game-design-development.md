# Game Design & Development

## Purpose and scope

Create engaging, coherent, reliable games and interactive play experiences. Game design defines player experience, rules, mechanics, progression, level structure, content, feedback, and balancing. Interactive Learning defines instructional integrity when learning is a goal; UI/UX defines general usability; software development implements technical systems.

## 1. Discovery and concept

Establish audience, platform, player context, session length, goals, genre, constraints, accessibility needs, monetization or distribution assumptions, and success criteria. Define the central player promise and a small set of design pillars. A pillar should guide real decisions, not function as a slogan.

## 2. Core loop and mechanics

Describe the repeated cycle of player action, system response, feedback, reward or consequence, and next choice. For each mechanic define:
- Player intent and available action.
- Rules, inputs, timing, and conditions.
- System response and feedback.
- Success, failure, and recovery.
- Dependencies, edge cases, and exploit risks.

Keep mechanics learnable and internally consistent. Introduce complexity progressively. Ensure controls are appropriate to target devices and accessible input methods.

## 3. Progression and level design

Design onboarding, difficulty curve, challenge variety, pacing, rewards, unlock conditions, checkpoints, replay, and completion. Explain why each level or region exists and what new skill or mechanic it introduces. Avoid arbitrary difficulty spikes, dead ends, and progression that can become permanently blocked.

For adaptive difficulty, define what is measured, how adaptation works, and how player agency and fairness are preserved. Make progress visible and persistent when required.

## 4. Narrative and world

Align setting, characters, tone, objectives, and environmental storytelling with the intended player experience. Keep narrative delivery appropriate to the audience and play context. Track canon, names, chronology, and approved character details. Do not introduce story facts that contradict the project's established world without authorization.

## 5. Game UX and feedback

Design menus, HUD, onboarding, instructions, prompts, feedback, pause, settings, save/load, and completion states. Every important player action should receive understandable feedback. Distinguish selected, focused, recommended, disabled, locked, completed, and unavailable states visually and behaviorally.

Prevent accidental loss of progress. Provide clear recovery from invalid input, interruptions, and errors. Use readable text and controls suitable for the target screen and age group.

## 6. Game architecture

Choose an architecture that fits scope and platform. Separate, where practical:
- Game state and rules.
- Input and interaction.
- Presentation and animation.
- Content/data definitions.
- Progress and persistence.
- Audio and media.
- Platform integration and services.

Use data-driven content for repeated questions, levels, items, or dialogue when it improves maintainability. Validate content schema and identifiers. Avoid unnecessary abstraction in small prototypes, but do not let a prototype's shortcuts silently become production assumptions.

## 7. Production stages

- **Prototype:** prove the central mechanic and key assumptions.
- **Vertical slice:** demonstrate a representative, integrated section at target quality.
- **Production:** build the agreed content and systems.
- **Integration:** assemble assets, code, audio, data, and platform behavior.
- **QA and balancing:** test rules, content, progression, performance, and player experience.
- **Release preparation:** verify build, platform requirements, privacy, licensing, and release assets.

Clearly label prototype limitations. A mockup or isolated function test is not a completed game.

## 8. Content and persistence

Track content source, status, version, difficulty, dependencies, and validation. Keep content distinct from presentation where practical. For saved progress, define data schema, migration strategy, reset behavior, privacy, and failure handling. Test refresh, restart, interrupted sessions, multiple devices, and corrupted or missing data where relevant.

## 9. Educational game considerations

When the game teaches:
- Define learning objectives separately from entertainment goals.
- Ensure questions, hints, feedback, and rewards reinforce accurate learning.
- Match language, cognitive load, reading level, and interaction to the audience.
- Verify factual content against authoritative sources appropriate to the project.
- Do not let speed, guessing, or reward loops undermine the learning objective.
- Make incorrect responses informative and allow appropriate retry or remediation.

Project-specific religious, cultural, or curriculum requirements must be documented in the project brief and verified against its chosen sources.

## 10. Audio, visuals, and performance

Maintain coherent art and audio direction. Ensure effects communicate state without overwhelming the player. Provide mute/volume controls where appropriate and captions or visual equivalents for essential audio cues. Optimize assets, draw calls, memory, loading, and rendering for target hardware. Test on representative low- and high-capability devices when feasible.

## 11. Testing and balancing

Test:
- Core mechanics and all input paths.
- Win, loss, retry, pause, resume, and completion.
- Progression, unlocks, scoring, rewards, and persistence.
- Content accuracy, duplicates, missing entries, and invalid data.
- UI states, accessibility, and responsive layouts.
- Audio, animation, asset loading, and performance.
- Edge cases, exploits, and regression after changes.

Balance through observed play and recorded results rather than intuition alone. Track difficulty, completion, failure points, and feedback where data collection is appropriate and privacy-respecting.

## 12. Continuity and delivery

Maintain a game design document or concise equivalent, mechanics and content specifications, level/progression map, asset inventory, technical architecture, known issues, QA record, build instructions, and handoff notes.

## Definition of done

The agreed gameplay loop and content are implemented and integrated, progression and persistence behave as specified, target platform requirements are addressed, relevant play and technical tests are recorded, and the build and project documentation are handed over with limitations disclosed.
