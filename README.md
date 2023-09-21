# Simultaneous Synchronization and Calibration for Wide-baseline Stereo Event Cameras
## ICRA2024 Paper Submission

This repository hosts the codebase and dataset for our research paper, "Simultaneous Synchronization and Calibration for Wide-baseline Stereo Event Cameras," currently under review for ICRA2024.

## Abstract
Event-based cameras offer remarkable advantages such as high temporal resolution and low power consumption but suffer from synchronization issues when deployed in multi-camera settings. Our paper introduces a software-based method to achieve millisecond-level synchronization while simultaneously estimating extrinsic parameters. Our approach eliminates the need for specialized hardware, thus making it particularly suitable for wide-baseline configurations. The robustness and applicability of our method are empirically demonstrated through extensive simulations and real-world experiments.
&nbsp;

<div align="center">
    <div align="center">
        <img src="./fig/head_a.png" width="500">
    </div>
    <div style="color: gray; font-size: 10px;">
        Illustration of dual-perspective event capture
    </div>
</div>
&nbsp;

<div align="center">
    <div align="center">
        <img src="./fig/head_b.png" width="500">
    </div>
    <div style="color: gray; font-size: 10px;">
        Temporal misalignment
    </div>
</div>
&nbsp;

## Usage


## Results
<div align="center">
    <div align="center">
        <img src="./fig/unsynchronized.gif" width="600">
    </div>
    <div style="color: gray; font-size: 10px;">
        Unsynchronized event streams and F matrix
    </div>
</div>
&nbsp;

<div align="center">
    <div align="center">
        <img src="./fig/synchronized.gif" width="600">
    </div>
    <div style="color: gray; font-size: 10px;">
        Synchronized event streams and F matrix
    </div>
</div>

## Contributions
- Novel software-based approach for temporal synchronization of event-based cameras in wide-baseline settings.
- Simultaneous estimation of extrinsic parameters, thus integrating these processes for increased efficiency.
- Comprehensive validation of the method through simulations and real-world experiments.

## Contact

For further inquiries or questions, please contact us at [wlxing@connect.hku.hk].

Thank you for your interest in our research.

