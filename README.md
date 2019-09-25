# actions
Github action to auto create a branch in master from forked repository on Pull Request

## Pre-requisites
- Base and forked repositories are created
- Forked repository is updated with the latest changes in the base repository

## Usage

- Copy the github action **.github/workflows/main.yaml** to your base repository
- Create new branch in your forked repository with your changes and raise a PR against the base repository
- Once the PR is raised, github action in your base repository under .github/workflows will get triggered
- The workflow will automatically create a new branch in your base repository with the new changes from the fork

