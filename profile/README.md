# CS2043 Operating Systems

Central repository organization for academic coursework, kernel-level systems development, laboratory practicals, and weekly study notes for CS2043 Operating Systems at the Department of Computer Science and Engineering, University of Moratuwa.

## Organization Repositories

### Theoretical Foundations & Lecture Synthesis
- [CS2043-Weekly-Notes](https://github.com/CS2043-Operating-Systems/CS2043-Weekly-Notes): Comprehensive weekly lecture notes covering operating system architectures, processes, kernel threads, CPU scheduling algorithms, synchronization primitives, and memory virtualization.

### Instructional Kernel Laboratory Repositories
- [pintos-lab-00](https://github.com/CS2043-Operating-Systems/pintos-lab-00): **Lab 0 — Getting Real: Boot, GDB & Kernel Monitor**. Complete boot path tracing (BIOS `0x7C00`, `loader.S`, `start.S` real-to-protected mode transition, temporary paging, and `pintos_init()`), remote GDB debugging over QEMU stub, and Ring 0 interactive kernel monitor supporting standard and extended commands (`whoami`, `shutdown`, `time`, `ram`, `thread`, `priority`, `exit`).
- [pintos-lab-01](https://github.com/CS2043-Operating-Systems/pintos-lab-01): **Lab 1 — Threads: Alarm Clock, Priority Scheduling & MLFQS**. Timer sleep by thread blocking, priority-based scheduling, priority donation for nested synchronization, and multi-level feedback queue scheduling.
- *Upcoming Milestones*: Separate repositories will be provisioned for Lab 2 (User Programs & System Calls), Lab 3 (Virtual Memory & Demand Paging), and Lab 4 (File Systems & Buffer Cache).

### Environment & Toolchain Infrastructure
- [pintos-wsl](https://github.com/shashika-mora/pintos-wsl): Canonical setup and verification guide for building and running 32-bit x86 Pintos on Windows 11 using WSL2, Ubuntu 26.04 LTS, GCC multilib, and QEMU, featuring comprehensive diagnostics for common toolchain issues.

### Workspace Configuration
- [.github](https://github.com/CS2043-Operating-Systems/.github): Organization profile and workspace configuration.

## Engineering & Git Standards

- **Commit Conventions**: All commits strictly adhere to the Conventional Commits specification (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Repository Isolation**: Each laboratory milestone operates in an isolated repository branched from its preceding verified baseline, maintaining clean commit histories and focused documentation.
- **Verification**: Kernel changes are verified through automated test suites executed in the build directory (`make check`) and manual verification runs under QEMU.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
