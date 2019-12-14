---
title: "Learning to Seek: Autonomous Source Seeking on a Nano Drone Microcontroller with Deep Reinforcement Learning"
date: 2019-01-01
publishDate: 2019-12-14T16:50:53.220278Z
authors: ["Bardienus P. Duisterhof", "Srivatsan Krishnan", "Jonathan J. Cruz", "Colby R. Banbury", "William Fu", "Aleksandra Faust", "Guido C. H. E. de Croon", "Vijay Janapa Reddi"]
publication_types: ["0"]
abstract: "Nano drones are uniquely equipped for fully autonomous applications due to their agility, low cost, and small size. However, their constrained form factor limits flight time, sensor payload, and compute capability, which poses a significant limitation on the use of source-seeking nano drones in GPS-denied and highly cluttered environments. The primary goal of our work is to demonstrate the effectiveness of deep reinforcement learning in fully autonomous navigation on highly constrained, general-purpose hardware and present a methodology for future applications. To this end, we present a deep reinforcement learning-based light seeking policy that executes, in conjunction with the flight control stack, on a commercially available off-the-shelf ultra-low-power microcontroller (MCU). We describe our methodology for training and executing deep reinforcement learning policies for deployment on constrained, general-purpose MCUs. By carefully designing the network input, we feed features relevant to the agent in finding the source, while reducing computational cost and enabling inference up to 100 Hz. We verify our approach with simulation and in-field testing on a Bitcraze CrazyFlie, achieving 94% success rate in a highly cluttered and randomized test environment. The policy demonstrates efficient light seeking by reaching the goal in simulation in 65 % fewer steps and with 60% shorter paths, compared to a baseline `roomba' algorithm. "
featured: false
publication: "*TC*"
links:
url_video: "https://www.youtube.com/watch?v=wmVKbX7MOnU"
url_code: "https://github.com/harvard-edge/source-seeking"
---
{{< youtube wmVKbX7MOnU >}}

