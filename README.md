# GitHub Actions Workflow Practice

This repository contains my first GitHub Actions workflow, completed as part of my Cloud Engineer Academy training.

The purpose of this project was to understand the basic structure of a GitHub Actions workflow before applying GitHub Actions to more advanced AWS and CI/CD automation projects.

## Project Overview

In this project, I created a simple GitHub Actions workflow that runs automatically when changes are pushed to the repository.

The workflow demonstrates how GitHub Actions uses events, jobs, runners and steps to automate tasks inside a repository.

Although this is a basic workflow, it helped me understand the foundation of CI/CD automation and how GitHub Actions can later be used for cloud deployment pipelines.

## What This Project Demonstrates

* Creating a GitHub repository and cloning it locally
* Creating the required `.github/workflows` folder structure
* Writing a basic workflow file in YAML
* Using a `push` event to trigger a workflow
* Defining a job inside a workflow
* Running the job on an Ubuntu runner
* Creating workflow steps with shell commands
* Using `echo` commands to print workflow output
* Displaying the GitHub repository name using a GitHub context variable
* Viewing workflow runs and logs in the GitHub Actions tab

## Technologies Used

* GitHub Actions
* YAML
* Git and GitHub
* VS Code
* Command Line / Terminal
* Ubuntu runner

## Repository Structure

```text
github_actions_workflows/
├── .github/
│   └── workflows/
│       └── main.yaml
└── README.md
```

## How the Workflow Works

1. A change is committed and pushed to the repository.
2. The push event triggers the GitHub Actions workflow.
3. GitHub provisions an Ubuntu runner.
4. The workflow job runs on the runner.
5. Each step runs in order.
6. The workflow prints a simple message and displays the repository name.
7. The workflow result can be checked in the GitHub Actions tab.

## Key Learning Outcomes

Through this project, I learned:

* Why GitHub Actions workflows are stored inside `.github/workflows`
* How YAML is used to define automation workflows
* How workflow triggers start automation
* What jobs, steps and runners mean in GitHub Actions
* How to read basic workflow output in GitHub Actions logs
* How GitHub Actions can be used as the foundation for CI/CD pipelines

## Why This Project Matters

This project was my starting point for understanding GitHub Actions.

It helped me move from only knowing Git and GitHub as version control tools to understanding how GitHub can also automate tasks through workflows.

This foundation later supports more advanced DevOps work, such as validating infrastructure code, deploying cloud resources, and automating AWS deployment pipelines.

## Future Improvements

* Add a workflow status badge
* Add more workflow examples using pull requests
* Add a validation step for code or configuration files
* Add AWS deployment steps in a separate project
* Add screenshots of successful workflow runs
