# JoLAZ Home Security - Web Server

This is the web server for JoLAZ's home security system.

## Setup the environment and run the project

To be able to run and contribute with this project, you'll need:

- Python 3.8
- [pipenv](https://pypi.org/project/pipenv)

With your venv activated, run:

```bash
pip install pip-tools
```

Then, on the project's root folder, install the dependencies using:

```bash
pip-sync
```

Finally, you can run the web server using:

```bash
uvicorn main:app --reload
```

Have fun!
