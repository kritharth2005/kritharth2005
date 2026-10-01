<div align="center">

<img src="https://capsule-render.vercel.app/api?type=wave&color=0:0d1117,50:6a0dad,100:ff6a00&height=200&section=header&text=Kritharth%20Shetty&fontSize=55&fontColor=ffffff&animation=fadeIn" />

<a href="https://github.com/kritharth2005">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=FF6A00&center=true&vCenter=true&width=600&lines=Systems+Software+Engineer;C+%2F+C%2B%2B+%2F+Go;Kernels%2C+drivers+and+datapaths;Measured%2C+not+guessed;sudo+make+me+sleep+--+Permission+denied" />
</a>

</div>

**Systems Software | OS Internals, Drivers & the Network Datapath**

I work on software close to the hardware: how drivers behave when devices misbehave, how packets move from the NIC to a socket, and where latency actually goes. I care about correctness under failure, and I'd rather measure a system than guess about it.

- 🔧 **Now:** building **Hostile Device** — a harness that plays a failing emulated PCIe device against real, unmodified Linux drivers under load, and judges whether they recover
- 🐧 **Lab:** a debug mainline kernel in QEMU with gdb attached (KASAN, lockdep, kmemleak) — kernel modules and drivers get written and broken there, never on the host
- 📚 **Learning in public:** C++ from the ground up (RAII, move semantics, memory ordering, cache-aware layout), C in its kernel dialect, computer architecture, and the Linux networking stack
- 🌱 **Open source:** Apache Pulsar contributor; currently reading [rdma-core](https://github.com/linux-rdma/rdma-core) ahead of contributing
- ⚙️ **Philosophy:** every design gets a deliberately injected failure before I trust it

<div align="center">

<a href="mailto:kritharth26@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/kritharth-shetty-23a246293/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>

</div>

---

### 🛠️ Projects

| Project | What it is | Stack |
|---|---|---|
| **Hostile Device** *(in progress)* | Fault injection at the PCIe boundary: event-triggered faults (withheld interrupts, all-1's reads after surprise removal, bogus completions) in QEMU device models, run against upstream drivers carrying real traffic. Every finding replays deterministically | C, QEMU, Linux kernel |
| **Rewind** | Local-first snapshot system — content-defined chunking, Zstandard reverse deltas, SQLite manifests. Two research papers on it | Go, SQLite |
| **Styx** | VPN built from scratch — control plane and packet engine split across a Unix domain socket, ChaCha20-Poly1305 | Rust, Java |
### 🌱 Open Source

- **Apache Pulsar** — Redis sink connector: [ACL support + TLS hardening (#126)](https://github.com/apache/pulsar-connectors/pull/126), [TLS peer verification and truststore support (#135)](https://github.com/apache/pulsar-connectors/pull/135)

---

### 💻 Tech Stack

<div align="center">

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Linux Kernel](https://img.shields.io/badge/Linux_Kernel-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-A42E2B?style=for-the-badge&logo=gnu&logoColor=white)
![perf / eBPF](https://img.shields.io/badge/perf_%2F_eBPF-222222?style=for-the-badge&logo=ebpf&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)

</div>

---

### 📊 GitHub Stats

<div align="center">

<img src="./profile/stats.svg" width="49%" />
<img src="./profile/top-langs.svg" width="49%" />

<img src="./profile/streak.svg" width="70%" />

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=wave&color=0:0d1117,50:6a0dad,100:ff6a00&height=100&section=footer" />
</div>
