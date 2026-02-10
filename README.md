# Hey, I'm Nil 👋

Backend developer focused on performance-critical systems, async concurrency, and Rust ↔ Python interoperability.

I use **Rust** where performance, correctness, and memory safety matter, and **Python** as a productive interface layer for APIs, tooling, and experimentation.

---

## About Me

I’m particularly interested in systems where latency, throughput, and correctness are first-class concerns.  
My work often sits at the boundary between high-level developer ergonomics and low-level performance.

I enjoy designing async systems, reasoning about concurrency, and building libraries that are both fast and usable.

---

## Projects

### Concurrent HTTP Client (Rust → Python)

I built a concurrent HTTP library in **Rust** using **Tokio** and **reqwest** after finding Python’s standard `requests` library too slow for testing APIs I was developing.

The core is implemented in Rust to take advantage of:
- Efficient async concurrency with Tokio
- Strong error handling using `Result` and explicit failure states
- Memory safety without a garbage collector

The library is exposed to Python using **PyO3**, allowing Python code to benefit from Rust-level performance while keeping a simple, familiar API.

This project reflects how I approach performance problems: push critical paths down to Rust, keep Python as a clean integration layer.

---

### TUI Quiz Application (Rust)

A small terminal-based quiz application built with **ratatui**, created as a way to practice for exams and challenge myself with Rust quizzes.

The application:
- Loads questions from JSON files using **serde**
- Separates data loading, application state, and rendering logic
- Focuses on correctness and simplicity rather than features

It’s not meant to be fancy — just a practical TUI app that helped me practice Rust while reinforcing clean structure and data-driven design.

---

## Technical Focus

### Rust
- Async programming with **Tokio**
- Concurrency patterns and task orchestration
- Error handling with `Result` and `Option`
- Ownership, lifetimes, and memory safety
- Rust ↔ Python bindings with **PyO3**
- Terminal UI development with **ratatui**

### Python
- FastAPI and Flask for API development
- REST API design and testing
- Data processing with NumPy and pandas
- Using Python as a high-level interface over performance-critical Rust code

---

## Interests

- Performance optimization and benchmarking
- Concurrent and asynchronous systems
- Designing libraries and developer-facing tools
- System architecture and trade-offs between safety, speed, and ergonomics

---

## Origin Story

I started programming about five years ago by building a Discord bot in Python.  
That led me into async I/O, API design, and eventually into performance bottlenecks that Python alone couldn’t solve.

Over time, this pushed me toward Rust — from low-level memory management and error handling to higher-level architectural patterns — while still keeping Python as a productive layer on top.

---

## GitHub Stats


# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat&logo=rust&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=flat&logo=windows-terminal&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=flat&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=flat&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=kama93i&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=kama93i&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=kama93i&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)


<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
