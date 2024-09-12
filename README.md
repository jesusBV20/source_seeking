# Source-seeking simulations for robot swarm

This repository contains a collection of Python simulations we use to numerically validate and test our source-seeking algorithms for swarms before moving to our robotic platforms.

## Content:

* `source_seeking_2D`: Implements our resilient source-seeking algorithm for robot swarms in 2D.
* `source_seeking_3D`: Implements a PD control in SO(3) to align robot swarms with the ascending direction given by our resilient source-seeking algorithm.
* `source_seeking_distr`: Implements a distributed consensus algorithm for robot swarms to estimate the ascending direction given by our source-seeking algorithm.

## Research Papers & Technical Notes

```
WIP

@misc{acuaviva2024resilientsourceseekingrobot,
  title={Resilient source seeking with robot swarms}, 
  author={Antonio Acuaviva and Jesus Bautista and Weijia Yao and Juan Jimenez and Hector Garcia de Marina},
  year={2024},
  url={https://arxiv.org/abs/2309.02937},
}

@misc{bautista2024so3attitudecontrollersalignment,
  title={SO(3) attitude controllers and the alignment of robots with non-constant 3D vector fields}, 
  author={Jesus Bautista and Hector Garcia de Marina},
  year={2024},
  url={https://arxiv.org/abs/2406.14998}, 
}
```
