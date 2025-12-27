##  Animated ASCII Christmas Tree in Python 🎄

This Python script creates a festive animated Christmas tree with falling snow and a sparkling star at the top — all in your terminal! ✨

You can also customize colors, tree height, and snow effects.

## Features

--Animated falling snow

--Colored tree with random ornaments

--Star on top of the tree

--Customizable colors, height, and width

--Runs in Windows, Linux, and macOS terminals

## Prerequisites

Python 3.x

A terminal that supports ANSI escape sequences (most modern terminals do)

## How to Run

Clone or download the repository:

git clone <your-repo-url>
cd <repo-folder>


## Run the script:

run it via executing or typing a cmd like 
``` bash 
python christmas_tree.py
```
##  Customization🎨
Change Tree Height and Width

At the top of the script:

height = 10   # Tree height
width = 2 * height  # Snow and tree width


Change height to make the tree taller or shorter. width adjusts snow movement.

Change Tree Colors

The script uses ANSI colors:

COLORS = [
    "\033[91m",  # Red
    "\033[92m",  # Green
    "\033[93m",  # Yellow
    "\033[95m",  # Magenta
    "\033[96m",  # Cyan
]
WHITE = "\033[97m"
YELLOW = "\033[93m"
RESET = "\033[0m"


Add or remove colors in COLORS to change ornaments.

WHITE controls snow color.

YELLOW controls the star and trunk.

Adjust Snow Density
snow = [random.randint(0, width) for _ in range(10)]


Change the 10 to a higher number for more snowflakes, or lower for fewer.

Adjust Speed
time.sleep(0.5)


Decrease the value (e.g., 0.2) to make the animation faster.

Increase the value (e.g., 1) to slow it down.

## Screenshots works nicely 👍👍👍

<img width="526" height="388" alt="image" src="https://github.com/user-attachments/assets/1608ccd3-6ab6-4fa2-a8df-306a350e8d3e" />



## Tips

Works best in terminals that support ANSI escape sequences.

On Windows, you may need to run in PowerShell or Windows Terminal.

Experiment with different colors and tree heights for a personalized touch 


#author 
--Arun Bohara 
