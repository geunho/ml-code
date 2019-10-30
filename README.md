## ml-code

[100-Days-Of-ML-Code](https://github.com/Avik-Jain/100-Days-Of-ML-Code) 따라잡기

Predefined environment in Docker image
https://cloud.docker.com/u/geunho/repository/docker/geunho/ml-py

```sh
# python 3.5
# installed packages: numpy, pandas, scikit-learn(dependent on scipy, joblib)
docker run -it --rm --name py -v REPO_PATH:/data geunho/ml-py:3.5 python3
```
