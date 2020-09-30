# Patching a TKG (guest cluster) in vSphere7 with Tanzu (Kubernetes) 

* This is an exampe of patching a Tanzu Kubernetes Grid (TKG / guest cluster) in vSphere 7 with Tanzu

* Create a TKG (version 1.68)

```
kubectl apply -f https://github.com/ogelbric/YAML/raw/master/TKG1001GA-3m-3w-1168.yaml
kubectl get tanzukubernetesclusters  

```

* Progress 

![GitHub](ClusterCreationTage.png)

* Result

![GitHub](ClusterRunningStage.png)

