---
name: hub-mirror issue template
about: 用于执行 hub-mirror workflow 的 issue 模板
title: "[hub-mirror] 请求执行任务"
labels: ["hub-mirror"]
---

{
    "platform":"",
    "hub-mirror": [
        "platform默认为linux/amd64，需要ARM架构请改为arm64或linux/arm64/v8",
        "格式：镜像:版本（$自定义镜像名:自定义标签名）可选",
        "registry.k8s.io/kube-apiserver:v1.27.4$my-kube-apiserver"
    ]
}
