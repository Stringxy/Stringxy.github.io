---
title: VirtualBox搭建Ubuntu-Kubernetes集群
date: 2025-02-08 10:33:24
tags: [VirtualBox,Ubuntu,Kubernetes]
categories: [云原生运维]
summary: Windows11下VirtualBox搭建Ubuntu22.04-Kubernetes1.27集群
---
# VirtualBox搭建Ubuntu-Kubernetes集群

## 准备工作
Windows11下VirtualBox搭建Ubuntu
##环境说明
1.硬件环境
虚拟机硬件规格：2CPU 40GB
虚拟机数量： 3台
虚拟机操作系统：ubuntu-22.04.3-live-server-amd64.iso

操作系统	主机名	IP
ubuntu-22.04.3	k8s-master	10.0.0.150
ubuntu-22.04.3	k8s-node1	10.0.0.151
ubuntu-22.04.3	k8s-node2	10.0.0.152