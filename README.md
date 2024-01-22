# A sample stateful MySQL application

## Deploy sample MySQL application

The MySQL application can be deployed using the following command to the K8s cluster:

```markdown
$ k apply -k base
namespace/mysql created
secret/mysql-pass-m62cbhd9kf created
service/mysql created
persistentvolumeclaim/mysql-pvc created
deployment.apps/mysql created
```

## Test MySQL database

Under the folder *test*, there are a liss of scripts to populate some sample employees data records to the deployed MySQL database. There are other scripts to test the populated data. 

Refer to the GitHub repo at https://github.com/datacharmer/test_db.git for the full scripts.

