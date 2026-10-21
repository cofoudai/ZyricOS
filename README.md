# ZyricOS

A modern, from-scratch operating system designed for simplicity, speed, and developer ergonomics.

ZyricOS is a long-term exploration in operating system design: a minimal kernel, a modular runtime, and a clean developer experience built around the idea that the system should feel fast, predictable, and easy to extend.

## Why ZyricOS?

Most operating systems are built around legacy constraints, complexity, and massive abstraction layers. ZyricOS aims to take a different path:

- minimal and understandable architecture
- performance-first design principles
- modular subsystems instead of monolithic complexity
- a developer-friendly environment for experimentation and learning
- a fresh foundation for modern computing workloads

## Vision

ZyricOS is not just another kernel project. It is a blueprint for a system that values:

- clarity over cleverness
- reliability over fragile shortcuts
- extensibility over rigid assumptions
- learning by building instead of copying patterns blindly

The project is intentionally ambitious and is being developed in stages, starting with the core foundations before expanding to userland tooling, package management, and system services.

## Current Status

This repository is in its early planning and foundation stage.

The current focus is on:

- defining the overall architecture
- designing kernel and process abstractions
- establishing memory and scheduling concepts
- creating a clean project layout for future development
- documenting the direction so contributors can build meaningfully from the start

## Core Design Goals

### 1. Simplicity
The codebase should remain readable and understandable even as the system grows.

### 2. Performance
Every subsystem should be designed with efficiency in mind, from scheduling to I/O handling.

### 3. Modularity
ZyricOS should be built from well-defined components that can evolve independently.

### 4. Portability
The design should leave room for different hardware targets without turning the system into a fragile one-off.

### 5. Learning Value
The project should be approachable enough for developers who want to understand how operating systems really work.

## Planned Architecture

A practical starting architecture may look like this:

- Kernel core
  - bootloader integration
  - CPU initialization
  - interrupt and exception handling
  - task scheduling
- Memory management
  - virtual memory model
  - page allocation
  - protection and isolation
- Filesystem abstraction
  - VFS layer
  - storage backends
  - metadata and permissions
- Device management
  - drivers
  - hardware abstraction
  - interrupt routing
- Userland
  - shell
  - system utilities
  - package and service model

## Roadmap

### Phase 1: Foundations
- boot sequence design
- kernel skeleton
- memory model and paging basics
- scheduler prototype

### Phase 2: Core Services
- system calls
- process management
- basic filesystem
- device driver framework

### Phase 3: User Experience
- shell and command interface
- startup services
- package management concepts
- basic networking stack

### Phase 4: Expansion
- security and sandboxing
- advanced filesystem features
- graphics and window system
- broader hardware support

## Repository Layout

```text
ZyricOS/
├── README.md
├── docs/
├── kernel/
├── drivers/
├── fs/
├── userland/
├── tools/
└── scripts/
```

This layout is a proposed organizational structure and will evolve as the OS takes shape.

## Getting Started

There is no production build or full operating system image yet. The next step is to define the core kernel foundations and establish a stable architecture before adding user-facing functionality.

For contributors, the ideal workflow is:

1. read the architecture docs
2. understand the current kernel design
3. propose a focused subsystem or module
4. implement and document incremental improvements

## Contributing

Contributions are welcome, especially in the areas below:

- kernel design and architecture
- memory management and scheduling
- filesystem design
- device driver abstractions
- documentation and developer guides
- tooling and build automation

If you want to help, start by opening an issue or proposing a well-scoped improvement. Clear design discussions are especially valuable at this stage.

## Development Principles

- document before implementation when the design is uncertain
- prefer modular systems over fragile shortcuts
- keep interfaces small and explicit
- test design assumptions early
- optimize for clarity, not hype

## License

This project is currently unlicensed. If you plan to use or extend it significantly, it may be appropriate to add an explicit license once the direction is more mature.

## Closing Thought

ZyricOS is a bold project at the intersection of systems programming, software design, and computer architecture. It is not about shipping a polished desktop OS overnight. It is about building a solid foundation and learning deeply while doing it.

If you are interested in building an operating system from the ground up, this project is a place to think carefully, experiment meaningfully, and create something intentional.

---

Built with the belief that great systems begin with clear ideas.
