# BGMI Bug Reports — QA Testing Portfolio

A collection of structured software bug reports documenting functional, UI, network, gameplay, and event-related issues identified during BGMI gameplay.

## About This Project

This repository demonstrates practical software testing and bug-reporting skills through real-world gameplay observations.

Each issue is documented using a structured QA format covering:

* Bug identification
* Environment and preconditions
* Steps to reproduce
* Expected result
* Actual result
* Reproducibility
* Severity and priority
* User impact
* Testing notes
* Evidence

The objective of this portfolio is to demonstrate the ability to identify, reproduce, document, and communicate software defects clearly.

## Bug Reports

| ID                                 | Bug                                                                        | Category                 | Severity | Priority | Status                |
| ---------------------------------- | -------------------------------------------------------------------------- | ------------------------ | -------- | -------- | --------------------- |
| [BGMI-001](bug-reports/BUG-001.md) | Virtual joystick becomes unresponsive during gameplay                      | Gameplay / Controls      | High     | High     | Requires Verification |
| [BGMI-002](bug-reports/BUG-002.md) | Displayed network ping does not accurately reflect network performance     | Network / UI             | Major    | High     | Requires Verification |
| [BGMI-003](bug-reports/BUG-003.md) | Event progress counter does not update after completing required objective | Events / Rewards         | Major    | High     | Requires Verification |
| [BGMI-004](bug-reports/BUG-004.md) | Service error occurs when attempting to exchange an event card             | Events / Social Features | Major    | Medium   | Requires Verification |
| [BGMI-005](bug-reports/BUG-005.md) | “Feature not available” message displayed despite feature being accessible | UI / Events              | Minor    | Medium   | Requires Verification |

## Testing Areas

The documented issues cover several areas of application testing:

* **Functional Testing** — Verifying whether game features perform their intended functions.
* **UI Testing** — Checking whether displayed information and messages accurately represent the current application state.
* **Gameplay Testing** — Observing core player interactions and controls during active gameplay.
* **Network Testing** — Comparing displayed network information with observed gameplay behavior.
* **Event Testing** — Testing event progression, item exchange, and reward-related functionality.

## Bug Report Structure

Each report follows a consistent structure:

```text
Bug ID
Title
Severity
Priority
Category
Type
Status
Reproducibility

Environment
Description
Preconditions
Steps to Reproduce
Expected Result
Actual Result
Reproducibility
Impact
Severity Rationale
Priority Rationale
Evidence
Notes
```

## Severity Classification

| Severity | Meaning                                                                                                                             |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Critical | Causes severe failure, prevents major portions of the application from functioning, or results in significant data/security impact. |
| High     | Significantly affects core functionality or gameplay.                                                                               |
| Major    | Prevents an important feature from working correctly or causes substantial user impact.                                             |
| Minor    | Causes limited functional or UI impact without significantly affecting core functionality.                                          |
| Trivial  | Cosmetic or very low-impact issue.                                                                                                  |

## Priority Classification

| Priority | Meaning                                                          |
| -------- | ---------------------------------------------------------------- |
| High     | Should be investigated and fixed with high urgency.              |
| Medium   | Should be addressed, but does not require immediate attention.   |
| Low      | Can be addressed when higher-priority issues have been resolved. |

## Reproducibility

Some reports are marked as **Intermittent / Requires Verification** because the issue was observed during gameplay but requires additional controlled testing to establish consistent reproduction conditions.

This distinction is intentional: an observation is documented separately from a fully verified defect.

## Evidence

Screenshots and screen recordings can be added to the repository as supporting evidence where available.

Suggested structure:

```text
evidence/
├── BUG-001/
├── BUG-002/
├── BUG-003/
├── BUG-004/
└── BUG-005/
```

## Disclaimer

This repository is an independent QA testing portfolio created for educational and professional demonstration purposes.

BGMI and Battlegrounds Mobile India are trademarks of their respective owners. This project is not affiliated with, sponsored by, or endorsed by the game's developer or publisher.

## Author

**QA / Software Testing Portfolio**

Focused on practical bug identification, reproduction, documentation, and software quality analysis.
