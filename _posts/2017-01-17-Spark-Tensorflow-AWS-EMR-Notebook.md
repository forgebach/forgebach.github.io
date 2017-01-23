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

![software_config](/images/2017-01-17/software_config.png =100x20)

![](/images/2017-01-17/bootstrap_actions.png)


##### Reference:
- Run Jupyter Notebook and JupyterHub on Amazon EMR [link]
(https://aws.amazon.com/blogs/big-data/running-jupyter-notebook-and-jupyterhub-on-amazon-emr/)
