* Set default namespace for comands:

   ```kubectl config set-context --current --namespace=dev-usa-gcp-rep```

* Port forward (change `redis-master-765d459796-258hz` to the name of the Pod):

   ```kubectl port-forward redis-master-765d459796-258hz 7000:6379```
