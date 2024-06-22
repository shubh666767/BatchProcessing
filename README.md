# BatchProcessing
This is a repository for batch processing

I am creating a batch processing project. It will have 2 microservices running on aws eks the first microservice will be using spring batch and MySQL. The second microservice will be using mongo db , spring and angular in front end. When I hit the first microservice api it will process data from file and store it in MySQL db and after the completion will publish an event on the Kafka topic. The second api will call the first api and fetch data store in mongo db and show on the angular front end.

Technologies used-
1. spring boot
2. spring batch
3. aws
4. kafka
5. angular
6. docker and kubernetes

DB used -
mysql and mongo db
