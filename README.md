# Awesome-Autonomous-Mobile-Robot-Management

## Top Autonomous Mobile Robot (AMR) Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Fleet Orchestration, Multi-Robot Traffic Control, Task Dispatch, Warehouse AMR Operations & Robotics Middleware*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Autonomous Mobile Robot (AMR) Management**. These systems coordinate fleets of mobile robots—task assignment, traffic deconfliction, integration with WMS/MES, and live monitoring—across warehouses, factories, and facilities.



**Examples** include SVT Robotics, InOrbit, Formant, Brain Corp, MiR Fleet, OTTO Fleet Manager, Vecna Robotics, Geek+ RMS, GreyMatter, LocusOne, Exotec Deepsky, and Seegrid Supervisor (the category leaders).



**Open-source emphasis**: Commercial fleet managers dominate industrial deployments. Open strength is centered on **Open-RMF**, **ROS 2**, and **Nav2**—the standard stack for multi-robot coordination and navigation research and integration. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[SVT Robotics, InOrbit, Formant](https://www.svtrobotics.com/)**  

  Vendor-agnostic robot operations platforms—fleet monitoring, integration, and orchestration across heterogeneous AMRs and fixed robots.



- **[MiR Fleet, OTTO Fleet Manager, Seegrid Supervisor, LocusOne](https://www.mobile-industrial-robots.com/)**  

  OEM fleet managers tightly integrated with their AMR hardware for tasking, traffic, and facility maps.



- **[Geek+ RMS, Exotec Deepsky, Brain Corp, Vecna, GreyMatter](https://www.geekplus.com/)**  

  Warehouse robotics management systems for goods-to-person, sorting, and large-scale AMR fleets.



- **[Other commercial AMR / fleet platforms](https://www.svtrobotics.com/)**  

  Additional solutions for multi-vendor interoperability and facility-level robot control.



## Open-Source GitHub Projects



- **[Open-RMF (Robotics Middleware Framework)](https://github.com/open-rmf/rmf)**  

  Leading open platform for multi-fleet robot management—task dispatch, traffic scheduling, and adapters for commercial and research robots on ROS 2.



- **[Nav2 (Navigation 2)](https://github.com/ros-navigation/navigation2)**  

  Standard open-source navigation stack for ROS 2—planning, control, and recovery behaviors used by most AMR research and many production integrations.



- **[ROS 2](https://github.com/ros2)**  

  Core open robotics middleware—communication, lifecycle, and tooling foundation for AMR software stacks worldwide.



- **[free_fleet & Open-RMF fleet adapters](https://github.com/open-rmf)**  

  Open adapters connecting Nav2-based or vendor robots into Open-RMF for coordinated multi-robot operation.



- **[Warehouse AMR simulation stacks](https://github.com/Pouya-Mansournia/warehouse-amr-ros2)**  

  Open multi-robot warehouse simulations with per-robot SLAM/Nav2 and station reservation patterns for development and testing.



- **[Andino / educational RMF demos](https://github.com/search?q=andino+rmf+OR+open-rmf+demo)**  

  Reference integrations showing Nav2 robots managed under Open-RMF for scalable fleet templates.



- **[SLAM Toolbox & mapping tools](https://github.com/SteveMacenski/slam_toolbox)**  

  Open mapping and localization packages commonly paired with Nav2 for AMR deployment.



- **[Gazebo / Ignition simulation for fleets](https://github.com/gazebosim/gz-sim)**  

  Open robot simulation used to validate fleet behaviors before real-hardware rollout.



### Additional Strong Open-Source Options



- **Fleet orchestration**: Open-RMF as the open multi-fleet traffic and task layer.

- **Single-robot navigation**: Nav2 + SLAM Toolbox on ROS 2.

- **Integration**: Vendor fleet adapters or free_fleet-style bridges into RMF.

- **Composable stacks**: ROS 2 robots → Nav2 → Open-RMF → WMS/MES API.

- Commercial fleet managers still lead in certified industrial support, vendor SLAs, and turnkey WMS connectors.



**Frameworks for building custom systems**:  

**ROS 2 + Nav2** for robot autonomy; **Open-RMF** for multi-robot tasking and traffic.  

Commercial platforms (MiR Fleet, OTTO, Geek+, InOrbit, Formant, SVT, etc.) provide production fleet UIs and enterprise integration.  

Research labs and integrators build on Open-RMF; most warehouses buy OEM or multi-vendor commercial fleet software. Fully open fleets are viable for R&D and controlled facilities with robotics expertise.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AMR fleets operate near people and inventory. Incorrect tasking or traffic control can cause injury or damage. Follow facility safety standards, risk assessments, and applicable regulations (e.g. ISO 3691-4). Validate in simulation and controlled pilots before production.

- Open-source stacks offer flexibility but require robotics engineering capability. Commercial platforms shift integration and support to the vendor. Neither replaces trained operators, maintenance, and site-specific safety procedures.



---



**Made for robotics engineers, warehouse automation leaders, and teams deploying AMR fleets.**  

Let's expand open multi-robot coordination through Open-RMF and ROS 2 while recognizing the industrial maturity of leading commercial AMR management platforms.
