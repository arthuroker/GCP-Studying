
*YAML files*

Defines the build steps and processes for CI/CD pipelines in GCP

A blueprint for each step is required like setting up environments and deploying code

Each step specifies:

1) Name = Docker image used to execute the step
2) Args = commands and parameters that are run in the step
3) Environment variables = optional variables to customize the step

*Substitution variables*

Example = ${ProjectID}, ${BranchName}

Allows you to inject specific variables at runtime and use different configurations depending on the environment

Simplifies multi-environment deployment



