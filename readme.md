# Shopping List (Notebook CLI) — Python

A small shopping list program with an interactive menu, implemented in a Jupyter notebook. Items are kept in an in-memory list of dictionaries for the duration of the running notebook session.

## Features

- Add, list, mark as purchased, and remove items
- Validate that names are not empty and quantities are positive integers

Each item has `nome` (name), `quantidade` (quantity), and `comprado` (purchased status) fields.

## How to run

1. Open `main.ipynb` in Jupyter, Google Colab, or a compatible notebook editor.
2. Run the cells that define the functions.
3. Run the final cell to start the interactive menu with `main()`.

The list is stored in memory and is not saved when the notebook session ends.

This exercise follows the style of the Rocketseat Fundamentals mini project.

## License

Original code and documentation are covered by [MIT](license). The existing Rocketseat copyright notice is preserved in LICENSE.
