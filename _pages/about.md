---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student under the supervision of [Olivier Simonin](http://perso.citi-lab.fr/osimonin/) (CITI Lab, INSA Lyon), [Isabelle Guerin-Lassous](https://perso.ens-lyon.fr/isabelle.guerin-lassous/) (LIP, ENS Lyon) and [Isabelle Fantoni](https://pagesperso.ls2n.fr/~fantoni-i/index.html) (LS2N, CNRS).

I research communication in groups of cooperative aerial robots, or fleets of drones. My Ph.D. subject is **Efficient control of UAV fleet subject to heterogeneous communication constraints**. 

More specifically, we aim at improving the co-habitation of different flows of information with contrasting Quality of Service (QoS) requirements in a group of flying robots (e.g. *piloting data flow* and *video streaming flow*). We focus our efforts towards the Wi-Fi technology for now, but other physical layers could be considered in the future. To investigate the open problems and challenges, we use both **simulation** and **real-life experiments**.

My research interest include *robotics* (in particular multi-robot systems), *ad-hoc networks* and *cyber-physical systems simulation*.

-------------

# Research details
Applications for multi-robot systems in the sky are numerous and rapidly growing, in several civil and military areas. We can cite applications such as search-and-recue, environment monitoring, wireless sensor networks, wildlife research and monitoring, large structure inspection, etc.

While drones already proved their relevancy, most applications only use one drone, controlled by a human on the ground. It has been proven that fleets of cooperative UAVs can accomplish a mission faster, with more robustness and for a reduced cost than a single UAV.

However, the practical problems faced during the deployment of such a multi-UAV system are numerous. More drones imply a higher level of autonomy, because you don't want to micro-manage each drone. It is also particularly interesting if the UAVs cooperate to accomplish a common goal. For all of the above, UAVs need reliable communication.

For this cooperation, UAVs could use simple sensing (for example, detecting the neighbors through an onboard camera to avoid collisions), or more complex forms of communications, using wireless communication technologies. In our research, we focus on the later.

One well known method for distributed control of a fleet of UAVs is flocking. Each robot can compute its command law with the sheer knowledge of it's neighbors' positions and speeds. When multiple agents comply to these rules, a global behavior emerges, resembling the dynamics of a flock of birds or school of fishes.

To transmit its position and velocity to its neighbors, each drone may rely on a wireless network - maybe based on Wi-Fi - with its peers. But this type of network could also be useful for mission-level purposes, such as video transmission, file exchange (local maps, for example), etc. These different flows of data greatly differ in type and quality of service requirements. Piloting data (the position and velocity) is a critical flow, require a light throughput but very low delay and is broadcasted to all close neighbors. Video data on the other hand, require a very high throughput, but can accept a less reliable channel and may suffer longer delays.

In this context, we investigate how these different flows can coexist inside a fleet of drones, and how to guarantee a certain level of QoS for piloting data. 