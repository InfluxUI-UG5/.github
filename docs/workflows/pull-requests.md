# Pull Request Process

1. Creating a Pull Request (PR):
   - Create a PR to merge your branch into the sprint branch.
   - Fill in the PR template with a clear title and description.
   - Link the PR to the relevant task issue.
   - Request reviews from team members.

   Example PR title: "Feature: Add user login form (#42)"

   Example PR description:
   ```
   This PR implements the user login form as described in issue #42.

   Changes made:
   - Created a responsive login form
   - Implemented client-side validation
   - Added unit tests for form validation logic

   Please review the form layout and validation logic.

   Closes #42
   ```

2. Code Review:
   - Address feedback by making new commits to your branch.
   - Update the PR by pushing these new commits.

   Example of addressing feedback:
   ```
   git commit -m "Refactor form validation as per review comments"
   git push origin feature/42-add-login-form
   ```

3. Merging:
   - Once approved and all checks pass, merge the PR into the sprint branch.
   - Delete the feature branch after merging.
   - Move the task to "Done" on the project board.
   - If this completes the user story, move it to "Done" as well.