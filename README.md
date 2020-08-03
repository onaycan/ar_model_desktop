<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)


<!-- ABOUT THE PROJECT -->
## About The Project

The main purpose of this small project to achieve stepwise a final goal: ar race car. 
In this little example i demonstrate in 3 steps an AR demonstrator for desktop only. 
The android application is not included here. 
Most of the content is taken/mixed from the three.js [example sources](https://threejs.org/examples/#webgl_animation_cloth)

### Built With
One major framewrk is used to achieve the goal: three.js. 
Additionally, a free model is chosen for the demonstration, which can replaced as user wishes to do it so.  
Special thanks goes to "chiefpad" of sketchfab. 

* [threejs](https://threejs.org/)
* [Sketchfab](https://sketchfab.com/3d-models/cockpit-model-vr-33acf5be400740aa85d7738871231962)

![Image 1](./readme_pics/sketchfab_model.png?raw=true "Model Chosen")


<!-- GETTING STARTED -->
## Getting Started

You need to fetch a local copy of these first.

### Prerequisites

Al the necessary prerequiests are included hereby. 
To run a simple web-server you can alternatively use miniweb, or similar.
I prefered to use python instead, so make sure you have open ports in your machine and you know how to serve there. 

### Installation

No needs of installation. 

<!-- USAGE EXAMPLES -->
## Usage
Simply run a server using python3's http.server on an open port, and navigate into your browser. 

```shell
you@yourmachine$ python3 -m http.server 5000
Serving HTTP on 0.0.0.0 port 5000 (http://0.0.0.0:5000/) ...
127.0.0.1 - - [03/Aug/2020 01:51:30] "GET / HTTP/1.1" 200 -
..
.
```

![Image 1](./readme_pics/folder_structure.png?raw=true "Folder Structure")