Repo for lambda functions without a pipeline. You need to construct a new one.

1. The resources for lambda function deployment should be first constructed by IaC tools like Terraform, CloudFormation, Ansible etc.
2. *DO NOT* operate on the `main` branch directly. Checkout your own branch instead, e.g. feature/new_pipeline
3. Compose your pipeline file and put them into `cicd`
4. Build up a pipeline on cicd platforms like Jenkins, Travis CI, Github Actions and have a test.
