channelstream_landing
=====================

Getting Started
---------------

- Change directory into your newly created project.

    cd channelstream_landing

- Create a Python virtual environment.

    python3 -m venv env

- Upgrade packaging tools.

    env/bin/pip install --upgrade pip setuptools

- Install the project in editable mode with its testing requirements.

    env/bin/pip install -e ".[testing]"

- Run your project's tests.

    env/bin/pytest

- Run your project.

    channelstream_landing_build_statics development.ini
    env/bin/pserve development.ini
