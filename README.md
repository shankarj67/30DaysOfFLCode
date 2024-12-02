# Awesome #30DaysOfFLCode [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A community curated and contributed list of helpful resources and materials about _Federated Learning_ and PETs as part of the [`#30DaysOfFLCode`](https://info.openmined.org/30daysofflcode) Challenge by [OpenMined](https://openmined.org).

## `#30DaysOfFLCode` Challenge

**Two main rules**:

1. Study Federated Learning (and/or any other PETs) for _at least_ 1 hour/day for 30 days
2. Share Your Progress Daily by posting on social media using `#30DaysOfFLCode` and engage with other participants.

**Publicly commit to the challenge**: Hold yourself accountable by making a public statement saying you intend to participate in the program

Discover more on [www.30DaysOfFLCode.com](https://www.30DaysOfFLCode.com).

## Contributing
We welcome contributions! Please follow these steps to contribute:

1. Fork this repository
2. Add your resource(s)
3. Submit a pull request

Find all the information and instructions on how to contribute in [CONTRIBUTING.md](./CONTRIBUING.md).

---

## Awesome Resources

Please find below all the contributed resources, organised by category



### Tutorials

* [SyftBox | #30DaysOfFLCode](https://syftbox-documentation.openmined.org/) - The new project by [OpenMined](https://openmined.org) that aims to make privacy-enhancing technologies more accessible and user-friendly for developers.

    * [SyftBox Computational Model](https://syftbox-documentation.openmined.org/computation-model) - How computation works on SyftBox, in a nutshell
    * [Federated CPU Tracker Member (part1)](https://syftbox-documentation.openmined.org/cpu-tracker-1) - An example of SyftBox API that monitors local CPU usage and shares a private/sanitized version of the data within the SyftBox federated network.
    * [Federated CPU Tracker Leader (part 2)](https://syftbox-documentation.openmined.org/cpu-tracker-2) - A SyftBox API that aggregates CPU data from all members contributing to the computation, and creates a live visualization dashboard.

* [From Centralised to Decentralised Training: An Intro to Federated Learning](https://github.com/deep-learning-indaba/indaba-pracs-2024/tree/main/practicals/Federated_Learning) - A Jupyter Notebook tutorial aimed to provide a practical overview with code examples to all the the foundational concepts tackled in federated learning. This tutorial was written by Andrej Jovanović, Sree Harsha Nelaturu and Luca Powell and presented at the 2024 iteration of the Deep Learning Indaba.
  
* [Collection of Tutorials in Federate Learning from Tensor Flow](https://www.tensorflow.org/federated/tutorials/tutorials_overview) - A TensorFlow Colab Notebook collection of Federated Learning tutorials designed to provide practical examples of Federated Learning, covering concepts from basic to advanced levels.

* [Federated Learning for Credit Scoring](https://blog.openmined.org/federated-credit-scoring/) - A detailed blog post exploring the application of federated learning to credit scoring. It discusses key concepts such as silo vs. device architectures, horizontal vs. vertical federated learning, and non-IID data challenges, and includes source code examples.

### Articles

* [Beyond Privacy Trade-offs with Structured Transparency](https://arxiv.org/abs/2012.08347) - Structured Transparency: a five-part framework to combine multiple PETs, such as secure computation and federated learning, to maximise their value, and to reduce lingering use-misuse trade-offs in multiple domains.

* [Private AI Series](https://blog.openmined.org/tag/private-ai-series/) - This blog series is a compendious alternative to get introduced with topics like information flow, structured transparency and more.

* [Federated Learning: Challenges, Methods, and Future Directions](https://arxiv.org/abs/1908.07873) - 
Federated learning involves training statistical models over remote devices or siloed data centers, such as mobile phones or hospitals, while keeping data localized. In this article, we discuss the unique characteristics and challenges of federated learning, provide a broad overview of current approaches, and outline several directions of future work that are relevant to a wide range of research communities.

* [Advances and Open Problems in Federated Learning](https://arxiv.org/abs/1912.04977) - Federated learning (FL) is a machine learning setting where many clients collaboratively train a model under the orchestration of a central server, while keeping the training data decentralized. Motivated by the explosive growth in FL research, this paper discusses recent advances and presents an extensive collection of open problems and challenges.

* [User-Empowered Federated Learning in the Automotive Domain](https://ieeexplore.ieee.org/abstract/document/10664305) - This paper proposes a User-Empowered FL approach, built upon the Flower Framework, implemented in an Android Automotive app. Source code is available [here](https://github.com/marcellomaugeri/User-Empowered-Federated-Learning-in-Automotive). Please note that the paper is not open access and requires an IEEE subscription or institutional login.

* [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf) - First paper on Federated Learning by McMahan et. al. Google Inc. This paper introduces the term Federated Learning, runs experiments on MNIST and CIFAR Datasets, and also introduces the famous aggregation algorithm FedAverage. Check out the blog based on the paper here: [Federated Learning: Collaborative Machine Learning without Centralized Training Data](https://research.google/blog/federated-learning-collaborative-machine-learning-without-centralized-training-data/)

* [An online comic on Federated Learning, by Google AI](https://federated.withgoogle.com/) - Google AI came up with this fun online comic on Federated Learning which is a great resource for beginners starting their journey in the field of Federated Learning. Great for building up the motivation to learn FL.

* [Federated Learning and Privacy](https://dl.acm.org/doi/pdf/10.1145/3500240) - This article provides a brief introduction to key concepts in federated learning and analytics with an emphasis on how privacy technologies may be combined in real-world systems and how their use charts a path toward societal benefit from aggregate statistics in new domains and with minimized risk to individuals and to the organizations who are custodians of the data.

### Courses

* [The Private AI Series](https://courses.openmined.org/) - Learn how privacy technology is changing our world and how you can lead the charge.

* [Federated Learning @ DeepLearning.AI](https://www.deeplearning.ai/short-courses/intro-to-federated-learning/) - An introductory course on federated learning delivered by DeepLearning.AI in collaboration with Flower.

* [Federated Fine-tuning of LLMs with Private Data @ DeepLearning.AI x Flower Labs](https://learn.deeplearning.ai/courses/intro-to-federated-learning-c2)- Part 2 of the Intro to Federated Learning course delivered by DeepLearning.AI and Flower Labs.

* [Federated Learning Tutorial @ NeurIPS 2020](https://drive.google.com/file/d/1QGY2Zytp9XRSu95fX2lCld8DwfEdcHCG/view) - Federated Learning Tutorial @ NeurIPS 2020

* [Secure and Private AI](https://www.udacity.com/course/secure-and-private-ai--ud185) - Learn skills to build AI systems that prioritize security and privacy using cutting-edge techniques. The course introduces tools and methods for securely handling sensitive data in AI applications, including Federated Learning, Differential Privacy, and Encrypted Computation.

* [Federated learning course at Aalto university](https://www.youtube.com/watch?v=54caAfGwM88&list=PLrbn2dGrLJK9TwK1TILxluPApQCLq1Tf5) - A master level Federated Learning course from Aalto university.

* [Foundations of Private Computation](https://courses.openmined.org/courses/foundations-of-private-computation) - A comprehensive training program offered by OpenMined on the Foundations of Private Computation. The course covers topics such as Federated Learning, Split Learning, Cryptography (including introductory concepts, underlying mathematical foundations, and practical applications), Homomorphic Encryption, Secure Multi-Party Computation, Public Key Infrastructure (PKI), and Private Set Intersection.

* [A Course In Differential Privacy](https://youtube.com/playlist?list=PLmd_zeMNzSvRRNpoEWkVo6QY_6rR3SHjp&si=_4r3HM1bTNSW9gwr) - An in-depth course by Dr Gautam Kamath exploring Differential Privacy and aligned concepts theoretically and mathematically. (CS-860: Algorithms for Private Data Analysis @ University of Waterloo)


### Videos

* [Tutorial on Differential Privacy](https://youtu.be/ekIL65D0R3o?feature=shared) - Katrina Ligett, California Institute of Technology - Big Data and Differential Privacy

* [Privacy Preserving AI (Andrew Trask) | MIT Deep Learning Series](https://youtu.be/4zrU54VIK6k?feature=shared) - Lecture by Andrew Trask in January 2020, part of the MIT Deep Learning Lecture Series.

* [Tutorial: Differential Privacy and Learning: The Tools, The Results, and The Frontier](https://youtu.be/hoEyvHCRRc8?feature=shared) - Katrina Ligett, California Institute of Technology - NeurIPS tutorial 2014

### Tools 

* [SyftBox](https://github.com/OpenMined/syft) - Discover SyftBox, an exciting new project by OpenMined that puts Privacy-Enhancing Technologies at its core.

* [Flower](https://github.com/adap/flower) - An ML framework agnostic friendly Federated AI network developed by Flower Labs.

### Books


* [Optimization Algorithms for Distributed Machine Learning](https://link.springer.com/book/10.1007/978-3-031-19067-4) - Textbook discussing SoTA optimization algorithms for distributed/federated machine learning. Access to materials requires subscription.

* [Programming Differential Privacy](https://programming-dp.com/) - An open source book about differential privacy, for programmers.

### Games & Simulations

* [DP Vision](https://www.oblivious.com/games/dp-vision) - Test your image recognition skills with differentially private images! Players manage a privacy budget to reveal image details, aiming to identify the correct image within 5 guesses while minimizing privacy loss.

* [Guess Who (DP Edition)](https://www.oblivious.com/games/guess-who) - A privacy-preserving twist on the classic game where players ask yes/no questions with adjustable accuracy levels. Lower epsilon means less reliable but more private answers, teaching the privacy-utility tradeoff.

* [WORDPL](https://www.oblivious.com/games/wordpl) - A Wordle-style game with differential privacy mechanics. Players guess 5-letter words while managing privacy budgets that affect the accuracy of feedback, demonstrating how DP noise impacts information gathering.

* [Federated Learning Hyperparam Tuning Game](https://amanpriyanshu.github.io/FL-Interactive-Game/) - Understand and play with federated learning hyperparams! In-browser tensorflow-js simulation of FedAvg to understand and gain intuition about IID and Non-IID Federated Learning settings.

* [Differentially Private Tetris](https://amanpriyanshu.github.io/Differentially-Private-Tetris/) - A unique twist on classic Tetris where players manage a privacy budget to reveal blocks, demonstrating differential privacy concepts through gameplay. Experience privacy-utility tradeoffs in an engaging way.

* [The Unlearning Protocol](https://amanpriyanshu.github.io/The-Unlearning-Protocol/) - An interactive game exploring machine learning unlearning and fairness concepts. Players select data points that least impact the dataset, providing hands-on experience with data removal and model fairness considerations.
