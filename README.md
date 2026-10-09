# Hello! I'm Emre.

I'm a final-year Computer Science student at the University of Exeter, currently achieving First-Class Honours, and a former Software Engineering Intern at Cloudflare. I've built production infrastructure tooling and worked on distributed systems, with a skillset bridging low-level optimisation and production-scale software development.

I am trilingual in English, French, and Turkish, and have a B1 in Spanish.

[![Website](https://img.shields.io/badge/Website-eacarsoy.com-ff7f00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://eacarsoy.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-emre--acarsoy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emre-acarsoy)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## Quick stats

![Top Langs](https://github-readme-stats-82m5.vercel.app/api/top-langs?username=AtlasICL&layout=compact&theme=github_dark&hide=jupyter%20notebook,javascript,css,lua,html&exclude_repo=acarsoy.co.uk)

## Experience

- **Software Engineering Intern** at **Cloudflare** (06/2026 – 09/2026)
  - Owned the end-to-end onboarding of 2 consumer-facing services (Workers KV and Containers) onto the Maintenance Coordination System (MCS), which models Cloudflare's infrastructure as a multi-layered graph to ensure maintenances are scheduled safely, coordinating with service teams to align requirements and resolve blockers
  - Modelled both services' quorum constraints in TypeScript, backed by unit and integration test suites, enabling MCS to automatically block quorum-breaking maintenances
  - Shipped independent codebase fixes: closed a CLI bypass of timeframe validation by moving checks into the API schema, diagnosed and fixed timezone-dependent test failures with a cross-timezone regression harness, and resolved a BFS path reconstruction bug

## Notable Projects

- [whatdidi: command-line history search tool](https://github.com/AtlasICL/whatdidi)
  - Searches your shell history across all shell sessions for commands matching a search term, matching 50k lines in 3ms
  - Supports compound commands and `sudo`-prefixed commands, on bash and zsh, macOS and Linux
  - Persistent user settings, including the default result count and filtering for unique results
  - Written in Bash, with a comprehensive automated test suite integrated into a CI pipeline using GitHub Actions

- [Granite block allocator](https://github.com/AtlasICL/granite_block_allocator)
  - Container-loading optimisation tool, built for a client and now in production use, increasing average container volume utilisation by 15%
  - Models each container as a 0/1 knapsack problem solved with dynamic programming, vectorised with NumPy
  - 62 unit tests run in GitHub Actions, covering malformed input and cases where DP outperforms greedy
  - Shipped as a standalone Windows executable with a GUI

- [Custom macOS/Linux setup script](https://github.com/AtlasICL/dotfiles)
  - One command turns a fresh macOS or Ubuntu/Debian machine into a ready-to-use development environment
  - Detects the OS and installs packages with apt or Homebrew, translating package names between the two
  - Installs compilers, Java/Maven, NeoVim (with config), tmux, and tools such as fzf, ripgrep, fd and bat
  - Generates SSH keys, backs up any config it overwrites, and shows a persistent progress bar

- [Game telemetry and balancing platform (team project)](https://github.com/AtlasICL/com2020)
  - Led a team of 7 across two Agile sprints, coordinating Jira task tracking, repository and workflow setup, team meetings and sprint demos
  - Implemented Google OAuth 2.0 (OIDC) authentication with role-based access control
  - Designed the JSON event schema connecting the game to the telemetry platform, and implemented event parsing, analytics, and a matplotlib GUI with CSV export

- [Custom 16-bit CPU with pipelining and interrupts](https://github.com/AtlasICL/16-bit-cpu)
  - 16-bit RISC-style CPU built in the Issie digital-logic simulator, from a half adder up to a pipelined processor
  - Designed the instruction-decode, ALU-control and conditional-branch logic, and fixed bugs in the provided blocks
  - Wrote 16- and 32-bit shift-and-add multiplication routines in assembly
  - Analysed the 2-stage pipeline and interrupt handling, verified cycle by cycle against a reference model

- [Why is Software OS-Specific?](https://github.com/AtlasICL/os-specific-software)
  - Technical presentation in LaTeX Beamer on why applications get tied to one operating system
  - Traces the causes to system call interfaces and graphics APIs
  - Evaluates translation layers (Wine/Proton), containers and VMs (Docker, Podman) and Electron, using published benchmark data

- More on my [website](https://eacarsoy.com/projects).
