# Contribution 1: Operation Filter List on Insights Page Is Cut Off at the Bottom

**Contribution Number:** 1
**Student:** Qimin Wu
**Issue:** https://github.com/graphql-hive/console/issues/3816
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose this issue because it is a beginner-friendly bug with a clear problem and expected result. The issue affects the user interface, which matches my interest in JavaScript, HTML, and CSS. I also wanted to gain experience contributing to an open-source project and learn how to investigate and fix a real bug in a production application.

Another reason I chose this issue is that the scope appears manageable for a first contribution. The issue description clearly explains the problem, and the project maintainers labeled it as a good first issue. I hope to learn more about debugging frontend issues, understanding a larger codebase, and working through the open-source contribution process.

---

## Understanding the Issue

### Problem Description

On the Insights page, the operation filter dropdown list is cut off at the bottom. Because of this, users cannot see all available items in the filter list.

### Expected Behavior

The operation filter dropdown should display all available items. If the list is longer than the available space, users should be able to scroll and access every option.

### Current Behavior

Part of the dropdown list is hidden because of an overflow or layout issue. Some items cannot be seen or selected.

### Affected Components

Based on the issue description, the affected components are likely the Insights page UI, the operation filter dropdown component, and the related CSS styling that controls layout, height, and overflow behavior.

---

## Reproduction Process

### Environment Setup

To be completed in Phase II.

### Steps to Reproduce

To be completed in Phase II.

### Reproduction Evidence

* **Commit showing reproduction:** TBD
* **Screenshots/logs:** TBD
* **My findings:** TBD

---

## Solution Approach

### Analysis

To be completed in Phase II.

### Proposed Solution

To be completed in Phase II.

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** Fix the operation filter dropdown so all options are visible and accessible.

**Match:** Review existing dropdown and overflow handling patterns used elsewhere in the application.

**Plan:**

1. Set up the project locally.
2. Reproduce the issue on the Insights page.
3. Identify the component responsible for the operation filter.
4. Investigate CSS and layout rules affecting the dropdown.
5. Implement a fix.
6. Verify that all options are visible and selectable.
7. Run relevant tests and submit a pull request.

**Implement:** To be completed in Phase III.

**Review:** Ensure the solution follows project contribution guidelines and does not introduce UI regressions.

**Evaluate:** Confirm that all filter options are visible and the dropdown behaves correctly across different screen sizes.

---

## Testing Strategy

To be completed in Phase III.

---

## Implementation Notes

### Week 1 Progress

Selected the issue, reviewed the issue description, commented on the GitHub issue, and began exploring the project structure.

---

## Pull Request

**PR Link:** TBD

**PR Description:** TBD

**Maintainer Feedback:**

* TBD

**Status:** Not Started

---

## Learnings & Reflections

To be completed throughout the project.

---

## Resources Used

* GraphQL Hive GitHub Repository
* GraphQL Hive Contribution Documentation
* GitHub Documentation
* CodePath AI301 Materials
