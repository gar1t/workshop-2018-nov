# TensorFlow/Guild AI Workshop, Nov 2018 - Chicago

This is the GitHub repository for the TensorFlow and Guild AI workshop
on Nov 30, 2018.

All workshop participants are required to [read and agree to our code
of conduct](CONDUCT.md).

Workshop organizers:

- Garrett Smith <br> g_at_rre.tt <br> 312_231_3900

Getting help:

- [Slack
  workspace](https://join.slack.com/t/guildai/shared_invite/enQtNDgxNDg5ODk2MjI2LWQ5ODI3ZGE2YzljYWViNTA0NjFmNDg4NTI3ZjY2Mjk2YTkzZjAxZWM3M2EyNTcyZWU0YzgzM2IwMTI0ZjFhNTU)
  (use `#workshop` channel to post questions)
- [Workshop issues on GitHub](https://github.com/gar1t/workshop-2018-nov/issues)

## Overview

### Goals

- Introduce AI application development in TensorFlow and Guild AI
- Apply one or more seminal papers to an application workflow
- Contribute back to community projects

### Approach

In this workshop we split into teams of 4-6 people. Each team selects
one paper from a predefined list to work with. Each paper has a
working implementation in TensorFlow.

Each team works collaboratively on these goals:

- Understand the gist of the paper and how it advances
  state-of-the-art
- Install and use the paper implementation to reproduce results
- Use Guild AI to automate model operations and document functionality
- Consider ways of applying project in an application
- Time permitting, consider improvements to the implementation project

Team members may continue to work with the project after the workshop,
either for application development or to contribute improvements to
the project.

We use this repository to manage source code and coordinate work
activities.

### Preparation

The workshop itself is limited to four hours so we spend time in
preparation to maximize our face-to-face time:

- Identify candidate papers and implementation projects
- Divide into teams
- Assign one paper per team
- Install Guild AI and complete the introduction guide
- Execute project code to become familiar with its features
- Fork implementation projects as needed to make improvements

Teams should try to make as much progress prior to the workshop as
possible.

### Laptop environment setup

All workshop participants should bring a configured laptop that is
suitable for their project work. The specific configuration depends on
their project and their team role.

In general, these guidelines apply to all paricipants:

- Be capable of SSHing into a remote server using public/private key
  authentication. We will use servers running in EC2 during the
  workshop.

- Complete the example steps in [Guild AI
  introduction](https://guild.ai/docs/intro/). This guide ensures that
  you are able to train a simple TensorFlow model and have Guild AI
  installed correctly.

- Once you have selected a project to work on, spend time reproducing
  the results documented in the project README.

If you face any issues, please use the [Slack
workspace](https://join.slack.com/t/guildai/shared_invite/enQtNDgxNDg5ODk2MjI2LWQ5ODI3ZGE2YzljYWViNTA0NjFmNDg4NTI3ZjY2Mjk2YTkzZjAxZWM3M2EyNTcyZWU0YzgzM2IwMTI0ZjFhNTU)
and post a question to the `#workshop` channel.

### Workshop time

We spend the four hour workshop moving each team forward. We use the
face-to-face time as an opportunity for in-depth collaboration.

Because of the wide scope of effort, we don't set hard goals for the
face-to-face workshop time. Work may continue after Nov 30.

### Post workshop

After the workshop, teams are free to continue work on their
projects. This may include:

- Finishing work started during the workshop
- Adding features or improvements
- Building an application
- Preparing pull requests for upstream projects

## Candidate papers

### Matrix Capsules with EM Routine

Paper: https://openreview.net/pdf?id=HJWLfGWRb

Implementation: https://github.com/www0wwwjs1/Matrix-Capsules-EM-Tensorflow

Application: Image classification

### Mask-RCNN

Paper: https://arxiv.org/abs/1703.06870

Implementation (Keras): https://github.com/matterport/Mask_RCNN

Application: Object detection and segmentation

### Real Time Trigger Word Detection with Keras

Blog post: https://www.dlology.com/blog/how-to-do-real-time-trigger-word-detection-with-keras/

Application: Speech recognition

### PointCNN: Convolution On X-Transformed Points

Paper: https://arxiv.org/abs/1801.07791

Project: https://github.com/yangyanli/PointCNN

Application: Point clouds

### Realistic Evaluation of Deep Semi-Supervised Learning Algorithms

Paper: https://arxiv.org/abs/1804.09170

Project: https://github.com/brain-research/realistic-ssl-evaluation

Application: Semi-supervised learning research

### Deep Reinforcement Learning in a Handful of Trials using Probabilistic Dynamics Models

Paper: https://arxiv.org/abs/1805.12114v1

Project: https://github.com/kchua/handful-of-trials

Application:

### LF-Net: Learning Local Features from Images

Paper: https://arxiv.org/abs/1805.09662

Project: https://github.com/vcg-uvic/lf-net-release

Application: Feature mapping

### Neural Architecture Optimization

Paper: https://arxiv.org/abs/1808.07233

Project: https://github.com/renqianluo/NAO

Application: Multiple

### Multi-View Silhouette and Depth Decomposition for High Resolution 3D Object Representation

Paper: https://arxiv.org/abs/1802.09987

Project: https://github.com/EdwardSmith1884/Multi-View-Silhouette-and-Depth-Decomposition-for-High-Resolution-3D-Object-Representation

Application: 3D object upsampling

### Neural Architecture Search with Bayesian Optimisation and Optimal Transport

Paper: https://arxiv.org/abs/1802.07191

Project: https://github.com/kirthevasank/nasbot

Application:

### SimplE Embedding for Link Prediction in Knowledge Graphs

Paper: https://arxiv.org/abs/1802.04868

Project: https://github.com/Mehran-k/SimplE

Application: Tensor factorization

### Attention in Convolutional LSTM for Gesture Recognition

Paper:

Project: https://github.com/GuangmingZhu/AttentionConvLSTM

Application:

### Neural Code Comprehension: A Learnable Representation of Code Semantics

Paper: https://arxiv.org/abs/1806.07336

Project: https://github.com/spcl/ncc

### Adapted Deep Embeddings: A Synthesis of Methods for k-Shot Inductive Transfer Learning

Paper: https://arxiv.org/abs/1805.08402

Project: https://github.com/tylersco/adapted_deep_embeddings

### Playing hard exploration games by watching YouTube videos

Paper: https://arxiv.org/abs/1805.11592

Project: https://github.com/MaxSobolMark/HardRLWithYoutube

### Robustness of Conditional GANs to Noisy Labels

Paper: https://arxiv.org/abs/1811.03205

Project: https://github.com/POLane16/Robust-Conditional-GAN

### Deep Dynamical Modeling and Control of Unsteady Fluid Flows

Paper: https://arxiv.org/abs/1805.07472

Project: https://github.com/sisl/deep_flow_control

### Semi-supervised Deep Kernel Learning: Regression with Unlabeled Data by Minimizing Predictive Variance

Paper: https://arxiv.org/abs/1805.10407

Project: https://github.com/ermongroup/ssdkl

### Mapping Images to Scene Graphs with Permutation-Invariant Structured Prediction

Paper: https://arxiv.org/abs/1802.05451

Project: https://github.com/nips2018axiomatic/Mapping-Images-to-Scene-Graphs-master

Notes:

- https://github.com/nips2018axiomatic/Mapping-Images-to-Scene-Graphs-master/issues/1
