<h1 align="center">Hi 👋, I'm Luís Gabriel</h1>
<h3 align="center">A passionate Machine Learning | Computer vision | Engineer/Reseacher from Brazil</h3>

- 🔭 I’m currently working on **computer vision/machine learning at Eldorado Research Institute**

- 🌱 I’m currently learning **about MLOps, self-supervised learning and synthetic data for computer vision**

- 👯 I’m looking to collaborate on **Deep learning open source projects**

- 💬 Ask me about **Computer vision, machine learning, deep learning, self-supervised learning ...**

- 📫 How to reach me **condadoslgpc@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/lgabrielpc" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="lgabrielpc" height="30" width="40" /></a>
<a href="https://kaggle.com/condados" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="condados" height="30" width="40" /></a>
<a href="https://www.youtube.com/channel/UCGqW9GuMni6KTZkLF2dxu4g" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="ucgqw9gumni6ktzklf2dxu4g" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://flask.palletsprojects.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg" alt="flask" width="40" height="40"/> </a> <a href="https://cloud.google.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://grafana.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/grafana/grafana-icon.svg" alt="grafana" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://opencv.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/opencv/opencv-icon.svg" alt="opencv" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=gabriellgpc&show_icons=true&locale=en" alt="gabriellgpc" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=gabriellgpc&" alt="gabriellgpc" /></p>

# Public Projects

# **Robotics**

## Software solution for our autonomous soccer team for the IEEE VSSS Competition - Team Poti
### Description
Software developed by the [Poti Robot Soccer Team](https://github.com/potiufrn/Futrobot) of the [Department of Computing and Automation](https://www.dca.ufrn.br/) (DCA) at [UFRN](https://www.ufrn.br/) aimed at the development of research in robotics and participation in robot soccer competitions ([IEEE VSSS](https://ieeevss.github.io/vss/index_ptbr.html)).
### Techstack

**C | C++ | Makefile | Linux | Qt | V4L2 | Bluetooth | Controllers | Path planning | Robotics | Many other.**

Qt to make the graphical interfaces, but the system also runs directly through the terminal, but it is necessary to use the interface at least to calibrate the colors (the vision system uses color segmentation)
Bluetooth for communication with the host(pc) and robots (fleet of three robots)
The rest is C++ for doing: image processing, computer vision, AI, control…
v4l2 (Video for Linux 2) used to build the library for camera control (configuration and consultation of camera parameters) and for capturing images in YUYV or RGBG.

### Source code [here](https://github.com/potiufrn/Futrobot)

## Path Planning using potential field and occupancy grid on CoppeliaSim (VREP)

TechStack: **C++ | CoppeliaSim | Qt | OpenGL**

Simulation using CoppeliaSim (formerly VREP), design in C++ (from scratch) of a path planner based on potential fields. Source Code [here](https://github.com/Gabriellgpc/sistemas_roboticos_autonomos/tree/master/program/p3m3). Obs.: I will leave a report in PDF explaining the general functioning of the system.

YouTube Video [here](https://www.youtube.com/watch?v=_S35ZPSqSBo&ab_channel=Lu%C3%ADsGabriel)