# AMP MVP Observation Test

> ⚠️ This file is a temporary test artifact for the Amp collaboration-observation MVP.
> It has no functional impact and exists only so a read-only observer thread can
> detect GitHub Issue / PR / branch / CI state changes.
>
> **Safe to remove** once the observation test is complete.

## Purpose

- Verify that a read-only observer can detect:
  - newly created Issues
  - newly created branches
  - newly opened (Draft) PRs
  - CI / check status on the PR
- Confirm the observer reports *only* changes, not unrelated activity.

## Origin

- Created by Amp thread T-019f8d53-4fd4-775d-ae7f-4331a571b424
- Associated Issue: #8
- Branch: `amp-mvp-test-observation`
- This PR is a **Draft** and must **not** be merged.

## Cleanup

After the observation test concludes, the coordinator may:
1. Close the Draft PR
2. Close Issue #8
3. Delete the `amp-mvp-test-observation` branch and this file.

No other repository state is affected by this test.
