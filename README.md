# wdio-perfecto-sample

This is a sample project showcasing basic integration of Cucumber WDIO JS framework with Perfecto Mobile cloud.

**How to set up the Project:**

  1. Download the project.
  2. Open the project on IDE (Optional).
  3. Open command prompt or terminal on the project folder.
  4. Execute **npm install** command to install project dependencies.
  5. Set following Environment variables:
     SECURITY_TOKEN - Perfecto Mobile's security token
     JOB_NAME – Name of CI Dashboard job name
     JOB_NUMBER – Number of CI Dashboard job
     PROJECT_NAME – Name of Project used in Perfecto’s reporting
     PROJECT_VERSION – Version of the Project
     BRANCH_NAME – Name of the branch

**How to execute tests in the Project:**
  npm run wdio

Test Execution report(s) will be available in Perfecto Mobile's Report analysis tab.
