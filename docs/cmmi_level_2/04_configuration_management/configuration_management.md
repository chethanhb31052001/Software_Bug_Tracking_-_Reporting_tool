
# Configuration Management (CM)

## 1. Purpose

This document describes the Configuration Management practices followed during the development of the Software Bug Tracking and Reporting Tool.

The purpose of Configuration Management is to establish and maintain the integrity of project work products by identifying, controlling, tracking and reviewing changes throughout the software development lifecycle.

The team uses Git and GitHub to manage source code, documentation, test files, configuration files and other project artefacts.

## 2. Configuration Management Objectives

The main objectives are:

- Maintain version control of project files.
- Identify and organise important project artefacts.
- Maintain a consistent repository structure.
- Track changes made by individual team members.
- Control changes through branches and pull requests.
- Review code and documentation before merging into the main branch.
- Maintain a history of project development.
- Support configuration audits using GitHub records.

## 3. Configuration Identification

Configuration items are the files and artefacts that need to be controlled throughout the project.

The following items are treated as configuration items:

| Configuration Item | Description |
|---|---|
| Python source code | Application modules and backend functionality |
| Test files | Black-box and white-box test cases |
| Project documentation | README and project planning documents |
| Requirements documentation | USER_REQUIREMENTS.md and acceptance criteria |
| CMMI documentation | Process-area documents and supporting evidence |
| Configuration files | Python dependencies and project settings |
| GitHub repository | Central location for project artefacts |
| Git branches | Separate development and documentation work |
| Pull requests | Records of proposed and reviewed changes |

Configuration items are maintained in the project GitHub repository.

## 4. Repository Management

The project uses GitHub as its central version control platform.

Repository:

`https://github.com/chethanhb31052001/Software_Bug_Tracking_-_Reporting_tool`

The repository contains the application source code, test packages, documentation and project evidence.

The team uses a structured directory layout to organise files and make project artefacts easier to locate.

Important repository areas include:

- `src/` – application source code.
- `tests/` – test packages and test cases.
- `docs/` – project and CMMI documentation.
- `README.md` – project setup and execution instructions.
- GitHub Issues and Projects – work tracking and task management.

Changes to repository files are tracked using Git.

## 5. Branch Management

Git branches are used to separate development activities and reduce the risk of uncontrolled changes to the main project.

The team maintains a main branch and uses separate branches for development and documentation activities.

Examples of project branches include:

- `main`
- `S1-10`
- `cmmi-level-2-process-area-documentation`

The team follows these branch-management practices:

1. Create a separate branch for a development or documentation task.
2. Make changes within the relevant branch.
3. Commit changes with meaningful commit messages.
4. Push the branch to the remote GitHub repository.
5. Submit a pull request for review.
6. Merge approved changes into the main branch.
7. Retain project branches in accordance with the assignment requirements.

Branches associated with user stories must be linked to their relevant GitHub Issues.

Project branches should not be deleted after merging because the assignment requires branches to be retained.

## 6. Version Control and Commit Management

Git is used to maintain a history of changes to project files.

Team members commit changes regularly rather than waiting until the end of a sprint.

Commit messages should describe the work performed.

Examples:

- `Add project planning documentation`
- `Add CMMI Level 2 monitoring evidence`
- `Implement bug reporting functionality`
- `Add test cases for bug status updates`

Commit history provides information about:

- What files were changed.
- When changes were made.
- Which repository contributor made the changes.
- The sequence of project modifications.

This information supports traceability and configuration audits.

## 7. Change Control

Changes to project artefacts are managed through GitHub Issues, branches and pull requests.

The team follows this process:

1. Identify the required change.
2. Record or associate the change with a relevant GitHub Issue.
3. Make the change in the appropriate branch.
4. Commit and push the updated files.
5. Submit a pull request describing the changes.
6. Review the proposed changes.
7. Address any review comments.
8. Merge the approved changes into the target branch.

Changes to requirements, user stories or sprint allocations should also be reflected in the relevant project documentation and tracking records.

This approach ensures that changes can be reviewed and traced.

## 8. Pull Request and Code Review Management

Pull requests are used to review proposed changes before they are integrated into the main branch.

The review process helps identify:

- Incorrect or incomplete implementation.
- Missing documentation.
- Unintended changes.
- Inconsistent coding practices.
- Missing or incomplete tests.
- Conflicts with existing project work.

A pull request should include:

- A descriptive title.
- A summary of the changes.
- Related GitHub Issue references.
- Relevant testing information.
- Any additional evidence required for review.

Changes should be merged only after the required review and checks have been completed.

## 9. Configuration Status Accounting

Configuration status accounting records the current state and history of controlled project artefacts.

The team uses the following GitHub information:

- Repository commit history.
- Branch history.
- Pull request records.
- GitHub Issue activity.
- Project milestones.
- Scrum Board status.
- File and directory structure.

These records help identify which changes have been made, which work products have been updated and whether changes have been integrated.

Configuration status is reviewed during sprint reviews and project documentation checks.

## 10. Configuration Verification and Audit

Configuration verification checks whether controlled project artefacts are maintained correctly and whether changes are traceable.

The team reviews:

- Whether required files are present in the repository.
- Whether the repository structure is consistent.
- Whether user-story branches are associated with their issues.
- Whether changes have corresponding commits.
- Whether pull requests describe the changes.
- Whether merged changes are present in the target branch.
- Whether required project branches are retained.
- Whether documentation reflects the current project state.

GitHub history and repository contents provide supporting evidence for these checks.

Configuration audits help identify missing files, untracked changes, incorrect versions and inconsistencies between project records.

## 11. Configuration Management Across Sprints

Configuration Management is applied throughout all three project sprints.

| Sprint | Configuration Management Activities |
|---|---|
| Sprint 1 | Repository setup, initial directory structure, test package setup and initial documentation |
| Sprint 2 | Version-controlled implementation, testing artefacts, CMMI documentation and pull request reviews |
| Sprint 3 | Continued development, integration, testing, final documentation and repository verification |

The team maintains the repository history throughout the project to support traceability and final assessment.

## 12. Roles and Responsibilities

All team members are responsible for maintaining the integrity of their contributions.

Responsibilities include:

- Creating and maintaining appropriate branches.
- Committing changes regularly.
- Associating changes with relevant GitHub Issues.
- Providing meaningful commit messages.
- Submitting pull requests.
- Reviewing proposed changes where required.
- Resolving merge conflicts.
- Ensuring that project documentation and tests are updated when necessary.

The team collectively reviews significant changes and maintains the shared repository.

## 13. Supporting Evidence

Configuration Management is supported by the following records:

- GitHub repository and directory structure.
- Git branch list.
- Git commit history.
- GitHub Issues and their linked branches.
- Pull request descriptions and review records.
- Pull request merge history.
- README and project documentation.
- Test files and execution evidence.
- Sprint milestones and project activity.

These records provide evidence of configuration identification, change control, version management and configuration verification.

## 14. Evidence Limitations and Status

Configuration Management is an ongoing activity throughout the project.

Repository setup and initial test package structure were completed during Sprint 1.

Further configuration activities continue during Sprint 2, including implementation, documentation and pull request management.

Sprint 3 will include continued integration, testing and final repository verification.

The presence of a branch or pull request alone does not establish that all configuration requirements have been satisfied. Each relevant activity must be checked against the repository and its associated evidence.

## 15. Conclusion

The team uses Git and GitHub to identify, control, track and review project configuration items.

Branches, commits, pull requests, issues and repository history provide traceability for changes made throughout the project.

These practices support the CMMI Level 2 Configuration Management process area by helping maintain the integrity and consistency of project work products.
