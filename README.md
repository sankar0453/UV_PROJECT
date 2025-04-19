# UV_PROJECT


pip install uv

Commands:
  run      Run a command or script
  init     Create a new project
  add      Add dependencies to the project
  remove   Remove dependencies from the project
  sync     Update the project's environment
  lock     Update the project's lockfile
  export   Export the project's lockfile to an alternate format
  tree     Display the project's dependency tree
  tool     Run and install commands provided by Python packages
  python   Manage Python versions and installations
  pip      Manage Python packages with a pip-compatible interface
  venv     Create a virtual environment
  build    Build Python packages into source distributions and wheels
  publish  Upload distributions to an index
  cache    Manage uv's cache
  self     Manage the uv executable
  version  Display uv's version
  help     Display documentation for a command

uv python install

uv python install 3.12

uv venv

.venv\Scripts\activate

(first_demo) D:\agno-workspace\UV_PROJECT\first_demo>

uv add numpy

uv add -r requirementx.txt

uv run main.py

uv sync

uv lock
