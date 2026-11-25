# Quality Assurance

## Purpose

Quality assurance verifies that creative and digital deliverables satisfy agreed requirements and are fit for their intended use. QA is not a vague final impression: it is a planned set of checks with observable results.

Each discipline applies its relevant checks. This reference defines the shared method and reporting standard.

## 1. Plan QA early

Identify:
- Requirements and acceptance criteria.
- Deliverables and critical user journeys.
- Target devices, browsers, operating systems, print processes, or playback environments.
- Risks, dependencies, and failure impact.
- Required accessibility, security, privacy, content, and license checks.
- Test data, reviewers, and evidence to retain.

Write acceptance criteria so a reviewer can determine whether they pass.

## 2. Adaptive QA levels

### Basic
For simple static graphics or low-risk assets:
- Content and spelling.
- Dimensions, resolution, alignment, and readability.
- Visual consistency and export integrity.
- Source/license requirements.

### Advanced
For interactive, multimedia, or multi-state products:
- All relevant basic checks.
- Interaction paths, state transitions, navigation, and error handling.
- Media playback, synchronization, and asset loading.
- Responsive behavior and representative device checks.
- Accessibility checks relevant to the experience.

### Comprehensive
For complex games, websites, and applications:
- Requirements traceability and critical journey coverage.
- Unit, integration, and end-to-end checks where available.
- Regression, data/persistence, security/privacy, and performance checks.
- Accessibility and cross-platform verification.
- Release build, deployment, recovery, and rollback readiness as applicable.

Choose depth according to complexity and risk, not a desire to maximize test count.

## 3. QA categories

- **Visual:** layout, hierarchy, typography, color, spacing, rendering, cropping, and asset consistency.
- **Content:** spelling, facts, data, labels, translations, answer keys, citations, and completeness.
- **Functional:** controls, interactions, rules, navigation, state, validation, and error handling.
- **Game:** mechanics, progression, difficulty, scoring, rewards, pause/resume, and persistence.
- **Educational:** learning-objective alignment, subject accuracy, feedback, assessment, and learner suitability.
- **Responsive:** viewport changes, orientation, zoom, overflow, touch, and device performance.
- **Accessibility:** semantics, keyboard, focus, contrast, captions, alternatives, reduced motion, and input flexibility.
- **Technical:** builds, imports, dependencies, APIs, data integrity, performance, security/privacy, and deployment.
- **Media:** playback, frame rate, synchronization, audio levels, encoding, and export quality.
- **Production:** print specifications, bleed, fonts, packaging dielines, file naming, and handoff completeness.

## 4. Test execution

For each check, record expected behavior, actual result, environment, evidence, and status. Use representative data and realistic usage conditions. Test edge cases, not only the ideal path.

Where automation is available, use it for repeatable checks. Combine automated and manual testing; visual quality, usability, and many accessibility issues still require human review.

## 5. Defect management

Record defects with:
- Unique identifier.
- Clear reproduction steps.
- Expected and actual result.
- Severity and user impact.
- Environment and affected version.
- Evidence such as screenshots, logs, or recordings.
- Owner/status and retest result.

Suggested severity:
- **Critical:** safety, data loss, security exposure, or product unusable.
- **High:** major core requirement or journey broken.
- **Medium:** significant defect with workaround.
- **Low:** minor visual, content, or usability issue.

Prioritize based on impact and likelihood, not cosmetic visibility alone.

## 6. Retest and regression

After a fix, retest the original defect and affected areas. Run regression checks proportionate to the change. A change to shared components, state management, content schema, or navigation may affect multiple flows and require broader coverage.

Do not silently mark a defect resolved without evidence or a stated reason it cannot be reproduced.

## 7. Reporting and release readiness

Report:
- Scope and version tested.
- Environment and methods.
- Checks passed, failed, blocked, or not run.
- Open defects by severity.
- Known limitations and risks.
- Evidence and recommendations.
- Release decision or required follow-up.

Use explicit statuses:
- **Pass:** tested and met the criterion.
- **Fail:** tested and did not meet the criterion.
- **Blocked:** could not be tested due to a dependency or environment issue.
- **Not run:** no test was performed.
- **Not applicable:** criterion does not apply, with rationale where useful.

A successful local check is not proof of production deployment or universal compatibility.

## 8. Integrity of claims

Never claim "fully tested", "bug-free", "secure", "accessible", "production-ready", or "compatible with all devices" without evidence appropriate to that claim. State the exact scope and limitations. Separate visual inspection from functional testing and functional testing from external release verification.

## Deliverables

Provide a QA checklist, test cases, defect register, evidence, summary, residual risks, and sign-off status appropriate to project complexity.

## Definition of done

All critical acceptance criteria have been tested or explicitly reported as blocked/not run, high-impact defects are resolved or accepted by an authorized owner, regression checks are complete where needed, and residual risks are visible to the decision-maker.
