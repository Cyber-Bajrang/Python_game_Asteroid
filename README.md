# Asteroid

A small pygame starter project for an Asteroids-style game ().

## Requirements

- Python 3.13+ - pygame==2.6.1 (managed in pyproject.toml)

## Setup

### Option 1: Using uv (recommended)

bash<span data-diff-end="13"></span> <span data-diff-start="14"></span>uv sync<span data-diff-end="14"></span> <span data-diff-start="15"></span>

### Option 2: Using pip

To run this project, open your terminal and set up the virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
pip install pygame==2.6.1
```

## Run

```
uv run python main.py
```

## Project Structure

- main.py – game loop and window setup 
- player.py – player ship drawing logic 
- circleshape.py – base sprite class 
- constants.py – screen and player constants 
- logger.py – simple JSONL state/event logging

## Notes

- Make sure Player(...) is created once before the game loop in main.py. - tempCodeRunnerFile.py is a scratch file and can be removed.


# My Awesome Game

![Status: Work in Progress](https://img.shields.io/badge/Status-Work_in_Progress-orange)

This is a Python game built with Pygame...


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
