dynamodb_local_ubuntu_dockerfile
================================

DynamoDB Local Client in an Ubuntu Container

This Image lets you use the AWS DynamoDB Local stuff.
Run this image with
```
docker run -d --name dynamodb kasitmp/dynamodb-local-ubuntu
```
If you publish the port 8000 with
```
docker run -d --name dynamodb --publish 8000:8000 kasitmp/dynamodb-local-ubuntu
```
you can access the DynamoDB Shell feature in your browser under http://<ip>:8000/shell

You find further information about [AWS DynamoDB Local](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Tools.DynamoDBLocal.html) and the [javascript shell](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Tools.DynamoDBLocal.Shell.html)
