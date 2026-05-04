<!-- ═══════════════════════════════════════════════════
     500BoiledPotatoes · Lu Jingyu · GitHub Profile
     ═══════════════════════════════════════════════════ -->

<div align="center">

<h1>Lu Jingyu</h1>

<p>
<img src="https://img.shields.io/badge/ANU-Postgraduate-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="ANU" />
&nbsp;
<img src="https://img.shields.io/badge/UCD-First%20Class%20Honours-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="UCD" />
&nbsp;
<img src="https://img.shields.io/badge/BJUT%20'24-Graduate-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="BJUT" />
</p>

<p>
<a href="mailto:jingyu.lu@anu.edu.au">
  <img src="https://img.shields.io/badge/jingyu.lu%40anu.edu.au-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/jingyu-lu-9ba475274/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin" />
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=500BoiledPotatoes&label=profile+views&color=6e7681&style=flat-square" alt="views" />
</p>

<p>
<code>systems</code> &nbsp;·&nbsp;
<code>hpc</code> &nbsp;·&nbsp;
<code>parallel computing</code> &nbsp;·&nbsp;
<code>llm safety</code>
</p>

</div>

<br>

---

## About

I build things close to the metal — CUDA kernels, distributed solvers, OS internals. My interests span **high-performance computing**, **systems programming**, and (more recently) **LLM safety research**.

Currently at **Australian National University**, previously **BJUT** and **University College Dublin**, where I graduated with First Class Honours.

- 🔭 &nbsp;Studying at **ANU** · applying for **PhD** positions
- 🌱 &nbsp;Deep in **CUDA**, **MPI**, **HPC**, and **Deep Learning**
- 📫 &nbsp;**jingyu.lu@anu.edu.au**

<br>

---

## Projects

<br>

**🖥️ &nbsp;Systems Programming**

<table>
<tr>
<td width="33%" valign="top">

**[`CSAPP-concurrent-train-traffic-control`](https://github.com/500BoiledPotatoes/CSAPP-concurrent-train-traffic-control)**

Concurrent train scheduler with **deadlock prevention** via resource ordering. Fine-grained mutex strategy minimises lock contention across critical sections.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/Concurrency-6e7681?style=flat-square" alt="concurrency" />
<img src="https://img.shields.io/badge/POSIX-6e7681?style=flat-square" alt="posix" />

</td>
<td width="33%" valign="top">

**[`CSAPP-memory-allocators-and-garbage-collectors`](https://github.com/500BoiledPotatoes/CSAPP-memory-allocators-and-garbage-collectors)**

Heap allocator with explicit free lists and **boundary-tag coalescing**, paired with a mark-and-sweep GC. Balanced for throughput and fragmentation ratio.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/Memory_Mgmt-6e7681?style=flat-square" alt="memory" />
<img src="https://img.shields.io/badge/GC-6e7681?style=flat-square" alt="gc" />

</td>
<td width="33%" valign="top">

**[`xv6-os-projects`](https://github.com/500BoiledPotatoes/xv6-os-projects)**

Kernel-level extensions to MIT's **xv6**: system calls, scheduling algorithms, virtual memory management, and file system features — all from scratch.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/OS_Kernel-6e7681?style=flat-square" alt="os" />
<img src="https://img.shields.io/badge/xv6-6e7681?style=flat-square" alt="xv6" />

</td>
</tr>
</table>

<br>

**⚡ &nbsp;Parallel & High-Performance Computing**

<table>
<tr>
<td width="50%" valign="top">

**[`shared-memory-gpu-advection-solver`](https://github.com/500BoiledPotatoes/shared-memory-gpu-advection-solver)**

GPU solver for advection equations using **CUDA shared memory tiling**. Warp-aligned data staging cuts global memory bandwidth and maximises on-chip reuse.

<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="cuda" />
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/HPC-6e7681?style=flat-square" alt="hpc" />
<img src="https://img.shields.io/badge/GPU-6e7681?style=flat-square" alt="gpu" />

</td>
<td width="50%" valign="top">

**[`distributed-advection-solver-mpi`](https://github.com/500BoiledPotatoes/distributed-advection-solver-mpi)**

Multi-node advection solver with **halo exchange**. Non-blocking MPI communication pipelines computation and communication across distributed processes.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/MPI-6e7681?style=flat-square" alt="mpi" />
<img src="https://img.shields.io/badge/Distributed-6e7681?style=flat-square" alt="distributed" />

</td>
</tr>
</table>

<br>

**🔐 &nbsp;LLM Safety**

<table>
<tr>
<td width="50%" valign="top">

**[`garak`](https://github.com/500BoiledPotatoes/garak)** &nbsp;<sup>fork</sup>

Contributing to an open-source **LLM vulnerability scanner** — probing models for jailbreaks, hallucination patterns, and safety boundary failures across multiple attack surfaces.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="python" />
<img src="https://img.shields.io/badge/LLM_Safety-6e7681?style=flat-square" alt="llm" />
<img src="https://img.shields.io/badge/Red--teaming-6e7681?style=flat-square" alt="red-team" />

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

<br>

---

## Tech Stack

<br>

<table>
<tr>
  <td><b>Low-level</b></td>
  <td>
    <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
    <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
    <img src="https://img.shields.io/badge/MPI-6e7681?style=flat-square" alt="MPI" />
    <img src="https://img.shields.io/badge/POSIX-6e7681?style=flat-square" alt="POSIX" />
  </td>
</tr>
<tr>
  <td><b>Systems</b></td>
  <td>
    <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
    <img src="https://img.shields.io/badge/xv6-6e7681?style=flat-square" alt="xv6" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  </td>
</tr>
<tr>
  <td><b>ML / AI</b></td>
  <td>
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
    <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  </td>
</tr>
</table>

<br>

---

## Stats

<br>

<p>
<img height="160" src="https://streak-stats.demolab.com/?user=500BoiledPotatoes&hide_border=true&date_format=j%20M%5B%20Y%5D&background=ffffff&stroke=e1e4e8&ring=4a90d9&fire=4a90d9&currStreakNum=24292f&sideNums=24292f&currStreakLabel=6e7681&sideLabels=6e7681&dates=6e7681" alt="streak" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=500BoiledPotatoes&layout=compact&hide_border=true&title_color=24292f&text_color=57606a&bg_color=ffffff&langs_count=4&hide=javascript,html,css,java,typescript,shell,makefile,cmake,batchfile" alt="top languages" />
</p>

<p>
<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=500BoiledPotatoes&theme=github" alt="profile summary" />
</p>

<br>

---

<p align="center"><sub><i>"Premature optimisation is the root of all evil — but late optimisation is the root of all latency."</i></sub></p>
