---
title: "企业级主机"
date: 2020-01-30T00:40:25+09:00
description: Test description
draft: false
enableToc: false
weight: 15
keyword: 云主机, QingCloud, 实例, 虚拟机
---

## 计算型 EC3

采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比性能大幅提升，独享 CPU 模式，适合大多数企业应用场景，适用于计算密集型应用程序，例如高性能计算、科学建模、专用游戏服务器和广告服务器引擎等。

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:1/1:2
- 支持 VPC 私有网络和基础网络
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持25Gbps内网带宽，PPS最高400万
- 超低延时，低至91μs
- I/O优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

计算型 EC3 包括的实例规格和性能指标如下：

| 实例规格        | vCPU | 内存 | 内网带宽 | 内网收发包PPS | 延时 |
| --------------- | ---- | ---- | -------- | ------------- | ---- |
| ec3.xlarge.r1   | 4核  | 4G   | 2.5Gbps  | 200万         | 91μs |
| ec3.2xlarge.r1  | 8核  | 8G   | 3.5Gbps  | 400万         | 91μs |
| ec3.3xlarge.r1  | 12核 | 12G  | 5Gbps    | 400万         | 91μs |
| ec3.4xlarge.r1  | 16核 | 16G  | 6Gbps    | 400万         | 91μs |
| ec3.8xlarge.r1  | 32核 | 32G  | 13Gbps   | 400万         | 91μs |
| ec3.large.r2    | 2核  | 4G   | 2Gbps    | 100万         | 91μs |
| ec3.xlarge.r2   | 4核  | 8G   | 2.5Gbps  | 200万         | 91μs |
| ec3.2xlarge.r2  | 8核  | 16G  | 3.5Gbps  | 400万         | 91μs |
| ec3.3xlarge.r2  | 12核 | 24G  | 5Gbps    | 400万         | 91μs |
| ec3.4xlarge.r2  | 16核 | 32G  | 6Gbps    | 400万         | 91μs |
| ec3.6xlarge.r2  | 24核 | 48G  | 9Gbps    | 400万         | 91μs |
| ec3.8xlarge.r2  | 32核 | 64G  | 13Gbps   | 400万         | 91μs |
| ec3.16xlarge.r2 | 64核 | 128G | 25Gbps   | 400万         | 91μs |

## 通用型 EG3

采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比性能大幅提升，独享 CPU 模式，适合大多数企业应用场景，尤其适合对计算与网络有更高性能要求的网站和Web服务器、企业级应用、中小型数据库及缓存服务器等。

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:4
- 支持 VPC 私有网络和基础网络
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持32Gbps内网带宽，PPS最高400万
- 超低延时，低至91μs
- I/O优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

通用型 EG3 包括的实例规格和性能指标如下：

| 实例规格        | vCPU  | 内存 | 内网带宽 | 内网收发包PPS | 延时 |
| --------------- | ----- | ---- | -------- | ------------- | ---- |
| eg3.large.r4    | 2核   | 8G   | 2Gbps    | 100万         | 91μs |
| eg3.xlarge.r4   | 4核   | 16G  | 2.5Gbps  | 200万         | 91μs |
| eg3.2xlarge.r4  | 8核   | 32G  | 3.5Gbps  | 400万         | 91μs |
| eg3.3xlarge.r4  | 12核  | 48G  | 5Gbps    | 400万         | 91μs |
| eg3.4xlarge.r4  | 16核  | 64G  | 6Gbps    | 400万         | 91μs |
| eg3.6xlarge.r4  | 24核  | 96G  | 9Gbps    | 400万         | 91μs |
| eg3.8xlarge.r4  | 32核  | 128G | 13Gbps   | 400万         | 91μs |
| eg3.16xlarge.r4 | 64核  | 256G | 25Gbps   | 400万         | 91μs |
| eg3.24xlarge.r4 | 96核  | 384G | 30Gbps   | 400万         | 91μs |
| eg3.30xlarge.r4 | 120核 | 480G | 32Gbps   | 400万         | 91μs |

