# A sample stateful MySQL application

## Deploy sample MySQL application

The MySQL application can be deployed using the following command to the K8s cluster:

```markdown
$ kubectl apply -k base
namespace/mysql created
secret/mysql-pass-m62cbhd9kf created
service/mysql created
persistentvolumeclaim/mysql-pvc created
deployment.apps/mysql created
```

## Test MySQL database

Under the folder *test*, there are a list of scripts to populate sample employees data records to the deployed MySQL database. There are also other scripts to test the populated data. Those scripts are grabbed from the GitHub repo *'test_db'* at https://github.com/datacharmer/test_db.git. 

Refer to this GitHub repo for the full scripts.

