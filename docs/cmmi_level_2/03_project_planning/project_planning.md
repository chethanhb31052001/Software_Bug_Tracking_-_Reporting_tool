
# CMMI Level 2 – Project Planning (PP)

## 1. Purpose

This document describes how the Software Bug Tracking and Reporting Tool project is planned, organised and managed. It records the project scope, activities, responsibilities, estimates, schedule, resources and risks.

The purpose is to establish and maintain a practical project plan that can be monitored throughout the three development sprints.

## 2. Project Overview

**Project Name:** Software Bug Tracking and Reporting Tool

**Module:** CO7095

**Development Language:** Python

**Development Environment:** PyCharm

**Version Control and Project Management:** GitHub and GitHub Projects

The project aims to develop a software bug tracking application that allows users to manage projects and software bugs, maintain bug information, track status changes and access relevant reports.

The detailed functional requirements are maintained in `USER_REQUIREMENTS.md`, covering 40 user stories identified as UR01–UR40.

## 3. Project Scope

The planned project functionality includes:

- User registration and authentication.
- User profile management.
- Project creation and management.
- Project membership and access control.
- Bug reporting and bug detail management.
- Bug severity and priority management.
- Bug status updates and status history.
- Bug assignment and comments.
- Bug searching and filtering.
- Bug summaries and report generation.
- Input validation and security controls.

The detailed scope is defined by the user stories and their acceptance criteria.

Any proposed scope changes must be reviewed and recorded through the requirements change-management process described in the REQM document.

## 4. Project Team and Responsibilities

The project is undertaken by four team members.

| Team Member | Development Responsibility |
|---|---|
| Chethan | Assigned user stories and implementation/testing |
| Shashank | Assigned user stories and implementation/testing |
| Vaishnavi | Assigned user stories and implementation/testing |
| Kalyan | Assigned user stories and implementation/testing |

Each member is responsible for implementing and testing their allocated user stories.

Additional coursework and report responsibilities are distributed across the team and documented in the project planning records.

## 5. Work Breakdown and Sprint Planning

The project is organised into three sprints.

### Sprint 1 – Requirements Confirmation and Team Coordination

**Period:** 2 November – 23 November 2026

Main activities included:

- Project selection and scope confirmation.
- Reviewing the coursework brief and assessment requirements.
- Preparing functional and non-functional requirements.
- Creating user stories and acceptance criteria.
- Initial Planning Poker and story-point recording.
- Establishing the GitHub repository and Scrum board.
- Preparing the initial CMMI documentation structure.
- Preparing Requirements Management documentation.

### Sprint 2 – Development and Project Management

**Period:** 24 November – 14 December 2026

Planned activities include:

- Preparing Project Planning, Project Monitoring and Control, and Configuration Management documentation.
- Implementing assigned user stories.
- Testing implemented functionality.
- Recording daily burndown information.
- Calculating team velocity.
- Preparing PERT and critical path calculations.
- Performing COCOMO I and COCOMO II estimation.
- Preparing Earned Value Management evidence.
- Consolidating testing and coverage evidence.

### Sprint 3 – Final Development and Verification

Sprint 3 is planned to complete the remaining allocated user stories and outstanding project deliverables.

Activities include:

- Completing remaining implementation and testing.
- Reviewing requirements traceability.
- Completing symbolic execution and concolic testing evidence.
- Reviewing test coverage and test results.
- Completing the CMMI documentation audit.
- Preparing and reviewing the final report and demonstration.

The exact Sprint 3 dates and detailed schedule must be taken from the approved GitHub milestone and project plan.

## 6. User Story Allocation

The project contains 40 user stories allocated across three sprints.

| Team Member | Sprint 1 | Sprint 2 | Sprint 3 | Total |
|---|---|---|---|---:|
| Chethan | 3 | 3 | 3 | 9 |
| Shashank | 3 | 3 | 3 | 9 |
| Vaishnavi | 3 | 3 | 3 | 9 |
| Kalyan | 5 | 4 | 4 | 13 |
| **Total** | **14** | **13** | **13** | **40** |

The allocation is documented in `USER_REQUIREMENTS.md`.

The team should review workload distribution to address differences in the number and estimated complexity of allocated stories.

## 7. Estimation and Planning Poker

The team uses Planning Poker to estimate the relative effort of user stories.

Story-point estimates are recorded in the sprint planning evidence.

The currently recorded estimates total:

| Sprint | Planned Story Points |
|---|---:|
| Sprint 1 | 33 |
| Sprint 2 | 32 |
| Sprint 3 | 39 |
| **Total** | **104** |

These figures represent the current recorded estimates. The available planning record does not contain all four members' votes for every story. Therefore, the estimates should not be described as fully validated unanimous Planning Poker results until the missing voting evidence is completed or clarified.

## 8. Project Resources

The project uses the following resources:

| Resource | Purpose |
|---|---|
| Python | Application development |
| PyCharm | Development environment |
| GitHub repository | Source code and version control |
| GitHub Issues | Task and requirement tracking |
| GitHub Projects | Sprint planning and progress monitoring |
| GitHub branches and pull requests | Code collaboration and review |
| Python testing tools | Test execution and verification |
| Coverage.py | Statement coverage measurement |
| Microsoft Teams | Team communication and meetings |

## 9. Project Risks and Mitigation

| Identified Risk | Potential Impact | Planned Mitigation |
|---|---|---|
| Uneven workload distribution | Delays or unequal contribution | Review story allocation and workload regularly |
| Incomplete requirements understanding | Incorrect implementation | Refer to acceptance criteria and discuss unclear requirements |
| Delayed implementation | Sprint objectives may not be achieved | Monitor GitHub issues and review progress |
| Insufficient testing | Defects may remain undetected | Prepare and execute tests for each assigned story |
| Missing project evidence | Reduced assessment quality | Attach supporting evidence before closing issues |
| Integration problems | Application components may not work together | Integrate and review changes regularly |
| Incomplete documentation | CMMI and report requirements may not be satisfied | Maintain documentation throughout the project |

## 10. Project Plan Monitoring

The project plan is monitored using:

- GitHub issue status.
- Sprint milestones and deadlines.
- GitHub Projects Scrum board.
- Pull requests and commit history.
- Sprint burndown charts.
- Team velocity calculations.
- Test execution and coverage results.
- Team review meetings.

Progress should be compared against the planned activities and any deviations should be recorded.

## 11. Supporting Evidence

The following records support Project Planning:

- `USER_REQUIREMENTS.md`
- Requirements Management documentation.
- Sprint planning and user story allocation.
- Planning Poker evidence.
- GitHub milestones and project board.
- GitHub issues and pull requests.
- PERT and critical path calculations.
- COCOMO I and COCOMO II estimates.
- Sprint burndown and velocity records.
- Team meeting minutes.

## 12. Conclusion

Project Planning establishes the scope, activities, responsibilities, estimates, resources and risks for the Software Bug Tracking and Reporting Tool project.

The project uses three development sprints and GitHub-based planning and tracking.

The project plan must be reviewed and updated when approved changes occur. Actual progress and completion must be supported by project records rather than assumed from planned activities.
