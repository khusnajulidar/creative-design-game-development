# Quality Assurance Checklist

> Record actual checks and evidence. Do not mark an item passed because it looks likely to work. Use N/A only with a brief reason.

## 1. Test record

- **Project / product:**
- **Version / commit / build:**
- **Date:**
- **Tester / reviewer:**
- **Environment / device / browser / OS:**
- **QA level:** Basic / Advanced / Comprehensive
- **Scope:**
- **Requirements / acceptance criteria reference:**

## 2. Status definitions

- **Pass:** tested and met the criterion.
- **Fail:** tested and did not meet the criterion.
- **Blocked:** could not be tested due to dependency or environment.
- **Not run:** not tested.
- **N/A:** not applicable; explain why.

## 3. Requirements and content

- [ ] All required deliverables and features are present.
- [ ] Content, spelling, numbers, names, labels, and translations are correct.
- [ ] Facts, data, citations, and answer keys are verified against appropriate sources.
- [ ] No required content is missing or duplicated.
- [ ] Content is suitable for the intended audience and context.

**Notes / evidence:**

## 4. Visual and asset review

- [ ] Hierarchy and readability are clear at intended size.
- [ ] Alignment, spacing, contrast, and composition are consistent.
- [ ] Approved branding and references are respected.
- [ ] Images, illustrations, icons, and fonts render correctly.
- [ ] No clipping, distortion, artifacts, missing assets, or unintended substitutions.
- [ ] Export dimensions, resolution, transparency, and color mode are correct.

**Notes / evidence:**

## 5. Functionality and interaction

- [ ] Primary user journeys work.
- [ ] Controls and navigation behave as specified.
- [ ] Focus, selected, disabled, loading, empty, error, and success states are correct.
- [ ] Validation, feedback, retry, cancellation, and recovery work.
- [ ] State changes and persistence behave as expected.
- [ ] No critical console, runtime, or integration errors remain.

**Notes / evidence:**

## 6. Game and learning checks (if applicable)

- [ ] Core gameplay loop and rules behave correctly.
- [ ] Scoring, hints, retries, unlocks, and progression are correct.
- [ ] Win, loss, pause, resume, and completion states work.
- [ ] Learning objectives align with activities and assessment.
- [ ] Feedback is accurate, constructive, and useful.
- [ ] Difficulty and reading load suit the target learners.
- [ ] Progress is not misleading or unfairly lost.

**Notes / evidence:**

## 7. Responsive and accessibility checks

- [ ] Relevant viewport sizes and orientations are checked.
- [ ] No unintended overflow or clipping occurs.
- [ ] Keyboard and touch input work where applicable.
- [ ] Focus is visible and order is logical.
- [ ] Contrast and text scaling are adequate.
- [ ] Essential information is not conveyed by color, sound, or motion alone.
- [ ] Captions, transcripts, and text alternatives are present where needed.
- [ ] Reduced-motion behavior is appropriate.

**Notes / evidence:**

## 8. Technical, security, and performance checks

- [ ] Build / import / export succeeds in the tested environment.
- [ ] Dependencies and asset paths are available.
- [ ] Data validation and error handling work.
- [ ] Secrets and sensitive data are protected.
- [ ] Privacy and permission behavior matches requirements.
- [ ] Loading, memory, rendering, and network performance are acceptable.
- [ ] Backup, recovery, and deployment behavior are checked where in scope.

**Notes / evidence:**

## 9. Media and production checks (if applicable)

- [ ] Audio/video playback and synchronization are correct.
- [ ] Titles, captions, safe areas, and text are readable.
- [ ] Audio levels are balanced and free of clipping.
- [ ] Export format, codec, resolution, frame rate, and duration are correct.
- [ ] Print bleed, trim, dieline, and embedded fonts are correct where applicable.

**Notes / evidence:**

## 10. Defect register

| ID | Severity | Steps / description | Expected vs actual | Evidence | Status / retest |
|---|---|---|---|---|---|
| BUG-01 | Critical / High / Medium / Low | | | | |

## 11. Regression and retest

- **Fixes retested:**
- **Affected areas regression-tested:**
- **Results:**
- **Not retested / reason:**

## 12. QA summary

- **Pass:**
- **Fail:**
- **Blocked:**
- **Not run:**
- **Open critical/high defects:**
- **Known limitations / residual risks:**
- **Recommended action:** Release candidate / Fix required / Further review

## 13. Sign-off

- **Tester:**
- **Reviewer / approver:**
- **Decision:** Approved / Conditional / Rejected / Pending
- **Date and notes:**
