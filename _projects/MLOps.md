---
layout: post
title: MLOps
description: ML system serve, deploy and monitor
---

- Intigrated MLFlow into existing systems that serve prediction periodically.
- The goal was to be able to detect any change in model accuracy, training data.
- Integrate developed systems into Airflow Scheduler to ensure timely prediction service.
- Migrate single machine Airflow service to multi-machine Airflow cluster that serve all the ML systems across machines with message passing system [RabbitMQ](https://www.rabbitmq.com/).
- Develop ML serving system using [Nvidia-Triton](https://developer.nvidia.com/triton-inference-server) to serve real-time ML inference and ensure scalability.