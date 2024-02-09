**AWS Cloud QUest: Machine Learnin Island**
**Amazon SageMaker**

- cloud quest- build own learning path with specific things- networking, machine learning, s3 etc
- aws escape room
- **Sagemaker**- machine learning process for AWS, giving resources to train models, fine-tune, dploy and maintaint
- **Sagemaker studip**- interface with access to all the ML models in AWS Sagemaker
- **Inference endpoint**- endpoint where the model gets trained to, so where it will be accessed for services to access the model with the pipeline
- **Temperature parameter**- higher usually means sort of creativity so the response wont be as specific, IMPORTANT for technical question/responses
- Maybe have lambda functions for the execution of the ML  model execution
- **Cloudfront**- CDN resource to host static websites
- **API Gateway**- creating API for backend services, any web service endpoints (lambda, ec2, cloud etc), good way o handle multiple requests and use of multiple resources


# Fine-Tuning LLM On AWS
- Training on custom dataset to deploy on model
- **Domain adapatation**- adatping a model to the scpecific areas like healthcare, finance, real estate etc
- **Hosting static websites**- Cloudfront, S3, Amazon API Gateway
- Store in S3 because easy to download files and easier
- Fine tuning also known as transfer learning
- can fine tune with a question and response type
- **Transformers Hugging Face API**- Using the LLM API to save resources rather than doing yourself
- Sagemaker takes the data stored from S3 to train on
- **HyperParameter**- set in the model to control the learning process
	- **Epoch**- the training process cycle the data set through the training algorithm, can basically say how many times you want it to go through
	- **Learning rate**- the rate at which the model is trying to learn the process
- **Environment variable**- good to have to store private data from the public
- Using lambda functions to be able to access the fine tuned model with the API gateway to the client
