# Example on AWS + DOCKER-COMPOSE with ansible 
 1.provision - this folder provides ec2 playbook which deployes centos7 in cloud
 2.deploy - this folder has docker-compose.yml which deployes complete stacks which covers mariadb,nginx,python-httpserver

 user requires to have AWS account to  run this code by setting up commandlie access.

# 1.provison/ec2.yml

 This will create ec2 instance in AWS CLOUD
 This will enable s3 bucket access to get DATABASE sql file by using IAM ROLE for EC2 -> S3 access


# 2.deploy/docker-compose.yml

 This will deploy complete stack which covers MARIADB + PYTHON_HTTPSERVER + NGINX
