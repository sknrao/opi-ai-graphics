**Table 1: The three pillars of data center compute**

| Processor | Primary role | Typical workloads | Key strengths |
| :--- | :--- | :--- | :--- |
| CPU | General-purpose computing | Application logic, operating systems, sequential tasks | High flexibility, broad compatibility, complex instruction sets |
| GPU | Massively parallel computing | AI/ML model training, graphics rendering, data analytics | Extremely high throughput for repetitive, parallel calculations |
| DPU / IPU | Infrastructure offloading & isolation | Networking (RDMA/OVS), security (IPSec/L4 firewalls), storage (NVMe-oF) | Low latency, high-bandwidth data movement, hardware programmability (P4/DOCA), strict security air-gapping |

**Table 2: DPU/IPU vendor landscape**

| Vendor | Flagship model | Primary architecture | ARM cores | Network interfaces | SDK / Ecosystem |
| :--- | :--- | :--- | :--- | :--- | :--- |
| NVIDIA | BlueField-3 | Custom ASIC + ARM Cortex-A78 + DPA accelerator | 16 (+ 16 DPA cores) | Up to 400G (Ethernet or NDR InfiniBand) | DOCA |
| AMD Pensando | Salina 400 | 232 P4 MPU engines + ARM Neoverse N1 | 16 | 2×400GbE ports (400G host bandwidth via PCIe Gen5) | SSDK |
| Intel | IPU E2100 | P4 programmable pipeline + ARM Neoverse N1 | 16 | Up to 200G (1×200GbE or 2×100GbE) | IPDK |
| Marvell | OCTEON 10 (CN106 / DPU400) | ASIC + ARM Neoverse N2 (5nm) | Up to 36 | Up to 400G | OCTEON SDK |
