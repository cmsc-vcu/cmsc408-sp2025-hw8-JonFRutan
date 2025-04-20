# Homework #8 - SQL Funhouse  
"Funhouse" may be a bit of misnomer. "Slaughterhouse" is more my feeling towards this assignment when recalling those final few tasks.  

## Assignment Goal  
This assignment was designed to really test our SQL mettle. It starts off relatively easy but slowly amps up the pressure until we reach the gruesomely difficult end-tasks.  
In particular tasks 18-20, which require a good understanding of nested subqueries, grouping, aggregation, and several other vital SQL functionalities  prove to be difficult and puzzling.  

## Relevant files/directories
- `reports` - Contains the QMD and rendered HTML of our document  
- `.env.sample` - Populate this file with your SQL connection data.  
- `poetry.lock/pyproject.toml` - These files are used for the setup process.  
- `reports/Makefile` - A makefile meant to streamline the Quarto rendering process.  

## Tools needed  
1. [Quarto](https://quarto.org/) - Used for rendering the QMD documents.  
2. [Poetry](https://python-poetry.org/) - Used for managing Python dependencies.  

## Running / Setup  
1. Clone the repo.  
2. Create and populate your own `.env` file in the project root following the provided sample `.env.sample`.  
2. From project root, run `poetry install`. This will install all necessary dependencies.  
3. In `reports`, to render the QMD run `poetry run quarto render report.qmd` ALTERNATIVELY you may simply run `make` using the provided Makefile.  
4. Open `report.html` to view the rendered report.  


