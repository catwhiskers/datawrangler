# datawrangler

Reference to: https://aws.amazon.com/blogs/aws/introducing-amazon-sagemaker-data-wrangler-a-visual-interface-to-prepare-data-for-machine-learning/ 

## Prepare Data 
1. Use titanic data on [kaggle](https://www.kaggle.com/c/titanic/data) 
1. Create S3 bucket - dw-titanic-\<id\>
1. Upload our titanic data   
  
## Import Data 
1. Go to SageMaker Studio 
1. Create a new flow - File --> New --> Flow 
1. In Import tab, select Amazon S3 and import the titanic files we just uploaded 

## Try Analysis Function 
1. Histograms of age distribution 


## Transform 
1. Ordinal encoding for pclass 
1. One-hot encoding for embarked 
1. Drop columns - Name, Ticket by custom transform 

## Try Analysis Again 
1. Use Quick Model how we are doing 

## Transform again 
1. One-hot encoding for Sex 

## Try Analysis Again 
1. Use Quick Model how we are doing again 

## Export 
1. To data wrangler flow 
1. To pyspark code
1. To pipeline 
1. To feature store 






  

