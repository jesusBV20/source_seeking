# Source-seeking simulations for robot swarms

This repository contains a collection of Python simulations we use to numerically validate and test our source-seeking algorithms for swarms before moving to our robotic platforms.

## Content
* `source_seeking_2D`: Resilient source-seeking algorithm for robot swarms in 2D.
* `source_seeking_3D`: PD controller in SO(3) to align robot swarms with the ascending direction given by our resilient source-seeking algorithm.
* `source_seeking_distr`: A distributed consensus algorithm for robot swarms to estimate the ascending direction given by our source-seeking algorithm.

## Research Journal Paper

**ABSTRACT:**

```
WIP
```

## Research Conference Paper

**ABSTRACT:** We present a solution for locating the source, or
maximum, of an unknown scalar field using a swarm of mobile
robots. Unlike relying on the traditional gradient information,
the swarm determines an ascending direction to approach
the source with arbitrary precision. The ascending direction
is calculated from field strength measurements at the robot
locations and their relative positions concerning the swarm
centroid. Rather than focusing on individual robots, we focus
the analysis on the density of robots per unit area to guarantee
a more resilient swarm, i.e., the functionality remains even if
individuals go missing or are misplaced during the mission.
We reinforce the algorithm’s robustness by providing sufficient
conditions for the swarm shape so that the ascending direction
is almost parallel to the gradient. The swarm can respond to an
unexpected environment by morphing its shape and exploiting
the existence of multiple ascending directions. Finally, we validate
our approach numerically with hundreds of robots. The fact
that a large number of robots with a generic formation always
calculate an ascending direction compensates for the potential
loss of individuals.

```
@misc{acuaviva2024resilientsourceseekingrobot,
  title={Resilient source seeking with robot swarms}, 
  author={Antonio Acuaviva and Jesus Bautista and Weijia Yao and Juan Jimenez and Hector Garcia de Marina},
  year={2024},
  url={https://arxiv.org/abs/2309.02937},
}
```

This paper was presented in IEEE Conference on Decision and Control (CDC) 2024.

## Technical Note

This technical note technical note aims to introduce geometric controllers
to roboticist for aligning 3D robots with non-constant 3D
vector fields. This alignment entails the control of the robot’s
3D attitude. We derive with excessive detail all the calculations
needed for the analysis and implementation of the controllers.

```
@misc{bautista2024so3attitudecontrollersalignment,
  title={SO(3) attitude controllers and the alignment of robots with non-constant 3D vector fields}, 
  author={Jesus Bautista and Hector Garcia de Marina},
  year={2024},
  url={https://arxiv.org/abs/2406.14998}, 
}
```

We strongly recommend referring to this technical note for a comprehensive understanding of the mathematical theory underlying the code in `source_seeking_3D`.
