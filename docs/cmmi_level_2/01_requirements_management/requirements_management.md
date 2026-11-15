
# Requirements Management (REQM)

## 1. Purpose

This document records how requirements are identified, documented, assigned, tracked, reviewed and controlled throughout the Software Bug Tracking and Reporting Tool project.

The purpose is to maintain clear traceability between user requirements, development activities and testing evidence.

## 2. Requirements Identification

The project requirements are based on:

- The CO7095 coursework assignment brief.
- Team discussions and agreed project scope.
- The project's 40 user stories, identified as UR01–UR40.

The user stories cover the expected functionality of the Software Bug Tracking and Reporting Tool and its intended user roles.

The detailed user story descriptions and acceptance criteria are maintained in the project's `USER_REQUIREMENTS.md` document.

## 3. Requirements Documentation

Each user story is identified using a unique requirement ID (UR01–UR40).

The requirements record includes:

- Requirement ID.
- User story description.
- Acceptance criteria.
- Assigned team member.
- Planned sprint.
- Story point estimate.
- Current implementation status.
- Related development and testing evidence.

Story point estimates are subject to team Planning Poker. Suggested estimates must not be treated as final agreed estimates until the team completes and records its votes.

## 4. Requirements Ownership and Sprint Allocation

The team has agreed the following allocation of all 40 user stories across three sprints.

### Sprint 1

| Owner | User Story IDs |
|---|---|
| Chethan | UR01, UR04, UR05 |
| Shashank | UR02, UR08, UR11 |
| Vaishnavi | UR03, UR07, UR12 |
| Kalyan | UR14, UR18, UR20, UR21, UR22 |

### Sprint 2

| Owner | User Story IDs |
|---|---|
| Chethan | UR06, UR09, UR10 |
| Shashank | UR15, UR16, UR19 |
| Vaishnavi | UR17, UR33, UR35 |
| Kalyan | UR23, UR24, UR25, UR26 |

### Sprint 3

| Owner | User Story IDs |
|---|---|
| Chethan | UR13, UR32, UR37 |
| Shashank | UR31, UR34, UR40 |
| Vaishnavi | UR36, UR38, UR39 |
| Kalyan | UR27, UR28, UR29, UR30 |

This allocation covers all 40 user stories without duplicate or unassigned requirement IDs.

The allocation identifies responsibility for the user stories. It does not, by itself, establish that every allocated story has been implemented or verified.

## 5. Requirements Tracking

Requirements are planned and monitored through the project's GitHub repository, issues and Scrum board.

The team uses the following records to monitor requirements:

- GitHub issues for individual tasks and responsibilities.
- Sprint milestones to identify planned sprint work.
- Project board status to monitor progress.
- Pull requests and commits to record development changes.
- Test records to provide evidence of verification.

Requirement status should reflect actual project progress and must be updated when implementation or testing changes.

## 6. Requirements Change Management

Any proposed change to an existing requirement should follow this process:

1. Record the proposed change and the affected requirement ID.
2. Discuss the change with the team.
3. Review its impact on scope, implementation, sprint allocation and testing.
4. Record the team's decision.
5. Update the relevant user story, acceptance criteria and project documentation if approved.
6. Update related GitHub issues and traceability records.

Changes should be documented so that the team can identify what changed and why.

## 7. Requirements Traceability

Each requirement should be traceable through the following stages:

| Traceability Stage | Evidence |
|---|---|
| Requirement identification | User story ID (UR01–UR40) |
| Planning | Assigned owner and sprint allocation |
| Development | Related implementation files, commits and pull requests |
| Testing | Related test cases and test results |
| Verification | Evidence that acceptance criteria have been checked |

The mapping between individual requirements, implemented functions and test cases must be completed and verified against the actual code and testing records.

No requirement should be marked as fully implemented or verified without supporting evidence.

## 8. Supporting Evidence

The following project records are used as REQM evidence:

- Coursework assignment brief.
- `USER_REQUIREMENTS.md`.
- Sprint planning and allocation records.
- GitHub issues and milestones.
- GitHub Scrum board.
- Team discussions and requirement change records.
- Source code, commits and pull requests.
- Test cases and test results.

Evidence should be linked to the relevant requirement wherever possible.

## 9. Implementation Evidence Review

The implementation source code supplied by the back-end developer was inspected to identify the relationship between requirements and application functionality.

The inspected implementation is currently maintained separately from the team's main GitHub repository. Therefore, the findings in this section represent preliminary source-code inspection evidence and do not confirm integration into the project repository or completion of the corresponding sprint deliverables.

### 9.1 Bug Report Requirements

The `create_bug()` function was inspected.

| Requirement | Implementation Function | Evidence Identified | Status |
|---|---|---|---|
| UR14 | `create_bug()` | Validates and stores bug title and description. | Source code inspected; testing pending |
| UR15 | `create_bug()` | Stores reproduction steps. | Source code inspected; testing pending |
| UR16 | `create_bug()` | Stores expected and actual results. | Source code inspected; testing pending |
| UR17 | `create_bug()` | Stores environment information. | Source code inspected; testing pending |
| UR18 | `create_bug()` | Validates supported severity values. | Source code inspected; testing pending |
| UR19 | `create_bug()` | Validates supported priority values. | Source code inspected; testing pending |
| UR23 | `create_bug()` | Prevents duplicate open bug titles within a project. | Source code inspected; testing pending |

