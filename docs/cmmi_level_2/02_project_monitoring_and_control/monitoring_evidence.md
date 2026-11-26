
# Project Monitoring and Control – Supporting Evidence

## 1. Purpose

This document records the available evidence demonstrating how the Software Bug Tracking and Reporting Tool project is monitored and controlled.

Evidence is collected from GitHub Issues, milestones, the Scrum Board, commits, pull requests, sprint records, burndown charts, velocity calculations and testing activities.

Only verified activities are recorded as completed. Planned and ongoing activities are identified separately.

## 2. Sprint Monitoring Summary

The project is organised into three sprints.

| Sprint | Period | Planned User Stories | Planned Story Points | Monitoring Status |
|---|---|---:|---:|---|
| Sprint 1 | 2–23 November 2026 | 14 | 34 | Completed |
| Sprint 2 | 24 November–14 December 2026 | 13 | 35 | In progress |
| Sprint 3 | As scheduled by the team | 13 | 40 | Pending |
| **Total** | | **40** | **109** | |

The planned totals are based on the team's confirmed user-story allocations and Planning Poker estimates.

## 3. Sprint 1 Monitoring Evidence

### 3.1 Sprint Completion

Sprint 1 was completed with all 14 milestone issues closed.

Available GitHub milestone information:

- Sprint: Sprint 1
- Planned period: 2–23 November 2026
- Total milestone issues: 14
- Closed issues: 14
- Open issues: 0
- Milestone issue completion: 100%

The 14 closed issues represent Sprint 1 project-management activities (S1-01 to S1-14). Their closure demonstrates completion of the recorded milestone activities but does not independently prove that all 14 planned software user stories were implemented and accepted.

### 3.2 GitHub Monitoring Records

Sprint 1 progress was tracked through GitHub Issues, the Scrum Board, commits and pull requests.

Examples of completed documentation and setup activities include:

| Activity | GitHub Evidence | Result |
|---|---|---|
| Repository skeleton and test package setup | Issue #10 and PR #15 | Completed |
| CMMI evidence folder setup | Issue #12 and PR #16 | Completed |
| Requirements Management documentation | Issue #17 and PR #18 | Completed |
| Sprint 1 review and retrospective activity | Issue #13 | Closed |

PR #18 added the Requirements Management documentation and supporting requirements information.

### 3.3 Sprint 1 Burndown Limitation

A daily Sprint 1 burndown record was not maintained.

The team therefore cannot present a complete historical daily burndown chart as contemporaneously recorded evidence.

If a retrospective chart is prepared, it must be based on available dated GitHub activity and clearly labelled as a reconstruction. Missing daily values must not be invented.

### 3.4 Sprint 1 Velocity

The planned Sprint 1 workload was 34 story points.

Actual velocity must be calculated from the story points of completed software user stories, using verified implementation and completion records.

The closure of 14 project-management milestone issues does not by itself prove that 34 software user-story points were completed.

| Measure | Value |
|---|---|
| Planned story points | 34 |
| Verified completed user-story points | Pending verification |
| Actual velocity | Pending calculation |

## 4. Sprint 2 Monitoring Evidence

### 4.1 Sprint Information

- Sprint: Sprint 2
- Period: 24 November–14 December 2026
- Planned user stories: 13
- Planned story points: 35
- Status: In progress

The Sprint 2 plan contains 13 user stories with a total estimated effort of 35 story points.

### 4.2 GitHub Issue Monitoring

Sprint 2 activities are tracked through GitHub Issues #19–#38.

The issues cover:

- CMMI Project Planning, Project Monitoring and Control, and Configuration Management documentation.
- Burndown chart preparation.
- Team velocity calculation.
- User-story implementation and testing.
- COCOMO I and COCOMO II estimation.
- PERT calculations and critical path.
- Earned Value Management.
- Test coverage consolidation.
- Implementation and testing evidence review.

The team monitors assigned issues through the GitHub Scrum Board and associated milestones.

### 4.3 Current CMMI Documentation Work

The following CMMI Level 2 documentation has been prepared and included in Pull Request #39 for review.

| Document | CMMI Area | Status |
|---|---|---|
| project_planning.md | Project Planning (PP) | Prepared – in PR review |
| planning_evidence.md | Project Planning (PP) | Prepared – in PR review |
| project_monitoring_and_control.md | Project Monitoring and Control (PMC) | Prepared – in PR review |
| monitoring_evidence.md | Project Monitoring and Control (PMC) | Prepared – in PR review |
| configuration_management.md | Configuration Management (CM) | Prepared – in PR review |
| configuration_evidence.md | Configuration Management (CM) | Prepared – in PR review |

The six documents have been added to PR #39, titled **Add CMMI Level 2 PP, PMC and CM Documentation**.

PR #39 is open and awaiting review. The documents must not be described as merged into the main branch until the pull request has been approved and merged.

### 4.4 Sprint 2 Burndown Monitoring

The initial planned Sprint 2 workload is 35 story points.

Remaining story points should be recorded regularly during the sprint using actual completed and accepted user-story progress.

