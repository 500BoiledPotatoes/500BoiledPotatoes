<!--
  ╔══════════════════════════════════════════════╗
  ║   500BoiledPotatoes / README.md              ║
  ║   Lu Jingyu · Systems · HPC · LLM Safety    ║
  ╚══════════════════════════════════════════════╝
-->
 
<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=14&pause=2000&color=555555&center=true&vCenter=true&width=600&lines=systems+%C2%B7+hpc+%C2%B7+parallel+computing+%C2%B7+llm+safety" alt="typing" />
# Lu Jingyu &nbsp;·&nbsp; 卢靖宇
 
<p>
  <img src="https://img.shields.io/badge/ANU-Postgraduate-1a1a2e?style=flat-square&labelColor=1a1a2e&color=4a90d9" />
  &nbsp;
  <img src="https://img.shields.io/badge/UCD-First%20Class%20Honours-1a1a2e?style=flat-square&labelColor=1a1a2e&color=4a90d9" />
  &nbsp;
  <img src="https://img.shields.io/badge/BJUT%20'24-Graduate-1a1a2e?style=flat-square&labelColor=1a1a2e&color=4a90d9" />
</p>
<p>
  <a href="mailto:jingyu.lu@anu.edu.au">
    <img src="https://img.shields.io/badge/jingyu.lu@anu.edu.au-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/jingyu-lu-9ba475274/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=500BoiledPotatoes&label=profile+views&color=555&style=flat-square" />
</p>
</div>
<br>
---
 
### `> whoami`
 
I build things close to the metal — CUDA kernels, distributed solvers, OS internals.
My interests span **high-performance computing**, **systems programming**, and (more recently) **LLM safety research**.
 
Currently at **Australian National University**, previously **BJUT** and **University College Dublin**, where I graduated with First Class Honours.
 
<br>
---
 
### `> ls ./projects`
 
<br>
#### ⚡ &nbsp;Parallel & High-Performance Computing
 
<table>
<tr>
<td width="50%" valign="top">
#### [`shared-memory-gpu-advection-solver`](https://github.com/500BoiledPotatoes/shared-memory-gpu-advection-solver)
 
GPU solver for advection equations using **CUDA shared memory tiling**. Warp-aligned data staging reduces global memory pressure and maximises on-chip reuse.
 
<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" /> <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" /> <img src="https://img.shields.io/badge/HPC-555?style=flat-square" /> <img src="https://img.shields.io/badge/GPU-555?style=flat-square" />
 
</td>
<td width="50%" valign="top">
#### [`distributed-advection-solver-mpi`](https://github.com/500BoiledPotatoes/distributed-advection-solver-mpi)
 
Multi-node advection solver with **halo exchange** and non-blocking MPI communication. Computation and communication are pipelined across processes.
 
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/MPI-555?style=flat-square" /> <img src="https://img.shields.io/badge/Distributed-555?style=flat-square" />
 
</td>
</tr>
</table>
<br>
#### 🖥️ &nbsp;Systems Programming
 
<table>
<tr>
<td width="50%" valign="top">
#### [`CSAPP-concurrent-train-traffic-control`](https://github.com/500BoiledPotatoes/CSAPP-concurrent-train-traffic-control)
 
Concurrent scheduler for train routing with **deadlock prevention** via resource ordering. Fine-grained mutex strategy minimises contention across critical sections.
 
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Concurrency-555?style=flat-square" /> <img src="https://img.shields.io/badge/POSIX_Threads-555?style=flat-square" />
 
</td>
<td width="50%" valign="top">
#### [`CSAPP-memory-allocators-and-garbage-collectors`](https://github.com/500BoiledPotatoes/CSAPP-memory-allocators-and-garbage-collectors)
 
Heap allocator with explicit free lists and **boundary-tag coalescing**, paired with a mark-and-sweep GC. Balanced for throughput and fragmentation.
 
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Memory_Management-555?style=flat-square" /> <img src="https://img.shields.io/badge/GC-555?style=flat-square" />
 
</td>
</tr>
</table>
<br>
#### 🐧 &nbsp;OS &nbsp;&&nbsp; Security
 
<table>
<tr>
<td width="50%" valign="top">
#### [`xv6-os-projects`](https://github.com/500BoiledPotatoes/xv6-os-projects)
 
Kernel-level extensions to MIT's **xv6**: system calls, scheduling algorithms, virtual memory management, and file system features — all implemented from scratch.
 
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" /> <img src="https://img.shields.io/badge/Kernel-555?style=flat-square" /> <img src="https://img.shields.io/badge/OS-555?style=flat-square" />
 
</td>
<td width="50%" valign="top">
#### [`garak`](https://github.com/500BoiledPotatoes/garak) &nbsp;<sub>*fork*</sub>
 
Contributing to an open-source **LLM vulnerability scanner** — probing language models for jailbreaks, hallucination patterns, and safety boundary failures.
 
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/LLM_Safety-555?style=flat-square" /> <img src="https://img.shields.io/badge/Red--teaming-555?style=flat-square" />
 
</td>
</tr>
</table>
<br>
---
 
### `> cat tech_stack.txt`
 
<br>
| Layer | Stack |
|---|---|
| **Low-level** | C &nbsp;·&nbsp; C++ &nbsp;·&nbsp; CUDA &nbsp;·&nbsp; MPI &nbsp;·&nbsp; POSIX |
| **Systems** | Linux &nbsp;·&nbsp; xv6 &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Nginx &nbsp;·&nbsp; Git |
| **ML / AI** | Python &nbsp;·&nbsp; TensorFlow &nbsp;·&nbsp; Pandas &nbsp;·&nbsp; OpenGL |
| **Web / Backend** | Java &nbsp;·&nbsp; Spring Boot &nbsp;·&nbsp; Vue &nbsp;·&nbsp; MySQL &nbsp;·&nbsp; SQLite |
 
<br>
<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,cuda,python,java,linux,git,docker,tensorflow,spring,vue,mysql&theme=light" alt="tech stack icons" />
</p>
<br>
---
 
### `> git log --stat`
 
<br>
<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=500BoiledPotatoes&show_icons=true&hide=contribs&count_private=true&rank_icon=github&hide_border=true&title_color=111&icon_color=555&text_color=333&bg_color=fafafa" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=500BoiledPotatoes&layout=compact&hide_border=true&title_color=111&text_color=333&bg_color=fafafa&langs_count=6" alt="top languages" />
</p>
<br>
---
 
<div align="center">
<sub><i>"Premature optimisation is the root of all evil — but late optimisation is the root of all latency."</i></sub>
</div>
