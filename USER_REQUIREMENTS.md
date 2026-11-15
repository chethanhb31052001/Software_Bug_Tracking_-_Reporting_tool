# User Requirements — Bug Tracking and Reporting Tool

## Roles

Reporter, Developer, Project Manager, Administrator.

## Estimation note

Story points use the Fibonacci scale: 1, 2, 3, 5, 8. Estimates below are starting suggestions, not recorded team votes. The team must estimate each story using Planning Poker and record the individual votes and agreed points separately.

## User stories

### Account and authentication

**UR01 — Register an account**  
As a user, I want to register with my name, email, and password so that I can use the bug tracking tool.  
Acceptance: A valid registration creates an account; invalid input and an already-used email are rejected.  
Suggested points: 3

**UR02 — Sign in**  
As a registered user, I want to sign in with my email and password so that I can access my account.  
Acceptance: Valid credentials return an access token; invalid credentials are rejected.  
Suggested points: 3

**UR03 — Sign out**  
As a signed-in user, I want to sign out so that my access token can no longer be used.  
Acceptance: A valid token is revoked; an unknown or already-revoked token is rejected.  
Suggested points: 2

**UR04 — View my profile**  
As a signed-in user, I want to retrieve my profile so that I can check my account details.  
Acceptance: The response contains my profile; unauthenticated requests are rejected.  
Suggested points: 2

**UR05 — Update my profile name**  
As a signed-in user, I want to update my name so that my profile stays current.  
Acceptance: A non-empty name is saved; blank or non-text names are rejected.  
Suggested points: 2

**UR06 — Protect account passwords**  
As a user, I want my password stored as a secure hash so that the original password is not kept in the database.  
Acceptance: Stored password data is hashed; correct passwords verify and incorrect passwords do not.  
Suggested points: 5

### Projects and membership

**UR07 — Create a project**  
As a Project Manager, I want to create a project so that bugs can be organised by project.  
Acceptance: A valid project is created and its creator becomes a member; duplicate names are rejected.  
Suggested points: 3

**UR08 — View a project**  
As a project member, I want to retrieve project details so that I can confirm the project information.  
Acceptance: Members can view the project; non-members and unknown projects are rejected.  
Suggested points: 2

**UR09 — List my projects**  
As a signed-in user, I want to see projects I belong to so that I can find my work.  
Acceptance: The response lists my projects and returns an empty list when I belong to none.  
Suggested points: 2

**UR10 — Update a project**  
As a Project Manager, I want to update my project’s name or description so that its details remain accurate.  
Acceptance: The creator can update valid fields; invalid input and duplicate names are rejected.  
Suggested points: 3

**UR11 — Add a project member**  
As a Project Manager, I want to add a registered user to my project so that they can work on its bugs.  
Acceptance: The creator can add an existing non-member; unknown users and duplicate memberships are rejected.  
Suggested points: 3

**UR12 — List project members**  
As a project member, I want to see the project’s members so that I know who is involved.  
Acceptance: Members can retrieve the list; non-members cannot.  
Suggested points: 2

**UR13 — Remove a project member**  
As a Project Manager, I want to remove a member who no longer needs access so that membership stays accurate.  
Acceptance: The creator can remove an eligible member; the creator cannot remove themselves, and members with open assigned bugs cannot be removed.  
Suggested points: 5

### Bug reports

**UR14 — Submit a bug report**  
As a Reporter, I want to submit a bug report so that the team can investigate it.  
Acceptance: A project member can submit a report with a non-empty title and description.  
Suggested points: 3

**UR15 — Include reproduction steps**  
As a Reporter, I want to provide reproduction steps so that developers can reproduce the problem.  
Acceptance: The report stores the supplied steps.  
Suggested points: 2

**UR16 — Include expected and actual results**  
As a Reporter, I want to record expected and actual results so that the difference is clear.  
Acceptance: The report stores both values.  
Suggested points: 2

**UR17 — Include the environment**  
As a Reporter, I want to record the environment where the bug occurred so that the team can understand its context.  
Acceptance: The report stores the supplied environment information.  
Suggested points: 2

**UR18 — Set bug severity**  
As a Reporter, I want to select a severity so that the impact of a bug is recorded.  
Acceptance: Only supported severity values are accepted.  
Suggested points: 2

**UR19 — Set bug priority**  
As a Project Manager, I want to set a bug’s priority so that the team can decide what to address first.  
Acceptance: Only supported priority values are accepted.  
Suggested points: 2

**UR20 — View project bugs**  
As a project member, I want to list the project’s bug reports so that I can review its work.  
Acceptance: Members can retrieve the list; non-members cannot.  
Suggested points: 2

