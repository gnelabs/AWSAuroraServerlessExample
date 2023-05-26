# AWSAuroraServerlessExample
Example cloudformation template for AWS Aurora Serverless V2 I/O optimized database.

## Notes
The resources in this cloudformation template give you a basic Aurora Serverless V2 cluster with a single database instance in a single AZ. The configuration is not particularly secure or redundant, but gives you a basic foundation to work off of. You can deploy this template as-is using SAM, and should have a endpoint you can log into. 

I made this for another project where I was experimenting with the performance of the new I/O optimized storage tier. I couldn't find any existing templates using this tier, so I made one. I ended up not using this configuration, however I am sharing it in case the next person wants to know how to create this resource using cloudformation.
