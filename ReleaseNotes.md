# Release 2.2.0

- Remove the ISSUE_TEMPLATE relying on the .github repository for the defaults.
- Add new workflows:
  - py-temp-fork-pvt_merge_with_local-def.yaml
  - py-temp-fork-scheduled_sync_with_upstream-def.yaml
- Removed workflow:
  - python-template-pypi-public-no-docker.yaml
- Updated config files
  - .gitignore
  - pre-commit-config.yaml
- Updated scripts
  - SetupDotEnv.ps1
  - SetupGitHubAccess.ps1
  - SetupPrivateRepoAccess.ps1

______________________________________________________________________

# Release 2.1.2

- Update ISSUE_TEMPLATE's
- Implement GitHub Reusable workflows.
- Upgrade to support Python 13.1
- Update formatting configuration files
  - flake8
  - .gitattributes
  - .gitignore
  - .pre-commit-config.yaml
  - readthedocs.yaml
  - rstcheck.cfg
- Delete redundant files
  - install.ps1
- Add utility scripts
  - SetupDotEnv.ps1
  - SetupGitHubAccess.ps1
  - SetupPrivateRepoAccess.ps1

______________________________________________________________________

# Release 2.1.1

- Updated GitHub Workflows
- Update GitHub ISSUE_TEMPLATE's
- Reconfigure GitHub Workflows and delete old configuration files.
- Update .gitignore
- Update Pre-Commit configuration
- Update Install.ps1
- Configure Poetry to latest version

______________________________________________________________________
