
# Configuration Management – Supporting Evidence

## 1. Purpose

This document records the evidence supporting Configuration Management practices followed during the development of the Software Bug Tracking and Reporting Tool.

The evidence is based on the GitHub repository, branches, commits, pull requests, issues and project documentation.

Only verified activities are recorded as completed. Proposed, ongoing and pending activities are identified separately.

## 2. Repository Information

| Item | Details |
|---|---|
| Project | Software Bug Tracking and Reporting Tool |
| Version Control System | Git |
| Repository Hosting | GitHub |
| Repository | [Software Bug Tracking and Reporting Tool](https://github.com/chethanhb31052001/Software_Bug_Tracking_-_Reporting_tool) |
| Main Development Branch | main |
| Local Development Environment | PyCharm |
| Programming Language | Python |

The GitHub repository acts as the central location for project source code, tests and documentation.

## 3. Configuration Item Identification

The project repository contains the following configuration items:

| Configuration Item | Repository Location | Purpose |
|---|---|---|
| Application source code | `src/` | Backend application implementation |
| Test packages | `tests/` | Test cases and testing evidence |
| Project documentation | `docs/` | Project documentation and assessment evidence |
| Requirements | `USER_REQUIREMENTS.md` | User stories and acceptance criteria |
| Project instructions | `README.md` | Setup and execution information |
| CMMI documentation | `docs/cmmi_level_2/` | CMMI process-area documentation |
| Dependency configuration | Project configuration files | Python environment and dependencies |

These items are maintained under Git version control.

## 4. Branch Management Evidence

The team uses branches to separate development and documentation activities.

Examples of branches include:

| Branch | Purpose |
|---|---|
| `main` | Main project branch |
| `S1-10` | Sprint 1 repository setup activity |
| `cmmi-level-2-process-area-documentation` | CMMI documentation work |

Additional branches are maintained for individual user-story implementation and testing activities.

The branch list can be verified through the GitHub repository's Branches page.

All required user-story branches should remain available after merging, in accordance with the assignment instructions.

Branches associated with user stories should be linked to their relevant GitHub Issues.

## 5. Commit Management Evidence

Git commit history records changes made to project files.

Commit records provide:

- Contributor information.
- Commit date and time.
- Commit message.
- Files changed.
- Change history.

Example local verification commands:

```powershell
git log --oneline --all
git status
git branch -a
```

These commands help verify repository history, working-tree status and available branches.

## 6. Pull Request Evidence

Pull requests are used to review and integrate proposed changes.

The following pull requests provide evidence of repository and documentation activities:

| Pull Request | Activity | Status |
|---|---|---|
| PR #15 | Repository skeleton and test package structure | Merged |
| PR #16 | CMMI evidence folder setup | Merged |
| PR #18 | Requirements Management documentation | Merged |
| PR #39 | CMMI Project Planning, Project Monitoring and Control, and Configuration Management documentation | Open – awaiting review |

PR #39 contains six CMMI documentation files covering Project Planning (PP), Project Monitoring and Control (PMC), and Configuration Management (CM).

The pull request is intended for review before integration into the main branch.

The pull request history provides evidence of proposed changes, file modifications and, where applicable, integration into the main branch.

## 7. Change Control Evidence

Changes to project files are managed using GitHub Issues, branches, commits and pull requests.

Examples of change-control records include:

- GitHub Issue descriptions and assignments.
- Branches associated with development activities.
- Commit messages describing modifications.
- Pull request descriptions and review comments.
- Merge records showing integration into the target branch.

For example, Requirements Management documentation was submitted through PR #18 and merged into the main branch.

The pull request included changes to requirements documentation and CMMI evidence.

PR #39 provides a current example of the team's documentation change-control process. It remains open while the proposed changes are reviewed.

## 8. Repository Structure Verification

The repository structure is reviewed to ensure that project artefacts are organised correctly.

The CMMI documentation structure is:

```text
docs/
└── cmmi_level_2/
    ├── README.md
    ├── 01_requirements_management/
    │   └── requirements_management.md
    ├── 02_project_monitoring_and_control/
    │   ├── project_monitoring_and_control.md
    │   └── monitoring_evidence.md
    ├── 03_project_planning/
    │   ├── project_planning.md
    │   └── planning_evidence.md
    ├── 04_configuration_management/
    │   ├── configuration_management.md
    │   └── configuration_evidence.md
    ├── 05_measurement_and_analysis/
    ├── 06_process_and_product_quality_assurance/
    └── 07_final_audit/
```

The structure can be checked using:

```powershell
tree docs\cmmi_level_2 /F
```

This helps verify that the CMMI documents are stored in their intended locations.

## 9. Configuration Verification Activities

The team checks configuration integrity by reviewing:

- Repository contents.
- Branch names and branch history.
- Commit records.
- Pull request changes.
- Merge status.
- GitHub Issue associations.
- Documentation consistency.
- Test files and project configuration.

A clean Git working tree can be checked using:

```powershell
git status
```

The team also reviews changes before committing and pushing them to the remote repository.

## 10. Sprint-wise Configuration Management Evidence

| Sprint | Configuration Activities | Evidence |
|---|---|---|
| Sprint 1 | Initial repository structure and test package setup | PR #15 |
| Sprint 1 | CMMI evidence folder setup | PR #16 |
| Sprint 1 | Requirements Management documentation | PR #18 |
| Sprint 2 | CMMI PP, PMC and CM documentation | Branch `cmmi-level-2-process-area-documentation`; PR #39 (open, awaiting review) |
| Sprint 2 | Implementation and testing changes | To be updated with actual commits and pull requests |
| Sprint 3 | Final integration and repository verification | To be updated during Sprint 3 |

## 11. Evidence Limitations and Status

The repository and its history provide evidence of configuration management activities completed during Sprint 1.

During Sprint 2, the team prepared CMMI Project Planning, Project Monitoring and Control, and Configuration Management documentation in the branch:

`cmmi-level-2-process-area-documentation`

These six documentation files have been submitted through PR #39 for review before merging into the main branch.

At the time of this evidence record, PR #39 is open and awaiting review. Its changes must not be treated as merged until the pull request is approved and merged.

Further implementation, testing, review and integration records will be added as the project progresses.

A branch existing locally or remotely does not by itself prove that its changes have been reviewed or merged.

## 12. Conclusion

Git and GitHub provide the mechanisms used by the team to manage project configuration items and control changes.

Repository structure, branches, commit history, pull requests and issue records provide supporting evidence for configuration identification, version control, change management and verification.

These practices support the CMMI Level 2 Configuration Management process area.