The following table is intended for actual daily records. Values must be updated from verified sprint activity.

| Date | Initial Story Points | Completed Story Points | Remaining Story Points | Notes |
|---|---:|---:|---:|---|
| 24 November 2026 | 35 | To be recorded | To be recorded | Sprint start |
| Subsequent dates | | | | Update using actual progress |
| 14 December 2026 | | | | Sprint review |

The remaining story points are calculated as:

**Remaining Story Points = Initial Sprint Story Points − Completed Story Points**

Any approved scope changes must be recorded separately and reflected in the burndown calculations.

### 4.5 Sprint 2 Velocity

Sprint 2 planned workload is 35 story points.

Actual velocity will be calculated at the end of the sprint using the estimates of completed and accepted user stories.

| Measure | Value |
|---|---|
| Planned story points | 35 |
| Completed story points | Pending |
| Actual velocity | Pending |

## 5. Implementation Monitoring

Implementation progress is monitored through:

- Assigned GitHub Issues.
- User-story acceptance criteria.
- Feature branches.
- Git commits.
- Pull requests.
- Code reviews.
- Integration checks.

Each member is responsible for implementing their allocated user stories and providing relevant implementation evidence.

A story is treated as complete only when its implementation has been checked against the acceptance criteria and the required evidence is available.

## 6. Testing Monitoring

Testing progress is monitored through test cases, test execution results and code coverage reports.

The team is required to demonstrate:

- Black-box specification-based testing.
- Black-box random-based testing.
- White-box testing.
- Symbolic execution.
- Concolic testing.
- Requirement-to-test traceability.
- Test pass rates and code coverage.

The assignment targets at least 85% test pass rate and 85% average code coverage for the relevant assessment criteria.

Actual results must be taken from test execution and coverage reports. Planned tests must not be reported as completed tests.

## 7. Risk and Corrective Action Records

The team monitors project risks and takes corrective action where necessary.

| Risk | Monitoring Method | Corrective Action |
|---|---|---|
| Implementation delays | GitHub issue status and sprint reviews | Review workload and resolve blockers |
| Unclear acceptance criteria | Requirements and issue review | Clarify requirements with the team |
| Integration problems | Pull requests and integration tests | Review and fix integration defects |
| Missing testing evidence | Test reports and coverage records | Add missing tests and evidence |
| Incomplete project documentation | Documentation issue tracking | Update and review the required documents |
| Uneven workload | Story allocation and point totals | Discuss workload balancing |

Corrective actions should be recorded with dates and supporting evidence when they occur.

## 8. Sprint Review and Retrospective Records

Sprint reviews are used to assess completed work, remaining activities and issues affecting project progress.

The review should record:

- Completed user stories.
- Incomplete user stories.
- Actual story points completed.
- Testing results.
- Identified risks and blockers.
- Corrective actions.
- Improvements for the next sprint.

Meeting minutes, GitHub activity and review records provide supporting evidence.

## 9. Supporting GitHub References

The following repository records support project monitoring:

| Evidence | Reference |
|---|---|
| Project repository | Software Bug Tracking and Reporting Tool GitHub repository |
| Sprint 1 milestone | Sprint 1 milestone |
| Sprint 2 milestone | Sprint 2 milestone |
| Scrum Board | CO7095 Scrum Board |
| Sprint 1 Requirements Management PR | PR #18 |
| Sprint 1 repository setup PR | PR #15 |
| Sprint 1 CMMI folder setup PR | PR #16 |
| Sprint 2 activity tracking | GitHub Issues #19–#38 |
| Sprint 2 CMMI documentation PR | PR #39 (open, awaiting review) |

Relevant links and screenshots should be added to the final evidence package.

## 10. Evidence Limitations

The following limitations are acknowledged:

1. Daily Sprint 1 burndown records were not maintained.
2. Sprint 1 actual velocity requires verification against completed and accepted software user stories.
3. Sprint 2 is ongoing, so its final velocity and completion figures are not yet available.
4. Sprint 2 daily burndown values must be based on actual recorded progress.
5. Sprint 3 monitoring evidence will be added during the final sprint.
6. Implementation and testing completion must be supported by actual commits, pull requests, test results and coverage reports.
7. PR #39 is still open, so its documentation has not yet been merged into the main branch.

These limitations are recorded to ensure that project monitoring evidence accurately represents the work performed.

## 11. Conclusion

The project uses GitHub Issues, milestones, the Scrum Board, commits, pull requests, burndown tracking, velocity calculations and testing records to monitor progress.

Sprint 1 milestone completion is supported by its closed milestone and associated GitHub records. However, the milestone closure does not independently establish the completion of all planned software user stories or the actual Sprint 1 velocity.

Sprint 2 monitoring is ongoing. Its planned workload is 35 story points, and its burndown and velocity records will be updated using verified progress. Sprint 3 evidence will be added as development progresses.

This evidence supports the CMMI Level 2 Project Monitoring and Control process area by documenting the team's approach to monitoring project progress, identifying issues and managing corrective actions.
