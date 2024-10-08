# Using GitHub Actions - Part 1:-
# Learning Objectives
- After completing this lab, you will be able to:

1. Create a GitHub workflow to run your CI pipeline
2. Add events to trigger the workflow
3. Add a job to the workflow
4. Add a job runner to the job
5. Add a container to the job runner

# Prerequisites
- You will need the following to complete the exercises in this lab:

1. A basic understanding of YAML
2. A GitHub account
3. An intermediate-level knowledge of CLIs

# Generate GitHub Personal Access Token:- 
# Fork and Clone the Repository
- In the terminal, if you are not already in the /home/project folder, change to your project folder now.

```bash
cd /home/project 
```
- Authenticate with GitHub
```bash
sudo apt update
sudo apt install gh
```
- Then. run the following command to authenticate with GitHub in the terminal. You will need the GitHub Personal Token you created in the previous step.
```bash
gh auth login
```
- good cool  
