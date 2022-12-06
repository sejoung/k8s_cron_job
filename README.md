# k8s_cron_job

로컬에서 k8s 실행

```shell

brew install minikube

minikube start

```


```shell

kubectl create -f ./yaml/job.yaml

kubectl create -f ./yaml/spring_batch_error_job.yaml

kubectl create -f ./yaml/cronjob.yaml

kubectl create -f ./yaml/cronjob_concurrenct_policy.yaml


```
