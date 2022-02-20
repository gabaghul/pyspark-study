# pyspark-study
Just a personal repo to play with pyspark for the first time.

![pyspark-logo](https://www.nobleprog.com.br/sites/hitrahr/files/category_images/height100_scale/pyspark_training.png?t=59415bb3) <img src="https://upload.wikimedia.org/wikipedia/pt/f/f9/Bundesliga_logo_%282017%29.png" alt="bundesliga" width="20%">

## Study case
Following the pyspark tutorial which link you find below, I'm analyzing matches from bundesliga (German soccer league) using pyspark to answer some questions suggested by the article.

All data used in this project is contained in `.csv` files under `data` directory.

The questions suggested in the article was:

1) Who are the winners of the D1 division in the Germany Football Association (Bundesliga) in the last decade?
2) Which teams have been relegated in the past 10 years?
3) Does Oktoberfest affect the performance of Bundesliga?
4) Which season of Bundesliga was the most competitive in the last decade?
5) What's the best month to watch Bundesliga?

## Requirements
In this project, I'm using a virtual environment and dependencies manager called [Poetry](https://python-poetry.org/docs/).

`Poetry` reads all dependencies into `pyproject.toml` and `poetry.lock` to install dependencies and dev dependencies. You need to install Poetry in your environment and do the following:

1) Run poetry install, and it will install all necessary dependencies, and create your virtual env as well.
   ```
    poetry install
   ```
   **Optional**: you can run one of the commands below to check if your venv is ok.
   ```
   poetry env list
   ```
   Or
   ```
   poetry env info
   ```

2) Run poetry shell to use your new virtual environment.
   ```
   poetry shell
   ```
3) Run `jupyter` from `poetry` using the command below:
   ```
   poetry run jupyter notebook
   ```
4) You can use one of the listed paths described into jupyter log to use the `.ipynb` notebook file, or use another environment of your preference (i for instance use vscode with jupyter plugin).

## References

Below are the links I read for guidance or to enlighten some problem I encountered

### **Pyspark** - distributed processing system used for big data manipulation
- **What is spark?**

  - https://chartio.com/learn/data-analytics/what-is-spark/

  - https://medium.com/data-hackers/entendo-funcionamento-do-pyspark-2b5ab4321ab9

- **Tutorial:**
  - https://towardsdatascience.com/a-project-driven-approach-to-learning-pyspark-4533c85f52b3
- **Spark windows feature**
  - https://sparkbyexamples.com/pyspark/pyspark-window-functions/
- **Repository from the reference project:**
  - https://github.com/henokyemam/Wrangling_PySpark

### **Poetry** - virtual env and dependencies manager
- **Official documentation:**
  - https://python-poetry.org/docs/

- **Some cheatsheet I read too (not really, but I used it as such):**
  - https://realpython.com/dependency-management-python-poetry/