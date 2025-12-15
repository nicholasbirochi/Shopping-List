# Shopping List (Notebook CLI) — Python

A mini **Shopping List** system with an interactive CLI menu (running inside a notebook), using an **in-memory list of dictionaries**. Built in the same style as the Rocketseat Fundamentals mini project.

## Requirements covered

- Loop menu with options:
  1. Add item
  2. List items
  3. Mark item as purchased
  4. Remove item
  5. Exit
- Functions implemented:
  - `adicionar_item`
  - `listar_itens`
  - `marcar_comprado`
  - `remover_item`
- Basic validations:
  - name cannot be empty
  - quantity must be an integer > 0

## In-memory data model

Each item is a dictionary with:
- `nome` (string)
- `quantidade` (positive integer)
- `comprado` (boolean; starts as `False`)

Example:
```python
{"nome": "Rice", "quantidade": 2, "comprado": False}
```

## How to run

1. Open the notebook in Jupyter / Google Colab / VS Code Notebook.
2. Run the cells that define the functions.
3. Run `main()` to start the interactive menu.

## Suggested project structure

```
.
├── shopping_list.ipynb
└── README.md
```

## Optional extra challenges

- Allow editing the quantity of an item
- Show only items that are not purchased

## License

MIT License

Copyright (c) Rocketseat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
Made with 💜 by Rocketseat 👋
