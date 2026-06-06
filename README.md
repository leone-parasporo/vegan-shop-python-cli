# Vegan Shop - Python CLI

The notebook implements a small command-line management tool for a vegan shop: it can add products, record sales, update inventory, and calculate revenue and profit.

## Contents

- `vegan_shop.ipynb`: main documented and reproducible notebook.
- `shop_storage.json`: initial inventory state.
- `shop_profits.txt`: initial revenue and profit values.
- `requirements.txt`: project dependencies.

## How to Run

1. Open `vegan_shop.ipynb` with Jupyter Notebook, JupyterLab, VS Code, or Google Colab.
2. Run the cells from top to bottom.
3. The demo and automated checks do not modify the data files.
4. To use the shop manager in interactive mode, uncomment `run_cli()` in the last notebook cell.

## Available Commands

- `add`: adds a new product or increases existing stock.
- `list`: shows the available products.
- `sell`: records a sale.
- `profits`: shows gross revenue and net profit.
- `help`: shows the available commands.
- `exit`: saves the data and closes the program.

## Technical Notes

The project uses only the Python standard library. Business logic is separated from interactive input, cells are reproducible, inputs are validated, data loading is robust, and final automated checks are included.
