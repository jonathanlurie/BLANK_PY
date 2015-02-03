# BLANK_PY
## What is it?
It provides a simple super-basic framework for making a Python app.

## How does it work?
It contains several folders and files, among them:

**Files:**

- `launcher.sh` a double click on it will launch your app, with the entry point in `src/main.py`. It also load  the local  `lib/`folder in `PYTHONPATH`.
- `settings.ini` a config file to be used with the `ConfigParser` module.
- `README.md` the readme, using markdown syntax.

**Folders:**

- `src` must contain your python source files.
- `lib` contains the external Python modules (from Pypi, Github...)
- `test` you can place your test sources there


## Platform
It was developped on **OSX** but should work without any problem on any **UNIX** platform.