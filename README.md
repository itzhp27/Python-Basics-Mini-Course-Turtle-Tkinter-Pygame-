# Python Basics Mini-Course: Turtle, Tkinter, Pygame

A short, beginner-friendly course that teaches core programming ideas through three visual Python libraries. Each lesson has a working example, a "what you'll learn" list, and practice exercises that build from easy to challenging.

Designed for school-age learners and anyone writing their first Python programs.

<!-- Add a screenshot or GIF of each lesson's output here, e.g.
![Turtle output](screenshots/lesson1.png)
-->

## Lessons

| # | Library | Lesson | Core ideas |
|---|---------|--------|------------|
| 01 | Turtle | Draw with code | Variables, `for` loops, functions |
| 02 | Tkinter | Build a window people can click | Event-driven programming, buttons and labels, program state |
| 03 | Pygame | Turn your code into a game | The game loop, keyboard input, boundary and collision checks |

### Lesson 01: Turtle

Students steer a turtle around the screen to learn variables, loops, and functions in the most visual way possible.

- **Example:** a multi-colored square (`lesson1_turtle.py`)
- **Exercises:** draw a triangle and a hexagon, write a reusable `draw_shape(sides, length)` function, and (challenge) draw a spiral

### Lesson 02: Tkinter

Students build a small window with a label and a button, and learn that code can wait for the user to act.

- **Example:** a click counter (`lesson2_tkinter.py`)
- **Exercises:** add a Reset button, show "Even" or "Odd" for the count, and (challenge) build a tip calculator

### Lesson 03: Pygame

Students combine drawing and interactivity inside a loop that runs 60 times a second.

- **Example:** a square you can move with the arrow keys (`lesson3_pygame.py`)
- **Exercises:** add up/down movement, make the square bounce off the screen edges, and (challenge) detect when two rectangles overlap

## Getting Started

### Requirements

- Python 3.8 or newer
- Turtle and Tkinter come bundled with Python. On some Linux distributions you may need to install Tkinter separately, for example `sudo apt install python3-tk`.
- Pygame is the only extra install:

```bash
pip install pygame
```

### Run the examples

```bash
python lesson1_turtle.py
python lesson2_tkinter.py
python lesson3_pygame.py
```

### View the lesson pages

Open `index.html` in any web browser to read the full lessons, including explanations, example code, and exercises.

## Repository Structure

```
.
├── index.html            # Lesson pages
├── lesson1_turtle.py     # Lesson 01 example
├── lesson2_tkinter.py    # Lesson 02 example
├── lesson3_pygame.py     # Lesson 03 example
└── README.md
```

<!-- Adjust the file names above to match your actual repo. -->

## How to Use This Course

1. Read the lesson introduction and the "What you'll learn" list.
2. Run the example code and see what it does.
3. Change one thing at a time and re-run it to see the effect.
4. Work through the exercises in order. The last one in each lesson is a challenge, so treat it as optional at first.

## Author

Made by **[Your Name]**, Computer Science student.
GitHub: [your-username](https://github.com/your-username)

## License

Add a license of your choice (for example, MIT) or remove this section.
