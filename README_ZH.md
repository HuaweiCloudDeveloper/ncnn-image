

<h1 align="center">NCNN轻量级AI视觉推理引擎</h1>
<p align="center">
  <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
</p>



## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[NCNN](https://github.com/Tencent/ncnn) 是基于高性能轻量级推理框架的AI视觉推理加速工具包。已集成主流人脸检测模型SCRFD和RetinaFace,以及目标检测YOLOv8等。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的NCNN。

## 核心特性

- **极致轻量、无第三方依赖：** 纯 C++ 实现，不依赖任何外部库，编译后体积极小，适用于嵌入式设备、移动端及资源受限环境，真正实现“零依赖”部署
- **专为移动端与边缘计算优化：** 深度适配 ARM 架构，针对 CPU 指令集（如 NEON）进行汇编级优化，显著提升推理速度，兼顾性能与功耗平衡
- **高性能推理引擎：** 提供算子融合、内存复用、多线程并行等优化策略，在保持高精度的同时实现毫秒级响应，满足实时性要求高的应用场景

本项目提供的开源镜像商品 [NCNN轻量级AI视觉推理引擎](https://marketplace.huaweicloud.com/hidden/contents/21eb05f2-1179-4ecf-a08f-b919782962af#productid=OFFI1144193128288825344) 已预先安装20250503版本的NCNN及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
>
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件

[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                     | 特性说明                                                 | 备注 |
| ------------------------------------------------------------ | -------------------------------------------------------- | ---- |
| [NCNN-20250503-kunpeng](https://github.com/HuaweiCloudDeveloper/ncnn-image/tree/NCNN-20250503-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |      |

## 获取帮助

- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/ncnn-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献

- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
