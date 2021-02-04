# End-to-End-Machine-Learning-CI-CD-Pipeline-on-AWS

## Continuous Integration and Continous Depoloyment

<img align="left" src="imgs/ezgif-1-e3d1c499b26c.gif">
</br></br></br></br></br></br></br></br></br></br></br></br></br></br>


**MLOps or Machine Learning Operations** is a concept that can help you:implement CI/CD applied to machine learning and create an automated infrastructure to support your AI processes.


**With this solution template you can:**
</br></br>
1. Create/operate an automated ML pipeline using a a CI/CD tool CodePipeline, to orchestrate the ML workflow.
</br></br>
2. Create a Docker container from scratch with your own algorithm.
</br></br>
3. Automatically start a training/deployment job by uploading data to S3.
</br></br>
4. Run A/B tests and more. 
</br></br>

**This also can be implemented a reference architecture that can be used as an inspiration to create your own solution!**

All required components of the pipeline including Lambda functions to automatically run our code are including in the CloudFormation template below.
The template creates the following services and infrastructure:
* Jupyter Notebook
* AWS CodePipeline
* AWS CodeCommit
* AWS CodeBuild
* Amazon ECR
* Amazon SageMaker
* AWS CloudFormation

Just click the launch stack and complete AWS steps to automatically build your infrastructure as code ML Ops pipeline!

Region| Launch
------|-----
US East 1 | [![Launch MLOps solution in us-east-1](imgs/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=CICDstack&templateURL=https://demoai-solutions-pipeline.s3.us-east-2.amazonaws.com/CICDTemplate.template)
