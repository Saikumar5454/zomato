# zomato

Github actions Components
=========================
Workflows
Jobs
Events
Actions
Runners

Workflow
========
A workflow is a configurable automated process that will run one or more jobs.
Workflows are defined in the .github/workflows directory in a repository
Workflows are defined by an YAML file.

Job
===
A Job is a set of steps in a workflow that is executed on the same runner.
Each step is either a shell script that will be executed, or an action that will be run.
Steps are executes in order and are dependent on each other

Event
=====
A Event is a specific activity in a repository that triggers a workflow run.
For example, activity can originate from GitHub when someone creates a pull request, opens an issue, or pushes a commit to a repository.

Actions
=======
An action is a custom application for the GitHub Actions platform that performs a complex
but frequently repeated task.
Use an action to help reduce the amount of repetitive code that you write in your workflow files.

Runner
======
A runner is a server that runs your workflows when they are triggered. Each runner can run a single job at a time.
GitHub provides githosted runners also we can create self hosted runners to run workflows.












