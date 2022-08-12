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
* wpp: [url](https://pdf.sciencedirectassets.com/271602/1-s2.0-S0166218X00X01667/1-s2.0-0166218X84900891/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAIaCXVzLWVhc3QtMSJGMEQCIH7CDqHaBbQDNwN4xqq1jJyWKJ3o%2BhYLyhi5Q8im%2FCBOAiBt54XdlFFukQ7r%2BUMQ8%2F6daQnQWpNrCsc%2F%2FPN%2FYPL5DirSBAhrEAUaDDA1OTAwMzU0Njg2NSIM55VA8jbjndDxNMooKq8E%2F4aqFqT6OX6qDlcnl5lKx0mTHUsAwq3R%2B%2BRQB6uPVVfSgpZtP4kl6Oosrwl2MoJJW6k2uhTnILoOmmqszDqgISSeKUizZhglAyM%2BetcAXkHDVVLIgaDGOXFlkgurIH8m71wJrKGrONGL%2FCkJQQSS1K1%2BEGA6LvYYf2jLYKHBgCidPW0MSaiheipHsY37z5bkwRp2JyLDPeP9yPkjrMrTKoEEz1vsZFo1xu4MWSviYIpi4TD%2BzK%2FEB8xYDh88k2AH8juxMiMBh1QQtvBD16oZszlbLHbOp9ovEP0qXg1WqBpS0mFTiO%2FuzUPqhGXSABbrjo2R%2Fik8BoT4PpgKIZ1oXyVXWuCPIXR3ztAGNzsr7wl94s%2Fac9Pqk%2BOXvzqv31fEpCiraV0v9x9phuCyMjIMosDLCV4JG4NATKfjf44CwGYnJ063H%2Bx%2Be6P5v1uGQFaa032vCG0K5eAAFPkvaBIoRFXbzeUudFuXYp5AVasktxo25qKNd33kmzxfFrVaBLcLJv91Sl4%2FxsnIk1zrpdn50k88QcH07nrK3BfH5DUpBgvTIIMsgY%2BWLVhLYgLe%2BvCkCt10VaTxzyMZ7IEi1NnIjMjrTMTIy9G427cDMQrWFcCoDKCpixf64fusMMB0M5KqdBt%2FmauxQIfWbBgrmXmtP4CBuzVC6tuz2pv6lso8Q91pKJMGMtlcQ%2BMQ3v%2BWTy1zxVyQEwfPhWDsmxiCo6jGSAgnFEThcHuVAyJCHIsnmDC139aXBjqqATRgYBfCO%2FhuPcn5rAzfOpDuAGKvKcavfO2wJ8GfEuq0szmC0aHGpHG9X5PAPoWE1iAmF1srYWp0VAEnY1k976oMCjVBLwPBEPICgLhBMGygYkTTE%2BquX9A8pQk7CT69yG%2BQxrwcz4J76gMJuCkKGD6FOyvb0uo9DWYHa9%2FbNe%2FOsGBREYC%2BqyB9HvlW9gwDaC%2Bz1gqO%2B4VQYgLRaD4FlFX3eHsGtBlIZ4Do&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20220812T022447Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY4XJVTTNL%2F20220812%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=0130c5e4bee1e28e77aee3520f337ec71a42476281d076d9d984d08f0f66e050&hash=e8c14c3395ac7e1d7e91c0f17468168fe40cd7fcc94496bc1b3da51df13a7747&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=0166218X84900891&tid=spdf-31004fc1-58ad-4c9b-91c4-566297429921&sid=4428e571231e414f042a726-3e3ba690e7e8gxrqa&type=client&ua=4d565f52065e060e530203&rr=7395c1ba0daa78ed)
* postman_problems: [https://github.com/brooksandrew/postman_problems](https://github.com/brooksandrew/postman_problems)
* acadia map: [https://www.nps.gov/acad/planyourvisit/maps.htm](https://www.nps.gov/acad/planyourvisit/maps.htm)
* acadia carriage map: [https://www.nps.gov/acad/planyourvisit/images/ACAD_Carriage-Road-Map_revised-Apr-2019_Page_2_2.jpg](https://www.nps.gov/acad/planyourvisit/images/ACAD_Carriage-Road-Map_revised-Apr-2019_Page_2_2.jpg)
* caltopo: [https://caltopo.com/m/G353F](https://caltopo.com/m/G353F)