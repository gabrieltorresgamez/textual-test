# Textual Test Project

A simple TUI (Text User Interface) application built with Textual.

## Running the Application

```sh
uv run main.py
```

## Building an Executable

```sh
uv run pyinstaller --add-data "styles.tcss:." --onefile main.py
```

## Publishing a Release

```sh
uv version x.y.z
git tag vx.y.z
git push --tags
```
