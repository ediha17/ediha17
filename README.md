## Hi I'm Edi

My career is driven by a deep curiosity about technology and how code interacts with it. I'm currently immersed in the **42 Barcelona** methodology, studying the Common Core, prioritizing peer-to-peer and self-taught learning.
 
*When I entered 42, I discovered my greatest fear... The Norminette* 😨

---

### 💻 Technical Stack
 
<table>
  <thead>
    <tr>
      <th align="center">Category</th>
      <th align="center">Technologies</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left"><b>Languages</b></td>
      <td>
        <img src="https://raw.githubusercontent.com/github/explore/f3e22f0dca2be955676bc70d6214b95b13354ee8/topics/c/c.png" height="50" alt="C logo" />
        <img width="12" />
        <img src="https://images.seeklogo.com/logo-png/15/2/java-logo-png_seeklogo-158094.png" height="50" alt="Java logo" />
        <img width="12" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
        <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
      </td>
    </tr>
    <tr>
      <td align="left"><b>Fundamentals</b></td>
      <td>
        <code>Algorithms</code> <code>Data Structures</code> <code>Systems Architecture</code> <code>Memory Management</code>
      </td>
    </tr>
    <tr>
      <td align="left"><b>Tools & Environments</b></td>
      <td>
        <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white" alt="Git">
        <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
        <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
        <img src="https://img.shields.io/badge/Neovim-%2357A143.svg?style=flat-square&logo=neovim&logoColor=white" alt="Neovim">
        <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash">
      </td>
    </tr>
  </tbody>
</table>

---

### 🏗️ Featured Projects
 
#### 🧠 [RAG Document Recommender](https://github.com/VanoviTeam/rag-document-recommender)
*Self-hosted, containerized AI recommendation system built on Retrieval-Augmented Generation*
 
**Tech Stack:** `Docker` `n8n` `PostgreSQL` `Qdrant` `Ollama / LLMs` `Redis` `Caddy`
 
Developed during my internship at Vanovi Design to automate book recommendations, this project orchestrates a complete RAG pipeline: incoming documents are chunked and embedded, stored as vectors in **Qdrant**, and retrieved semantically whenever a user asks a question — so the AI Agent only answers based on the actual hosted documents instead of hallucinating.
 
* The entire workflow — ingestion, embedding, retrieval, and response generation — is automated and coordinated through **n8n**, with an AI Agent node that autonomously decides when it needs to query the document database before crafting its answer.
* Runs **fully self-hosted** using local LLMs served through **Ollama**, avoiding dependency on paid external APIs and keeping all data processing on-premise.
* **PostgreSQL** and **Redis** handle relational data and caching, while **Caddy** acts as the reverse proxy in front of the stack.
* The whole system is packaged with **Docker Compose**, and has been validated both on cloud infrastructure (Oracle Cloud ARM instances) and on modest local hardware running CPU-only.
  
#### 🌀 [A-Maze-Ing](https://github.com/ediha17/42bcn_A-Maze-Ing)
*Maze generator and solver built from scratch, developed as part of the 42 curriculum*
 
**Tech Stack:** `Python` `Algorithms` `Data Structures`
 
This project follows 42's maze specification: generate a fully-connected maze of configurable size in a Unix environment, encode it to a file, and compute a valid path between an entry and an exit point — all implemented from the ground up without relying on external maze libraries.
 
* Builds the maze as a **graph of cells**, using a randomized generation algorithm to carve out corridors while guaranteeing full connectivity and no isolated areas.
* Solves the maze by finding the **shortest path** from entry to exit, applying graph-traversal logic over the generated structure.
* Strengthened my practical understanding of **recursion/iteration trade-offs, graph traversal, and encoding structured data** (the maze layout) into a compact file format.
  
#### 🔀 [Push_swap](https://github.com/ediha17/42Bcn_Push_swap)
*High-performance sorting algorithm restricted to two stacks and a minimal instruction set*
 
**Tech Stack:** `C` `Algorithm Optimization` `Sorting Algorithms`
 
Push_swap sorts a list of integers using only two stacks (A and B) and a fixed set of operations (`sa`, `sb`, `ss`, `pa`, `pb`, `ra`, `rb`, `rr`, `rra`, `rrb`, `rrr`), with the goal of reaching a sorted state in the **lowest possible number of moves**.
 
* Implements **two distinct strategies depending on input size**: for small stacks (2–5 elements), hand-optimized logic based on the stack's median finds the shortest sequence of moves; for large stacks (100–500 elements), a **Radix Sort in base 2** — using bitwise shift and mask operations — sorts efficiently in near-linear time.
* Values are **pre-indexed** before sorting to safely handle negative numbers and to minimize the number of bits Radix Sort needs to process.
* Ships with a companion **checker** program to validate that the generated sequence of moves actually results in a sorted stack, plus a visualizer used during development to debug the algorithm step by step.
* Rigorously tested for memory safety with **Valgrind**, in line with the 42 Norm's zero-leak requirement.

---

### 🧠 Beyond the Terminal
* **Deep Curiosity:** Always exploring the layers beneath the software—enjoying the deep dive into system performance, operating systems, and cutting-edge paradigms like RAG and automation.

* **Craftsmanship:** Writing code isn't just about making it work; it's about treating development as an evolving craft where efficiency, clarity, and elegance matter.

* **Relentless Problem Solving:** Thriving on complex challenges that require creative logic, continuous self-teaching, and adapting quickly to entirely new technology stacks.

### 📈 Coding Metrics

![Metrics](https://github-readme-stats.vercel.app/api?username=ediha17&show_icons=true&count_private=true&theme=dark)

<!--
### 🛠️ Current Focus
* 🚀 Mastering **Data Structures** (Linked Lists, Binary Trees, Hash Maps).
* 🛡️ Enhancing **Defensive Programming** techniques in C.

### 📫 Contact
* **LinkedIn:** [Tu Nombre]
* **Email:** [Tu Email]
-->
---
*:sparkles:"Trying to go beyond the code.":sparkles:*
