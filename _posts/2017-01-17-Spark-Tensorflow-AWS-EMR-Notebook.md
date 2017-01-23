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

#### prerequisites
- AWS account
- EMR security group with inbound settings for jupyter notebook

<img src="/images/2017-01-17/software_config.png" width="680px" />

Bootstrap actions:

<img src="/images/2017-01-17/bootstrap_actions.png" width="800px" />

##### Reference:
- Run Jupyter Notebook and JupyterHub on Amazon EMR [link](https://aws.amazon.com/blogs/big-data/running-jupyter-notebook-and-jupyterhub-on-amazon-emr/)
