# Sprint Planning, Review and Retrospective

## Product Backlog

- The Product Owner creates user stories as cards in the project board.
- These cards are placed in the "Product Backlog" column.
- Each card is labeled with "User Story" for clear identification.
- At this stage, user stories are not assigned to any specific repository or team member.
- The Product Owner prioritizes these user stories within the Product Backlog based on business value and other relevant factors.

## Sprint Planning

- The team selects user stories for the sprint.
- Selected user stories move from Product Backlog to Sprint Backlog.

Example of Sprint Planning:
```
   - Product Backlog:
     1. "As a user, I want to log in to the application" (High Priority)
     2. "As a user, I want to reset my password" (Medium Priority)
     3. "As a user, I want to view my profile" (Low Priority)
   
   - After Sprint Planning:
     - Sprint Backlog:
       1. "As a user, I want to log in to the application"
       2. "As a user, I want to reset my password"
     - Remaining in Product Backlog:
       3. "As a user, I want to view my profile"
```

## Task Creation and Management

- During sprint planning, the development team breaks down selected user stories into smaller, technical tasks.
- Create new issues for each task in the appropriate repository (e.g., frontend, backend).
- Each task issue is linked to its parent user story for traceability.
- Tasks are initially placed in the "Sprint Backlog" column of the project board.
- Only move tasks to "To Do" when they are ready to be worked on immediately.

Example of Task Flow:
```
   - User Story: "As a user, I want to log in to the application"
     1. Task: "Implement basic email/password authentication" (moved to "To Do")
     2. Task: "Implement OAuth integration" (stays in "Sprint Backlog")
   - The OAuth task is only moved to "To Do" once the basic authentication is completed.
```

## Sprint Review and Retrospective
   - At the end of the sprint:
     - Review completed user stories and tasks.
     - Merge the sprint branch into the main branch.
     - Create a new sprint branch for the next sprint.
     - Move incomplete user stories back to the Product Backlog or to the next sprint's backlog, as decided by the team.