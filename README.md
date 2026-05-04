<!-- ═══════════════════════════════════════════════════
     500BoiledPotatoes · Lu Jingyu · GitHub Profile
     ═══════════════════════════════════════════════════ -->

<div align="center">

<h1>Lu Jingyu &nbsp;·&nbsp; 卢靖宇</h1>

<p>
<img src="https://img.shields.io/badge/ANU-Postgraduate-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="ANU" />
&nbsp;
<img src="https://img.shields.io/badge/UCD-First%20Class%20Honours-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="UCD" />
&nbsp;
<img src="https://img.shields.io/badge/BJUT%20'24-Graduate-0d1117?style=flat-square&labelColor=0d1117&color=4a90d9" alt="BJUT" />
</p>

<p>
<a href="mailto:jingyu.lu@anu.edu.au"><img src="https://img.shields.io/badge/jingyu.lu%40anu.edu.au-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="email" /></a>
&nbsp;
<a href="https://www.linkedin.com/in/jingyu-lu-9ba475274/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="linkedin" /></a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=500BoiledPotatoes&label=profile+views&color=6e7681&style=flat-square" alt="views" />
</p>

<p><code>systems</code> &nbsp;·&nbsp; <code>hpc</code> &nbsp;·&nbsp; <code>parallel computing</code> &nbsp;·&nbsp; <code>llm safety</code></p>

</div>

<br>

---

<h3><code>&gt; whoami</code></h3>

I build things close to the metal — CUDA kernels, distributed solvers, OS internals. My interests span **high-performance computing**, **systems programming**, and (more recently) **LLM safety research**.

Currently at **Australian National University**, previously **BJUT** and **University College Dublin**, where I graduated with First Class Honours.

- 🔭 &nbsp;Studying at **ANU** · applying for **PhD** positions
- 🌱 &nbsp;Deep in **CUDA**, **MPI**, **HPC**, and **Deep Learning**
- 📫 &nbsp;**jingyu.lu@anu.edu.au**

<br>

---

<h3><code>&gt; ls ./projects</code></h3>

<br>

**⚡ Parallel & High-Performance Computing**

<table>
<tr>
<td width="50%" valign="top">

**[`shared-memory-gpu-advection-solver`](https://github.com/500BoiledPotatoes/shared-memory-gpu-advection-solver)**

GPU solver for advection equations using **CUDA shared memory tiling**. Warp-aligned data staging cuts global memory bandwidth and maximises on-chip reuse.

<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="cuda" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="cpp" />
<img src="https://img.shields.io/badge/HPC-6e7681?style=flat-square" alt="hpc" />
<img src="https://img.shields.io/badge/GPU-6e7681?style=flat-square" alt="gpu" />

</td>
<td width="50%" valign="top">

**[`distributed-advection-solver-mpi`](https://github.com/500BoiledPotatoes/distributed-advection-solver-mpi)**

Multi-node advection solver with **halo exchange**. Non-blocking MPI communication pipelines computation and communication across distributed processes.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/MPI-6e7681?style=flat-square" alt="mpi" />
<img src="https://img.shields.io/badge/Distributed_Systems-6e7681?style=flat-square" alt="distributed" />

</td>
</tr>
</table>

<br>

**🖥️ Systems Programming**

<table>
<tr>
<td width="50%" valign="top">

**[`CSAPP-concurrent-train-traffic-control`](https://github.com/500BoiledPotatoes/CSAPP-concurrent-train-traffic-control)**

Concurrent train scheduler with **deadlock prevention** via resource ordering. Fine-grained mutex strategy minimises lock contention across critical sections.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/Concurrency-6e7681?style=flat-square" alt="concurrency" />
<img src="https://img.shields.io/badge/POSIX_Threads-6e7681?style=flat-square" alt="posix" />

</td>
<td width="50%" valign="top">

**[`CSAPP-memory-allocators-and-garbage-collectors`](https://github.com/500BoiledPotatoes/CSAPP-memory-allocators-and-garbage-collectors)**

Heap allocator with explicit free lists and **boundary-tag coalescing**, paired with a mark-and-sweep GC. Balanced for throughput and fragmentation ratio.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/Memory_Management-6e7681?style=flat-square" alt="memory" />
<img src="https://img.shields.io/badge/Garbage_Collection-6e7681?style=flat-square" alt="gc" />

</td>
</tr>
</table>

<br>

**🐧 OS & Security**

<table>
<tr>
<td width="50%" valign="top">

**[`xv6-os-projects`](https://github.com/500BoiledPotatoes/xv6-os-projects)**

Kernel-level extensions to MIT's **xv6**: system calls, scheduling algorithms, virtual memory management, and file system features — all from scratch.

<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="c" />
<img src="https://img.shields.io/badge/OS_Kernel-6e7681?style=flat-square" alt="os" />
<img src="https://img.shields.io/badge/xv6-6e7681?style=flat-square" alt="xv6" />

</td>
<td width="50%" valign="top">

**[`garak`](https://github.com/500BoiledPotatoes/garak)** &nbsp;<sup>fork</sup>

Contributing to an open-source **LLM vulnerability scanner** — probing models for jailbreaks, hallucination patterns, and safety boundary failures.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="python" />
<img src="https://img.shields.io/badge/LLM_Safety-6e7681?style=flat-square" alt="llm" />
<img src="https://img.shields.io/badge/Red--teaming-6e7681?style=flat-square" alt="red-team" />

</td>
</tr>
</table>

<br>

---

<h3><code>&gt; cat tech_stack.txt</code></h3>

<br>

| Layer | Stack |
|:---|:---|
| **Low-level** | C &nbsp;·&nbsp; C++ &nbsp;·&nbsp; CUDA &nbsp;·&nbsp; MPI &nbsp;·&nbsp; POSIX |
| **Systems** | Linux &nbsp;·&nbsp; xv6 &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Nginx &nbsp;·&nbsp; Git |
| **ML / AI** | Python &nbsp;·&nbsp; TensorFlow &nbsp;·&nbsp; Pandas &nbsp;·&nbsp; OpenGL |
| **Web / Backend** | Java &nbsp;·&nbsp; Spring Boot &nbsp;·&nbsp; Vue &nbsp;·&nbsp; MySQL &nbsp;·&nbsp; SQLite |

<br>

<p>
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white" alt="C" />
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Vue-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
</p>

<br>

---

<h3><code>&gt; git log --stat</code></h3>

<br>

<p>
<img height="160" src="https://github-readme-stats.vercel.app/api?username=500BoiledPotatoes&show_icons=true&hide=contribs&count_private=true&rank_icon=github&hide_border=true&title_color=24292f&icon_color=6e7681&text_color=57606a&bg_color=ffffff" alt="stats" />
&nbsp;
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=500BoiledPotatoes&layout=compact&hide_border=true&title_color=24292f&text_color=57606a&bg_color=ffffff&langs_count=6" alt="top languages" />
</p>

<br>

---

<p align="center"><sub><i>"Premature optimisation is the root of all evil — but late optimisation is the root of all latency."</i></sub></p>
