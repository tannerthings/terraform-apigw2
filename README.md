# terraform-apigw2
AWS HTTP to easily expose a Lambda function

## Deploy

* ```terraform init```
* ```terraform apply```
* Go to the output URL

## Usage

* ```<cloudfront url>/``` goes to the API mapped to the default cache behavior
* ```<cloudfront url>/test/``` goes to the API with a path pattern and a route_key mapped to the ```/test/``` path

## Cleanup

* ```terraform destroy```
