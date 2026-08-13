# Cloud Infrastructure Components

Overview of the core infrastructure components analyzed within the **KillerCoda** sandbox environment.

---

## 🖥️ Compute Resources

* **Purpose:** Compute resources provide the processing power required to run applications, execute commands, and handle workloads. This encompasses the CPU and the operating system's capability to schedule and manage processes.
* **Importance in Cloud Computing:** Compute is the core engine that transforms stored data and network requests into actionable results. Without compute power, a cloud environment cannot process user queries, host web servers, or execute software.
* **KillerCoda Context:** Represented by a single virtual CPU (**Intel Xeon E312xx, 1 core**) powering the Ubuntu system and executing all terminal commands during the investigation.

---

## 💾 Storage Resources

* **Purpose:** Storage resources persistently retain data, including operating system files, applications, and user-created files.
* **Importance in Cloud Computing:** Storage ensures data persists beyond a single session, enabling systems to save configurations, system logs, and user content for future retrieval across various performance and cost tiers.
* **KillerCoda Context:** Verified via the `df -h` command, which identified the primary partition `/dev/vda1` along with essential system partitions:

```bash
# Storage Layout
/dev/vda1    19G Total  | 13G Available
/boot        System Boot Loader Files
/boot/efi    EFI System Partition
