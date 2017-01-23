---
layout: post
title: Build a EMR spark cluster with deep learning packages
categories: 
- Notes
tags:
- Deep Learning
- Spark
---

The need of spark tensorflow/theano integrations has been satisfied in many ways. With AWS EMR boostrap commands, we can simply spin up our own spark cluster with EMR.

## prerequisites
- AWS account
- EMR security group with inbound settings for jupyter notebook

### Step 1 : setup software configurations with EMR including spark, hadoop etc. 

<img src="/images/2017-01-17/software_config.png" width="680px" />

### Step 2 : Bootstrap actions:
- add bootstrap action from s3://aws-bigdata-blog/artifacts/aws-blog-emr-jupyter/install-jupyter-emr5.sh
- put args for keras, tensorflow installations
- then spin up the cluster as usual

<img src="/images/2017-01-17/bootstrap_actions.png" width="680px" />

## Run with Pyspark:
<img src="/images/2017-01-17/example_1.png" width="680px" />

* An example of pyspark application with Gradient Boosting Trees Classifier 

<img src="/images/2017-01-17/example_4.png" width="680px" />
<img src="/images/2017-01-17/example_2.png" width="680px" />
<img src="/images/2017-01-17/example_3.png" width="680px" />

* The full notebook can be found [here](https://github.com/forgebach/tensorflow-pyspark/blob/master/notebook/pyspark_example.ipynb)

## Run with tensorflow on MNIST




#### Reference:
- Run Jupyter Notebook and JupyterHub on Amazon EMR [link](https://aws.amazon.com/blogs/big-data/running-jupyter-notebook-and-jupyterhub-on-amazon-emr/)
