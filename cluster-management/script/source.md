---
voice: Jeff
theme: light
transition: pixelize
background: dreams.mp3 0.05
size: 2560x1440
---

(pause: 2)

```
Rancher Cluster Management
```

![](background.png)

<!-- Start Script --> 
Rancher provides a graphical user interface to assist in cluster management tasks.
The following videos present some basic tasks that can be done through the `UI`.
<!-- End Script -->

---

(video:
  file: dashboard.mp4
  segment: 00:06 - 00:15
  sync: freeze)

<!-- Start Script -->
The Rancher `UI` presents basic information for every cluster such as Pod, Core, and Memory Usage. You can also see the stream of events displayed on screen.
<!-- End Script -->

---

(video:
  file: workload-create.mp4
  segment: 00:06 - 01:10
  sync: freeze)

<!-- Start Script -->
Through Rancher you can create a workload such as a deployment through the UI. Instead of learning each resource's specification, the Rancher `UI` presents an easy to use and organized user experience. This example is a basic nginx workload with a service exposing port 80.
<!-- End Script -->

---

(video:
  file: workload-edit.mp4
  segment: 00:06 - 00:44
  sync: freeze)

<!-- Start Script -->
You can also modify existing workloads or workloads generated by sources other than Rancher. This example shows a port and volume edit.
<!-- End Script -->

---

(video:
  file: workload-delete.mp4
  segment: 00:06 - 00:26
  sync: freeze)

<!-- Start Script -->
And finally, we can see that Rancher handles the full lifecycle when it deletes a given workload.
<!-- End Script -->

---

(video:
  file: interact.mp4
  segment: 00:06 - 00:30
  sync: freeze)

<!-- Start Script -->
But you aren't limited to the `UI`. You can upload resources in their original YAML, interact with the included shell environment, or download the cluster configuration file to interact in a terminal of your choosing.
<!-- End Script -->

---

```
Explore the UI!
```

![](background.png)

<!-- Start Script -->
These examples are by no means exhaustive. Explore the `UI` and discover new ways to interact with your clusters.
<!-- End Script -->

(pause: 2)

---
