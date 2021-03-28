
1. Please install the following plugin before running the code:
https://github.com/UnitedIncome/serverless-python-requirements

```
npm install --save serverless-python-requirements
```
2. Run npm install to get all the library dependencies

PROJECT OUTLINE:

--> Created a service using lambda which generates image thumbnails when an image is uploaded to S3.
     Whenever an image is uploaded to S3, it gets resized based on the provided resolution.

--> All the configuration related to the function, IAM role specification, S3 bucket creation are specified in serverless.yml

--> Technologies & services: Python, S3 and AWS lambda.