### 9.2 Access Control Evidence

The `create_bug()` function checks the authentication token, token expiry and project membership before accepting a bug report.

This provides initial implementation evidence relevant to:

- UR36 – Require authentication.
- UR37 – Restrict project data to project members.

These requirements require further verification across all protected application routes and project-related operations.

### 9.3 Evidence Limitations

The following limitations were identified during the review:

- The inspected implementation is currently maintained in a separate folder and has not yet been integrated into the team's GitHub repository.
- The team's initial `src` and `tests` Python files were found to be empty during inspection.
- The supplied `TEST_EVIDENCE.md` reports 49 passing tests and 95% statement coverage. These results have not yet been independently reproduced, and the test suite has not yet been verified against the team's GitHub repository.
- The implementation of each requirement must be checked against its complete acceptance criteria.
- Requirements without identifiable implementation or test evidence must remain recorded as evidence gaps.

### 9.4 Bug Editing and Status Management Evidence

The inspected implementation provides initial source-code evidence for selected bug editing and status management requirements. These findings are preliminary and do not represent confirmation that the corresponding sprint deliverables have been completed or accepted.

#### Bug Editing Evidence

The `edit_bug()` function is associated with the following requirements:

| Requirement ID | Requirement | Implementation Evidence | Review Status |
|---|---|---|---|
| UR15 | Store reproduction steps | `edit_bug()` supports updating reproduction steps. | Source code inspected; testing pending |
| UR16 | Store expected and actual results | `edit_bug()` supports updating expected and actual results. | Source code inspected; testing pending |
| UR17 | Store environment details | `edit_bug()` supports updating environment information. | Source code inspected; testing pending |
| UR18 | Validate severity | `edit_bug()` validates severity against supported values. | Source code inspected; testing pending |
| UR19 | Validate priority | `edit_bug()` validates priority against supported values. | Source code inspected; testing pending |
| UR22 | Edit bug details | `edit_bug()` supports updating permitted bug fields and rejects unsupported fields. | Source code inspected; testing pending |
| UR36 | Require authentication | The function checks the bearer token and its expiry. | Source code inspected; testing pending |
| UR37 | Restrict project access | The function checks project membership before allowing updates. | Source code inspected; testing pending |
| UR38 | Validate input | The function checks field types, required title and description values, and supported severity and priority values. | Partial source-code evidence; testing pending |
| UR39 | Prevent cross-project data access | The function retrieves the bug using both the bug ID and project ID. | Source code inspected; testing pending |

The inspected function allows updates to title, description, reproduction steps, expected results, actual results, environment, severity and priority. It also checks that the bug belongs to the specified project.

#### Bug Status Management Evidence

The inspected `update_bug_status()` function provides initial implementation evidence for UR24 and UR25.

| Requirement ID | Requirement | Implementation Evidence | Review Status |
|---|---|---|---|
| UR24 | Update bug status | The function accepts the supported statuses `new`, `in_progress`, `resolved` and `closed`, and rejects unsupported status values. | Source code inspected; testing pending |
| UR25 | Maintain status history | When a bug's status changes, the previous status, new status and user ID are recorded in the `bug_status_history` table. No additional history entry is created when the status remains unchanged. | Source code inspected; testing pending |

The status update function also checks authentication, token expiry, project membership and whether the bug belongs to the specified project.

#### Evidence Limitations

The above findings are based on source-code inspection of the implementation supplied for review. They do not independently confirm successful test execution or complete satisfaction of the requirements' acceptance criteria.

Integration with the team's GitHub repository and further test verification remain pending.

### 9.5 Requirements Requiring Further Verification

The following requirements have not yet been fully mapped to verified implementation and test evidence:

| Requirement Group | Requirements | Further Evidence Required |
|---|---|---|
| User registration and authentication | UR01, UR02, UR03, UR06 | Verify registration, login, logout and password protection. |
| User profiles | UR04, UR05 | Verify profile retrieval and profile updates. |
| Project management | UR07, UR08, UR09, UR10, UR11, UR12, UR13 | Inspect project creation, retrieval, listing, updates and membership functions. |
| Bug reporting and workflow | UR20, UR21, UR26, UR27, UR28, UR29, UR30 | Inspect remaining bug retrieval, listing, assignment and comment functions; verify all related acceptance criteria and tests. |
| Search and reporting | UR31, UR32, UR33, UR34, UR35 | Inspect search filters, summary reports and CSV export. |
| Access control and validation | UR36, UR37, UR38, UR39, UR40 | Verify protected routes, project isolation, input validation and administrative functionality. |

This table identifies outstanding verification work. It does not mean that all listed requirements are unimplemented. Some requirements have preliminary source-code evidence, but complete acceptance-criteria and test verification are still required.

## 10. REQM Conclusion

Requirements Management provides a structured way to maintain clear ownership, traceability and control of the project's requirements.

The project has established 40 identified user stories, allocated responsibilities across three sprints and created a requirements documentation structure.

Initial implementation source-code inspection has identified evidence for selected bug reporting, editing, validation and access-control requirements.

Further source-code inspection, test verification and integration into the team's GitHub repository are required before all requirements can be considered fully implemented and verified.

All completion claims will be supported by actual project evidence.
