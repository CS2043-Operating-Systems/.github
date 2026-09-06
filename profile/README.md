# CS2043 Operating Systems

Central repository organization for academic coursework, kernel-level development, laboratory practicals, and weekly notes for CS2043 Operating Systems at the Department of Computer Science and Engineering, University of Moratuwa.

## Organization Repositories

### Course Notes
- [CS2043-Weekly-Notes](https://github.com/CS2043-Operating-Systems/CS2043-Weekly-Notes): Comprehensive weekly lecture notes covering OS architecture, processes, threads, CPU scheduling, synchronization, and memory management.

### Practical & Kernel Development Hub
- [pintos-cs2043](https://github.com/CS2043-Operating-Systems/pintos-cs2043): Central instructional operating system repository for all CS2043 laboratory milestones and kernel projects, structured through dedicated feature branches:
  - **Lab 0**: Boot sequence and kernel interactive shell (`lab01-interactive-shell`)
  - **Lab 1**: Thread sleep via blocking, priority scheduling, priority donation, and MLFQS (`project1-alarm-clock`)
  - **Lab 2**: User programs, process execution, and system call boundaries (`lab02-user-programs`)
  - **Lab 3**: Virtual memory, demand paging, frame allocation, and swap (`lab03-virtual-memory`)
  - **Lab 4**: File systems, indexed inodes, buffer cache, and directory hierarchy (`lab04-file-systems`)

### Organization Workspace
- [.github](https://github.com/CS2043-Operating-Systems/.github): Organization profile and workspace configuration.

## Module Documentation

Weekly learning notes are structured through Notion and maintained in GitHub for version-controlled, durable reference. Topics focus on core operating system abstractions, concurrency control, resource allocation, and practical kernel-level implementation.

## Engineering & Git Standards

- **Commit Conventions**: All commits adhere to Conventional Commits format (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`).
- **Branching Workflow**: Milestones and laboratory assignments branch from prior stable baselines (`lab01-...`, `project1-...`) rather than creating fragmented repositories.
- **Code Quality**: Kernel C implementations maintain strict formatting standards, clean build configs, and automated test suite verification.

## Academic Context

Department of Computer Science and Engineering, University of Moratuwa.
