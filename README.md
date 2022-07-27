### Deployed multiple Transformers models using Amazon SageMaker Multi-Model Endpoints 

With Amazon SageMaker multi-model endpoints, customers can create an endpoint that seamlessly hosts up to thousands of models. These endpoints are well suited to use cases where any one of many models, which can be served from a common inference container, needs to be callable on-demand and where it is acceptable for infrequently invoked models to incur some additional latency.

We covered the steps below in this project.
- Development Environment and Permissions
- Retrieve Model Artifacts
- Write the Inference Script
- Package Models
- Upload multiple Hugging Face models to S3
- Create Multi-Model Endpoint
- Get Predictions
- Dynamically deploying models and Updating a model to the endpoint
- Delete the Multi-Model Endpoint

Please refer to the [Medium article](hhttps://medium.com/@shwet.prakash97/deployed-multiple-transformers-models-using-amazon-sagemaker-multi-model-endpoints-e73d109dc7cf) for detailed information.
 
