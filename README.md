# Automate Task via GitHub Actions
A repo that contains automation of repetitive tasks via GitHub Actions

## Notes for Kogito branch
### OperatorHub PRs creation for Kogito Operator
If you would like to create the required PRs for the Kogito Operator in order to have a new version available on
OperatorHub you need to edit the ``.github/variables/kogito/operatorhub-prs.env`` file with the desired VERSION and 
the DRY_RUN flag to enable the push on your fork and the creation of a draft PR.

So if you would like to open the PRs for the OperatorHub for version 1.34.0 you need to edit the file to include the 
following content:
```shel
VERSION=1.34.0
DRY_RUN=false
```