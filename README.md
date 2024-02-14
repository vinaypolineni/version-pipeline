# version-pipeline
this code used to implement code using pipe line to s3 bucket and using static web hosting we can use it with help of code commit (git hub) and code pipeline 

### create a bucket with public access and enable website hosting

### create a pipeline by using below details

```
Step-1
 enter pipeline name as your mention
 select v2 version (recommended)
 role will be automatically created based on your pipeline details

step-2
 select your repository the code which your placed it may be git hub or code commit based on your requirements
 provide repo name & branch
 remaing default options

step-3
 you can skip this stage currently we are working only pipeline

step-4
 we have multiple options to deploy now we select amazon s3
 S3 object key enter sample.zip file

review all and create pipeline

after creating pipeline will be trigger automatically stop that tigger

edit pipeline and add stage select s3 bucket and and here select extract files options
```
 
