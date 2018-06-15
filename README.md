# resizer
A modern in memory promise based NodeJS Lambda Image resizer.

## Install
```
$ npm install

$ node index.js

```

## AWS CLI

### AWS Configure access
```
$ aws configure

AWS Access Key ID [****************T77Q]:
AWS Secret Access Key [****************HnJu]:
Default region name [ap-southeast-1]:
Default output format [None]:

```

### AWS S3 check bucket
```
$ aws s3 ls <s3-bucket-name>
```

## Deploy to AWS Lambda
```
$ grunt deploy

$ grunt invoke
```


