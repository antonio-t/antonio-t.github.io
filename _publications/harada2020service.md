---
title: "Service robots: A unified framework for detecting, opening and navigating through doors"
collection: publications
permalink: /publication/harada2020service
date: 2020-01-01
venue: 'Springer Communications in Computer and Information Science'
citation: 'Harada, T., Tejero-de-Pablos, A., Quer, S., & Savarese, F. (2020). Service robots: A unified framework for detecting, opening and navigating through doors. In Springer Communications in Computer and Information Science, vol. 1250, issue 1, pp. 179-204. (2020).'
excerpt: ''
---
For an autonomous robotic system, detecting, opening, and navigating through doors remains a very challenging problem. It involves several hard-to-solve sub-tasks such as recognizing the door frame and the handle, discriminating between different type of doors and their status, and opening and moving through the doorway. Previous works often tackle single individual sub-problems, assuming that the robot is moving in a well-known static environments or it is already facing the door handle. However, ignoring navigation issues, using specialized robots, or restricting the analysis to specific types of doors or handles, reduce the applicability of the proposed approach. In this paper, we present a unified framework for the door opening problem, by taking a navigation scenario as a reference. We implement specific algorithms to solve each sub-task and we describe the hierarchical automata which integrates the control of the robot during the entire process. We build a publicly available data-set which consists in 780 images of doors and handles crawled from Google Images. Using this data-set, we train a deep learning neural network, exploiting the Single Shot MultiBox Detector, to recognize doors and handles. We implement error recovery mechanisms to add robustness and reliability to our robot, and to guarantee a high success rate in every task. We carry-out experiments on a realistic scenario, the “Help Me Carry” task of the RoboCup 2018, using a standard service robot, the Toyota Human Support Robot. Our experiments demonstrate that our framework can successfully detect, open, and navigate through doors in a reliable way, with low error rates, and without adapting the environment to the robot.

[Download here](https://www.springerprofessional.de/en/service-robots-a-unified-framework-for-detecting-opening-and-nav/18203150)

Bibtex:
```
@article{harada2020service,
  title={Service robots: A unified framework for detecting, opening and navigating through doors},
  author={Harada, Tatsuya and Tejero-de-Pablos, Antonio and Quer, Stefano and Savarese, Francesco},
  journal={Springer Communications in Computer and Information Science},
  volume={1250}
  number={1}
  pages={179--204},
  year={2020},
  organization={Springer}
}
```