**UR21 — View a bug report**  
As a project member, I want to view one bug’s details so that I can understand the report.  
Acceptance: Members can retrieve an existing project bug; a missing bug returns not found.  
Suggested points: 2

**UR22 — Edit a bug report**  
As a project member, I want to edit bug details so that incorrect or incomplete information can be fixed.  
Acceptance: Supported fields can be updated; invalid fields and invalid values are rejected.  
Suggested points: 3

**UR23 — Prevent duplicate open bug reports**  
As a project member, I want the tool to identify duplicate open bug titles so that duplicate work is reduced.  
Acceptance: A duplicate open title in the same project is rejected; resolved or closed bugs do not count as open duplicates.  
Suggested points: 3

### Bug workflow and collaboration

**UR24 — Change a bug’s status**  
As a Developer, I want to change a bug’s status so that the team can track its progress.  
Acceptance: Only supported statuses are accepted; the bug’s status is updated.  
Suggested points: 3

**UR25 — Record status history**  
As a Project Manager, I want status changes recorded so that the bug’s progress can be reviewed.  
Acceptance: A genuine status change records old and new status; submitting the same status does not add a duplicate history entry.  
Suggested points: 3

**UR26 — Assign a bug to a project member**  
As a Project Manager, I want to assign a bug to a project member so that responsibility is clear.  
Acceptance: A bug can be assigned to a member; a non-member cannot be assigned.  
Suggested points: 3

**UR27 — Clear a bug assignment**  
As a Project Manager, I want to clear a bug’s assignment so that it can be reassigned.  
Acceptance: The bug’s assignee can be set to null.  
Suggested points: 2

**UR28 — View bugs assigned to me**  
As a Developer, I want to list bugs assigned to me so that I can track my work.  
Acceptance: The response contains my assigned bugs or an empty list when none are assigned.  
Suggested points: 2

**UR29 — Add a comment to a bug**  
As a project member, I want to comment on a bug so that I can share investigation notes.  
Acceptance: A member can add a non-empty comment to an existing project bug.  
Suggested points: 3

**UR30 — View bug comments**  
As a project member, I want to view comments on a bug so that I can follow the discussion.  
Acceptance: Members can retrieve the comments for an existing bug.  
Suggested points: 2

### Search, reporting, and export

**UR31 — Search bugs by text**  
As a project member, I want to search bug titles and descriptions so that I can find relevant reports.  
Acceptance: The search returns bugs matching the supplied text.  
Suggested points: 3

**UR32 — Filter bugs by status**  
As a project member, I want to filter bugs by status so that I can focus on a workflow stage.  
Acceptance: A valid status filter returns matching bugs; an invalid status is rejected.  
Suggested points: 2

**UR33 — Filter bugs by severity and priority**  
As a project member, I want to filter bugs by severity and priority so that I can focus on important reports.  
Acceptance: Valid filters return matching bugs; unsupported filter values are rejected.  
Suggested points: 3

**UR34 — View a project bug summary**  
As a Project Manager, I want a summary of bugs by status and severity so that I can understand project progress.  
Acceptance: The summary gives total bugs and counts by status and severity, including zero counts when there are no bugs.  
Suggested points: 3

**UR35 — Export bugs to CSV**  
As a Project Manager, I want to export project bugs as a CSV file so that I can analyse or share the data.  
Acceptance: The export has a CSV content type, column headings, and bug rows when available.  
Suggested points: 3

### Validation, access, and administration

**UR36 — Require authentication for protected actions**  
As a user, I want protected project and bug operations to require a valid token so that unauthorised users cannot access them.  
Acceptance: Missing, invalid, and expired tokens are rejected.  
Suggested points: 5

**UR37 — Restrict project data to members**  
As a Project Manager, I want project data limited to project members so that unrelated users cannot access it.  
Acceptance: Members can use project routes; non-members are denied.  
Suggested points: 5

**UR38 — Validate API input**  
As a user, I want clear errors for invalid request data so that I can correct my request.  
Acceptance: Malformed JSON, incorrect field types, missing required values, and unsupported enum values return suitable client errors.  
Suggested points: 3

**UR39 — Keep project records separate**  
As a project member, I want bugs and comments associated with the correct project and bug so that records do not appear in the wrong place.  
Acceptance: Queries and updates use the requested project and bug identifiers and do not return another project’s records.  
Suggested points: 5

**UR40 — Administer user accounts**  
As an Administrator, I want to manage user accounts and roles so that access can be maintained.  
Acceptance: Only an authorised administrator can perform account or role-management actions, and changes are persisted.  
Suggested points: 8

## Status: Planned-not Implemented 