## 内存型 ER3

采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比性能大幅提升，独享 CPU 模式，为处理内存中的大型数据集的工作负载交付快速、稳定的性能，适用于高网络包收发、高性能数据库、大数据分析与挖掘、分布式内存缓存、Hadoop和Spark集群搭建等高内存场景。

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:8
- 支持 VPC 私有网络和基础网络
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持12Gbps内网带宽，PPS最高400万
- 超低延时，低至91μs
- I/O优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

内存型 ER3 包括的实例规格和性能指标如下：

| 实例规格       | vCPU | 内存 | 内网带宽 | 内网收发包PPS | 延时 |
| -------------- | ---- | ---- | -------- | ------------- | ---- |
| er3.large.r8   | 2核  | 16G  | 2Gbps    | 100万         | 91μs |
| er3.xlarge.r8  | 4核  | 32G  | 2.5Gbps  | 200万         | 91μs |
| er3.2xlarge.r8 | 8核  | 64G  | 3.5Gbps  | 400万         | 91μs |
| er3.3xlarge.r8 | 12核 | 96G  | 5Gbps    | 400万         | 91μs |
| er3.4xlarge.r8 | 16核 | 128G | 6Gbps    | 400万         | 91μs |
| er3.6xlarge.r8 | 24核 | 192G | 9Gbps    | 400万         | 91μs |
| er3.8xlarge.r8 | 32核 | 256G | 13Gbps   | 400万         | 91μs |

## 网络增强计算型 EC3NE

独享 CPU 模式，采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比综合性能大幅提升，网络优化实例，尤其适合网络包收发场景如NFV/SD-WAN、直播、游戏等，和数据分析、批量计算、视频编码等计算密集型应用程序

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:1/1:2
- 支持 VPC 私有网络和基础网络
- 网络性能大幅提升，延时低至25μs，内网收发包最高2400万
- 支持DPDK与RDMA
- I/O性能优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

备注：

如果物理服务器遭遇偶然硬件故障，会自动将云服务器关机后迁移到正常物理服务器上，此过程持续几秒，涉及开机、关机操作。

网络增强计算型 EC3NE 包括的实例规格和性能指标如下：

| 实例规格         | vCPU | 内存 | 内网带宽 | 内网收发包PPS | 延时 |
| ---------------- | ---- | ---- | -------- | ------------- | ---- |
| ec3ne.xlarge.r1  | 4核  | 4G   | 2.5Gbps  | 200万         | 25μs |
| ec3ne.2xlarge.r1 | 8核  | 8G   | 3.5Gbps  | 400万         | 25μs |
| ec3ne.3xlarge.r1 | 12核 | 12G  | 5Gbps    | 600万         | 25μs |
| ec3ne.4xlarge.r1 | 16核 | 16G  | 6Gbps    | 800万         | 25μs |
| ec3ne.8xlarge.r1 | 32核 | 32G  | 13Gbps   | 200万         | 25μs |
| ec3ne.large.r2   | 2核  | 4G   | 2Gbps    | 100万         | 25μs |
| ec3ne.xlarge.r2  | 4核  | 8G   | 2.5Gbps  | 200万         | 25μs |
| ec3ne.2xlarge.r2 | 8核  | 16G  | 3.5Gbps  | 400万         | 25μs |
| ec3ne.3xlarge.r2 | 12核 | 24G  | 5Gbps    | 600万         | 25μs |
| ec3ne.4xlarge.r2 | 16核 | 32G  | 6Gbps    | 800万         | 25μs |
| ec3ne.6xlarge.r2 | 24核 | 48G  | 9Gbps    | 1200万        | 25μs |
| ec3ne.8xlarge.r2 | 32核 | 64G  | 13Gbps   | 2400万        | 25μs |

## 网络增强通用型 EG3NE 

