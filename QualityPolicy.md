### Quality Policy
> Describe your Quality Policy in detail for this Sprint (remember what I ask you to do when I talk about the "In your Project" part in the lectures and what is mentioned after each assignment (in due course you will need to fill out all of them, check which ones are needed for each Deliverable). You should keep adding things to this file and adjusting your policy as you go.
> Check in Project: Module Concepts document on Canvas in the Project module for more details 

**GitHub Workflow** (start Sprint 1)
  Git/GitHub Workflow
1.Creating Branches:
	•Main Branches:
		•master/main: This is the root branch. It must always be stable and reflect the most recent, tested, and deployable version of the project.
		•dev: This branch is used for development. All new features and fixes are first integrated here before being merged into the master branch.
	•Feature/Task Branches:
		•US#-<short description>: For each User Story (US) from the Taiga board, create a branch from the dev branch. The branch name should include the User Story number and a brief description of the task.
		•Task#-<short description> (Optional): If a User Story is broken down into smaller tasks, you can create sub-task branches from the relevant User Story branch.
2.Committing Changes:
	•Commit Messages: Each commit message must include the User Story (US#) and Task# it relates to. Write clear and descriptive messages to indicate what changes were made. Use "WIP" to denote incomplete work.
	•Frequency: Commit changes often to save progress and keep the history detailed. Regular commits help in tracking changes and resolving issues faster.
3.Merging Changes:
	•Pull Requests (PRs) to dev:
		•Once you complete a User Story or a significant update, create a PR from the User Story branch to the dev branch.
		•Ensure the code passes all tests and meets the project’s quality standards.
		•If conflicts are found when reviewing to merge whoever issued the PR needs to be notified to fix it. 
		•The Git Master can squash minor commits on merge to Dev.
		•At least one team member must review the PR before merging. This can be the Git Master but ideally whoever sees the request first. 
		•The Git Master must review the PR. Once approved, the Git Master merges it into dev. If the Git Master is the one issuing the PR they’ll have another team member review before merging.
	•Pull Requests (PRs) to master:
		•When the dev branch has been tested and is stable, create a PR from dev to master.
		•This Git Master makes sure this is a fast-forward merge, ensuring no conflicts.
		•At least one team member must review the PR before merging. This can be the Git Master but ideally whoever sees the request first.  
		•The Git Master must review the PR. Once approved, the Git Master merges it into master.
		•It’s up to the Git Master if they want to do a rebase merge from Dev to master.  Ideally, discuss with teammates before rebase to ensure no conflicts. 
4.Review Process:
	•All PRs require at least one review by another team member to ensure code quality and correctness. 
	•The Git Master is not responsible for all reviews.  Ideally whoever sees the code up for review first should review and then let the Git Master know. 
	•If conflicts are found in the review let the team member who submitted the pull request know. It is their job to fix their conflict and resubmit the request.  Also, let the Git Master know so they don’t waste time reviewing and/or pushing. 
	•The Git Master is notified of all reviews and does all the PR merging, ensuring they meet the project’s standards.
5.Post-Sprint Maintenance:
	•After each sprint, ensure the master branch reflects the current state of the project. This involves merging all completed and reviewed User Stories from dev to master.


**Unit Tests Blackbox** (start Sprint 2)
  > Describe your Blackbox testing policy 

 **Unit Tests Whitebox** (online: start Sprint 2, campus: start Sprint 3)
  > Describe your Whitebox testing policy 

**Code Review** (online: start Sprint 2, campus: start Sprint 2)
  > Describe your Code Review policy for on campus it is ok to have a less formal process in Sprint 2, should be updated in Sprint 3 though

  > Include a checklist/questions list which every developer will need to fill out/answe when creating a Pull Request to the Dev branch. 

  > Include a checklist/question list which every reviewer will need to fill out/anser when conducting a review, this checklist (and the answers of course) need to be put into the Pull Request review.

**Static Analysis**  (online: start Sprint 3, campus: start Sprint 3)
  > Your Static Analysis policy   

**Continuous Integration**  (start Sprint 3, campus: start Sprint 3)
  > Your Continuous Integration policy
