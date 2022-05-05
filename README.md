ros_ensemble (in initial stages of development)
------------



A Lightweight Ensembles-Based Component System Implementation for ROS based systems

Ensemble-based components systems are a paradigm for implementing distributed dynamic systems, with emergent collaborations. 

The 'ros_ensemble' encapsulates low-level details about communication between ROS nodes which are likely to be dependent of the version or the DDS provider, allowing the control of the cooperation be independent of the details associated with the communication.


Alternative Approaches
----------------------

ros_ensemble is inspired by DEEco but with a lightweight approach. The DEEco implementations (e.g., JDEEco) have redundant features when compared with ROS2. In ros_ensemble we use as much as possible the functionalities or ROS2, implementing just one node for negotiating the ensemble participation and exchange of knowledge. 

