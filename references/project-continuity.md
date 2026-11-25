# Project Continuity & Version Control

## Purpose

Preserve project knowledge and working state across sessions, collaborators, tools, and agents. Continuity is an operational requirement: a new contributor should be able to understand what exists, why decisions were made, what remains, and how to continue without guessing.

## 1. Source of truth

Identify the authoritative location for:
- Current source code and project files.
- Approved specifications and decisions.
- Final and working assets.
- Content, data, and dependencies.
- QA evidence and release artifacts.

Avoid parallel undocumented copies. If multiple locations are necessary, state which is authoritative and how they stay synchronized.

## 2. Project record

Maintain a concise but useful record of:
- Project objective, audience, scope, and deliverables.
- Current phase and task status.
- Approved decisions and their rationale.
- References and assets, including origin and license.
- File tree and important entry points.
- Tools, frameworks, dependencies, versions, and environment assumptions.
- Completed work and verified outcomes.
- Open issues, risks, blockers, and pending approvals.
- QA scope, results, defects, and limitations.
- Next actions in priority order.

Update records when a consequential decision or implementation change occurs, not only at the end.

## 3. Decision management

Distinguish proposed, approved, rejected, superseded, and pending decisions. Record owner, date/version, rationale, and affected areas where useful. Do not treat an idea or assistant recommendation as approved merely because it was discussed.

When a new request conflicts with an approved decision, identify the conflict. Follow the instruction priority defined in the main skill and clarify only when necessary.

## 4. Asset and dependency management

Use predictable folder structures and file names. Record asset role, version, dimensions or technical properties, source, license, and dependencies. Keep editable sources separate from final exports where appropriate. Avoid duplicate files with ambiguous names such as "final-final-new".

Do not delete or replace source assets until their use and backup status are understood. Check links and imports after moving or renaming assets.

## 5. Version control

Use Git or an equivalent system for source and documentation where suitable:
- Make focused, descriptive commits.
- Preserve stable checkpoints before risky changes.
- Use branches for parallel or experimental work where helpful.
- Keep secrets, credentials, and private data out of public repositories.
- Review diffs before committing.
- Tag releases only when release criteria are met.

Version control does not replace backups for large binary assets or external services.

## 6. Change control

Before a substantial change:
1. Identify the requested outcome and affected components.
2. Check approved specifications and existing behavior.
3. Assess dependencies, risks, and potential regressions.
4. Preserve a recoverable state.
5. Make the smallest change that achieves the goal.
6. Test the change and affected paths.
7. Update documentation and change history.

Routine improvements may proceed autonomously when low-risk and within scope. Seek approval before destructive, irreversible, costly, privacy-sensitive, or scope-expanding actions.

## 7. Cross-session and cross-agent handoff

A useful handoff must include:
- Project and repository location.
- Current branch/version or authoritative file locations.
- Summary of completed work.
- Exact files changed and important entry points.
- Approved decisions and constraints.
- What has and has not been tested.
- Known issues, risks, and blockers.
- Immediate next steps and dependencies.
- Actions that must not be repeated or undone.

Avoid vague instructions such as "continue where we left off". Provide concrete paths, state, and priorities.

## 8. Recovery and external access

If a repository, file, connector, or tool is unavailable, state what could and could not be accessed. Do not infer file contents from filenames or prior summaries. Recover from an authoritative source when possible; otherwise reconstruct only with a clear note that it is a reconstruction, not the original.

Before writing to a repository, confirm the target, branch, permissions, and whether the path already exists. For updates, fetch the current version and use the current content identifier. Verify writes by reading the result back.

## 9. Continuity summary

At the end of a substantial work session, prepare a compact continuation note:
- Current verified state.
- Latest commits or version identifiers.
- Files completed or changed.
- Outstanding tasks.
- Exact next action.
- Relevant links and constraints.

The note should be sufficient for another session to continue safely without relying on unstated context.

## Definition of done

The project state is recoverable and understandable, approved decisions and changes are traceable, assets and dependencies are accounted for, QA status is honest, and a future contributor can continue from documented next steps.
