# automation-pipelines


- Github Actions:
    - `actions/checkout@v2`: It is an official GitHub Action used to check-out a repository so a workflow can access it. By default, this action will check-out to the SHA for that workflow’s event (such as push and pull_request). Otherwise, uses the default branch (usually main or master in a standard repository).
    - `actions/setup-python@v2`: 
        This action sets up a Python environment for use in actions by
        1. optionally installing and adding to PATH a version of Python that is already installed in the tools cache.
        1. downloading, installing and adding to PATH an available version of Python from GitHub Releases (actions/python-versions) if a 1. specific version is not available in the tools cache.
        1. failing if a specific version of Python is not preinstalled or available for download.
        1. optionally caching dependencies for pip, pipenv and poetry.
        1. registering problem matchers for error output.