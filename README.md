# k8s-yaml-examples

This repository contains various K8s yaml examples across several use cases.

### **NOTE: Open For Contribution**

### Purpose

1. Quick and ready to use K8s yaml examples during development and testing. 
2. Reference to create your own custom K8s yaml files.


### Few Files Description
**Kube-state-metrics.yaml**: It covers ClusterRole, ClusterRoleBinding, Role, 
RoleBinding, ServiceAccount, Service and Deployment K8s Objects.

**pod-pvc.yaml**: It covers PersistentVolume, PersistentVolumeClaim and Pod 
K8s objects.

**deployment-pvc.yaml**: It covers PersistentVolume, PersistentVolumeClaim, S
ervice and Deployment K8s objects.

**statefulset-pvc.yaml**: It covers PersistentVolume, PersistentVolumeClaim, 
Service and StatefulSet K8s objects.

**pod-configmap.yaml**: It covers ConfigMap and Pod K8s objects. 
Configmap as Env or as VolumeMount both are covered.

**pod-secret.yaml**: It covers Secret and Pod K8s objects.
Secret as Env or as VolumeMount both are covered.

**pod-oom-killed.yaml**: Yaml file to simulate OOM Killed event for Pod.
