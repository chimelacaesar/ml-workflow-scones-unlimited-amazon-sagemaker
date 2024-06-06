# ml-workflow-scones-unlimited-amazon-sagemaker
## Build an ML Workflow for Scones Unlimited on Amazon SageMaker
Image Classifiers are used in the field of computer vision to identify the content of an image and it is used across a broad variety of industries, from advanced technologies like autonomous vehicles and augmented reality, to eCommerce platforms, and even in diagnostic medicine.

Imagine that you are hired as a Machine Learning Engineer for a scone-delivery-focused logistics company, Scones Unlimited, and you’re working to ship an Image Classification model. The image classification model can help the team in a variety of ways in their operating environment: detecting people and vehicles in video feeds from roadways, better support routing for their engagement on social media, detecting defects in their scones, and many more.
## Description ##
In this project, we'll be building an image classification model that can automatically detect which kind of vehicle delivery drivers have, in order to route them to the correct loading bay and orders. Assigning delivery professionals who have a bicycle to nearby orders and giving motorcyclists orders that are farther can help Scones Unlimited optimize their operations.

As an MLE, your goal is to ship a __scalable and safe__ model. Once your model becomes available to other teams on-demand, it’s important that your model __can scale to meet demand,__ and that __safeguards are in place to monitor and control__ for drift or degraded performance.

In this project, we’ll use AWS Sagemaker to build an __image classification model__ that can _tell bicycles apart from motorcycles._ We'll deploy our model, use AWS Lambda functions to build supporting services, and AWS Step Functions to compose our model and services into an event-driven application. At the end of this project, we will have created a portfolio-ready demo that showcases our ability to build and compose scalable, ML-enabled, AWS applications.
## Project Steps Overview ##
* Step 1: Data staging
* Step 2: Model training and deployment
* Step 3: Lambdas and step function workflow
* Step 4: Testing and evaluation

These steps can be found in the Jupyter notebook file`starter.ipynb`

