# Graph Report - .  (2026-06-22)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 107 nodes · 136 edges · 34 communities (11 shown, 23 thin omitted)
- Extraction: 88% EXTRACTED · 12% INFERRED · 0% AMBIGUOUS · INFERRED: 17 edges (avg confidence: 0.83)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `440748e2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Kubernetes Cluster Setup|Kubernetes Cluster Setup]]
- [[_COMMUNITY_Docker Fundamentals|Docker Fundamentals]]
- [[_COMMUNITY_Kubernetes Core Concepts|Kubernetes Core Concepts]]
- [[_COMMUNITY_CKA Course Content|CKA Course Content]]
- [[_COMMUNITY_Kind Cluster Setup|Kind Cluster Setup]]
- [[_COMMUNITY_Kubernetes Auth and RBAC|Kubernetes Auth and RBAC]]
- [[_COMMUNITY_Ingress Configuration|Ingress Configuration]]
- [[_COMMUNITY_CKA Exam Prep|CKA Exam Prep]]
- [[_COMMUNITY_Kubernetes Services|Kubernetes Services]]
- [[_COMMUNITY_Autoscaling and Metrics|Autoscaling and Metrics]]
- [[_COMMUNITY_Why Kubernetes|Why Kubernetes]]
- [[_COMMUNITY_Kubernetes Architecture|Kubernetes Architecture]]
- [[_COMMUNITY_NodePort Service|NodePort Service]]
- [[_COMMUNITY_Taints and Node Affinity|Taints and Node Affinity]]
- [[_COMMUNITY_RBAC Tasks|RBAC Tasks]]
- [[_COMMUNITY_Problem 1 Script|Problem 1 Script]]
- [[_COMMUNITY_Problem 2 Script|Problem 2 Script]]
- [[_COMMUNITY_Multi-Container Pod Task|Multi-Container Pod Task]]
- [[_COMMUNITY_DaemonSet CronJob Task|DaemonSet CronJob Task]]
- [[_COMMUNITY_Static Pods Task|Static Pods Task]]
- [[_COMMUNITY_Taints Tolerations Task|Taints Tolerations Task]]
- [[_COMMUNITY_Node Affinity Task|Node Affinity Task]]
- [[_COMMUNITY_Autoscaling Task|Autoscaling Task]]
- [[_COMMUNITY_Health Probes Task|Health Probes Task]]
- [[_COMMUNITY_ConfigMaps Secrets Task|ConfigMaps Secrets Task]]
- [[_COMMUNITY_TLS Task|TLS Task]]
- [[_COMMUNITY_ClusterRole Binding Task|ClusterRole Binding Task]]
- [[_COMMUNITY_Service Account Task|Service Account Task]]
- [[_COMMUNITY_Docker Volumes Task|Docker Volumes Task]]
- [[_COMMUNITY_DNS Task|DNS Task]]
- [[_COMMUNITY_CNI Networking Task|CNI Networking Task]]
- [[_COMMUNITY_Flask App Requirements|Flask App Requirements]]
- [[_COMMUNITY_Monitoring and Logging|Monitoring and Logging]]

## God Nodes (most connected - your core abstractions)
1. `Kubernetes` - 43 edges
2. `CKA 2024 Course README` - 32 edges
3. `Day 27 Kubeadm Multi-Node Cluster README` - 13 edges
4. `Docker` - 7 edges
5. `#40daysofkubernetes Challenge` - 4 edges
6. `Day 6 Install Kind Cluster README` - 4 edges
7. `Day 8 Task` - 4 edges
8. `Day 9 Services README` - 4 edges
9. `Day 22 Authentication Authorization README` - 4 edges
10. `Day 23 RBAC README` - 4 edges

## Surprising Connections (you probably didn't know these)
- `Day 20 SSL/TLS README` --references--> `Kubernetes`  [INFERRED]
  Resources/Day20/readme.md → README.md
- `Day 30 DNS README` --references--> `Kubernetes`  [INFERRED]
  Resources/Day30/readme.md → README.md
- `CKA 2024 Course README` --references--> `Day 4 README`  [EXTRACTED]
  README.md → Resources/Day04/readme.md
- `CKA 2024 Course README` --references--> `Day 7 Pods README`  [EXTRACTED]
  README.md → Resources/Day07/readme.md
- `CKA 2024 Course README` --references--> `Day 8 ReplicaSets and Deployments README`  [EXTRACTED]
  README.md → Resources/Day08/readme.md

## Import Cycles
- None detected.

## Communities (34 total, 23 thin omitted)

### Community 0 - "Kubernetes Cluster Setup"
Cohesion: 0.10
Nodes (21): Calico CNI, Kubeadm, Day 26 Network Policies README, Day 26 Task, Day 27 Kubeadm Multi-Node Cluster README, Day 27 Task, Day 29 Task, Day 30 DNS README (+13 more)

