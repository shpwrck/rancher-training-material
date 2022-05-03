---
voice: Jeff
theme: light
transition: pixelize
background: dreams.mp3 0.05
---

(pause: 2)

```
Rancher Cluster Provisioning
```

![](background.png)

<!-- Start Script -->
Rancher allows you to create and import clusters.
<!-- End Script -->

---

(video:
  file: imported-cluster.mp4
  segment: 00:06 - 00:26
  sync: freeze)

<!-- Start Script -->
Importing a cluster is the process of installing an agent on a cncf certified distribution of kubernetes.
This mode allows you to apply role based access policy and fleet workloads to the imported cluster.
<!-- End Script -->

---

(video:
  file: custom-cluster.mp4
  segment: 00:06 - 00:48
  sync: freeze)

<!-- Start Script -->
If you do not have a cluster already but you do have servers, then you can create a fully customizeable RKE, RKE2, or K3S cluster whose lifecycle can be managed through Rancher.
<!-- End Script -->

---

(video:
  file: node-driver-cluster.mp4
  segment: 00:06 - 00:37
  sync: freeze)

<!-- Start Script -->
If instead you want Rancher to provision both the infrastructure and the kubernetes components, then you can use the node driver option.
The node driver option supports multiple hypervisors both in the cloud and on premise. 
<!-- End Script -->

---

(video:
  file: operator-cluster.mp4
  segment: 00:06 - 00:48
  sync: freeze)

<!-- Start Script -->
Finally, if you'd like take advantage of the managed kubernetes offerings of AWS, Azure, or GCP, then you can use operator based provisioning.
With this mode Rancher will declaratively maintain the state of EKS, AKS, or GKE.
<!-- End Script -->

---

```
Try provisioning a cluster!
```

![](background.png)

<!-- Start Script -->
These four methods allow for many diverse circumstances. Most organizations run through many of these modes throughout their kubernetes journey and Rancher can help lighten the provisioning burden at each step in the process.
<!-- End Script -->

(pause: 2)

---
