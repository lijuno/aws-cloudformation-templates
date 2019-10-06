# AWS Data Pipeline Templates


## Description

While the [Data Pipeline tutorials](https://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/welcome.html) were informative about several important use cases, its CloudFormation reference was quite vague. Below are working templates I found useful:

- "dynamodb-export-on-demand.template.yml": Based on the "Export DynamoDB table to S3" JSON template from [here](https://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/dp-importexport-ddb-console-start2.html). It will export a DynamoDB table to a specific S3 bucket on-demand. You will need to change a few fields according to your needs as explained in the template.


## Reference

- [AWS Data Pipeline resource reference](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-datapipeline-pipeline.html)

- [AWS Data Pipeline developer guide](https://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/what-is-datapipeline.html)

