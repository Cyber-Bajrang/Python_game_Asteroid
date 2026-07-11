# Asteroid

A small pygame starter project for an Asteroids-style game ().

## Requirements

- Python 3.13+ - pygame==2.6.1 (managed in pyproject.toml)

## Setup

### Option 1: Using uv (recommended)

bash<span data-diff-end="13"></span> <span data-diff-start="14"></span>uv sync<span data-diff-end="14"></span> <span data-diff-start="15"></span>

### Option 2: Using pip

bash<span data-diff-end="19"></span> <span data-diff-start="20"></span>python -m venv .venv<span data-diff-end="20"></span> <span data-diff-start="21"></span>source .venv/bin/activate<span data-diff-end="21"></span> <span data-diff-start="22"></span>pip install pygame==2.6.1<span data-diff-end="22"></span> <span data-diff-start="23"></span>

## Run

bash<span data-diff-end="27"></span> <span data-diff-start="28"></span>python main.py<span data-diff-end="28"></span> <span data-diff-start="29"></span>

## Project Structure

- main.py – game loop and window setup 
- player.py – player ship drawing logic 
- circleshape.py – base sprite class 
- constants.py – screen and player constants 


## Notes

- Make sure Player(...) is created once before the game loop in main.py. - tempCodeRunnerFile.py is a scratch file and can be removed.