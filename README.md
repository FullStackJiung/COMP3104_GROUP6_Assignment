\# COMP3104 Group 6 Assignment



\## Group Members



\- \*\*Team Leader:\*\* Jiung Yang (101272609) - \[GitHub](https://github.com/FullStackJiung)

\- \*\*Member:\*\* Felipe da Rocha Vieira Mattos (101581203) - \[GitHub](https://github.com/felipervm)



\## Project Description



This repository contains the COMP3104 DevOps Group 6 Assignment at George Brown Polytechnic. The project demonstrates collaborative Git and GitHub workflows, individual developer branches, pull requests, continuous integration with GitHub Actions, and the role of DevOps practices in the software development lifecycle.



Each group member works on an individual branch, creates the required assignment files, makes descriptive commits, and merges completed work into the `main` branch through a pull request.



\## Required Assignment Files



Each member creates the following files using their own student ID:



\- `STUDENTID\_gb.txt` - Information about George Brown Polytechnic

\- `STUDENTID\_devops.txt` - Information about the COMP3104 DevOps course and DevOps concepts

\- `STUDENTID\_sdlc.txt` - The importance of DevOps in the Software Development Life Cycle



\## Setup Instructions



1\. Clone the repository:



```bash

git clone https://github.com/FullStackJiung/COMP3104\_GROUP6\_Assignment.git

```



2\. Move into the project folder:



```bash

cd COMP3104\_GROUP6\_Assignment

```



3\. Fetch the latest branches:



```bash

git fetch

```



4\. Create or switch to your individual branch using the required naming convention:



```bash

git checkout -b STUDENTID-Name

```



5\. Commit changes regularly with clear and descriptive messages.



6\. Push your branch to GitHub:



```bash

git push -u origin STUDENTID-Name

```



7\. Open a pull request from your individual branch into `main`.



\## CI/CD Pipeline



This project uses \*\*GitHub Actions\*\* for Continuous Integration.



The workflow is defined in:



```text

.github/workflows/ci.yml

```



The workflow runs automatically on pushes and pull requests. It checks the repository structure and required assignment files so the team can confirm that changes integrate successfully before merging.



\## Branching Strategy



The team uses a \*\*per-developer branching strategy\*\*.



Each member works in a branch named using the format:



```text

STUDENTID-Name

```



Current branches include:



\- `101272609-JiungYang`

\- `101581203-Felipe`



This strategy protects the `main` branch and allows members to work independently. Completed work is reviewed through pull requests and merged into `main` after successful CI checks.



\## Pull Request Workflow



1\. Complete the required work on an individual branch.

2\. Push the branch to GitHub.

3\. Open a pull request into `main`.

4\. Review the changed files and commit history.

5\. Confirm that GitHub Actions checks pass.

6\. Resolve merge conflicts if necessary.

7\. Merge the pull request into `main`.



A pull request template is available at:



```text

.github/PULL\_REQUEST\_TEMPLATE.md

```



\## Tools Used



\- Git

\- GitHub

\- GitHub Actions

\- Visual Studio Code

\- Command Line / PowerShell



\## Current Contributions



\### Jiung Yang - 101272609



\- `101272609\_gb.txt`

\- `101272609\_devops.txt`

\- `101272609\_sdlc.txt`

\- GitHub Actions CI setup

\- Pull request template



\### Felipe da Rocha Vieira Mattos - 101581203



\- `101581203\_gb.txt`

\- `101581203\_devops.txt`

\- `101581203\_sdlc.txt`

\- 10 descriptive commits on the individual developer branch

\- Pull Request #3 successfully merged into `main`



\## Repository



https://github.com/FullStackJiung/COMP3104\_GROUP6\_Assignment

