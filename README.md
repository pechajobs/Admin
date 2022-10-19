<h1 align="center">
  <br>
  <a href="https://openpecha.org"><img src="https://avatars.githubusercontent.com/u/111121384?s=400&u=8845a52564bdd6b236cbff4c95843c475f0fa3b7&v=4" alt="OpenPecha" width="150"></a>
  <br>
</h1>

<h3 align="center">Requests</h3>


<!-- Replace the title of the repository -->

<p align="center">
  <a href="#description">Description</a> •
  <a href="#owner">Owner</a> •
  <a href="#integrations">Integrations</a> •
  <a href="#docs">Docs</a>
</p>
<hr>

# Pecha.jobs Workflow

## Roles
- The **Client/Management** orders and pays for the job. ལས་ཀའི་སྦྱིན་བདག
- The **Job Owner** oversees the job for the Management. འགན་འཁུར་བ།
- The **Team Lead** plans and does the job. ལག་བསྟར་བ།
- The Team Lead's **Teammates** help the Team Lead do the job. ལས་གྲོགས།

## Workflow

### 1. Create a request for job (RFJ)
The Job Owner writes an RFJ that details the job that the Client asks for.

### 2. Create a request for comments (RFC)
The Team Lead writes an RFC to show that they understand the work and have a plan that will lead to success.

### 3. Approve the RFC
The Job Owner reviews the RFC and meets with the Team Lead to go over it. Once the Job Owner is satisfied with the Team Lead's plan, the Job Owner signs off on the RFC.

### 4. Create a repository
The Team Lead creates a job repository, updates its readme file, and transfers the RFC to the new repo.

### 5. Create a Github project and milestones
The Team Lead creates a Github project for the job. Then they create milestones based on the key phases of the RFC's detailed plan.

### 6. Convert work plan items into issues
The Team Lead converts each item in the RFC work plan into an issue and assigns it to both the job's repository and project.

### 7. Assign issues to the team
The Team Lead assigns each issue to themselves or their Teammates if working as a team.

### 8. Assign milestones to issues
The Team Lead assigns issues to milestones.

### 9. Do the work and create pull requests
The Team Lead and their teammates do the work and add commits. When they are done, they make one pull request per issue/task.

### 10. Merge requests
The Job Owner reviews each pull request, asks for changes if needed, and signs off on the work by merging the PR. After merging the PR, the Job Owner moves the issue to the completed section of the project board.
