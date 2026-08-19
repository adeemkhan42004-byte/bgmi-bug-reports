# BGMI Bug Reports — QA Testing Portfolio

A collection of structured bug reports documenting gameplay, UI, network, event, and functional issues observed during BGMI gameplay.

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

The objective of this portfolio is to demonstrate the ability to identify, analyze, document, and communicate potential software defects in a clear and professional format.

## Bug Reports

| ID                                 | Bug                                                                        | Category                 | Severity | Priority | Status                |
| ---------------------------------- | -------------------------------------------------------------------------- | ------------------------ | -------- | -------- | --------------------- |
| [BGMI-001](bug-reports/BUG-001.md) | Virtual joystick becomes unresponsive during gameplay                      | Gameplay / Controls      | High     | High     | Requires Verification |
| [BGMI-002](bug-reports/BUG-002.md) | Displayed network ping does not accurately reflect network performance     | Network / UI             | Major    | High     | Requires Verification |
| [BGMI-003](bug-reports/BUG-003.md) | Event progress counter does not update after completing required objective | Events / Rewards         | Major    | High     | Requires Verification |
| [BGMI-004](bug-reports/BUG-004.md) | Service error occurs when attempting to exchange an event card             | Events / Social Features | Major    | Medium   | Requires Verification |
| [BGMI-005](bug-reports/BUG-005.md) | “Feature not available” message displayed despite feature being accessible | UI / Events              | Minor    | Medium   | Requires Verification |

## Testing Areas

The reports cover several areas of software testing:

### Functional Testing

Testing whether game features perform their intended functions.

### UI Testing

Checking whether displayed messages, counters, and status information accurately represent the application's current state.

### Gameplay Testing

Testing player controls and interactions during active gameplay.

### Network Testing

Observing network-related behavior and comparing displayed network information with gameplay responsiveness.

### Event Testing

Testing event progression, item exchanges, and reward-related functionality.

## Bug Report Structure

Each report follows a consistent QA documentation structure:

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
Impact
Severity Rationale
Priority Rationale
Notes
```

## Severity Classification

| Severity | Meaning                                                                           |
| -------- | --------------------------------------------------------------------------------- |
| Critical | Severe failure that significantly prevents the application from functioning.      |
| High     | Significant impact on core functionality or gameplay.                             |
| Major    | Important feature is not functioning correctly or causes substantial user impact. |
| Minor    | Limited functional or UI impact with relatively low user impact.                  |
| Trivial  | Cosmetic or very low-impact issue.                                                |

## Priority Classification

| Priority | Meaning                                                          |
| -------- | ---------------------------------------------------------------- |
| High     | Should be investigated with high urgency.                        |
| Medium   | Should be investigated after higher-priority issues.             |
| Low      | Can be addressed when higher-priority issues have been resolved. |

## Reproducibility

Some reports are marked **Intermittent / Requires Verification** because the behavior was observed during gameplay but requires additional controlled testing to establish consistent reproduction conditions.

This distinction is intentional. The repository documents observed potential defects rather than presenting unverified observations as confirmed defects.

## Methodology

The reports were created using a structured manual testing approach:

1. Identify unexpected application behavior.
2. Determine the expected behavior.
3. Document the conditions under which the behavior was observed.
4. Create reproducible steps based on the observation.
5. Compare expected and actual results.
6. Assess potential user impact.
7. Assign severity and priority.
8. Document areas requiring further verification.

## Disclaimer

This repository is an independent QA testing portfolio created for educational and professional demonstration purposes.

BGMI and Battlegrounds Mobile India are trademarks of their respective owners. This project is not affiliated with, sponsored by, or endorsed by the game's developer or publisher.

## Author

**QA / Software Testing Portfolio**

Focused on practical bug identification, manual testing, defect documentation, and software quality analysis.
