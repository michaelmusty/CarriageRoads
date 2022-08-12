# CarriageRoads

## setup

```
git clone git@github.com:michaelmusty/CarriageRoads.git
cd CarriageRoads/
python -m venv env
vim .gitignore  # ignore env directory
source env/bin/activate
pip install isort loguru black mypy numpy pandas networkx matplotlib

isort --skip-gitignore . && black . && mypy tsp && mypy cpp
```

## tsp

## cpp

## references
* cpp: [http://brooksandrew.github.io/simpleblog/articles/intro-to-graph-optimization-solving-cpp/](http://brooksandrew.github.io/simpleblog/articles/intro-to-graph-optimization-solving-cpp/)
* rpp: [http://brooksandrew.github.io/simpleblog/articles/sleeping-giant-rural-postman-problem/](http://brooksandrew.github.io/simpleblog/articles/sleeping-giant-rural-postman-problem/)
* postman_problems: [https://github.com/brooksandrew/postman_problems](https://github.com/brooksandrew/postman_problems)