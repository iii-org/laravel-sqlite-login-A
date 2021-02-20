# php-laravel-app-example1

## k8s前置工作(將環境變數匯入)
kubectl create configmap laravel-env --from-env-file=./app/.env.example

## k8s部屬工作
kubectl apply -f ./k8s.yaml

## reference
[Laravel Login Registration Tutorial](https://www.soengsouy.com/2020/04/laravel-7-register-and-login-account.html?m=1)
