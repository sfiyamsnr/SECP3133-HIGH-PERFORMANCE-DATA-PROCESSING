# SECP3133-HIGH-PERFORMANCE-DATA-PROCESSING

# 🚀 High Performance Data Processing (SECP3133-02) - Learning Portfolio

Welcome to my portfolio for the **High Performance Data Processing (SECP3133)** course.

---

## 📑 Overall Course Reflection

High Performance Data Processing has fundamentally shifted my paradigm on how large-scale enterprise data should be managed, ingested, and processed. Moving beyond basic local scripts, this course instilled a rigorous engineering mindset focused on computational efficiency, mitigating memory bottlenecks, and designing highly scalable architectures capable of handling datasets that far exceed physical RAM limitations.

Key personal and technical takeaways include:
* **Breaking Memory Boundaries:** Learning to shift away from standard, memory-heavy data loads by mastering advanced processing strategies like dynamic chunking, column downcasting, and lazy evaluation frameworks using Polars and Dask.
* **Orchestration Over Automation:** Realizing that high-performance code must be backed by a resilient infrastructure. Transitioning to containerized ecosystems taught me how to ensure absolute reproducibility and high availability across distributed nodes.
* **The Scale-Up Philosophy:** Big data engineering is not just about writing code; it is about managing resource trade-offs. Balancing the execution speed of microservices against security isolation profiles is a critical engineering skill I will carry forward into production environments.

---

## 🛠️ Repository Contents & Benchmarking

| Category | Repository Link |
| :--- | :--- |
| **Assignment 1**  | [View Folder](https://github.com/sfiyamsnr/SECP3133-HIGH-PERFORMANCE-DATA-PROCESSING/blob/main/HPDP%20(1).pdf) |
| **Assignment 2**  | [View Folder](https://github.com/sean-seah/HPDP/tree/main/2526/assignment/A2/Group%20taktahulahu) |

---

## ⚙️ Technologies & Infrastructure Devised

* **Containerization & Orchestration:** Docker Engine, Kubernetes Cluster Orchestration (Control Plane, Worker Nodes, Pods)[cite: 18].
* **Scalable Data Ecosystems:** Polars, Dask, PyArrow, and Pandas Memory Optimization.
* **Distributed Frameworks:** Hadoop Ecosystem, HDFS, and Apache ZooKeeper Coordination Patterns.
* **Environment:** Google Colab, GitHub Version Control, and Cloud-Native Testing Topologies.

---

## 🛠️ Assignment-by-Assignment Reflection

### 🔹 [Assignment 1: Cloud-Native Virtualization & Orchestration Performance Analysis]
* **Concepts Focused:** Operating system-level virtualization, container orchestration mechanics, microservices clustering, and infrastructure auto-scaling.
* **Implementation Details:** Conducted a deep architectural and structural analysis of **Docker container technology** and **Kubernetes orchestration**, referencing the verbatim study. Evaluated the control plane infrastructure (`API Server`, `etcd`, `Scheduler`) against worker node execution environments (`Kubelet`, `Kube-proxy`, and `Pods`).
* **Reflection:** This assignment completely redefined my understanding of deployment scalability. Moving away from traditional hypervisor-based Virtual Machines (VMs)—which carry massive resource overhead and agonizingly slow provisioning times—I learned how shared-kernel containerization reduces startup latency from minutes to mere seconds. Delving into Kubernetes' declarative configuration model and Horizontal Pod Autoscalers (HPA) demonstrated how modern distributed systems automate fault recovery and remain resilient under sudden traffic spikes without manual operator intervention.

### 🔹 [Assignment 2: Virtualization Tier Benchmarking (VMs vs. Containers)]
* **Concepts Focused:** Microservices Frameworks, Resource Footprint Profiling, Pipeline Ingestion Speed, and Isolation Boundaries.
* **Implementation Details:** Engineered a structural data matrix comparing hypervisor-bound environments against containerized deployments, mapping critical performance parameters such as portability, fault recovery vectors, deployment model flexibility, and CI/CD integration pipelines.
* **Reflection:** Compiling this architectural benchmark matrix proved that high-performance computing requires balancing raw processing power against data safety. While the Docker and Kubernetes pipeline delivers near bare-metal execution speeds and seamless portability, it introduces weaker isolation boundaries due to a shared host kernel. This task taught me that choosing a processing environment isn't about finding the "best" tool, but rather about matching the workload's risk tolerance with the architecture's throughput capacity.

---

## 👥 Group Project

Beyond individual architectural profiling, this module gave me great hands-on experience in building real high-performance data pipelines. Through the lab tasks and our group assignment, I learned how to move away from slow, manual spreadsheet manipulations and step into automated big data engineering. I discovered how to process massive files efficiently by applying chunking, optimizing column data types, and utilizing scalable libraries like Dask and Polars.

Working with my team also taught me how to collaborate better on a shared GitHub repository while structuring data models[cite: 18]. Overall, this module helped me understand how to solve real data bottlenecks and made me much more confident in writing optimized, production-ready processing workflows[cite: 18].
