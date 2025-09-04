# python-module-template

## Usage

1. Open [pyproject.toml](pyproject.toml) and update the following fields as needed:

   - **[project].name**
     The name of your project.

   - **[project].version**
     The version number of your project.

   - **[project].description**
     A short description of your project.

   - **[project].authors**
     Project authors' name and email.

   - **[project].maintainers**
     Project maintainers' name and email.

   - **[project].scripts**
     Entry points for executable scripts.

   - **[project.urls]**
     Optional URLs for project page.

   - **[tool.setuptools.dynamic]**
     Path to the version file.

   - **[tool.ruff.lint.isort].known-first-party**
     Specify your project’s first-party modules for import sorting.
