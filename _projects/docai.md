---
layout: post
title: DocAI
description: System to varify and extract data from document during Registration
---

<!-- Details of the Project -->

- DocAI varifies and extracts document data used for app registration.
- It works for English and Bangla language and able to detect different types of varification documents.
- The core model is based on [Donut](https://huggingface.co/docs/transformers/model_doc/donut) model.
- It is further trained on synthetic data and available limited real data. The synthetic data was generated with [SynthDog](https://github.com/clovaai/donut/tree/master/synthdog) and [DocSim](https://github.com/AI4Bharat/DocSim).
- The system is served using Nvidia-Triton to maximise GPU utilization and ensure scalability which enables real-time usage.

<!-- 
DocAI is a real-time document verifying system that varifies and extractes document data for registration platform in both English and Bengali language. The core model is based on pre-trained Donut model. The model is further trained on real data and synthetic data for the specific document layout. The process has also been repeated for training the existing model on Bengali language. Finally, it had achieved 96% accuracy on test set. The synthetic data was produced using SynthDog and DocSim. Then the model is served with Nvidia-Triton that ensured 10 TPS service quality and maximum GPU utilization.  -->