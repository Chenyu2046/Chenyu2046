<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=190&text=Chenyu&fontAlign=50&fontAlignY=34&fontSize=48&desc=C%2B%2B%20%2F%20Linux%20Systems%20Engineer&descAlign=50&descAlignY=58&color=0:0f172a,35:075985,70:0369a1,100:0f766e&fontColor=ffffff&animation=fadeIn" alt="Chenyu banner" />

### C++ / Linux Systems Engineer

**eBPF · Observability · Distributed Systems · Embedded Software · AI Engineering**

Building software close to the system boundary — from kernel observability and high-concurrency services to embedded DSP and developer infrastructure.

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-17%2F20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Linux-Systems-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/eBPF-Kernel_Observability-111111?style=for-the-badge&logo=linuxfoundation&logoColor=white" alt="eBPF" />
  <img src="https://img.shields.io/badge/gRPC-Distributed_Systems-244C5A?style=for-the-badge" alt="gRPC" />
</p>

</div>

---

<table>
<tr>
<td width="50%" valign="top">

## 💼 Experience

### Harman International
**C++ Embedded Software Intern** · 2026.05 — Present

Automotive Karaoke DSP software around **Audio HAL, AIDL/HIDL IPC, real-time audio processing and runtime concurrency**.

- Decoupled IPC control requests from real-time processing through a dedicated control path and message queue.
- Built DSP frame adaptation for variable HAL frame sizes and fixed-size algorithm blocks.
- Hardened Processor/buffer lifecycle with concurrency boundaries and sanitizer-backed stress validation.

### MetaApp
**iOS Software Engineer Intern** · 2025.09 — 2026.02

Worked on high-traffic resource-list/search flows, state handling and performance optimization for GPark.

</td>
<td width="50%" valign="top">

## 🌐 Open Source

### [Envoy](https://github.com/envoyproxy/envoy/pull/46723)
**RLQS Rate Limit Infrastructure · Open upstream PR #46723**

Reworked RLQS usage reporting so each bucket can honor its own `reporting_interval` while retaining a single global timer. The scheduling path tracks the earliest bucket deadline and preserves interval state across assignment, fallback and expiration transitions.

`C++` `Scheduling` `Rate Limiting` `Distributed Systems`

### [BCC / eBPF](https://github.com/iovisor/bcc/pull/5541)
**tcpconnect · Open upstream PR #5541**

Moved IPv4/IPv6 selection into **BPF source generation, probe attachment and userspace Map/Event initialization**, removing unnecessary IPv6 dependencies when `tcpconnect -4` runs on IPv4-only kernels.

`eBPF` `Linux Kernel` `Networking` `Python`

</td>
</tr>
</table>

---

## 🚀 Featured Systems

<table>
<tr>
<td width="50%" valign="top">

### 🔭 [KernScope](https://github.com/Chenyu2046/MonitorSystem)
**Linux Kernel Observability · Performance Diagnostics**

Worker/Manager observability system combining **Kernel Module + mmap, TC eBPF, On/Off-CPU profiling, adaptive diagnostics and evidence-based root-cause analysis**.

`C++17` `Linux` `eBPF` `gRPC` `MySQL`

</td>
<td width="50%" valign="top">

### 🧠 [Pico](https://github.com/Chenyu2046/Pico)
**Local Coding Agent Harness · Developer Infrastructure**

Repository-aware coding agent focused on **tool execution, long-context management, layered memory, checkpoint recovery, run tracing and regression evaluation**.

`Python` `Agent Harness` `Tool Calling` `Context Engineering`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [Robot_ROS2](https://github.com/Chenyu2046/Robot_ROS2)
**ROS 2 · Autonomous Mobile Robot Stack**

C++17 indoor AMR stack covering chassis abstraction, **SLAM, Nav2, path tracking, mission scheduling, facility integration and fleet coordination**.

`C++17` `ROS 2` `Nav2` `SLAM` `Gazebo`

</td>
<td width="50%" valign="top">

### 📦 [HydraFS](https://github.com/Chenyu2046/HydraFS)
**Storage Backend · High-Concurrency Service Architecture**

C/C++ private-cloud file platform built around **FastCGI, Nginx and FastDFS**, with resumable uploads, deduplication, Redis/MySQL persistence and semantic search.

`C/C++` `FastDFS` `Nginx` `Redis` `MySQL`

</td>
</tr>
</table>

## 📈 Selected Engineering Results

<table>
<tr>
<td align="center" width="33%">

### 87.11 Gb/s
**TC eBPF benchmark**

Peak controlled-veth throughput with **248.2k packets/s** coverage.

</td>
<td align="center" width="33%">

### 11.7% ↓
**Manager completion time**

100-host A/B after host-hash sharding and asynchronous persistence.

</td>
<td align="center" width="33%">

### 45,000 / 45,000
**Stable persistence**

75 hosts · 1 s reporting · 10 min with zero queue-full and persistence rejects.

</td>
</tr>
</table>

## 🛠️ Engineering Stack

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/eBPF-111111?style=flat-square&logo=linuxfoundation&logoColor=white" alt="eBPF" />
  <img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square" alt="gRPC" />
  <img src="https://img.shields.io/badge/Protobuf-4285F4?style=flat-square" alt="Protobuf" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

---

<div align="center">

**Systems Programming · Kernel Observability · Open Source · Developer Infrastructure**

<sub>Build it · measure it · make it observable · make it reliable</sub>

</div>