独享 CPU 模式，采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比综合性能大幅提升，网络优化实例，尤其适合网络包收发场景如NFV/SD-WAN、直播、游戏等，和企业网站和Web服务器、企业级应用、中小型数据库及缓存服务器等。

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:4
- 支持 VPC 私有网络和基础网络
- 网络性能大幅提升，延时低至25μs，内网收发包最高2400万
- 支持DPDK与RDMA
- I/O性能优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

备注：如果物理服务器遭遇偶然硬件故障，会自动将云服务器关机后迁移到正常物理服务器上，此过程持续几秒，涉及开机、关机操作。

网络增强通用型 EG3NE 包括的实例规格和性能指标如下：

| 实例规格          | vCPU  | 内存 | 内网带宽 | 内网收发包PPS | 延时 |
| ----------------- | ----- | ---- | -------- | ------------- | ---- |
| eg3ne.large.r4    | 2核   | 8G   | 2Gbps    | 100万         | 25μs |
| eg3ne.xlarge.r4   | 4核   | 16G  | 2.5Gbps  | 200万         | 25μs |
| eg3ne.2xlarge.r4  | 8核   | 32G  | 3.5Gbps  | 400万         | 25μs |
| eg3ne.3xlarge.r4  | 12核  | 48G  | 5Gbps    | 600万         | 25μs |
| eg3ne.4xlarge.r4  | 16核  | 64G  | 6Gbps    | 800万         | 25μs |
| eg3ne.6xlarge.r4  | 24核  | 96G  | 9Gbps    | 1200万        | 25μs |
| eg3ne.8xlarge.r4  | 32核  | 128G | 13Gbps   | 2400万        | 25μs |
| eg3ne.16xlarge.r4 | 64核  | 256G | 25Gbps   | 2400万        | 25μs |
| eg3ne.24xlarge.r4 | 96核  | 384G | 30Gbps   | 2400万        | 25μs |
| eg3ne.30xlarge.r4 | 120核 | 480G | 32Gbps   | 2400万        | 25μs |

## 网络增强内存型 ER3NE 

独享 CPU 模式，采用第三代英特尔®至强®可扩展处理器（Ice Lake），和上一代相比综合性能大幅提升，网络优化实例，尤其适合网络包收发场景如NFV/SD-WAN、直播、游戏等，和缓存及大数据分析等高内存需求场景。

特点：

- 第三代英特尔®至强®可扩展处理器（Ice Lake），主频：2.6GHz，睿频：3.4GHz
- 处理器内存配比1:8
- 支持 VPC 私有网络和基础网络
- 网络性能大幅提升，延时低至25μs，内网收发包最高2400万
- 支持DPDK与RDMA
- I/O优化，最高iops达100k
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

备注：如果物理服务器遭遇偶然硬件故障，会自动将云服务器关机后迁移到正常物理服务器上，此过程持续几秒，涉及开机、关机操作。

网络增强内存型 ER3NE 包括的实例规格和性能指标如下：

| 实例规格         | vCPU | 内存 | 内网带宽 | 内网收发包PPS | 延时（μs） |
| ---------------- | ---- | ---- | -------- | ------------- | ---------- |
| er3ne.large.r8   | 2核  | 16G  | 2Gbps    | 100万         | 25μs       |
| er3ne.xlarge.r8  | 4核  | 32G  | 2.5Gbps  | 200万         | 25μs       |
| er3ne.2xlarge.r8 | 8核  | 64G  | 3.5Gbps  | 400万         | 25μs       |
| er3ne.3xlarge.r8 | 12核 | 96G  | 5Gbps    | 600万         | 25μs       |
| er3ne.4xlarge.r8 | 16核 | 128G | 6Gbps    | 800万         | 25μs       |
| er3ne.6xlarge.r8 | 24核 | 192G | 9Gbps    | 1200万        | 25μs       |
| er3ne.8xlarge.r8 | 32核 | 256G | 13Gbps   | 2400万        | 25μs       |

## 通用型 E2 

