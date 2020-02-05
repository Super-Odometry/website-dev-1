---
layout: post
title:  "Real-time Fault Detection for Autonomous Aerial Vehicles"
date:   2019-08-01 10:50:07
categories: research
description: "Real-time Fault Detection for Autonomous Aerial Vehicles"
author: "Azarakhsh  Keipour"
published: true
sidebar:  false
permalink: /fault-detection/
---

<div>
The recent increase in the use of aerial vehicles raises concerns about the safety and reliability of autonomous operations. There is a growing need for methods to monitor the status of these aircraft and report any faults and anomalies to the safety pilot or to the autopilot to deal with the emergency situation. In this project, we developed a real-time approach to detecting anomalies in the behavior of an aircraft. Additionally, we created and published a dataset of the 47 flight sequences where the anomalies happen. Our anomaly detection method is based on the Recursive Least Squares. The approach models the relationship between correlated input-output pairs online and uses the model to detect the anomalies. The result is an easy-to-deploy anomaly detection method that does not assume a specific aircraft model and can detect many types of faults and anomalies in a wide range of autonomous aircraft. The experiments on this method show a precision of 88.23%, recall of 88.23% and 86.36% accuracy for over 22 flight tests. For more details about the work, please refer to the publications below. More information about the dataset is available <a href="http://theairlab.org/alfa-dataset/" target="_blank" rel="noopener"><span style="color: blue;">here</span></a>. [embed]https://youtu.be/HCtGbnqjKj8[/embed] <h3>Publications</h3> The real-time anomaly detection method for the autonomous aerial vehicles is described in the following publication (<a href="https://arxiv.org/abs/1907.00511" target="_blank" rel="noopener"><span style="color: #3366ff;">PDF available on arXiv</span></a>): <em>BibTeX:</em> @inproceedings{keipour:detection:2019, author={Azarakhsh Keipour and Mohammadreza Mousaei and Sebastian Scherer}, booktitle={2019 IEEE International Conference on Robotics and Automation (ICRA)}, title={Automatic Real-time Anomaly Detection for Autonomous Aerial Vehicles}, year={2019}, month={May}, pages={forthcoming} } <em>IEEE Style:</em> A. Keipour, M. Mousaei, and S. Scherer, “Automatic Real-time Anomaly Detection for Autonomous Aerial Vehicles,” in 2019 IEEE International Conference on Robotics and Automation (ICRA), May 2019, forthcoming. The dataset is described <a href="http://theairlab.org/alfa-dataset/" target="_blank" rel="noopener"><span style="color: blue;">here</span></a> and in the following publication (<a href="https://arxiv.org/abs/1907.06268" target="_blank" rel="noopener"><span style="color: #3366ff;">PDF available on arXiv</span></a>): <em>BibTeX:</em> @article{keipour:dataset:2019, author={Azarakhsh Keipour and Mohammadreza Mousaei and Sebastian Scherer}, title={ALFA: A Dataset for UAV Fault and Anomaly Detection}, journal = {The International Journal of Robotics Research}, volume = {}, number = {}, pages = {}, year = {In press}, } <em>IEEE Style:</em> A. Keipour, M. Mousaei, and S. Scherer, “ALFA: A dataset for UAV fault and anomaly detection,” The International Journal of Robotics Research, In press. <h3>Contact</h3> Azarakhsh Keipour - (keipour [at] cmu [dot] edu) Mohammadreza Mousaei - (mmousaei [at] cmu [dot] edu) Sebastian Scherer - (basti [at] cmu [dot] edu) <h3>Acknowledgments</h3> This work was supported through NASA Grant Number NNX17CL06C.
</div>