# ECE 535 Project - Federated Learning on Heterogeneous Sensor Data

Contributors: Huy Tran, Brian Tan, Jacob Glenn

## Motivation

The main motivation here is to understand and characterize data from hetergenous sensors and its impact on Federated learning. In addition, under these similar circumstances
test in conditions that aren't as ideal.

## Design Goals

Characterize the impact of heterogeneity sensoring data gathering on a federated learning model. Then perform the same task under
adversial conditions/environments.

## Deliverables

- Understand Federated Learning and heterogeneity. (paper provided) <br>
- Implement FL with different datasets and different levels of heterogeneity. <br>
- Now include some adversarial attacks and perform the same characterization. <br>
- What do you observe in adversarial vs non-adversarial settings? Why do you think the impact of heterogeneity is different in both settings? <br>

## System Blocks

Some potential system blocks, would be how to first characterize and quantify a diverse set of data from our sensors? What exactly should we be sensing and
how can this be fed into a federated learning model in both adversial and non-adversial conditions?

## Hardware / Software requirments

The hardware required is a laptop with CUDA-enabled GPU. The software is working in Python, where specifically Google Colab should be fine.

## Team member responsibilities

Huy Tran - Responsible for organizing, and sorting tasking as progress continues, such identifying roadblocks and addressing issues <br>

- More specifically, networking and algorithm design. <br>

Brian Tan - Coordinate between team members on technical aspects, and quantifying issues and how time should be allocated per problem. <br>

- More specifically, software. <br>

Jacob Glenn - Coordinate timeframes, making sure project timeline is going as planned and keeping team on track. <br>

- More specifically, setup and writing research.<br>

## Project Timeline

There isn't much of a project timeline currently until more information is revealed about the project itself. For now, the general time can proceed as follows: <br>

- Research and learn more exactly what federated learning is, and how it can be utilized in different ways (First week)
- Exactly understand what and how we can quantify hetergenous sensor data gathering (First week)
- Begin testing and experimenting with different kinds hetergeneous sensors, and develop a FL model. (Third week)

## References

The following references were used this [FedLab](https://github.com/SMILELab-FL/FedLab/tree/master/tutorials/Datasets-DataPartitioner-tutorials) github, which provided a tutorial
for data partioning. <br>
In addition, this [research paper](http://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf) provided a good description on what federated learning is and how it can be used
for deep networks.
