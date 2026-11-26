
# Project Monitoring and Control (PMC)

## 1. Purpose

This document describes how the Software Bug Tracking and Reporting Tool project is monitored and controlled throughout its development lifecycle.

The purpose of Project Monitoring and Control is to track project progress against the established plan, identify deviations, monitor risks and issues, and take corrective action when necessary.

The team uses GitHub Projects, GitHub Issues, milestones, pull requests, commits, sprint reviews and testing records to monitor project activities.

## 2. Project Monitoring Approach

The project is organised into three development sprints.

Progress is monitored using the following activities:

- Tracking assigned user stories through GitHub Issues.
- Monitoring sprint milestones and their completion dates.
- Reviewing the status of tasks on the GitHub Scrum Board.
- Monitoring implementation progress through branches, commits and pull requests.
- Tracking testing activities and test results.
- Recording remaining story points for sprint burndown charts.
- Calculating team velocity based on completed story points.
- Identifying delays and taking corrective action.

The team reviews progress regularly to ensure that planned activities remain aligned with the assignment requirements.

## 3. Sprint Progress Monitoring

Each sprint has a defined set of activities, assigned responsibilities and planned user stories.

The confirmed sprint allocation and story point totals are:

| Sprint | Period | Planned User Stories | Planned Story Points |
|---|---|---:|---:|
| Sprint 1 | 2–23 November 2026 | 14 | 34 |
| Sprint 2 | 24 November–14 December 2026 | 13 | 35 |
| Sprint 3 | As scheduled by the team | 13 | 40 |
| **Total** | **Three sprints** | **40** | **109** |

Sprint progress is monitored through GitHub milestones and the Scrum Board.

Tasks are moved through the relevant workflow stages as work progresses. A task is marked complete only after its implementation or documentation work has been completed and the required evidence is available.

Sprint 1 was completed with all 14 milestone issues closed. These milestone issues represent Sprint 1 project-management activities and should not, by themselves, be treated as proof that all 14 planned software user stories were implemented and tested.

Sprint 2 is currently in progress. Its implementation, testing and documentation activities are monitored through their assigned GitHub issues.

Sprint 3 will be monitored using the same approach.

## 4. GitHub Issue and Scrum Board Monitoring

GitHub Issues are used to record project activities, user stories, responsibilities and completion evidence.

Each issue contains relevant information such as:

- Issue title and description.
- Assigned team member.
- Associated sprint milestone.
- Acceptance criteria or completion requirements.
- Related branches and pull requests where applicable.
- Supporting implementation, testing or documentation evidence.

The GitHub Scrum Board provides an overview of task progress.

The team uses the board to identify:

- Tasks that have not yet started.
- Tasks currently in progress.
- Tasks awaiting review.
- Completed tasks.
- Activities that require further attention.

Issue status is updated according to actual progress rather than assumed completion.

## 5. Schedule and Progress Monitoring

The team compares actual task progress against the planned sprint schedule.

The following information is considered:

- Planned sprint start and end dates.
- Issue creation and assignment.
- Development progress.
- Pull request submission and review.
- Testing completion.
- Issue closure dates.

GitHub issue activity, pull request history and commit records provide supporting evidence of project progress.

If a task is delayed, the team reviews its cause and considers whether additional time, clarification, reassignment or technical support is required.

## 6. Burndown Chart Monitoring

Burndown charts are used to monitor the remaining work during each sprint.

The chart tracks remaining story points against the sprint timeline.

The team records the remaining work regularly and compares actual progress with the planned progress.

The following information is used:

- Total planned sprint story points.
- Remaining story points.
- Completed user stories.
- Sprint timeline.
- Changes to the sprint backlog, where applicable.

The confirmed initial story point totals are:

| Sprint | Initial Story Points |
|---|---:|
| Sprint 1 | 34 |
| Sprint 2 | 35 |
| Sprint 3 | 40 |

Sprint 1 burndown evidence was not recorded daily. Any retrospective reconstruction must therefore be clearly identified and based on available GitHub activity records. Missing historical daily values must not be presented as actual recorded measurements.

For Sprint 2 and Sprint 3, the team aims to maintain regular burndown records to provide more reliable progress information.

## 7. Team Velocity Monitoring

Team velocity measures the number of story points completed during a sprint.

Velocity is calculated using:

**Team Velocity = Total Story Points of Completed User Stories**

Only completed user stories are included in the final velocity calculation.

Planned story points are not treated as completed story points.

The team records the final completed story points at the end of each sprint and compares them with the original estimates.

| Sprint | Planned Story Points | Completed Story Points | Actual Velocity |
|---|---:|---|---|
| Sprint 1 | 34 | To be verified | To be calculated |
| Sprint 2 | 35 | Pending | Pending |
| Sprint 3 | 40 | Pending | Pending |

Sprint 1 velocity will be calculated using verified completion evidence. Sprint 2 and Sprint 3 velocity will be updated after their respective reviews.

