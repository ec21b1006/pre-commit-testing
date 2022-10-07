# Guide to setup pre-commit hooks for your package

First install pre-commit package manager:

`sudo snap install pre-commit --classic`

You can check out version of the pre-commit by running this command:

`pre-commit --version`

Now create a file named in your package naming `.pre-commit-config.yaml` and copy all the contents from the ".pre-commit-config.yaml" file available in this repository

Installing pre-commit hooks(this command has to be run if you add a new hook in the pre-commit-config.yaml file):

`pre-commit install`

Now perform your standard git commands and while *git commit* you can see all the hooks working.
