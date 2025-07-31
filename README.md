

<h1 align="center">NCNN Lightweight AI Visual Reasoning Engine</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
</p>






## Table of Contents

- [Repository Introduction](#project-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Project Introduction



[NCNN](https://github.com/Tencent/ncnn)  is an AI visual inference acceleration toolkit based on a high-performance lightweight inference framework. We have integrated mainstream face detection models SCRFD and RetinaFace, as well as object detection YOLOv8. This product provides an out-of-the-box NCNN based on the Huawei Cloud EulerOS 2.0 64-bit system of Kunpeng servers.

## Core Features

- **Extremely lightweight, no third-party dependency:** Pure C++implementation, does not rely on any external libraries, has an extremely small compiled size, suitable for embedded devices, mobile devices, and resource constrained environments, truly achieving "zero dependency" deployment
- **Optimized for mobile terminals and edge computing:** Deeply adapted to ARM architecture, assembly level optimization is carried out for CPU instruction sets (such as NEON), significantly improving inference speed while balancing performance and power consumption
- **High performance inference engine:** Provide optimization strategies such as operator fusion, memory reuse, and multi-threaded parallelism to achieve millisecond level response while maintaining high precision, meeting high real-time requirements for application scenarios

The open-source image product [NCNN Lightweight AI Visual Reasoning Engine](https://marketplace.huaweicloud.com/intl/hidden/contents/f3898299-3955-4b1b-ade4-96555d81a1d4) provided by this project has pre-installed the the 20250503 version of NCNN and its related runtime environment, and provides deployment templates. Come and refer to the usage guide to easily start an efficient "out-of-the-box" experience!

> **System requirements are as follows:**
>
> - CPU: 2vCPUs or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites



[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description



| Image Specification                                          | Feature Description                                          | Remarks |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------- |
| [NCNN-20250503-kunpeng](https://github.com/HuaweiCloudDeveloper/ncnn-image/tree/NCNN-20250503-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |         |

## Get Help

- For more questions, you can contact us through [issues](https://github.com/HuaweiCloudDeveloper/ncnn-image/issues) or the service support of the specified product in the Huawei Cloud Marketplace.
- For other open-source images, please refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute

- Fork this repository and submit a merge request.
- Synchronously update README.md based on your open-source image information.
