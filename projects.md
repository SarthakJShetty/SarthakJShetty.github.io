---
layout: page
title: Projects
permalink: /projects/
---

For a full list of my projects, see my [GitHub](https://github.com/SarthakJShetty).

- <strong><i><a title='ToolFlowNet' target = "_blank" class="links" href='https://sites.google.com/view/point-cloud-policy/home'>ToolFlowNet</a></i>: Robotic Manipulation with Tools via Predicting Tool Flow from Point Clouds</strong><a class="links" title="ToolFlowNet" href="https://github.com/DanielTakeshi/softagent_tfn" target="_blank"> [Code] </a> <a class="links" title="ToolFlowNet" href="https://arxiv.org/abs/2211.09006" target="_blank"> [Paper, CoRL '22] </a>  
    - Imitation learning from point clouds, for robot manipulation of deformable objects. PointNet++ Segmentation backbone imitates ~100 human demonstrations of the task.
    - Developed the entire physical experiments for this work, including setting up <a title="Rethink Sawyer" class="links" href="https://www.rethinkrobotics.com/sawyer">Rethink Sawyer</a> robot, extrinsic calibration of <a title="Azure Kinect" class="links" href="https://learn.microsoft.com/en-us/azure/kinect-dk/sensor-sdk-download">Azure Kinect</a> depth sensor, writing human data collection system, collecting multiple sessions worth of human demonstrations, deploying trained network on Rethink Sawyer, and adapting training code to work with real data.
    - Tech stack included PyTorch, Azure Kinect SDK, MoveIt, <a title="ZeroMQ" href="https://zeromq.org/" class="links">ZeroMQ</a> and <a title="Rethink Intera" class="links" href="https://sdk.rethinkrobotics.com/intera/Main_Page">Intera API</a>.


- <strong><a title='pyResearchInsights' target = "_blank" class="links" href='https://pypi.org/project/pyResearchInsights'>`pyResearchInsights`</a>: An open-source tool for scientific text analysis</strong><a class="links" title="Bias" href="https://github.com/SarthakJShetty/pyResearchInsights" target="_blank"> [Code] </a> <a class="links" title="Paper" href="https://onlinelibrary.wiley.com/doi/full/10.1002/ece3.8098" target="_blank"> [Paper, Ecology & Evolution 2021] </a>
    - We developed <i><a title='pyResearchInsights' target = "_blank" class="links" href='https://pypi.org/project/pyResearchInsights'>pyResearchInsights</a></i> an end-to-end, open-source, automated content analysis tool that <b>Scrapes</b> abstracts, <b>Cleans</b> them up, <b>Analyses</b> temporal frequency of keywords and <b>Visualizes</b> themes of discussions using natural language processing.
    - Collaboration with <a class="links" title="Vijay" href="https://evolecol.weebly.com/" target="_blank">Vijay Ramesh</a> from the <a class="links" title="E3B" href="http://e3b.columbia.edu/" target="_blank">Department of Ecology, Evolution and Environmental Biology</a>, <a class="links" title="Columbia University" href="columbia.edu">Columbia University</a>, and <a title="Anand" href="https://www.ncf-india.org/author/646617/anand-m-osuri" class="links" target="_blank">Anand MO</a> from the <a title="NCF India" href="https://ncf-india.org" class="links" target="_blank">Nature Conservation Foundation</a>.
    - Package built using <a title="Pandas" class="links" href="https://pandas.pydata.org/" target="_blank">Pandas</a>, <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/' class="links" title="BeautifulSoup" target="_blank">BeautifulSoup</a>, <a href='https://radimrehurek.com/gensim/' class="links" title="gensim" target="_blank">gensim</a> and <a href='https://spacy.io' class="links" title="spaCy" target="_blank">spacy</a>.

- <strong>Probabilistic Exploration for Unmanned Aerial Teams</strong><a class="links" title="Weight" href="https://github.com/SarthakJShetty/Weight" target="_blank"> [Code]</a> <a title="Weight 2021 Paper" class="links" href="https://arxiv.org/abs/2012.11131" target="_blank">[Paper, IEEE CONNECT 2021]</a>
    - Developed exploration strategies for multi-UAV swarm to conduct reconnaissance of survivors in flooded areas. Advised by [Professor Debasish Ghose](http://aero.iisc.ac.in/people/debasish-ghose/){:target="_blank"} at the Mobile Robotics Laboratory, [Department of Aerospace Engineering](http://aero.iisc.ac.in/){:target="_blank"}, [Indian Institute of Science](https://iisc.ac.in){:target="_blank"}.
    - Simulated the [weight-based](https://arxiv.org/abs/2003.12559){:target="_blank"} model on a multi-UAV system comprising of [3DR Iris Quadcopters](https://3dr.com/support/articles/iris/){:target="_blank"} on ROS & Gazebo, using [MAVROS/MAVLINK](https://dev.px4.io/v1.8.0/en/simulation/ros_interface.html){:target="_blank"} as a communication protocol.


- <strong>Weight-Based Exploration for Unmanned Aerial Vehicles</strong><a class="links" title="Weight" href="https://github.com/SarthakJShetty/Weight" target="_blank"> [Code]</a> <a title="Elsevier Weight 2020 Paper" class="links" href="https://www.sciencedirect.com/science/article/pii/B9780128202760000236" target="_blank">[Paper]</a> <a title="Weight 2020 Paper" class="links" href="https://arxiv.org/abs/2003.12559" target="_blank">[Paper, Elseiver 2020]</a>
    - Developed a weight-based path-planning model for Unmanned Aerial Vehicles involved in search and rescue. Advised by [Professor Debasish Ghose](http://aero.iisc.ac.in/people/debasish-ghose/) at the Mobile Robotics Laboratory, [Department of Aerospace Engineering](http://aero.iisc.ac.in/), [Indian Institute of Science](https://iisc.ac.in).
    - Simulated the probabilistic ["weight-based"](https://arxiv.org/abs/2003.12559) algorithm on [3DR Iris Quadcopters](https://3dr.com/support/articles/iris/) on ROS & Gazebo, using [MAVROS/MAVLINK](https://dev.px4.io/v1.8.0/en/simulation/ros_interface.html) as a communication protocol.
    - [Deployed](https://github.com/SarthakJShetty/Weight#32-physical-testing-results) the model on an [off-the-shelf](https://github.com/SarthakJShetty/Weight#32-physical-testing-results) UAV running a [MAVROS](https://dev.px4.io/v1.8.0/en/simulation/ros_interface.html) node onboard a [Pixhawk](https://pixhawk.org/).


- <strong>Transiently Informed Robotic Swarms</strong><a class="links" title="Transient" href="https://github.com/SarthakJShetty/Transient" target="_blank"> [Code] </a>
    - Part of undergraduate thesis research on developing coordination & exploration strategies for robotic swarms involved in search & rescue, inspired by transiently informed ant swarms. Advised by [Professor Vishwesha Guttal](https://teelabiisc.wordpress.com/members/) and [Professor Debasish Ghose](http://aero.iisc.ac.in/people/debasish-ghose/).
    - Model designed on ROS using [Frontier Exploration](http://wiki.ros.org/frontier_exploration), [Adaptive Monte Carlo Localization (AMCL)](http://wiki.ros.org/amcl), and [move_base](http://wiki.ros.org/move_base).
    - Exploration stack is being prototyped on a swarm of [Clearpath Huskies](https://clearpathrobotics.com/husky-unmanned-ground-vehicle-robot/), each mounted with a LiDAR to map the environment around it in three dimensions.

- <strong>IUCN Red List species threats and stressess database</strong><a class="links" title="Red" href="https://github.com/SarthakJShetty/Red" target="_blank"> [Code] </a> <a class="links" title="Red" href="https://conbio.onlinelibrary.wiley.com/doi/full/10.1111/conl.12815" target="_blank"> [Paper, Conservation Letters 2021] </a>
    - Generated a database on species threats and stresses by scraping the [IUCN Red List](https://www.iucnredlist.org/).
    - Collaboration with [Uttara Mendiratta](https://www.researchgate.net/profile/Uttara_Mendiratta) and [Anand MO](https://www.ncf-india.org/author/675623/anand-osuri-2) from the Nature Conservation Foundation.
    - Utilized [Selenium Web Driver](https://www.selenium.dev/) to automate the scraping procedure and [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) to scrape the HTML contents. [Pandas](https://pandas.pydata.org/) was used to build dataframes and interface with a local .CSV file.

- <strong>Fracture-Detection System</strong><a class="links" title="Fracture-Detection System" href="https://github.com/SarthakJShetty/Fracture" target="_blank"> [Code]</a> <a title="A2IC 2018 Paper" href="https://premc.org/doc/A2IC2018/A2IC2018_Book_Of_Abstracts.pdf" class="links" target="_blank">[Paper, A2IC 2018]</a> <a title="A2IC 2018 arXiv Paper" href="" class="links" target="_blank">[arXiv]</a>
    - Built a fracture detection system to identify fractures and fatiguing in manufactured components, and predictions were made about the same.
    - The system employed OpenCV through which fractures were identified, after being subjected to different filters.
    - The TensorFlow model, based on ImageNet, retrained on a dataset of normal and fractured gear images, was used as an example to make predictions about wearability and test the system.

- <strong>Biomimetic Robotic Fish</strong><a class="links" title="Fish" href="https://github.com/SarthakJShetty/Fish" target="_blank"> [Code] </a>
    - Built a predatory robotic fish, as a part of Summer Research Internship at the [Theoretical Ecology & Evolution Laboratory](https://teelabiisc.wordpress.com).
    - The Robotic Fish will be used to research collective behavior and aggregation patterns in *Serpae tetra* species of fish.
    - Worked under the guidance of [Professor Vishwesha Guttal](https://teelabiisc.wordpress.com) from [Center for Ecological Sciences](https://ces.iisc.ac.in), [Indian Institute of Science](https://iisc.ac.in).

- <strong>Differential Drive Donkey Car</strong><a class="links" title="DonkeyCar" href="https://github.com/SarthakJShetty/Donkey" target="_blank"> [Code] </a>
    - Built a small-scale differential drive [autonomous car](https://www.DonkeyCar.com), powered by a TensorFlow based Autopilot, trained on nearly 10,000 images of a track.
    - The Autopilot was used to drive the vehicle autonomously around the track. Check it out [here!](https://youtu.be/0Sid7q3nsWY)
    - Research undertaken at the [Center for System Design](http://www.nitk.ac.in/centre-excellence/centre-system-design) at the [National Institute of Technology Karnataka](https://www.nitk.ac.in), jointly advised by [Professor Gangadharan KV](http://mech.nitk.ac.in/faculty/k-v-gangadharan) and [Professor Pruthviraj Umesh](http://appmech.nitk.ac.in/faculty/pruthviraj-u).

- <strong>Gesture Controlled Robotic Arm</strong><a class="links" title="Arm" href="https://github.com/SarthakJShetty/Arm" target="_blank"> [Code] </a>
    - Built and designed a 3D printed robotic arm, controlled by human gestures using a Microsoft Kinect 360.
    - [Open Natural Interactions Library](https://github.com/OpenNI/OpenNI) for Processing was used to detect user's pose and joint angles.
    - Detected angles were translated to joint movements of the [Arm](https://github.com/SarthakJShetty/Arm) by an Arduino Uno.
