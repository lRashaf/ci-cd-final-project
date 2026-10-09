# CI/CD Final Project

This repository contains my Final Project for the Coursera course **CI/CD Tools and Practices**.

## Project Name

**ci-cd-final-project**: a Flask service with a CI pipeline on GitHub Actions and a CD pipeline on OpenShift using Tekton.

## Setup

After entering the lab environment you will need to run the `setup.sh` script in the `./bin` folder to install the prerequisite software.

```bash
bash bin/setup.sh
```

Then you must exit the shell and start a new one for the Python virtual environment to be activated.

```bash
exit
```

## Tasks

- GitHub Actions CI workflow: `.github/workflows/workflow.yml` (lint with flake8, unit tests with nose)
- Tekton CD pipeline: `.tekton/tasks.yml` (cleanup, nose tests)

## License

Licensed under the Apache License. See [LICENSE](/LICENSE)

## Author

Skills Network

## <h3 align="center"> © IBM Corporation 2023. All rights reserved. <h3/>