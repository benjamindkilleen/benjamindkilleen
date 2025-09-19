Hi! Welcome to my GitHub. For more info about me, please visit [my website](https://benjamindkilleen.com).

I'm a researcher who uses GitHub extensively. Many projects have multiple repositories, which I've outlined here. To request access to private repositories, if you are a student or collaborator of mine, please do so via [this form](https://docs.google.com/forms/d/e/1FAIpQLSeMGh1kZXtFn8I7t3O6ghT2HSJwqPqb3K8CGJTLjSc1jzhR8g/viewform?usp=header). Do not request access via email or GitHub, as it may be overlooked.

These are grouped by project and listed roughly in order of importance/recency.

## Libraries

These are complete libraries that are used in multiple projects.

[Link to MICCAI 2019 DeepDRR paper](https://arxiv.org/abs/1803.08606).

| Repository                                                   | Description                                                | Note                                           |
| ------------------------------------------------------------ | ---------------------------------------------------------- | ---------------------------------------------- |
| [deepdrr](https://github.com/arcadelab/deepdrr)              | X-ray simulation framework.                                | Public. `dev` branch contains latest features. |
| [killeengeo](https://github.com/benjamindkilleen/killeengeo) | Python library for 2D, 3D geometry.                        | Public                                         |
| [loopx](https://github.com/benjamindkilleen/loopx)           | Code for controlling the Loop-X and reading Loop-X images. | Private                                        |
| [tull](https://github.com/benjamindkilleen/tull)             | Creating primitives for figures in talks and papers.       | Public                                         |

## FluoroSAM

[Link to MICCAI 2025 FluoroSAM paper](https://arxiv.org/abs/2403.08059).

| Repository                                                     | Description                                                     | Note    |
| -------------------------------------------------------------- | --------------------------------------------------------------- | ------- |
| [fluorosam](https://github.com/arcadelab/fluorosam)            | Main public codebase for FluoroSAM (in progress).               | Public  |
| [fluoroseg](https://github.com/arcadelab/fluoroseg)            | Code for reading and using the FluoroSeg dataset (in progress). | Public  |
| [nmdid-utils](https://github.com/benjamindkilleen/nmdid-utils) | Utilities for processing NMDID CT data.                         | Public  |
| [prephix](https://github.com/benjamindkilleen/prephix)         | Simulation and training code for FluoroSAM.                     | Private |
| [nmdid-arcade](https://github.com/arcadelab/nmdid-arcade)      | Original implementation for NMDID processing.                   | Private |

## Pelphix

[Link to MICCAI 2023 Paper](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_13)

| Repository                                             | Description                                                                              | Note   |
| ------------------------------------------------------ | ---------------------------------------------------------------------------------------- | ------ |
| [pelphix](https://github.com/benjamindkilleen/pelphix) | Main codebase for Pelphix simulation and training.                                       | Public |
| [perphix](https://github.com/arcadelab/perphix)        | Code for reading and using data in the Pelphix format, for percutaneous pelvic fixation. | Public |

## Real-time Integrated X-ray Studies

These repositories support real-time integrated studies with the Loop-X robot, voice control, and/or augmented reality.

- IPCAI 2023 paper: ["An Autonomous X-ray Image Acquisition and Interpretation..."](https://link.springer.com/article/10.1007/s11548-023-02941-y)
- IPCAI 2024: ["Take a Shot..."](https://link.springer.com/article/10.1007/s11548-024-03120-3)
- IPCAI 2025: ["Intelligent Control of Robotic X-ray Devices..."](https://link.springer.com/article/10.1007/s11548-025-03351-y)

| Repository                                                                           | Description                                               | Note                |
| ------------------------------------------------------------------------------------ | --------------------------------------------------------- | ------------------- |
| [IPCAI-pelvic-corridors](https://github.com/benjamindkilleen/ipcai-pelvic-corridors) | Implementation for pelvic corridor studies in IPCAI 2023. | Public, standalone. |

| [corridors](https://github.com/benjamindkilleen/corridors) | Main server for integration studies. Contains triangulation, model inference code. Also contains the GUI code for the original IPCAI 2023 paper. | Private |
| [xeno](https://github.com/benjamindkilleen/xeno) | Voice control client (e.g. laptop in the room) for IPCAI 2023 (`main` branch), 2024 (`patient_model_client_2` branch) papers. | Private |
| [phelix](https://github.com/benjamindkilleen/phelix) | Used to train the Corridors X-ray model. Relies on [`perphix`](#pelphix) for data format. | Private |

## Simulated FluoroSAM Voice Control Demo

Uses [DeepDRR](#libraries) to simulate X-ray images using FluoroSAM model for voice control, similar to [corridors](#real-time-integrated-x-ray-studies) but without Loop-X.

| Repository                                                                                 | Description                                                                                      | Note    |
| ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ | ------- |
| [fluorosam-vui-demo-server](https://github.com/benjamindkilleen/fluorosam-vui-demo-server) | Server for voice control simulation Demo.                                                        | Private |
| [fluorosam-vui-demo](https://github.com/benjamindkilleen/fluorosam-vui-demo)               | Laptop-side client for voice control simulation Demo. Has good GUI for real-time speech-to-text. | Private |

## Full-body CT Diffusion Project

2024 - 2025 with Bohua Wan and Aditya Kulkarni. [Link to paper.](https://arxiv.org/abs/2502.09688)

| Repository                                                | Description                                    | Note                                |
| --------------------------------------------------------- | ---------------------------------------------- | ----------------------------------- |
| [ct-diffusion](https://github.com/arcadelab/ct-diffusion) | Main codebase for CT Diffusion project.        | Private. Use branch `oracle_cloud`. |
| [nmdid-arcade](https://github.com/GlenGGG/nmdid-arcade)   | Fork of nmdid-arcade for CT Diffusion project. | Private                             |

## VRPelviSim

CIS 2024 Project. Adds more intuitive controls and a tutorial to [PelvisVR](#pelvisvr).

| Repository                                                                        | Description   | Note    |
| --------------------------------------------------------------------------------- | ------------- | ------- |
| [vrpelvisim-surgical-room](https://github.com/arcadelab/vrpelvisim-surgical-room) | Unity client. | Private |
| [vrpelvisim-deepdrr-zmq](https://github.com/arcadelab/vrpelvisim-deepdrr-zmq)     | ZMQ server.   | Public  |

## PelvisVR

CIS 2023 Project. [Link to IPCAI 2024 Surgeons Shoes Paper](https://link.springer.com/article/10.1007/s11548-024-03138-7)

| Repository                                                       | Description                     | Note    |
| ---------------------------------------------------------------- | ------------------------------- | ------- |
| [vr_surgical_room](https://github.com/PelvisVR/vr_surgical_room) | PelvisVR Unity Client           | Private |
| [deepdrr_zmq](https://github.com/PelvisVR/deepdrr_zmq)           | DeepDRR ZMQ Server for PelvisVR | Public  |

## X-Pose

2022 AE-CAI paper "Mixed reality interfaces for achieving desired views with robotic X-ray systems." [Link to paper.](https://www.tandfonline.com/doi/abs/10.1080/21681163.2022.2154272)

Does not directly control the Loop-X, but was a precursor to the real-time integrated studies.

| Repository                                               | Description                             | Note    |
| -------------------------------------------------------- | --------------------------------------- | ------- |
| [X-Pose-Project](https://github.com/benjamindkilleen/X-Pose-Project) | Unity client for X-Pose project. | Private |
| [x-pose](https://github.com/benjamindkilleen/x-pose)| DeepDRR ZMQ server for X-Pose project. | Private  |