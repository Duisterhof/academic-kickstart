---
title: "Learning to Seek: Deep Reinforcement Learning for Phototaxis of a Nano Drone in an Obstacle Field"
date: 2019-01-01
publishDate: 2019-12-14T16:50:53.220278Z
authors: ["Bardienus P. Duisterhof", "Srivatsan Krishnan", "Jonathan J. Cruz", "Colby R. Banbury", "William Fu", "Aleksandra Faust", "Guido C. H. E. de Croon", "Vijay Janapa Reddi"]
publication_types: ["0"]
abstract: "Nano drones are uniquely equipped for fully autonomous applications due to their agility, low cost, and small size. However, their constrained form factor limits flight time, sensor payload, and compute capability. While visual servoing of nano drones can achieve complex tasks, state of the art solutions have significant impact on endurance and cost. The primary goal of our work is to demonstrate phototaxis in an obstacle field, by adding only a lightweight and low-cost light sensor to a nano drone. We deploy a deep reinforcement learning model, capable of direct paths even with noisy sensor readings. By carefully designing the network input, we feed features relevant to the agent in finding the source, while reducing computational cost and enabling inference up to 100 Hz onboard the nano drone. We verify our approach with simulation and in-field testing on a Bitcraze CrazyFlie, achieving 94% success rate in cluttered and randomized test environments. The policy demonstrates efficient light seeking by reaching the goal in simulation in 65% fewer steps and with 60% shorter paths, compared to a baseline random walker algorithm. "
featured: false
publication: "*TC*"
links:
url_video: "https://www.youtube.com/watch?v=wmVKbX7MOnU"
url_code: "https://github.com/harvard-edge/source-seeking"
---
{{< youtube wmVKbX7MOnU >}}

