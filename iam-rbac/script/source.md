---
voice: Jeff
theme: light
transition: pixelize
background: dreams.mp3 0.05
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
  segment: 00:05 - 01:40
  sync: freeze)

<!-- Start Script -->
Rancher supports connecting identity providers using L-DAP, O-AUTH, OIDC, or SAML.
After passing in the proper configuration Rancher and the attached clusters will have access to the relevant users and groups.
You can modify permissions for users and groups with a number of built in roles or by creating your own custom roles at the Global, Cluster, or Project scope. Rancher leverages standard kubernetes policy using verbs, resources, and api groups.
The best of this integration is that it is enforced at every interface, `UI` or `API`.
<!-- End Script -->

---

```
Get familiar with IAM/RBAC!
```

![](background.png)

<!-- Start Script -->
Tray creating a few local users through the UI and discover how powerful role based access control can be!
<!-- End Script -->

(pause: 2)

---
