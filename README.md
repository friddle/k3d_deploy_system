# k3d_deploy_system

**简单 k3d 部署系统** · native package `com.github.friddle.k3d_deploy_system`

## 职责
基于 **k3d**（docker 里的 k3s）做部署/发布：起集群、应用 manifest、canary-check。
作为 `stand_release_system` 的轻量替代/演示，对接 `core_developer_system` 产出的镜像。

## 状态
占位骨架（MVP）。`description.yaml` 已可被 `native install` 解析安装。
后续填充：init/usage/maintenance 模板 + k3d 部署 skill（k3d cluster create / kubectl apply）。
设计见 [agent_developer_platform](https://github.com/friddle/agent_developer_platform)。
