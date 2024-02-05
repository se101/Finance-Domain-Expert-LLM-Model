# Finance-Domain-Expert-LLM-Model
Proof of concept (POC) for a domain expert model: 

This model will be trained on a dataset of domain-specific knowledge in finance.

## Training and Fine-Tuning a Large Language Model: 

    Meta Llama 2 7B foundation model Ver 1.0.0

    Chat Optimized, Text Generation, LLAMA 2

  Llama 2 is an auto-regressive language model that uses an optimized transformer architecture. 
  
  ![image](https://github.com/se101/Finance-Domain-Expert-LLM-Model/assets/73610600/ed71bcb7-adc8-4708-9416-b11a291a316c)

  JumpStartModel 
  
    (model_id, model_version,) = ("meta-textgeneration-llama-2-7b","2.*",)

  JumpStartEstimator 
    
    (model_id=model_id,  environment={"accept_eula": "true"},instance_type = "ml.g5.2xlarge")

  Instance type for training job usage (EC2 instance with GPU for fine-tuning from AWS Service Quotas)
  
    ml.g5.2xlarge 

  AWS SageMaker IAM Role for ComputeFullAccess

  AWS SageMaker Notebook
  
    instance(ml.t3.medium)
    
    platform(Amazon Linux 2, Jupyter Lab 3)
    
    kernel(Python 3.10 Pytorch or Tensorflow)

## Using the AWS platform and tools like, 

    AWS SageMaker (Python SDK and boto3, JumpStartModel, JumpStartEstimator)
    
    AWS Rekognition
    
    AWS S3 (s3://genaiwithawsproject2024/training-datasets/finance)
    
    Amazon Bedrock
    
    AWS PartyRock
    
    AWS CodeWhisperer
    
    AWS Cloud9
    
    AWS Service Quotas


