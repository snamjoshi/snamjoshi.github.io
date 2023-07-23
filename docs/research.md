---
title: Research and Talks
---

## Talks
In Winter 2020 I gave two talks at the [Deep Learning Meetup](https://www.meetup.com/austin-deep-learning/) in Austin, TX on the history of AI. The aim of these talks was to weave together a unique historical perspective on AI that integrates developments in philosophy, mathematics, and neuroscience and the various paths toward AI as we think of it today. The recordings of these talks can be found below:

* The History of AI Part I: Before the AI Winter (1822-1980) [Link](https://www.youtube.com/watch?v=wgG5h6RTNmw)
* The History of AI Part II: Modern Developments in AI and Neuroscience (1980-Present) [Link](https://www.youtube.com/watch?v=kkh42Z9DTLo)

## Personal research

**Active inference textbook** (Summer 2019-present): My primary research focus is the development of a textbook and other educational resources around active inference. I have worked on this book outside of work but since January 2023 I have been on sabbatical to focus on it exclusively. More detailed information is given on the [textbook](faif.md) page

**Animal learning-based AI** (December 2021-present): In collaboration with [Roy Clymer](https://matheta.com/) we are writing a paper to showcase his work on an AI model inspired by animal learning. The model is based on synaptic connections but is entirely different in construction with feed-forward neural networks; superficially the model has some similarities with spiking neural networks. It includes an agent-environment loop and is capable of fairly complex behavioral chaining and learning in continuous time without any explicit calculations of gradients. More information and proof of concept results (using a Roomba) can be found on Roy's website linked above and in [this YouTube video](https://youtu.be/9IE-STHKxew).

**Asynchronous federated learning** (December 2022-present): In collaboration with my co-worker ZZ Si. As part of my work at KUNGFU.AI we had to utilize federated learning in order to prevent the mixture of private patient data stored in different AWS cloud accounts. Federated learning as implemented by tools such as [Flwr](https://flower.dev/) require synchronous learning where the slowest dataset to train becomes the bottleneck for the other datasets. ZZ developed the idea and original implementation of an asychronous federated learning architecture that we worked together into a Python package. With our asynchronous federated learning setup it is possible continue training asynchronously and eliminates the issues of bottlenecking datasets. 

## Industry research (highlights)

At KUNGFU.AI I have served as lead on a project to develop breast-cancer risk prediction software. The project involved developing a deep learning model using over 30 terrabytes of mammography data and temporal patient outcome data from hosptials around the world. The goal of the model was to provide calibrated risk scores with a 5-year predictive risk window that radiologists could use to provide more informed recommendations for their patients. This project involved a fairly complicated architecture that involved the application of federated learning to datasets stored on different cloud servers that could interact through VPC peering. 

At Hypergiant

KUNGFU AI
Hypergiant
Hookbang
Yonder/New Knowledge

## Postdoctoral research

Textbook
Flwr paper
Roy's paper - Roy's paper and work?

Include summary of different labs I worked in and link to their lab websites

Post-doc work.
Zhang Lab 
Kishida Lab

## Graduate research

Raab-Graham Lab
Stevens Lab

## Undergraduate research
Eberhart Lab

I was initially trained in molecular biology and moved into bioinformatics analysis of molecular neuroscience data. 