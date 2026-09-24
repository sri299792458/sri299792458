# Srinivas Kantha Reddy

I'm a robotics master's student at the University of Minnesota's [RPM Lab](https://rpm-lab.github.io/), working on robot learning and manipulation.

Before UMN, I worked on quadruped locomotion at [IISc's Stoch Lab](https://www.stochlab.com/). My background is in physics and mechanical engineering from BITS Pilani, India (Class of 2025).

I'm looking for opportunities in robotics and machine learning.

[Email](mailto:kanth042@umn.edu) · [LinkedIn](https://www.linkedin.com/in/sri-k08/) · [Google Scholar](https://scholar.google.com/citations?user=gRlgDrsAAAAJ&hl=en)

## Selected robotics work

### Quadruped locomotion

I trained and deployed locomotion policies on a custom 70 kg quadruped at IISc, working through controller integration, sim-to-real failures and field tests on uneven terrain. My [Barrier-Loco implementation](https://github.com/sri299792458/Barrier-Loco) builds on Legged Gym and prior locomotion methods, with separate task and barrier critics.

I also coauthored **[GRoQ-LoCO: Generalist and Robot-agnostic Quadruped Locomotion Control using Offline Datasets](https://arxiv.org/abs/2505.10973)** (2025).

### G1 / Dex3 manipulation

I built a cube-stacking pipeline for the Unitree G1 with Dex3 hands, demonstrated on the physical robot. It integrates camera calibration and object pose estimation with offline GraspGenX grasp qualification, CuRobo motion planning, robot control and recovery, and episode recording.

[Demonstration and guide](https://sri299792458.github.io/g1-research-docs/manipulation/tasks.html)

### Robot-learning data infrastructure

I developed a [data pipeline around SPARK](https://github.com/sri299792458/spark-data-collection/tree/main/data_pipeline) to record robot demonstrations and convert them into LeRobot datasets. It captures RGB-D, tactile and robot-state streams through ROS 2, with session metadata and a Qt console for configuring sensors and controlling recordings.

[Setup and design guide](https://rpm-lab-umn.github.io/spark-data-collection/)

## ML and vision

The VLM, LLM and image-retargeting projects below were developed through graduate coursework.

| Project | Work |
| --- | --- |
| [Quest 3 bowling tracking](https://github.com/sri299792458/quest3-bowling-ball-tracking) | Mixed-reality bowling analysis combining headset video streaming, YOLO/SAM2 tracking, calibrated trajectory reconstruction, and shot statistics and replay in the headset. |
| [Language-guided grasp detection](https://github.com/sri299792458/vlm-grasp) | Grasp prediction from images and language using Qwen3-VL-8B, LoRA fine-tuning and constrained decoding, evaluated on OCID-VLG. |
| [Dream Team](https://github.com/sri299792458/dream-team-research-automation) | Research agents that recruit specialists, execute code, recover from failed steps and record experiments. |
| [WorldValuesBench](https://github.com/sri299792458/worldvalues-qwen-finetuning) | Qwen3 fine-tuning experiments on survey-response prediction, comparing direct supervision with synthetic reasoning data. |
| [Class-aware image retargeting](https://github.com/sri299792458/cv5561-f25-team-asa) | Team project for content-aware image resizing, using composition, depth and saliency models to guide seam carving. |

Other work: [Isaac Gym on remote GPU servers](https://github.com/sri299792458/isaac-gym-server-gui), [diffusion sampler comparisons](https://github.com/sri299792458/diffusion-sampler-benchmarks), and an [interactive grasp-planning explainer](https://github.com/sri299792458/planning-optimal-grasps-html-demo).
