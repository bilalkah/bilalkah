# Bilal Kahraman

**C++ Systems Engineer — Database Internals** · Database Kernel Developer @ Huawei

I work on PostgreSQL internals and database engine development, and contribute
upstream to Babelfish for PostgreSQL — T-SQL compatibility, type systems, and
engine-level bug fixes.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bilalkah)
[![Email](https://img.shields.io/badge/Email-kahramannbilal%40gmail.com-red?logo=gmail&logoColor=white)](mailto:kahramannbilal@gmail.com)

---

## 🐘 Open-Source Contributions

**[Babelfish for PostgreSQL](https://babelfishpg.org)** — T-SQL compatibility for PostgreSQL

Merged contributions in both layers of the project:

- **[PostgreSQL engine (modified for Babelfish)](https://github.com/babelfish-for-postgresql/postgresql_modified_for_babelfish/pulls?q=is%3Apr+author%3Abilalkah+is%3Amerged)** —
  engine-level fixes in the modified PostgreSQL core
- **[Babelfish extensions](https://github.com/babelfish-for-postgresql/babelfish_extensions/pulls?q=is%3Apr+author%3Abilalkah+is%3Amerged)** —
  T-SQL type-system compatibility

Highlights:
- Implemented bidirectional `char`/`nchar` ↔ `binary`/`varbinary` casting with
  encoding-aware conversions, including `TRY_CAST`/`CONVERT`/`TRY_CONVERT` support
- Fixed T-SQL decimal→integer conversion semantics (truncation vs. rounding) —
  a correctness issue affecting financial computations in migrated workloads
- Engine-side function behavior fixes in the modified PostgreSQL core

---

## Featured Projects

- **[Kergit — Real-Time Communication Platform](https://github.com/bilalkah/kergit-server)**
  Open-source voice and messaging platform: custom C++ WebSocket server, Protocol
  Buffers protocol, PostgreSQL persistence, Redis session state, LiveKit media,
  self-hosted deployment.
- **[Wolfenstein-Style Game Engine](https://github.com/bilalkah/wolfenstein)**
  Raycasting engine from scratch in C++/SDL — DDA rendering, A* pathfinding,
  state-machine enemy behavior.
- **[Path Planning Library](https://github.com/bilalkah/path-planning)**
  C++ implementations of A*, RRT, RRT* and friends, with simulation and visualization.

---

## Tech

**Languages:** C++11/17, C, Python, SQL, Bash
**Focus:** PostgreSQL internals · database kernel development · performance engineering · networking
**Infra:** Linux, Docker, WebSockets, Protocol Buffers, Redis
**Background:** robotics & autonomous systems, automotive simulation