采用第二代英特尔®至强®金牌 6240 处理器，独享 CPU 模式，平衡、稳定的计算、内存和网络资源，适合大多数企业应用场景，尤其适合对计算与网络有性能要求的网站和Web服务器、企业级应用、中小型数据库及缓存服务器等。

特点：

- 第二代英特尔®至强®金牌6240处理器，主频：2.6GHz，睿频最高可达3.9GHz
- 配有全新的 Intel Advanced Vector Extension (AVX-512) 指令集，在深度学习的多种场景性能提升4倍
- 处理器内存配比1:4
- I/O优化
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持12Gbps内网带宽
- 支持 VPC 私有网络和基础网络
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

通用型 E2 包括的实例规格和性能指标如下：

| 实例规格      | vCPU | 内存 | 内网带宽 |
| ------------- | ---- | ---- | -------- |
| e2.large.r4   | 2核  | 8G   | 1.5 Gbps |
| e2.xlarge.r4  | 4核  | 16G  | 2 Gbps   |
| e2.2xlarge.r4 | 8核  | 32G  | 3 Gbps   |
| e2.3xlarge.r4 | 12核 | 48G  | 4.5 Gbps |
| e2.4xlarge.r4 | 16核 | 64G  | 5.5 Gbps |
| e2.6xlarge.r4 | 24核 | 96G  | 8 Gbps   |
| e2.8xlarge.r4 | 32核 | 128G | 12 Gbps  |

## 内存型 E2

采用第二代英特尔®至强®金牌 6240 处理器，独享 CPU 模式，为处理内存中的大型数据集的工作负载交付快速、稳定的性能，适用于高性能数据库、大数据分析与挖掘、分布式内存缓存、Hadoop和Spark集群搭建等高内存场景。

特点：

- 第二代英特尔®至强®金牌6240处理器，主频：2.6GHz，睿频最高可达3.9GHz
- 配有全新的 Intel Advanced Vector Extension (AVX-512) 指令集，在深度学习的多种场景性能提升4倍
- 处理器内存配比1:8
- I/O优化
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持12Gbps内网带宽
- 支持 VPC 私有网络和基础网络
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

内存型 E2 包括的实例规格和性能指标如下：

| 实例规格      | vCPU | 内存 | 内网带宽 |
| ------------- | ---- | ---- | -------- |
| e2.large.r8   | 2核  | 16G  | 1.5 Gbps |
| e2.xlarge.r8  | 4核  | 32G  | 2 Gbps   |
| e2.2xlarge.r8 | 8核  | 64G  | 3 Gbps   |
| e2.3xlarge.r8 | 12核 | 96G  | 4.5 Gbps |
| e2.4xlarge.r8 | 16核 | 128G | 5.5 Gbps |
| e2.6xlarge.r8 | 24核 | 192G | 8 Gbps   |
| e2.8xlarge.r8 | 32核 | 256G | 12 Gbps  |

## 计算型 E2 

采用第二代英特尔®至强®金牌 6240 处理器，独享 CPU 模式，适用于计算密集型应用程序，例如高性能计算、科学建模、专用游戏服务器和广告服务器引擎等。

特点：

- 第二代英特尔®至强®金牌6240处理器，主频：2.6GHz，睿频最高可达3.9GHz
- 配有全新的 Intel Advanced Vector Extension (AVX-512) 指令集，在深度学习的多种场景性能提升4倍
- 处理器内存配比1:1/1:2
- I/O优化
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持12Gbps内网带宽
- 支持 VPC 私有网络和基础网络
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN

计算型 E2 包括的实例规格和性能指标如下：

