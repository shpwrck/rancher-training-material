---
voice: Jeff
theme: light
transition: pixelize
background: dreams.mp3 0.05
size: 2560x1440
---

(pause: 2)

```
Rancher Continuous Integration
(Fleet)
```

![](background.png)

<!-- Start Script -->
Rancher includes a continuous deivery tool called Fleet that helps manage Kubernetes resources at scale with git ops.
Put simply, fleet allows you to maintain your clusters and cluster resources by watching the contents of a git repository.
<!-- End Script -->

---

```
Git Repo Components:

* URL & Branch Name
* One or Many Paths
* Selection Criteria
```

![](background.png)

<!-- Start Script -->
A basic fleet git repo definition consists of three main components.
A URL and a branch name to identify the repository.
A set of paths within the given repository that define what resources to track.
And selection criteria that determines what clusters will receive the defined resources.
<!-- End Script --> 

---

(video:
  file: fleet.mp4
  segment: 00:05 - 01:34
  sync: freeze)

<!-- Start Script -->
In this example, we first create a cluster group to identify which clusters are running in a cloud environment.
We then proceed to create a git repository using the example repository and specify the group we just created as the destination.
Once the git repo resource has been created, we can see that the resources are being deployed to a member of the cloud group.
<!-- End Script -->

---

```
Fleet can manage any Kubernetes resource!
```

![](background.png)

<!-- Start Script -->
The previous example was just a taste of what Fleet can accomplish. Many users leverage fleet to manage operational workloads as well as consumer workloads. Try Fleet in your own environment and see how it simplifies operations at scale.
<!-- End Script -->

(pause: 2)

---
