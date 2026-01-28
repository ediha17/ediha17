## Hi I'm Edi

My career in software development is driven by a deep curiosity about technology and how code interacts with it. I’m currently fully immersed in the 42 methodology as a student at the Barcelona campus, prioritizing peer-to-peer and self-taught learning.

*When i enter in 42, I discover my greatest fear... The Norminette*😨.

---

### 💻 Technical Stack
<table>
  <thead>
    <tr>
      <th align="center">Category</th>
      <th align="left">Technologies</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>Languages</b></td>
      <td>
        <img src="https://raw.githubusercontent.com/github/explore/f3e22f0dca2be955676bc70d6214b95b13354ee8/topics/c/c.png" height="50" alt="C logo" />
            <img width="12" />
        <img src="https://images.seeklogo.com/logo-png/15/2/java-logo-png_seeklogo-158094.png" height="50" alt="Java logo" />
          <img width="12" />
      </td>
    </tr>
    <tr>
      <td align="center"><b>Specialties</b></td>
      <td>
        <code>Memory Management</code> <code>Algorithm Design</code> <code>Unix Programming</code>
      </td>
    </tr>
    <tr>
      <td align="center"><b>Tools</b></td>
      <td>
        <img src="https://img.shields.io/badge/Makefile-%23A81D33.svg?style=flat-square&logo=gnu&logoColor=white" height="50" alt="Makefile">
        <img src="https://img.shields.io/badge/GDB-%23313739.svg?style=flat-square&logo=gnu&logoColor=white" alt="GDB">
        <img src="https://img.shields.io/badge/Valgrind-%23191919.svg?style=flat-square&logo=valgrind&logoColor=white" alt="Valgrind">
        <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=flat-square&logo=git&logoColor=white" alt="Git">
        <img src="https://img.shields.io/badge/Neovim-%2357A143.svg?style=flat-square&logo=neovim&logoColor=white" alt="Neovim">
      </td>
    </tr>
  </tbody>
</table>

---

### 🏗️ Core Projects

#### 🖨️ [ft_printf](https://github.com/ediha17/42Bcn_printf.git)
*Custom Implementation of the C Standard Library printf*

* **The Challenge:** Handling variadic arguments and data conversion without memory leaks.

* **Architecture:** Developed a **modular dispatcher** system that maps specifiers to specialized internal logic, ensuring high extensibility and O(1) function lookup for conversions.

* **Key Learning:** Deep dive into the **call stack**, `va_list` management, and binary-to-hexadecimal conversion algorithms.

#### 📌 [ft_get_next_line](https://github.com/ediha17/42Bcn_get_next_line.git)
*Line-by-line File Reading via File Descriptors*

* **The Challenge:** Designing a function that efficiently reads from a file descriptor (`fd`) and returns a single line per call, without knowing the line length in advance or losing data between consecutive calls.

*  **Architecture:** Implemented a **static buffer management system** that preserves the "leftover" data from the previous `read()` operation. The algorithm uses a loop to accumulate data into a static variable until a newline character (`\n`) is detected or the end of the file (EOF) is reached.

*  **Key Learning:** Advanced handling of static variables, heap memory allocation, and optimizing the read() system call using a configurable `BUFFER_SIZE`. Mastery of **memory leak prevention** during string concatenation and truncation.

### 📚 [libft](https://github.com/ediha17/42Bcn_Libft.git)
*Custom Static Library of C Standard Functions*

* **The Challenge:** Reimplementing a significant portion of the libc functions and additional utility functions to be used in all subsequent 42 projects.

* **Architecture:** Designed as a monolithic static library (.a) with a focus on modularity and rigorous error handling. The project includes reimplementations of string manipulation, memory allocation (`malloc`, `calloc`), and linked list management.

* **Key Learning:** Mastery of pointer arithmetic, understanding the underlying behavior of standard functions, and developing a reusable code base. This project established my foundation for memory management and the importance of writing highly portable code.

---

### 🧠 Programming Philosophy

* **Efficiency First:** Always prioritizing memory footprint and CPU cycles, especially in constrained environments.
* **Modular Design:** Breaking complex problems into isolated, testable, and reusable auxiliary functions.
* **Robustness:** Strict adherence to the **42 Norm**, ensuring code quality through static analysis and rigorous testing with **Valgrind**.

---

### 📈 Coding Metrics

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ediha17&theme=dark&hide_border=true)
![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=ediha17&show_icons=true&theme=dark&hide_border=true)

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
