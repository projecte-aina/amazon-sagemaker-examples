![SageMaker](https://github.com/aws/amazon-sagemaker-examples/raw/main/_static/sagemaker-banner.png)

# Amazon SageMaker Examples

Example Jupyter notebooks that demonstrate how to build, train, and deploy machine learning models using Amazon SageMaker.

## :books: Background

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service for data science and machine learning (ML) workflows.
You can use Amazon SageMaker to simplify the process of building, training, and deploying ML models.

The [SageMaker example notebooks](https://sagemaker-examples.readthedocs.io/en/latest/) are Jupyter notebooks that demonstrate the usage of Amazon SageMaker.

The [Sagemaker Example Community repository](https://github.com/aws/amazon-sagemaker-examples-community) are additional notebooks, beyond those critical for showcasing key SageMaker functionality, can be shared and explored by the commmunity.

## :hammer_and_wrench: Setup

The quickest setup to run example notebooks includes:
- An [AWS account](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-account.html)
- Proper [IAM User and Role](http://docs.aws.amazon.com/sagemaker/latest/dg/authentication-and-access-control.html) setup
- An [Amazon SageMaker Notebook Instance](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html)
- An [S3 bucket](http://docs.aws.amazon.com/sagemaker/latest/dg/gs-config-permissions.html)


They can be accessed by cloning this repo inside Jupyter or just uploading/copying the example.

Although most examples utilize key Amazon SageMaker functionality like distributed, managed training or real-time hosted endpoints, these notebooks can be run outside of Amazon SageMaker Notebook Instances with minimal modification (updating IAM role definition and installing the necessary libraries).

## :notebook: Examples

### Inference
- [Aguila 7b Hugging Face Large Model Inference - TGI](inference/huggingface-tgi/aguila-7b/sagemaker-huggingface-tgi-aguila7b-example.ipynb) shows how to deploy common large language models such as projecte-aina/aguila-7b, using Hugging Face Text Generation Inference (TGI) Deep Learning Container on Amazon SageMaker
- [Aguila 7b fine-tunning with instruction dataset] (https://github.com/projecte-aina/amazon-sagemaker-examples/tree/main/finetunning/aguila-7b/instrucat) shows how to fine-tune a the falcon 7B aguila model projecte-aina/aguila-7b, using a instructional dataset (in this case an example from the InstructCat collection) with a g5 instance from Amazon Sagemaker.

