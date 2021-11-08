# Hans Dhondea's portfolio

## Research projects
- **DFTS2: Deep Feature Transmission Simulator version 2** and **CALTeC: Content-Adaptive Linear Tensor Completion for collaborative intelligence**

. - Collaborative Intelligence is a hybrid AI deployment strategy: it involves splitting a deep neural network model into two sub-models. The first sub-model runs on a device with limited computational power such as a mobile phone. The second sub-model runs on a remote cloud service, with comparatively large computing power. By leveraging both types of compute resources, collaborative intelligence leads to reduced latency and increased energy savings as compared to single-resource deployment strategies. A deep feature tensor is transmitted over an imperfect communication channel from the device to the cloud. Due to the lossy nature of the communication channel, there may be lost or corrupted packets in the tensor received at the cloud. Potential applications of CI include Internet of Things services, autonomous naviagation and point of care services. These applications may involve a lossy communication channel. To understand the impact of lossy channels in collaborative intelligence applications, a simulator named DFTS was developed. DFTS stands for Deep Feature TRansmission S. I modified DFTS to become compatible with TensorFlow version 2. Furthermore, this updated DFTS has sophisticated features:

.. - additional communication channel models and simulation modes.
.. - tensor packet recovery methods from the recent literature.

. - DFTS2 can be cloned from this [repo](https://github.com/AshivDhondea/DFTS2). I also provide packet traces, experiment files, example yml scripts to replicate experiments published in my ICIP 2021 and VCIP 2021 papers.

. - I also provide a work-in-progress [user documentation manual](https://github.com/AshivDhondea/dfts2_user_doc)

- **SORADSIM: Space Object RADar SIMulator**

. -[Repo](https://github.com/AshivDhondea/SORADSIM)

. -[Repo for TiKZ figures](https://github.com/AshivDhondea/TikZ_Bistatic_Radar_Astrodynamics)

. -[repo for RadarConf paper](https://github.com/AshivDhondea/ashiv_2019_radar_conf)

. -[repo for satellite orbit plotting in Python](https://github.com/AshivDhondea/Satellite_Ground_Track_Plotting_Python)

. -[Initial work done in MATLAB](https://github.com/AshivDhondea/TrackingSpaceDebris)

## Academic projects

. - **Performance analysis of YouTube streaming over WiFi** 

.. - Term project for the course ENSC 894 - Communication Networks in Spring 2020 at Simon Fraser University.

.. - Project done in collaboration with Amandeep Kaur and Haotian Ye.

.. - [Project website](http://www.sfu.ca/~hdhondea/ENSC894Group2.html)

.. - [report](https://github.com/AshivDhondea/ENSC894_project_report)

. - **Classifying car images in the TCC dataset**

.. - [repo](https://github.com/AshivDhondea/ENSC813_Project)

## Self-study projects

. - **Python implementation of MATLAB simulations for radar systems design**

.. - I studied extensively from the book "MATLAB simulations for radar systems design" over the years. I do not have access to MATLAB anymore, so I thought that I could implement the same methods in Python to assist those who, like me, do not have access to a MATLAB license.

.. -[Repo](https://github.com/AshivDhondea/simulations_radar_systems_design)

. - **Python Target Tracking Toolbox**
.. -I developed a Python toolbox for target tracking experiments. The intention behind it is to be a learning tool, not a library that can be used in production code. So the coding approach is very simplistic and aims to demonstrate the inner mechanics of target tracking algorithms.
.. - [Repo](https://github.com/AshivDhondea/PyTrackingToolbox)

. - **Reentry vehicle tracking**
.. - I studied reentry vehicle tracking using Simmo Saerkkae's book.
.. - [repo](https://github.com/AshivDhondea/Reentry_Vehicle_Tracking)

. - **Simulating stochastic differential equations in Python**
.. - I self-studied stochastic differential equations some time back. I wrote some code to show how numerical methods for SDEs work.
.. -[repo](https://github.com/AshivDhondea/Simulating_Stochastic_DEs)
