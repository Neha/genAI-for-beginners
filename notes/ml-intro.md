## What is AI?

1. AI (Artifical Intelligence):
Allows computer to mimic human's intelligence using logic. 

2. ML (Machine Learning):
ML collects the past (historical) data, train this day to identify the patterns and output a inference. eg: collect the past bank data and try to find the transaation is a fraud or not.  

## Machine Learning Model:

Model contains rules (algoithims) that can identify and show relationships between input datasets and targeted output values. These models make predictions. 

We get the dataset (labeled), try to recognize the pattern and make prediction. Eg: we can feed images of cats, train of identify if the image is cat or not and then make a predition on new image to tell - cat or not 

## Key concepts of ML modeling

Before we provide the data to models we need to do data exploration, cleaning, and prepration. Once we have a clean data then we need to look into:

1. Features: 

helps in determining accurate output. Identify the patterns

2. Weights:

how important this feature is . How it is going to effect the accuracy of outcome.
also knowns as parameters

3. Labels: 

outcome of past customers; trying to predict outcome. Eg: cat or not

## Types of Data

1. labeled data: has annotations. Eg: Spam or not

2. unlabeled data: Lack annotations

3. structure data : that is organized eg: DB, excel sheets,  (tabular data, time series data)

4. Unstructured data: that lacks a predefined structure or format. Image data, text data, videos


## ML - when to use and not to use

### Usecases:

Personlaized recommendation, future recommendations, prediction, translation, sentiment analysis, image, and video recognition


### When not to use

Evolving and rapid change enviornemnt, safety critical applications, requires 100% accuracy, regulatory and legal constraints, highly sensitive or ethical decisions, small datasets


## ML types

1 . Supervised: data is labeleb input and output

a. classification: spam or not

b. regression: predicate a continues numerical o/p more than just a yes or no. It is range eg: stock, housing price.

2 . unsupervised: Data is not labeled 

a. Clustring: given data, create patterns (cluster) 

b. Anomly detection: finding something unusual...not able to find pattern. rare items, events or observations. Finding uncommon things. Use: server traffic, heartbeat (normal vs abnirmal)  

3 . Reinforcement learning: learn from enviornment. 



## ML development Lifecycle
 
PS: We keep dataset 80% for training and 20% for validation  (evalution)

1. Data exploration 

a. data collection and integration

b. data processing and visulaization

2. Model training 

a. Model training

b. Model evalution

3. Model tunning

4. Model deployment

5. Model monitoring 

## AWS sagemaker

End to End AI tool

Train, Build, and Deloy ML models

Services:

1. SageMaker Studio: an integrated IDE that provides unified web-based interface for all ML development steps, including data preparation, model building, training, deployment, and management

1. data Wrangler: 

Data wrangler clean and analyze the model data

data preparation by providing a visual interface to aggregate, transform, and prepare data for ML.

2. Ground Truth : To label and review the data (here we can also involve Human too to label data)

3. Feature Store:  centralized repository to store, share, and manage ML features, ensuring consistency and reusability across models.

4. SageMaker Canvas: A low-code/no-code platform for business analysts and citizen data scientists to build and deploy ML models without extensive coding knowledge.

5. SageMaker JumpStart: Provides a collection of pre-trained models and solutions for common use cases, enabling rapid deployment with minimal effort.

## Model Deployment and Inference:

The job of ML models needs to deploy. AWS sagemaker provides endpoint to make inference (outcome)

1. Real time Endpoints
use for live predictions/traffic;
sustained traffic 
low latency; 
consitent perf; eg: fraud detection

2. Batch Transform
large datasets; eg: take thousands of data (images)
process offline (24hr to days)
use it when workload is not time sensitive; 
cost opitmized
eg: A retailer predicts product demand across stores for the next week.

3. Async
near real time
logng processing times (1hr) ; 
1GB ; large payloads; almost real time 
eg: use case - credit risk prediction 

3. Serverless  
deployed methods w/o managing any underlaying infra/endpoints
can tolrate cold start
interemittent traffic is okay or periods of no traffic
eg: credit risk application
