## Learning GitHub Work-flows
* It is the fastest way for integrating CI/CD pipelines for your projects.
* Referring to [Understanding Github Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)
* Helps automating build, test, and deployment pipelines.

## Notes :
**Components** 
* Actions : Unit of code that acomplish frequently repeated tasks(build, deployment, notifications etc), generally defined on a `.yml` file.
* Workflow : Configurable automated process that runs multiple jobs. They are defined inside `.github/workflow` folder within the project.
* Jobs : Set of steps in a workflow.
* Events : A specific activity that triggers a workflow (push, merge, issues opening etc.).
* Runner : A virtual machine or a docker container that runs the workflow. 
