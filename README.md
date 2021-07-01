*[Last updated: July 2021]*

![](tensorflow_developer_badge.png) [my TensorFlow Developer Certificate](https://www.credential.net/00b8f611-b2e9-4d65-9151-a5fd39d332ae)

I have recently started working on personal projects in machine / deep learning. This is an overview of the (currently very short list of) projects that I have done so far.

To finally act upon my interest in machine learning, I am currently trying to gain and keep up an overall understanding of the fast advancing field, as well as become a competent practitioner and (hopefully soon) an active contributor in some specific areas.

Here are the links to my repos:

- [Time Series Anomaly Detection via Prediction and Reconstruction](https://github.com/pokman/time_series_anomaly_detection)
- [Feature Visualization: Mini Lucid TF2](https://github.com/pokman/mini_lucid_tf2)



## Time Series Anomaly Detection via Prediction and Reconstruction

This project is to implement examples of two approaches to time series anomaly detection, one using *prediction* methods and one using *reconstruction* methods.

For each approach, we have selected a particular deep learning model -- [DeepAR](https://arxiv.org/abs/1704.04110) for prediction, [TadGAN](https://arxiv.org/abs/2009.07769v3) for reconstruction -- and demonstrated the end-to-end process with a dataset from the [Numenta Anomaly Benchmark repository](https://github.com/numenta/NAB). The demonstrations entail, respectively, the use of SageMaker SDK for DeepAR training and inference, and a re-implementation of TadGAN in TensorFlow 2.



## Feature Visualization: Mini Lucid TF2

This project is to re-implement part of [Lucid](https://github.com/tensorflow/lucid) in TensorFlow 2. Lucid is a package for research in neural network interpretability, and is built on TensorFlow 1.

Specifically, we have so far covered roughly the part for [feature visualization](https://distill.pub/2017/feature-visualization/). The key idea is to visualize features learned in a convolutional neural network by maximizing the activations of its different components from an image.

