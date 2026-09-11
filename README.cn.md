# cluster-api-provider-aws

[English version](./README.md)

Kubernetes Cluster API Provider AWS provides consistent deployment and day 2 operations of "self-managed" and EKS Kubernetes clusters on AWS.

![cluster-api-provider-aws](https://repo.x-cmd.io/cluster-api-provider-aws.svg?lang=zh)

## 安装

```sh
x install cluster-api-provider-aws
```

## 代码洞察

合计: **261,858** 行代码（覆盖前 5 种语言、共 **1005** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 145,958 | 24,089 | 19,606 | 675 |
| Yaml | 112,500 | 633 | 402 | 297 |
| Sh | 866 | 578 | 262 | 26 |
| Makefile | 761 | 140 | 227 | 6 |
| Css | 472 | 43 | 73 | 1 |

## OpenSSF Scorecard 评分

总评分: **6.6 / 10**

评分最低的几项:

- **Packaging** (-1/10) — packaging workflow not detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Fuzzing** (0/10) — project is not fuzzed

## 源代码

- **上游仓库**: <https://github.com/kubernetes-sigs/cluster-api-provider-aws>
- **官网**: <http://cluster-api-aws.sigs.k8s.io/>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v2.13.0` (2026-07-29)
- **最近提交**: 2026-09-09
- **Release 含资产**: 42 个

## 流行度

- **Star**: 728 · **Fork**: 705 · **开放 issue**: 1,872 · **贡献者**: 673

## 累计统计

- **发布数**: 102 · **已合并 PR**: 3264 · **开放 PR**: 52 · **已关闭 issue**: 1703 · **开放 issue**: 169 · **提交数**: 5828

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 21 | 20 | 0 | 4 | 14 |
| last60d | 2026-07-13 | 1 | 58 | 25 | 4 | 8 | 56 |
| 90d | 2026-06-13 | 2 | 92 | 28 | 11 | 26 | 87 |
| last180d | 2026-03-15 | 5 | 180 | 37 | 20 | 35 | 177 |
| 360d | 2025-09-16 | 10 | 295 | 49 | 49 | 44 | 301 |
| last720d | 2024-09-21 | 18 | 563 | 50 | 143 | 67 | 1025 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [AWSIAMManagedPolicyCloudProviderControlPlane.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyCloudProviderControlPlane.json) | 3.2 KiB | `other` |
| [AWSIAMManagedPolicyCloudProviderNodes.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyCloudProviderNodes.json) | 1.7 KiB | `other` |
| [AWSIAMManagedPolicyControllers.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllers.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithEKS.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllersWithEKS.json) | 7.9 KiB | `other` |
| [AWSIAMManagedPolicyControllersWithS3.json](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/AWSIAMManagedPolicyControllersWithS3.json) | 8.3 KiB | `other` |
| [CHANGELOG.md](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/CHANGELOG.md) | 248 B | `other` |
| [cluster-api-provider-aws_2.13.0_checksums.txt](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-api-provider-aws_2.13.0_checksums.txt) | 1.1 KiB | `other` |
| [cluster-template-dualstack-ipv4-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-dualstack-ipv4-primary.yaml) | 27.8 KiB | `other` |
| [cluster-template-dualstack-ipv6-primary.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-dualstack-ipv6-primary.yaml) | 28.7 KiB | `other` |
| [cluster-template-eks-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-clusterclass.yaml) | 1.9 KiB | `other` |
| [cluster-template-eks-fargate.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-fargate.yaml) | 1007 B | `other` |
| [cluster-template-eks-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-ipv6.yaml) | 2.4 KiB | `other` |
| [cluster-template-eks-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-machinepool.yaml) | 1.8 KiB | `other` |
| [cluster-template-eks-managedmachinepool-gpu.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool-gpu.yaml) | 4.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool-vpccni.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool-vpccni.yaml) | 1.7 KiB | `other` |
| [cluster-template-eks-managedmachinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks-managedmachinepool.yaml) | 1.6 KiB | `other` |
| [cluster-template-eks.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-eks.yaml) | 1.9 KiB | `other` |
| [cluster-template-flatcar-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-flatcar-machinepool.yaml) | 28.3 KiB | `other` |
| [cluster-template-flatcar.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-flatcar.yaml) | 28.0 KiB | `other` |
| [cluster-template-ipv6.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-ipv6.yaml) | 28.7 KiB | `other` |
| [cluster-template-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-machinepool.yaml) | 26.2 KiB | `other` |
| [cluster-template-multitenancy-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-multitenancy-clusterclass.yaml) | 8.1 KiB | `other` |
| [cluster-template-rosa-machinepool.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa-machinepool.yaml) | 2.9 KiB | `other` |
| [cluster-template-rosa-role-config.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa-role-config.yaml) | 1.4 KiB | `other` |
| [cluster-template-rosa.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-rosa.yaml) | 2.3 KiB | `other` |
| [cluster-template-simple-clusterclass.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template-simple-clusterclass.yaml) | 6.5 KiB | `other` |
| [cluster-template.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/cluster-template.yaml) | 25.8 KiB | `other` |
| [clusterawsadm-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-darwin-amd64) | 91.9 MiB | `native/darwin/x64` |
| [clusterawsadm-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-darwin-arm64) | 82.7 MiB | `native/darwin/arm64` |
| [clusterawsadm-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterawsadm-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-linux-arm64) | 79.6 MiB | `native/linux/arm64` |
| [clusterawsadm-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterawsadm-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterawsadm-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [clusterctl-aws-darwin-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-darwin-amd64) | 91.9 MiB | `native/darwin/x64` |
| [clusterctl-aws-darwin-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-darwin-arm64) | 82.7 MiB | `native/darwin/arm64` |
| [clusterctl-aws-linux-amd64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-linux-amd64) | 89.4 MiB | `native/linux/x64` |
| [clusterctl-aws-linux-arm64](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-linux-arm64) | 79.6 MiB | `native/linux/arm64` |
| [clusterctl-aws-windows-amd64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-windows-amd64.exe) | 91.2 MiB | `native/win/x64` |
| [clusterctl-aws-windows-arm64.exe](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/clusterctl-aws-windows-arm64.exe) | 80.6 MiB | `native/win/arm64` |
| [infrastructure-components.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/infrastructure-components.yaml) | 1.2 MiB | `other` |
| [metadata.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/metadata.yaml) | 1.4 KiB | `other` |
| [rosa-network.yaml](https://github.com/kubernetes-sigs/cluster-api-provider-aws/releases/download/v2.13.0/rosa-network.yaml) | 336 B | `other` |

## 改进这些数据

cluster-api-provider-aws 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `cluster-api-provider-aws` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/cluster-api-provider-aws.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T00:10:26Z._