## 8. Implementation Monitoring

Implementation progress is monitored through GitHub branches, commits and pull requests.

Each team member is responsible for implementing their allocated user stories.

The team monitors:

- Whether assigned user stories have been implemented.
- Whether implementation changes are committed to GitHub.
- Whether changes are associated with the relevant issue.
- Whether pull requests are submitted and reviewed.
- Whether the implementation satisfies the acceptance criteria.
- Whether integration issues have been identified and addressed.

A user story is not considered fully verified merely because code has been committed. Its implementation must be checked against the corresponding acceptance criteria.

## 9. Testing Monitoring

Testing activities are monitored separately from implementation activities.

Each team member is responsible for preparing and executing tests for their allocated user stories.

The team monitors:

- Black-box specification-based testing.
- Black-box random-based testing.
- White-box testing.
- Test execution results.
- Failed test cases and defects.
- Statement and branch coverage where available.
- Requirement-to-test traceability.

Test results and coverage measurements are recorded as evidence.

The team aims to achieve at least 85% test pass rate and 85% average code coverage in accordance with the assignment assessment requirements.

These targets are evaluated using actual test execution and coverage reports rather than estimates.

## 10. Risk and Issue Monitoring

The team monitors risks and issues that could affect project completion.

| Risk or Issue | Potential Impact | Monitoring and Corrective Action |
|---|---|---|
| Delayed implementation | Sprint tasks may remain incomplete | Review issue progress and redistribute work where appropriate |
| Unclear requirements | Incorrect or incomplete functionality | Review user stories and acceptance criteria |
| Integration problems | Features may not work together | Review pull requests and perform integration testing |
| Insufficient test coverage | Defects may remain undetected | Review test reports and add missing test cases |
| Uneven workload | Some members may experience excessive workload | Review assignments and discuss reallocation |
| Missing project evidence | Assessment requirements may not be demonstrated | Maintain evidence in the repository throughout development |
| Delayed documentation | Final report may be incomplete | Monitor documentation tasks through GitHub Issues |

Risks are reviewed during project discussions and sprint reviews.

Corrective actions are recorded through relevant GitHub issues or project documentation where appropriate.

## 11. Corrective Action and Change Monitoring

When actual progress differs from the planned schedule or scope, the team reviews the deviation and identifies an appropriate corrective action.

Corrective actions may include:

- Clarifying user-story acceptance criteria.
- Reassigning tasks after team discussion.
- Resolving implementation or integration issues.
- Adding missing test cases.
- Updating documentation.
- Reviewing the remaining sprint workload.
- Escalating significant issues during team meetings.

Changes to requirements, responsibilities or sprint activities are recorded using the relevant GitHub issues and project documentation.

Changes are reviewed to ensure that they do not compromise the assignment requirements.

## 12. Sprint Review and Retrospective

At the end of each sprint, the team reviews completed work against the sprint plan.

The review considers:

- Completed and incomplete user stories.
- Implementation and testing evidence.
- Sprint burndown information.
- Actual team velocity.
- Issues and risks encountered.
- Workload distribution.
- Improvements required for the next sprint.

Retrospective findings are used to improve planning, communication, implementation and testing activities in subsequent sprints.

Sprint review outcomes should be supported by meeting records, GitHub activity and relevant project evidence.

## 13. Supporting Evidence

The following project records support Project Monitoring and Control:

- GitHub Projects Scrum Board.
- Sprint 1, Sprint 2 and Sprint 3 milestones.
- GitHub Issues and issue activity.
- Assigned user stories and acceptance criteria.
- Git branches, commits and pull requests.
- Sprint burndown charts.
- Team velocity calculations.
- Test execution reports.
- Code coverage reports.
- Sprint review and retrospective records.
- Risk and corrective-action records.

Evidence is maintained in the project repository and updated as the project progresses.

## 14. Evidence Limitations and Status

Project Monitoring and Control is an ongoing activity throughout the three sprints.

Sprint 1 has been completed, with all 14 milestone issues closed. However, daily Sprint 1 burndown records were not maintained, and its historical progress must be reconstructed only where reliable evidence is available.

Sprint 1 actual velocity remains subject to verification against completed user-story implementation and acceptance evidence.

Sprint 2 is currently in progress. Burndown, velocity, implementation and testing evidence will be updated as work is completed.

Sprint 3 monitoring records will be added during the final development sprint.

Planned activities and targets are not treated as completed evidence.

## 15. Conclusion

The team monitors project progress using GitHub Issues, milestones, the Scrum Board, branches, commits, pull requests, burndown charts, velocity calculations and testing records.

Regular monitoring helps the team identify deviations, manage risks, review implementation and testing progress, and take corrective action when required.

This process supports the CMMI Level 2 Project Monitoring and Control process area by providing a structured approach to monitoring project performance against the established project plan.