### Community 1 - "Docker Fundamentals"
Cohesion: 0.24
Nodes (10): #40daysofkubernetes Challenge, Docker, Day 1 Docker Fundamentals README, Day 1 Task, Day 2 Dockerize Application README, Day 2 Task, Day 3 Multi-Stage Docker Build README, Day 3 Task (+2 more)

### Community 2 - "Kubernetes Core Concepts"
Cohesion: 0.22
Nodes (9): Kubernetes, Day 7 Pod YAML (nginx-pod), Day 7 Pods README, Day 8 ReplicaSets and Deployments README, Day 18 Health Probes README, Day 29 Kubernetes Volumes README, Day 31 CoreDNS README, Day 32 Kubernetes Networking CNI README (+1 more)

### Community 3 - "CKA Course Content"
Cohesion: 0.22
Nodes (9): Day 10 Namespaces README, Day 11 Multi-Container Pods README, Day 12 DaemonSet CronJob Job README, Day 13 Static Pods Labels Selectors README, Day 16 Resource Requests and Limits README, Day 19 ConfigMaps and Secrets README, Day 20 SSL/TLS README, Day 21 TLS in Kubernetes README (+1 more)

### Community 4 - "Kind Cluster Setup"
Cohesion: 0.25
Nodes (8): Kind Cluster, Day 6 Install Kind Cluster README, Day 6 Task, Day 7 Task, Day 8 Deployment YAML, Day 8 ReplicationController YAML, Day 8 ReplicaSet YAML, Day 8 Task

### Community 5 - "Kubernetes Auth and RBAC"
Cohesion: 0.40
Nodes (5): Day 21 Task, Day 22 Authentication Authorization README, Day 23 RBAC README, Day 24 ClusterRole ClusterRoleBinding README, Day 25 Service Account README

### Community 6 - "Ingress Configuration"
Cohesion: 0.83
Nodes (4): Day 33 Flask Deployment YAML, Day 33 Flask Ingress YAML, Day 33 Ingress README, Day 33 Flask Service YAML

### Community 7 - "CKA Exam Prep"
Cohesion: 0.67
Nodes (3): CKA Exam, Day 33 Task, Day 41 CKA Exam Tips README

### Community 8 - "Kubernetes Services"
Cohesion: 0.67
Nodes (3): Kind Cluster Config, Day 9 Services README, Day 10 Task

### Community 9 - "Autoscaling and Metrics"
Cohesion: 0.67
Nodes (3): Day 16 Metrics Server YAML, Day 16 Task, Day 17 Autoscaling HPA VPA README

## Knowledge Gaps
- **43 isolated node(s):** `problem1.sh script`, `problem2.sh script`, `Kind Cluster Config`, `Day 5 Task`, `Day 6 Task` (+38 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **23 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Kubernetes` connect `Kubernetes Core Concepts` to `Kubernetes Cluster Setup`, `Docker Fundamentals`, `CKA Course Content`, `Kind Cluster Setup`, `Kubernetes Auth and RBAC`, `Ingress Configuration`, `CKA Exam Prep`, `Kubernetes Services`, `Autoscaling and Metrics`, `Why Kubernetes`, `Kubernetes Architecture`, `NodePort Service`, `Taints and Node Affinity`?**
  _High betweenness centrality (0.370) - this node is a cross-community bridge._
- **Why does `CKA 2024 Course README` connect `CKA Course Content` to `Kubernetes Cluster Setup`, `Docker Fundamentals`, `Kubernetes Core Concepts`, `Kind Cluster Setup`, `Kubernetes Auth and RBAC`, `CKA Exam Prep`, `Kubernetes Services`, `Autoscaling and Metrics`, `Why Kubernetes`, `Kubernetes Architecture`, `Taints and Node Affinity`?**
  _High betweenness centrality (0.196) - this node is a cross-community bridge._
- **Why does `Day 27 Kubeadm Multi-Node Cluster README` connect `Kubernetes Cluster Setup` to `Kubernetes Core Concepts`, `CKA Course Content`?**
  _High betweenness centrality (0.170) - this node is a cross-community bridge._
- **Are the 3 inferred relationships involving `Kubernetes` (e.g. with `Docker` and `Day 20 SSL/TLS README`) actually correct?**
  _`Kubernetes` has 3 INFERRED edges - model-reasoned connections that need verification._
- **What connects `problem1.sh script`, `problem2.sh script`, `Kind Cluster Config` to the rest of the system?**
  _43 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Kubernetes Cluster Setup` be split into smaller, more focused modules?**
  _Cohesion score 0.1 - nodes in this community are weakly interconnected._