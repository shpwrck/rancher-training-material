---
voice: Jeff
theme: light
transition: pixelize
background: dreams.mp3 0.05
size: 2560x1440
---

(pause: 2)

```
Rancher Identity and Access Management
```

![](background.png)

<!-- Start Script -->
One of the major benefits of running Rancher is centralized identity and access management for all of your kubernetes clusters.
<!-- End Script -->

---

(video:
  file: iam-rbac.mp4
  segment: 00:05 - 00:31
  sync: freeze)

<!-- Start Script -->
Rancher supports connecting identity providers using L-DAP, O-AUTH, OIDC, or SAM-L.
After passing in the proper configuration Rancher and the attached clusters will have access to the relevant users and groups.
<!-- End Script -->

---

(video:
  file: iam-rbac.mp4
  segment: 00:31 - 00:57
  sync: freeze)

<!-- Start Script -->
You can modify permissions for users and groups with a number of built in roles or by creating your own custom roles at the Global, Cluster, or Project scope.
This is an example of downgrading a user to the "User Base" role and allowing them access to manage users.
<!-- End Script -->

---

(video:
  file: iam-rbac.mp4
  segment: 00:57 - 01:40
  sync: freeze)

<!-- Start Script -->
Rancher leverages standard kubernetes policy using verbs, resources, and api groups.
Here we are creating then deleting an example role that can delete configmaps.
This role and any other will be enforced at every level, `UI`, `API`, or `CLI`.
<!-- End Script -->

---

```
Get familiar with IAM/RBAC!
```

![](background.png)

<!-- Start Script -->
Try creating a few local users through the UI and discover how powerful role based access control can be!
<!-- End Script -->

(pause: 2)

---
