# Hi, I'm Aniket Raval 👋

### IIT Madras · Software Engineering · C++ · DSA · Backend Systems

> **I like turning engineering problems into software systems.**

I'm a **B.Tech Civil Engineering student at IIT Madras** exploring software
engineering through **data structures, algorithms, backend development,
databases, and system design**.

My projects range from implementing core algorithms such as **Trie, BFS,
Kruskal's MST and DSU** to building complete applications involving
**REST APIs, databases, authentication, testing, Docker and deployment**.

---

## 🧭 My Engineering Journey

```text
Engineering Problems
        ↓
Computational Thinking
        ↓
Data Structures & Algorithms
        ↓
Software Systems
        ↓
Reliable Applications
```

I enjoy understanding not only **how** something works, but also:

- Why was this data structure chosen?
- Why is this algorithm appropriate?
- What happens as the input grows?
- How should the system handle failures?
- How can the code be tested?
- How can the system be made easier to maintain?

---

# 🚀 Featured Projects

## 🔎 FastSearch — Trie-Based Search Engine

A full-stack search system that evolved from a core **Trie implementation**
into a complete software application.

### What it demonstrates

- Trie-based prefix search and autocomplete
- C++20 REST API
- SQLite persistence
- React + TypeScript frontend
- Layered backend architecture
- Service and repository patterns
- Docker Compose
- GoogleTest-based testing

### Architecture

```text
                    ┌─────────────────────┐
                    │   React + TypeScript│
                    │      Frontend       │
                    └──────────┬──────────┘
                               │
                              HTTP
                               │
                               ▼
                    ┌─────────────────────┐
                    │     C++ REST API    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   Search Service    │
                    └──────────┬──────────┘
                               │
                     ┌─────────┴─────────┐
                     ▼                   ▼
              ┌─────────────┐     ┌─────────────┐
              │    Trie     │     │    SQLite   │
              │   Index     │     │  Persistence│
              └─────────────┘     └─────────────┘
```

🔗 **[View Repository](https://github.com/ce24b101-Aniket/Fast-Search-Dictionary-Trie-)**

---

## 🚖 RapidRide — Corporate Ride Sharing

A corporate ride-sharing MVP designed to simplify employee commuting
through verified ride participation and sustainable transportation.

### What it demonstrates

- Next.js + React + TypeScript
- Supabase / PostgreSQL
- Google OAuth authentication
- OTP-based ride verification
- Ride creation and participation
- Database-backed workflows
- CO₂ savings tracking
- Responsive frontend
- Vercel deployment

### Architecture

```text
                    ┌───────────────┐
                    │     User      │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │    Next.js    │
                    │   Frontend    │
                    └───────┬───────┘
                            │
                  ┌─────────┴─────────┐
                  ▼                   ▼
           ┌──────────────┐    ┌──────────────┐
           │ Supabase Auth│    │  PostgreSQL  │
           │    / OAuth   │    │   Database   │
           └──────────────┘    └──────────────┘
```

🔗 **[Live Demo](https://rapidride-eta.vercel.app/)**  
🔗 **[View Repository](https://github.com/ce24b101-Aniket/rapidride)**

---

## 🌐 Infrastructure Network Optimizer

A graph-based infrastructure planning system using **Kruskal's Algorithm
and Disjoint Set Union** to construct a minimum-cost connected network.

### Core concepts

`Graphs` · `Minimum Spanning Tree` · `Kruskal` · `DSU` · `Greedy Algorithms`

### Complexity

```text
Sorting Edges      → O(E log E)
DSU Operations     → Nearly O(1) amortized
Overall            → O(E log E)
```

🔗 **[View Repository](https://github.com/ce24b101-Aniket/Infrastructure-Network-Optimizer)**

---

## 🗺️ CityGrid Pathfinder

A C++ pathfinding system that models an urban layout as a grid and uses
**Breadth-First Search** to find shortest feasible routes while avoiding
blocked regions.

### Core concepts

`Graphs` · `BFS` · `Shortest Path` · `Queues` · `STL`

### Complexity

```text
Time  → O(V + E)
Space → O(V)
```

🔗 **[View Repository](https://github.com/ce24b101-Aniket/City-Grid-Pathfinder)**

---

## 🅿️ Smart Parking Lot

A C++ parking management system designed using **object-oriented
programming principles** to model vehicles, parking slots and parking
operations.

### Core concepts

`C++` · `OOP` · `Encapsulation` · `Abstraction` · `STL`

🔗 **[View Repository](https://github.com/ce24b101-Aniket/Smart-Parking-Lot-System)**

---

# 🧠 Data Structures & Algorithms

I enjoy using algorithms as tools for solving practical problems.

```text
Data Structures
├── Arrays / Vectors
├── Linked Lists
├── Stacks & Queues
├── Hash Tables
├── Trees
├── Tries
└── Graphs

Algorithms
├── Searching
├── Sorting
├── BFS / DFS
├── Shortest Paths
├── Minimum Spanning Trees
├── Greedy Algorithms
└── Dynamic Programming
```

---

# 🛠️ Tech Stack

### Languages

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

### Backend & Databases

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

### Engineering Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GoogleTest](https://img.shields.io/badge/GoogleTest-4285F4?style=flat-square&logo=google&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

---

# 💻 Computer Science

Currently strengthening my foundations in:

- **Data Structures & Algorithms**
- **Object-Oriented Programming**
- **Database Management Systems**
- **Operating Systems**
- **Computer Networks**
- **Backend Engineering**
- **System Design**
- **Software Testing**
- **Git & CI/CD**

---

# 📈 What I'm Currently Working On

```text
DSA
 │
 ▼
Modern C++
 │
 ▼
Backend Engineering
 │
 ▼
Databases & APIs
 │
 ▼
Testing & CI/CD
 │
 ▼
System Design
 │
 ▼
Scalable Software
```

My current goal is to move from simply **writing code that works**
towards building software that is:

```text
Correct
   +
Testable
   +
Maintainable
   +
Understandable
   +
Scalable
```

---

# 🏗️ Engineering Beyond Code

At IIT Madras, I have also worked on technical and organizational
initiatives involving:

- Technical leadership
- Event technology and operations
- Team coordination
- Vendor coordination
- Student mentoring
- Community initiatives

These experiences have taught me that engineering is not only about
writing code — it is also about **communication, ownership and
building systems with other people**.

---

# 🎓 Education

### Indian Institute of Technology Madras

**B.Tech — Civil Engineering**

I enjoy combining my engineering background with computational
problem-solving and software development.

---

# 🧩 How I Think About Software

> **Good software is not just code that works.  
> It is code whose decisions can be explained.**

When building a system, I try to understand:

**Why this data structure?**  
**Why this algorithm?**  
**Why this architecture?**  
**What happens when the input grows?**  
**What happens when something fails?**  
**How do we test it?**

---

# 🤝 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aniket_Raval-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](www.linkedin.com/in/aniket-raval-a4b6a6318)

[![GitHub](https://img.shields.io/badge/GitHub-ce24b101--Aniket-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ce24b101-Aniket)

---

### Thanks for visiting! 👋

If you're interested in **algorithms, backend systems, engineering
problems or building things from scratch**, feel free to explore
my repositories.

⭐ **Always learning. Always building.**
