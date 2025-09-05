## Template for Raylib Python games

See it deployed: https://github.com/electronstudio/raylib-example-game

## How to use

Install uv from https://docs.astral.sh/uv/getting-started/installation/

Install copier:

    uv tool install copier

Run copier:

    copier copy gh:electronstudio/python-raylib-template my_game

Read your new README.md for build instructions.

## Features

- Multi-screen game template with transitions and animations
- Resizable window with render texture scaling and bilinear filtering
- Uses `raylib_sdl` for better controller compatibility
- Modern Python packaging with `uv` and `pyproject.toml`
- Cross-platform binary builds via GitHub Actions
- Web build support via pygbag
