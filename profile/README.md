## Network Resiliency Infrastructure

This project is a hardware-software complex designed for building fault-tolerant networks. At the core of the solution is an intelligent router engineered to operate under unstable communication links and meet critical uptime requirements.

### Device Architecture

The implemented multi-channel architecture enables the aggregation of several independent communication lines into a single resilient circuit. The system monitors quality metrics in real-time—such as latency, packet loss, and jitter—and automatically reroutes traffic to the most stable path. To prevent software failures, the device utilizes a checkpoint mechanism: if a malfunction is detected following an update or configuration change, the system performs an instantaneous rollback to the last known stable state.

### Centralized Control System

A fleet of devices is managed via a unified server application, allowing for the administration of geographically distributed infrastructure from a single point of entry.

* **Automation:** Automated link diagnostics and configuration self-healing.
* **Security:** A hierarchical role-based access control (RBAC) model and detailed logging of all network manipulations.
* **Scalability:** Remote deployment of updates and network parameter adjustments without the need for on-site technicians.

This solution minimizes the impact of human error and reduces the technical expertise required from local personnel while ensuring the continuity of business processes.
