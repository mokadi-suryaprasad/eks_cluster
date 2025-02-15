# eks_cluster

## Kubernetes Kubeconfig Commands

This document provides useful `kubectl` commands to manage Kubernetes configurations.

### View the Entire Kubeconfig File

```bash
kubectl config view
```

### Check Current Kubernetes Context
To see which Kubernetes context is currently active, run:

```bash
kubectl config current-context
```

### AWS EKS Configuration Guide

This guide explains how to configure `kubectl` to connect with an **AWS EKS cluster**.

### Update Kubeconfig for EKS
To connect your local `kubectl` to an **EKS cluster**, run the following command:

```bash
aws eks update-kubeconfig --region us-east-1 --name my-eks-cluster
```


