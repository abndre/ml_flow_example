# Example MLflow project

mlflow models serve -m runs:/502d35006a4e448786a3d739ff6a3288/model --no-conda --port 1234


7,0.27,0.36,20.7,0.045,45,170,1.001,3,0.45,8.8

curl -d '{"columns":["x"], "data":[[1], [-1]]}' -H 'Content-Type: application/json; format=pandas-split' -X POST localhost:5000/invocations


curl -d '{"data": [[8.8, 0.045, 0.36, 1.001, 7, 45, 3, 20.7, 0.45, 170, 0.27]]}' -H 'Content-Type: application/json; format=pandas-split' -X POST localhost:5000/invocations