| 实例规格      | vCPU | 内存 | 内网带宽 |
| ------------- | ---- | ---- | -------- |
| e2.large.r2   | 2核  | 4G   | 1.5 Gbps |
| e2.xlarge.r2  | 4核  | 8G   | 2 Gbps   |
| e2.2xlarge.r2 | 8核  | 16G  | 3 Gbps   |
| e2.3xlarge.r2 | 12核 | 24G  | 4.5 Gbps |
| e2.4xlarge.r2 | 16核 | 32G  | 5.5 Gbps |
| e2.6xlarge.r2 | 24核 | 48G  | 8 Gbps   |
| e2.8xlarge.r2 | 32核 | 64G  | 12 Gbps  |
| e2.xlarge.r1  | 4核  | 4G   | 2 Gbps   |
| e2.2xlarge.r1 | 8核  | 8G   | 3 Gbps   |
| e2.3xlarge.r1 | 12核 | 12G  | 4.5 Gbps |
| e2.4xlarge.r1 | 16核 | 16G  | 5.5 Gbps |

## 专业增强型 P1 

 vCPU 独享型云服务器，可为用户提供更高的计算性能、更大的内存带宽与稳定性，满足企业用户对 CPU 主频及网络吞吐性能有极高要求，且需要独享 vCPU 资源的应用系统，特别适用于企业核心数据库、线上关键业务等应用场景。

特点：

- 采用英特尔®至强®Platinum 8168 CPU @ 2.70GHz 高主频处理器 ，并支持英特尔睿频加速技术，最高可达 3.7GHz 主频；
- 支持1:1、1:2、1:4、1:8多种处理器内存配比
- 基于 QingCloud 优化的 SSD Hyper 全闪存存储架构；
- I/O优化
- 网络性能与规格对应，规格越高网络转发性能强，最高可支持25Gbps内网带宽
- 支持 VPC 私有网络和基础网络
- 系统盘支持企业级SSD硬盘，数据盘支持企业级SSD硬盘、容量型和企业级分布式 SAN
- 支持 VPC 私有网络和基础网络

专业增强型 P1 包括的实例规格和性能指标如下：

| 实例类型       | CPU  | 内存 | 内网带宽 |
| -------------- | ---- | ---- | -------- |
| p1.large.r2    | 2核  | 4G   | 1.5 Gbps |
| p1.large.r4    | 2核  | 8G   | 1.5 Gbps |
| p1.large.r8    | 2核  | 16G  | 1.5 Gbps |
| p1.xlarge.r1   | 4核  | 4G   | 2 Gbps   |
| p1.xlarge.r2   | 4核  | 8G   | 2 Gbps   |
| p1.xlarge.r4   | 4核  | 16G  | 2 Gbps   |
| p1.xlarge.r8   | 4核  | 32G  | 2 Gbps   |
| p1.2xlarge.r1  | 8核  | 8G   | 3 Gbps   |
| p1.2xlarge.r2  | 8核  | 16G  | 3 Gbps   |
| p1.2xlarge.r4  | 8核  | 32G  | 3 Gbps   |
| p1.2xlarge.r8  | 8核  | 64G  | 3 Gbps   |
| p1.3xlarge.r1  | 12核 | 12G  | 4.5 Gbps |
| p1.3xlarge.r2  | 12核 | 24G  | 4.5 Gbps |
| p1.3xlarge.r4  | 12核 | 48G  | 4.5 Gbps |
| p1.3xlarge.r8  | 12核 | 96G  | 4.5 Gbps |
| p1.4xlarge.r1  | 16核 | 16G  | 5.5 Gbps |
| p1.4xlarge.r2  | 16核 | 32G  | 5.5 Gbps |
| p1.4xlarge.r4  | 16核 | 64G  | 5.5 Gbps |
| p1.4xlarge.r8  | 16核 | 128G | 5.5 Gbps |
| p1.6xlarge.r2  | 24核 | 48G  | 8 Gbps   |
| p1.6xlarge.r4  | 24核 | 96G  | 8 Gbps   |
| p1.6xlarge.r8  | 24核 | 192G | 8 Gbps   |
| p1.8xlarge.r2  | 32核 | 64G  | 12 Gbps  |
| p1.8xlarge.r4  | 32核 | 128G | 12 Gbps  |
| p1.8xlarge.r8  | 32核 | 256G | 12 Gbps  |
| p1.16xlarge.r4 | 64核 | 256G | 25 Gbps  |

