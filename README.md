# DriveCamSim: Generalizable Camera Simulation via Explicit Camera Modeling for Autonomous Driving

## News
* **`27 May, 2025`:** We release the DriveCamSim paper on [arXiv](). Code & Models will be released after preparation. Please stay tuned!

## Introduction
> DriveCamSim is a generation framework for generalizable camera simulation. With proposed Explicit Camera Modeling and Information-Preserving control mechanism, DriveCamSim not only achieves SOTA performance in visual quality and controllability, but also unleashes the generalization capability across spatial-level(camera extrinsic/intrinsic, number of views) and temporal-level(video frequency, reverse temporal order), supporting flexible camera simulation for downstream application.
- 
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="resources/spatial_temporal_generalization.png" width="1000">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Instead of (a) implicit camera modeling in 2D image space, we propose (b) explicit camera modeling in 3D physical world to unleash the (c) spatial-level and (d) temporal-level generalization capabilities for flexible camera simulation.</div>
</center>
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="resources/overall_framework.png" width="1000">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">Overall framework of DriveCamSim.</div>
</center>
