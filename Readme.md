#### STATIC WEBSITE HOSTED ON APACHE WEB SERVER ON AN AWS EC2 INSTANCE

1. This projects deploys a static website to an EC2 instance hosting an Apache web server

2. In this project, Amazon S3 bucket was used to store the source code

sudo apt install apache2

3. Copying the source code from the S3 BUCKET :  sudo aws s3 cp s3://dynamicwebapptolu --region us-east-2 /var/www/html/ --recursive

