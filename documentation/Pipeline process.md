# CircleCI pipeline

## Prerequisites

Sign up with GitHub account.

### Connect to your code

1. #### Select Project

   Find the repository, and click Set Up Project.

2. #### Select a config.yml
   In the “Select your config.yml file” modal, select Fast, then click Set Up Project.

You should soon have your first green pipeline. If you are happy with this configuration, merge it into your main branch or continue to make changes.

### Trigger a pipeline on push to your code repository

- pushing code to the main branch will be detected by CircleCI, CircleCi will run a series of steps that is configured in CircleCI config.yml file.

- CircleCi Orbs configures Node, AWS Elastic Beanstalk and AWS Cli.

- CircleCi uses root level package.json to run scripts for both front-end and back-end.
  - Installing Dependencies (front-end, back-end)
  - Frontend Lint
  - Frontend Build
  - API Build
  - Deploy App (front-end, back-end)
