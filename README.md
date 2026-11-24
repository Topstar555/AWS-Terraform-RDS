# AWS-Terraform-RDS

# AWS-RDS-Terraform
AWS RDS Instance with read-replica using Terraform

### Architecture:

<img width="1464" height="1234" alt="image" src="https://github.com/user-attachments/assets/85c1cc6d-1812-4fa4-8e56-30fb5dcc98f2" />


## Install postgresql and Connect from EC2

```bash
sudo apt-get install -y postgresql
```

```bash
psql --host=mypostgresql.c6c8mwvfdgv0.us-west-2.rds.amazonaws.com --port=5432 --username=awsuser --password --dbname=mypgdb
```

Reference Doc: https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToPostgreSQLInstance.html



