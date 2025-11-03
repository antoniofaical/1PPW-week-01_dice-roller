# CLI Dice Roller

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

> Version: 1.0  
> Author: Antonio Elias Faiçal Jr.

---

## Features

- Command-line utility for rolling RPG-style dice.
- Supports multiple dice expressions like `2d6 + 1d8`.
- Built-in validation for standard dice types: d4, d6, d8, d10, d12, d20.
- Outputs individual rolls, grouped by expression, with total sums.
- Clear and user-friendly terminal interface.

---

## Requirements

- Python 3.7 or later  
- No external libraries required (uses Python’s built-in `random` module)

---

## How to Use

Run the script using Python:

```bash
python dice_roller.py
```

You’ll see a welcome message and usage instructions.

Examples:

- To roll two d4 dice:
  ```
  2d4
  ```

- To roll one d6 and one d8:
  ```
  1d6 + 1d8
  ```

- To roll just a single d20 (you can omit the number 1):
  ```
  d20
  ```

To quit the program at any time, press `Ctrl+C`.

---

## License

This repository — including all documentation, descriptions, and educational materials —  
is distributed under the  
[**Creative Commons Attribution–NonCommercial 4.0 International License (CC BY-NC 4.0)**](https://creativecommons.org/licenses/by-nc/4.0/).

You are welcome to study, share, and adapt the content for learning purposes.  
Commercial use is not permitted without explicit permission.
