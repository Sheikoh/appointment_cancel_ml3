```
docker build . -t mlflow3-sheikoh
docker tag mlflow3-sheikoh sheikoh/mlflow3-sheikoh
docker push sheikoh/mlflow3-sheikoh
docker run sheikoh/mlflow3-sheikoh
```
