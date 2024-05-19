

cd C:\Data\github\kubernetes-examples\hello

kubectl apply -f .\hello



kubectl apply -f hello-job.yaml

kubectl apply -f hello-cronjob.yaml



//kubectl describe jobs/<job-name>
kubectl describe jobs/hello-world


kubectl logs jobs/hello-world


kubectl delete jobs/hello-world

or,

kubectl delete -f hello-job.yaml

kubectl delete -f hello-cronjob.yaml

