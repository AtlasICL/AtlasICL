# Hello! I'm Emre.

I'm a final year Computer Science student at the University of Exeter, currently achieving First-Class Honours, with a skillset bridging low-level optimisation and
production-scale software development.

[![Website](https://img.shields.io/badge/Website-eacarsoy.com-ff7f00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://eacarsoy.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-emre--acarsoy-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emre-acarsoy)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)

## Quick stats

![Top Langs](https://github-readme-stats-82m5.vercel.app/api/top-langs?username=AtlasICL&layout=compact&theme=github_dark&hide=jupyter%20notebook,javascript,css,lua,html&exclude_repo=acarsoy.co.uk)

## Experience

- Software Engineering Intern at **Cloudflare** (06/2026 – 09/2026)
  - Worked within the IPO - MCS team

## Notable Projects

- [whatdidi: command-line history search tool](https://github.com/AtlasICL/whatdidi)
  - Searches your shell history (persistent and current session) for commands matching a search term
  - Compatible with bash and zsh, on macOS and Linux
  - Supports compound commands, `sudo`-prefixed commands and unique-only results
  - Persistent user settings, self-update and uninstall, and an automated test suite

- [Custom macOS/Linux setup script](https://github.com/AtlasICL/dotfiles)
  - One command turns a fresh macOS or Ubuntu/Debian machine into a ready-to-use development environment
  - Detects the OS and installs packages with apt or Homebrew, translating package names between the two
  - Installs compilers, Java/Maven, NeoVim (with config), tmux, and tools such as fzf, ripgrep, fd and bat
  - Generates SSH keys, backs up any config it overwrites, and shows a persistent progress bar

- [Custom 16-bit CPU with pipelining and interrupts](https://github.com/AtlasICL/16-bit-cpu)
  - 16-bit RISC-style CPU built in the Issie digital-logic simulator, from a half adder up to a pipelined processor
  - Designed the instruction-decode, ALU-control and conditional-branch logic, and fixed bugs in the provided blocks
  - Wrote 16- and 32-bit shift-and-add multiplication routines in assembly
  - Analysed the 2-stage pipeline and interrupt handling, verified cycle by cycle against a reference model

- [Granite block allocator](https://github.com/AtlasICL/granite_block_allocator)
  - Desktop tool that packs granite blocks into containers, loading each one as close to its weight limit as possible
  - Solves each container as a 0/1 knapsack problem using dynamic programming, vectorised with NumPy
  - Optional blocks-per-container limit, with a greedy fallback for very large inputs
  - tkinter GUI, unit tests run with GitHub Actions, and packaged as a Windows executable

- [Why is Software OS-Specific?](https://github.com/AtlasICL/os-specific-software)
  - Technical presentation in LaTeX Beamer on why applications get tied to one operating system
  - Traces the causes to system call interfaces and graphics APIs
  - Evaluates translation layers (Wine/Proton), containers and VMs (Docker, Podman) and Electron, using published benchmark data
  - 25 cited sources in IEEE style

- More on my [website](https://eacarsoy.com/projects).
