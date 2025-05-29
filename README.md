## End to End MAchine Learning Project
# MLOPS_Students_Score_Regression_Azure_deployment


## Run from terminal:

docker build -t testdockerkrish.azurecr.io/mltest:latest .

docker login testdockerkrish.azurecr.io

docker push testdockerkrish.azurecr.io/mltest:latest
