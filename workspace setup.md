# Workspace Setup 📡

Below are suggested workflows on how to complete the courses and tips on how to set up your environment. Please bear in mind that you will use the command line to spin up resources on these different platforms fairly often. There is no particular resource for learning the command line but more you do it you will get used to it and if you need something you can just Google it. 



## Google Cloud Platform (GCP)

Google has an equally great cloud offering that can be used for a wide variety use cases. 

However, Google offers [Colabortory](https://colab.research.google.com/) . Which is an online Juypter notebook that is powered by a Tesla K80 GPU. You can install all your favourite libraries such as TensorFlow, Keras etc. 

[Google Colab Free GPU Tutorial](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d) 

For a more traditional Approach you could used GCP's [Compute Engine](https://cloud.google.com/compute/pricing#gpus), choose an instance type and attach a GPU to your instance. This is a bit more administrative and I would not recommend it if you are just starting out. 

[TPU](https://cloud.google.com/tpu/)
Google has built Tensor Processing Units designed for computational demanding workloads. When getting started this sort of setup is not necessary. However, it is great to know about because somewhere down the line you need an environment like this. 

[Get Started!](https://cloud.google.com/tpu/docs/quickstart)

[ML Engine](https://cloud.google.com/ml-engine/docs/tensorflow/getting-started-training-prediction)

ML engine allows teams to train and deploy their models via the service. It also deploys your model with serverless hosting and can scale with TBs of data. You can also import models that have been trained on another service.

[Get Started!](https://cloud.google.com/ml-engine/docs/tensorflow/getting-started-training-prediction)

[Cloud Deep Learning VM Image (Beta)](https://cloud.google.com/deep-learning-vm-image/)

A deep learning virtual machine is preconfigured with all the necessary ML frameworks. You can also add Cloud TPU nad GPU support! 

[Documentation](https://cloud.google.com/deep-learning-vm/docs/)

[Cloud Lab](https://cloud.google.com/datalab/)

This is Google's Jupyter Notebook as a service. It allows you use all the Jupyter features and lets you intergrate with all og GCPs different services like BigQuery etc. 

## Azure

[Data Science Virtual Machines](https://azure.microsoft.com/en-us/services/virtual-machines/data-science-virtual-machines/)

Azure's pre-configured VMs are perfect for data sciensits! They come packed with all the tools you need like Anaconda, deep learning tools like TensorFlow, it has data platform and visualization tools like Spark, SQL Server, PowerBI and many more! You can choose between a Windows or Linux machine. Obvisouly if you're just doing basic ML experiments or Deep Learning projects you need configure the machine according to your needs. 

[Azure Notebooks](https://notebooks.azure.com/)

This is Microsoft's host Jupyter Notebook as a service. It is perfect if you want to host everything in the cloud and as usual it comes with all the necessary goodies needed to create Data Science experiments. You're able to share them too. You can also create and Deploy a cloud service too.

[Machine Learning Studio](https://azure.microsoft.com/en-us/services/machine-learning-studio/)

This is a really powerfull tool that allows you drag and drop different processes that envolve creating a ML model. There are different modules that take care of Data Cleaning for you and you can select from a wide range of ML models. You can then easily deploy your model as an HTTP endpoint! What is also great is that you explore other users solutions and customize them according to your own needs. 

## AWS

[AWS Deep Learning AMIs](https://aws.amazon.com/machine-learning/amis/?nc2=h_m1)

This is a P3 EC2 instance especially made for Deep Learning. You can either setup a CONDA or BASE AMI. A CONDA AMI is preconfigured with pip deep learning frameworks and is avaiable in Ubuntu, Amazon Linux or Windows 2016. The BASE AMI is a clean instance that is available in Ubuntu or Amazon Linux. 



[SageMaker](https://aws.amazon.com/sagemaker/?nc2=h_m1)

SageMaker is a platform that allows you to build, train and deploy ML models at scale. It also includes a hosted Jupyter Notebook service to see your training data in S3. It also has popular frameworks like TensorFlow etc for you. It also has many common ML models for you to use or you can use your own. This is only scratching the surface of what SageMaker can offer!

## Kaggle

## FloydHub

